<template>
  <div class="home">
    <!-- DevLand --> 
    <DevLand/>
  </div>
</template>

<script>
// @ is an alias to /src
//import BlueLand from '@/components/BlueLand.vue'
import DevLand from '@/components/DevLand.vue'


export default {
  name: 'HomeView',
  components: {
    //BlueLand,
    DevLand
  }
}
</script>
