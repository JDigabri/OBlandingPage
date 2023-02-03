

<template>
    <div class="container"> 
        <div class="dCont">
            <div src="" class="stretch" alt="">
                <h1 style="font-family: 'Rubik', sans-serif;font-style: normal;font-weight: 800;font-size: 68px;color: #FFFFFF;cursor:default;">
                    Are you a...
                </h1>
                <div class="dbuttons">
                    <div class="db1">
                        Developer
                    </div>
                    <div class="orButton">
                        <p style="margin-top:20px;">or</p>
                    </div>
                    <div class="db2">
                        Consumer
                    </div>
                </div>

                <h1 style="font-family: 'Rubik', sans-serif;font-style: normal;font-weight: 800;font-size: 24px;color: #FFFFFF;cursor:default;margin-top:125px;">
                    As a consumer  keyzy offers a platform <br> for you to own the games you buy
                </h1>            
            </div>
            <div class = "dSecOne">
                <div class="dwalcus">
                    <img src="../assets/selldev.png" />
                </div>
                <div class ="dsecOneText">
                     <h1 style="font-family: 'Rubik', sans-serif;font-style: normal;font-weight: 800;font-size: 30px;color: black;cursor:default;">SELL YOUR GAMES FOR CRYPTO</h1>   
                     <p style="font-family: 'Inter', sans-serif;font-size: 24px;color: black;cursor:default;">Your game costs the same price everywhere in the world, 1 price for all</p>
                </div>
            </div>
            <div class = "dSecTwo">
                <div class ="dsecOneText">
                    <h1 style="font-family: 'Rubik', sans-serif;font-style: normal;font-weight: 800;font-size: 30px;color: black;cursor:default;">ENJOY GREAT SPLITS</h1>   
                    <p style="font-family: 'Inter', sans-serif;font-size: 24px;color: black;cursor:default;">Developers earn 99% of the profits made their games and earn a 1% royalty every time their game is sold on the community market</p>
               </div>
                <div class="downcus">
                    <img src="../assets/splitdev.png" />
                </div>

    
            </div>            
            <div class = "dSecThree">
                <div class="dwalcus">
                    <img src="../assets/recdev.png" />
                </div>
                <div class ="dsecOneText">
                     <h1 style="font-family: 'Rubik', sans-serif;font-style: normal;font-weight: 800;font-size: 30px;color: black;cursor:default;">EARN WHEN YOUR GAMES ARE REFUNDED</h1>   
                     <p style="font-family: 'Inter', sans-serif;font-size: 24px;color: black;cursor:default;">Our refund policy states that after 14 days or 3 hours, game are able to be refactored back into item form, where they can be sold on the market or broken back into a game</p>
                </div>
            
            </div>
            <div class = "dSecFour">
                <div class="dImgDesk">
                    <img src="../assets/demoimg.png" />
                </div>
                <p style="font-family: 'Inter', sans-serif;font-size: 24px;color: black;cursor:default;margin-top:50px;">Try out our UI demo to really get a feel of the service</p>
                <div class="ddemoButton"><p>TRY THE DEMO</p></div>
            
            </div>
        </div>
        <div class="mCont">
            <div src="" class="stretch2" alt="">
                
                
            </div>
        </div>
    </div>
</template>>

<style scoped>
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
.ddemoButton > p{
    font-family: 'Rubik', sans-serif;    
    font-style: normal;
    font-weight: 800;
    font-size: 30px;
    color: #FFFFFF;
    cursor: pointer;
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
    margin-bottom: 20px;
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
    font-family: 'Rubik', sans-serif;
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
    font-family: 'Rubik', sans-serif;
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
    font-family: 'Rubik', sans-serif;
    font-style: normal;
    font-weight: 800;
    font-size: 28px;
    color: white;
    cursor:default;
    
}



@media only screen and (max-width: 900px){
    .dCont{
      display: none;
    }
    .mCont{
        display: flex;
    }
 
    .stretch2{
        display: flex;
        background-image: url("../assets/WAVD.svg");
        height: 400px;
        width: 100vw;
        background-repeat: no-repeat;
        background-size:100% 100%;
    }
 }
</style>