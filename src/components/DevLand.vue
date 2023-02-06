<template>
    <meta name = "theme-color" content = "#FFC563">

    <div class="navCont">
    
    
    </div>
    <div class="container"> 
        <div class="dCont">
            <div src="" class="stretch" alt="">
                <h1 style="">
                    Are you a...
                </h1>
                <div class="dbuttons">
                    <div  class="db1">
                        Developer
                    </div>
                    <div class="orButton">
                        <p style="margin-top:20px;">or</p>
                    </div>
                    <v-btn @click="changeStep" class="db2">
                        Consumer
                    </v-btn>
                </div>

                <h1 class="mainText">
                    As a developer keyzy offers a platform for<br> you to earn the most from your games 
                </h1>            
            </div>
            <div class = "dSecOne">
                <div class="dwalcus">
                    <div class="sellcus" />
                </div>
                <div class ="dsecOneText">
                     <h1 class="secTitle">SELL YOUR GAMES FOR CRYPTO</h1>   
                     <p class="secText">Your game costs the same price everywhere in the world, 1 price for all</p>
                </div>
            </div>
            <div class = "dSecTwo">
                <div class ="dsecOneText">
                    <h1 class="secTitle">ENJOY GREAT SPLITS</h1>   
                    <p class="secText">Developers earn 99% of the profits made their games and earn a 1% royalty every time their game is sold on the community market</p>
               </div>
                <div class="downcus">
                    <div class="owncus" />
                </div>

    
            </div>            
            <div class = "dSecThree">
                <div class="dwalcus">
                    <div class="walcus" />
                </div>
                <div class ="dsecOneText">
                     <h1 class="secTitle">EARN WHEN YOUR GAMES ARE REFUNDED</h1>   
                     <p class="secText">Our refund policy states that after 14 days or 3 hours, game are able to be refactored back into item form, where they can be sold on the market or broken back into a game</p>
                </div>
            
            </div>
            <div class = "dSecFour">
                <div class="dImgDesk">
                    <div class="demoimg" />
                </div>
                <p style="">Try out our UI demo to really get a feel of the service</p>
                <div class="ddemoButton"><a href="https://keyzydemo.netlify.app/#/">TRY THE DEMO</a></div>
            
            </div>
        </div>
    </div>
</template>>

<style scoped>
.dSecFour > p{
    font-family: Inter, sans-serif;
    font-size: 24px;
    color: black;
    cursor:default;
    margin-top:50px;
}
.stretch > h1{
    font-family: Rubik, sans-serif;font-style: normal;font-weight: 800;font-size: 68px;color: #FFFFFF;cursor:default;
    margin-top:33px;
}
.navCont{
    position: fixed;
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100vw;
    height: 50px;
    background-color: #FFC563;
    /*background-color: #6198FF;*/
    z-index: 4;
    font-size: 28px;
  
  }
  
.mCont{
    display: none;
 }

.dCont{
    display: flex;
    flex-direction: column;
}
.ddemoButton{
    width: 361px;
    height: 82px;
    background: #FFA800;
    border-radius: 15px;
    
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;

}
.ddemoButton > a{
    font-family: Rubik, sans-serif;    
    font-style: normal;
    font-weight: 800;
    font-size: 30px;
    color: #FFFFFF;
    cursor: pointer;
    text-decoration: none;
}
.dImgDesk{
    height: 600px;
    width: 900px;
    margin-top:50px;
}
.dwalcus{
    margin-right: 12vw;
    padding: 25px;


}
.downcus{
    margin-left: 12vw;
    padding: 25px;
}
.dsecOneText{
    padding: 25px;
    width:  30vw;

}

.dSecOne{
    height: 500px;
    width: 100vw;
    margin-bottom: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.dSecTwo{
    height: 500px;
    width: 100vw;
    background-color: #F0F0F0;
    margin-bottom: 20px;
    display: flex;
    justify-content: center;
    align-items: center;

}
.dSecThree{
    height: 500px;
    width: 100vw;
    margin-bottom: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.dSecFour{
    height: 870px;
    width: 100vw;
    background-color: #F0F0F0;
    display: flex;
    align-items: center;
    flex-direction: column;
}
.stretch{
    background-image: url("../assets/WAVD.svg");
    height: 700px;
    width: 100vw;
    background-repeat: no-repeat;
    background-size:100% 100%;
    
}
.dbuttons{
    width: 100vw;
    justify-content: center;
    display: flex;
    
}
.db1{
    width: 255px;
    height: 84.75px;
    display: flex;
    justify-content: center;
    align-items: center;
    background: #BDBDBD;
    border: 3px solid #000000;
    transform: rotate(-9deg);
    font-family: Rubik, sans-serif;
    font-style: normal;
    font-weight: 800;
    font-size: 28px;
    color: black;
    cursor:default;

}


.db2{
    width: 255px;
    height: 84.75px;
    background: #FFFFFF;
    border: 3px solid #000000;
    margin-left: 25px;
    display: flex;
    justify-content: center;
    align-items: center;
    --scaler: 1;
    transform: scale(var(--scaler)) rotate(5deg);
    font-family: Rubik, sans-serif;
    font-style: normal;
    font-weight: 800;
    font-size: 28px;
    color: black;
    cursor:pointer;
    transition: ease-in .1s;

}

.db2:hover{
    --scaler:1.05;
}
.orButton{
    box-sizing: border-box;
    position: absolute;
    width: 65px;
    height: 65px;
    z-index: 3;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    background: #C68200;
    border: 3px solid #000000;
    box-shadow: 0px 2px 5px 3px rgba(0, 0, 0, 0.25);
    font-family: Rubik, sans-serif;
    font-style: normal;
    font-weight: 800;
    font-size: 28px;
    color: white;
    cursor:default;
    
}
.walcus{
    background-image: url("../assets/recdev.png");
    height: 247px;
    width: 260px;
    background-size: contain;

}
.owncus{
    background-image: url("../assets/splitdev.png");
    height: 408px;
    background-repeat: none;
    width: 267px;
}

.demoimg{
    background-image: url("../assets/demoimg.png");
    width: 924px;
    height: 609px;
}
.sellcus{
    background-image: url("../assets/selldev.png");
    height: 320px;
    width: 395px;
}
.secTitle{
    font-family: Rubik, sans-serif;font-style: normal;font-weight: 800;font-size: 30px;color: black;cursor:default;
}
.secText{
    font-family: Inter, sans-serif;font-size: 24px;color: black;cursor:default;
}
.mainText{
    font-family: Rubik, sans-serif;font-style: normal;font-weight: 800;font-size: 24px !important;color: #FFFFFF;cursor:default;margin-top:25px;
}

@media only screen and (max-width: 900px){
    div#site-header-inner {
		background-color: #FFC563;
	}
       .container{
        overflow-x:hidden !important;
    }
    .dSecFour > p{
        font-family: Inter, sans-serif;
        font-size: 24px;
        color: black;
        cursor:default;
        margin-top:50px;
    }
    .mainText{
        font-family: Rubik, sans-serif;font-style: normal;font-weight: 800;font-size: 14px !important;color: #FFFFFF;cursor:default;margin-top:25px;
    }
    .stretch > h1{
        margin-top:40px;

        font-family: Rubik, sans-serif;font-style: normal;font-weight: 800;font-size: 42px;color: #FFFFFF;cursor:default;
    }

    .navCont{
        position: fixed;
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100vw;
        height: 50px;
        background-color: #FFC563;
        z-index: 4;
        font-size: 28px;
      
      }
      
    
    .sellcus{
        background-image: url("../assets/selldev.png");
        background-size: contain;
        height: 200px;
        width: 250px;
        background-repeat: no-repeat;
        margin-left:40px;
    }
    .dCont{
        display: flex;
        flex-direction: column;
    }
    .ddemoButton{
        width: 361px;
        height: 82px;
        background: #FFA800;
        border-radius: 15px;
        
        display: flex;
        align-items: center;
        justify-content: center;
        cursor: pointer;
    
    }
    .ddemoButton > a{
        font-family: Rubik, sans-serif;    
        font-style: normal;
        font-weight: 800;
        font-size: 30px;
        color: #FFFFFF;
        cursor: pointer;
        text-decoration: none;
    }
    .dImgDesk{
        height: 600px;
        width: 900px;
        margin-top:50px;
    }
    .dwalcus{
        margin-right: 12vw;
        padding: 25px;
    
    
    }
    .demoimg{
        background-image: url("../assets/mDemoImg.png");
        width: 309px;
        height: 468px;
        margin-left: 295px;
        margin-right: 1px !important;
        background-repeat: no-repeat;

    }

    .walcus{
        background-image: url("../assets/recdev.png");
        height: 322px;
        margin-left:50px;
        width: 260px;
        background-size: contain;

        background-repeat: no-repeat;

    }
    .owncus{
        background-image: url("../assets/splitdev.png");
        height: 408px;
        width: 330px;
        background-repeat: no-repeat;

    }
    .dsecOneText{

        width:  80vw;
    
    }
    .secTitle{
        font-family: Rubik, sans-serif;font-style: normal;font-weight: 800;font-size: 30px;color: black;cursor:default;
    }
    .secText{
        font-family: Inter, sans-serif;font-size: 24px;color: black;cursor:default;
    }
    .dSecOne{
        height: 600px;
        width: 100vw;
        margin-bottom: 15px;
        display: flex;
        flex-direction: column-reverse;
        justify-content: center;
        align-items: center;
    }
    .dSecTwo{
        height: 900px;
        width: 100vw;
        background-color: #F0F0F0;
        margin-bottom: 70px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    
    }
    .dSecThree{
        height: 600px;
        width: 100vw;
        margin-bottom: 20px;
        display: flex;
        flex-direction: column-reverse;
        justify-content: center;
        align-items: center;
    }
    .dSecFour{
        height: 800px;
        width: 100vw;
        background-color: #F0F0F0;
        display: flex;
        align-items: center;
        flex-direction: column;

    }
    .stretch{
        background-image: url("../assets/WAVD.svg");
        height: 450px;
        width: 100vw;
        background-repeat: no-repeat;
        background-size:200% 100%;
        
    }
    .dbuttons{
        width: 100vw;
        justify-content: center;
        align-items: center;
        display: flex;
        flex-direction: column;
        
    }
    .db1{
        width: 200px;
        height: 66.4px;
        display: flex;
        justify-content: center;
        align-items: center;
        background: #BDBDBD;
        border: 3px solid #000000;
                --scaler: 1;

        transform: scale(var(--scaler)) rotate(-9deg);
        font-family: Rubik, sans-serif;
        font-style: normal;
        font-weight: 800;
        font-size: 28px;
        color: black;
        cursor:default;

    
    }
    
    
    .db2{
        margin-top: 25px;
        width: 200px;
        height: 66.4px;
        background: #FFFFFF;
        border: 3px solid #000000;
        margin-left: 25px;
        display: flex;
        justify-content: center;
        align-items: center;
                --scaler: 1;

        transform: scale(var(--scaler)) rotate(5deg);
        font-family: Rubik, sans-serif;
        font-style: normal;
        font-weight: 800;
        font-size: 28px;
        color: black;
        cursor:pointer;
        transition: ease-in .1s;
    }
    
    .db2:hover{
        --scaler:1.05;
    }
    .orButton{
        box-sizing: border-box;
        position: absolute;
        width: 65px;
        height: 65px;
        z-index: 3;
        border-radius: 50%;
        display: flex;
        justify-content: center;
        align-items: center;
        background: #C68200;
        border: 3px solid #000000;
        box-shadow: 0px 2px 5px 3px rgba(0, 0, 0, 0.25);
        font-family: Rubik, sans-serif;
        font-style: normal;
        font-weight: 800;
        font-size: 28px;
        color: white;
        cursor:default;
        
    }
    

 }
 
</style>


<script>
export default {
    name: "DevLand", 
    methods: {
        changeStep() {
            this.$emit("nextStep", "BlueLand");
        }
    }

}
</script>