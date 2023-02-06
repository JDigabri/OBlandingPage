<template>
  <div class="home">
    <component @nextStep="changeStep" v-bind:is="selectedComponent"></component>
  </div>
</template>

<script>
import BlueLand from '@/components/BlueLand.vue'
import DevLand from '@/components/DevLand.vue'

export default {
    name: "HomeView",
    components: {
      BlueLand,
      DevLand    
    },
    data() {
        return {
            selectedComponent: "BlueLand"
        }
    }, methods: {
        changeStep(step) {
            this.selectedComponent = step;
        }
    }, 
}

</script>
