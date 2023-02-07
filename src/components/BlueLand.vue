<template>
    <meta name = "theme-color" content = "#6198FF">    
    <div class="navCont">
        <img src="../assets/favwhite.png" alt="zaza">

    </div>
    <div class="container"> 
        <div class="dCont">
            <div src="" class="stretch" alt="">
                <h1 style="">
                    Are you a...
                </h1>
                <div class="dbuttons">
                    <v-btn @click="changeStep" class="db1">
                        Developer
                    </v-btn>
                    <div class="orButton">
                        <p style="margin-top:20px;">or</p>
                    </div>
                    <div class="db2">
                        Consumer
                    </div>
                </div>

                <h1 class="mainText">
                    As a consumer jules offers a platform <br> for you to own the games you buy
                </h1>            
            </div>
            <div class = "dSecOne">
                <div class="dwalcus">
                    <div class = "sellcus" />
                </div>
                <div class ="dsecOneText">
                     <h1 class = "secTitle" style="">BUY GAMES WITH ANY WALLET</h1>   
                     <p  class = "secText" style="">Use any crypto currency or any wallet to purchase games.</p>
                </div>
            </div>
            <div class = "dSecTwo">
                <div class ="dsecOneText">
                    <h1 class = "secTitle" style="">OWN AND STORE YOUR GAMES</h1>   
                    <p class = "secText" style="">Once you purchase YOUR games YOU own them, granting the ability to break the game down into a playable form in your library</p>
               </div>
                <div class="downcus">
                    <div class = "owncus" />
                </div>

    
            </div>            
            <div class = "dSecThree">
                <div class="dwalcus">
                    <div class="walcus" />
                </div>
                <div class ="dsecOneText">
                     <h1 class = "secTitle" style="">SELL YOUR UNPLAYED GAMES</h1>   
                     <p class = "secText" style="">A game sits un-played in your inventory? no problem sell it on the community run market. </p>
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
.mainText{
    font-family: Rubik, sans-serif;font-style: normal;font-weight: 800;font-size: 24px !important;color: #FFFFFF;cursor:default;margin-top:125px;
}
.navCont{
    position: fixed;
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100vw;
    height: 50px;
    background-color: #6198FF;
    z-index: 4;
    font-size: 28px;
  
  }
  

.sellcus{
    background-image: url("../assets/walcus.png");
    height: 284px;
    width: 488px;
}
.dCont{
    display: flex;
    flex-direction: column;
}
.ddemoButton{
    width: 361px;
    height: 82px;
    background: #266DD3;
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
    background-image: url("../assets/demoimg.png");
    width: 924px;
    height: 609px;
}
.downcus{
    margin-left: 12vw;
    padding: 25px;
}
.walcus{
    background-image: url("../assets/sellcus.png");
    height: 322px;
    width: 395px;
}
.owncus{
    background-image: url("../assets/owncus.png");
    height: 436px;
    width: 524px;
}
.dsecOneText{
    padding: 25px;
    width:  30vw;

}
.navCont > img{
    height: 40px;
    filter: drop-shadow(0 0 25px black);
    transition: ease-in .1s;
  }

  .navCont > img:hover{
    transform: scale(1.1);
    cursor: pointer;
  }

.secTitle{
    font-family: Rubik, sans-serif;font-style: normal;font-weight: 800;font-size: 30px;color: black;cursor:default;
}
.secText{
    font-family: Inter, sans-serif;font-size: 24px;color: black;cursor:default;
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
    background-image: url("../assets/WAVB.svg");
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
    background: #FFFFFF;
    border: 3px solid #000000;
    --scaler: 1;
    transform: scale(var(--scaler)) rotate(-9deg);
    font-family: Rubik, sans-serif;
    font-style: normal;
    font-weight: 800;
    font-size: 28px;
    color: black;
    cursor:pointer;
    transition: ease-in .1s;

}


.db2{
    width: 255px;
    height: 84.75px;
    background: #BDBDBD;
    border: 3px solid #000000;
    margin-left: 25px;
    display: flex;
    justify-content: center;
    align-items: center;
    transform: rotate(5deg);
    font-family: Rubik, sans-serif;
    font-style: normal;
    font-weight: 800;
    font-size: 28px;
    color: black;
    cursor:default;
}

.db1:hover{
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
    background: #275AA4;
    border: 3px solid #000000;
    box-shadow: 0px 2px 5px 3px rgba(0, 0, 0, 0.25);
    font-family: Rubik, sans-serif;
    font-style: normal;
    font-weight: 800;
    font-size: 28px;
    color: white;
    cursor:default;
    
}



@media only screen and (max-width: 900px){
    .downcus{
        margin-left: 0;
        padding: 0;
    }
    div#site-header-inner {
		background-color: #6D97E2;
	}
    .container{
        overflow-x:hidden ;
    }
    .dSecFour > p{
        font-family: Inter, sans-serif;
        font-size: 24px;
        color: black;
        cursor:default;
        margin-top:50px;
    }
    .stretch > h1{
        margin-top:40px;

        font-family: Rubik, sans-serif;font-style: normal;font-weight: 800;font-size: 42px;color: #FFFFFF;cursor:default;
    }
    .mainText{
        font-family: Rubik, sans-serif;font-style: normal;font-weight: 800;font-size: 14px !important;color: #FFFFFF;cursor:default;margin-top:25px;
    }
    .navCont{
        position: fixed;
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100vw;
        height: 50px;
        background-color: #6198FF;
        z-index: 4;
        font-size: 28px;
      
      }
      
    
    .sellcus{
        background-image: url("../assets/Mwalcus.png");
        background-size: contain;
        height: 284px;
        width: 312px;
        background-repeat: no-repeat;
    }
    .dCont{
        display: flex;
        flex-direction: column;
    }
    .ddemoButton{
        width: 361px;
        height: 82px;
        background: #266DD3;
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
        margin-right: 0vw;
        padding: 0px;

    
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
        background-image: url("../assets/Msellcus.png");
        height: 250px;
        width: 300px;
        background-repeat: no-repeat;
        background-size: contain;
    }
    .owncus{
        background-image: url("../assets/Mowncus.png");
        height: 400px;
        width: 250px;
        background-repeat: no-repeat;
        background-size: contain;
 
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
        height: 800px;
        width: 100vw;
        background-color: #F0F0F0;
        margin-bottom: 20px;
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
        padding-bottom: 25px;

    }
    .stretch{
        background-image: url("../assets/WAVB.svg");
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
        background: #FFFFFF;
        border: 3px solid #000000;
        --scaler: 1;
        transform: scale(var(--scaler)) rotate(-9deg);
        font-family: Rubik, sans-serif;
        font-style: normal;
        font-weight: 800;
        font-size: 28px;
        color: black;
        cursor:pointer;
        transition: ease-in .1s;
    
    }
    
    
    .db2{
        margin-top: 25px;
        width: 200px;
        height: 66.4px;
        background: #BDBDBD;
        border: 3px solid #000000;
        margin-left: 25px;
        display: flex;
        justify-content: center;
        align-items: center;
        transform: rotate(5deg);
        font-family: Rubik, sans-serif;
        font-style: normal;
        font-weight: 800;
        font-size: 28px;
        color: black;
        cursor:default;
    }
    
    .db1:hover{
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
        background: #275AA4;
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
    name: "BlueLand", 
    methods: {
        changeStep() {
            this.$emit("nextStep", "DevLand");
        }
    }

}
</script>