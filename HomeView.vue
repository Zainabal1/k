<template>
 
  <img class="bg-jedex" src="@/assets/background.svg">
  <div class="bg">


    
    
  </div>
  
  <header>
    <div class="red-header"></div>
    <div class="white-header">
     
     
      

    </div>

    <img class="logo-context" src="@/assets/j.svg">
    <img class="jedex-logo" src="@/assets/logo.svg">
    <div class="vertical"></div>
    <div class="menu">
        
    <router-link to='/main'>
      <input class="input-tabs" type="radio" id="home" name="header" checked>
      <label for="home">Home</label>
    </router-link>
    <router-link to='/about'>
      <input class="input-tabs" type="radio" id="about" name="header" >
      <label for="about">About Us</label>
    </router-link>
    <router-link to="/featur">
      <input class="input-tabs" type="radio" id="feature" name="header">
      <label for="feature">Feature</label>
    </router-link>
    <router-link to="service">
      <input class="input-tabs" type="radio" id="service" name="header">
      <label for="service">Service</label>
    </router-link>
    <router-link to="Testimonials">
      <input class="input-tabs" type="radio" id="Testimonials" name="header" >
      <label for="Testimonials">Testimonials</label>
    </router-link>
    </div>
    <p class="lan">اللغة العربية</p>
    <button class="login">Log in</button>
    
    
    </header>
    <p class="safe">safe & faster</p>
    <p class="logi">logistic services</p>
    <input class="order-id" type="text" placeholder=" Enter Your Odrder ID">
    <button class="track">track</button>

    <div ><img class="icon" src="@/assets/call.svg"></div>
    <div ><img class="icon2" src="@/assets/loc.svg"></div>
    <div ><img class="icon3" src="@/assets/login.svg"></div>
    <div ><img class="icon4" src="@/assets/Line.svg"></div>
    <div ><img class="icon5" src="@/assets/what.svg"></div>
    <div ><img class="icon6" src="@/assets/ins.svg"></div>
    <div ><img class="icon7" src="@/assets/t.svg"></div>
</template>
     
<script lang="ts">
import { Vue } from 'vue-class-component'
export default class HomeView extends Vue {}

</script>

    
<style scoped>
.bg{
position: absolute;
bottom: 100;
left:0;
background: rgba(0, 0, 0, 0.67);
width: 100%;
height: 100%;
}
.bg-jedex{
  position: absolute;
  width: 100%;
  left:0;
  height: 99.7%;
  padding: 0;
  margin: 0;
}

.white-header{
 
  position: absolute;
  left: -60vh;
  top: 50px;
  background-color:#ffffff;
  height:47px;
width:128.7%;
opacity:3;

}
.red-header{
  
  position: absolute;
  left: -60vh;
  top: 0px;
  background-color: #ED4445;
  height:50px;
width:128.6%;
opacity:3;
}

#red-icon{
  position: relative;
  display: float;
  margin-left: 5%;
  font-size: 15px;
  color: #FAFAFA;
  top:30%;
  left: 4%;
}
.menu{
  position: absolute;
  top:60px;
  left:300px;
}

.login{
  position: relative;
  left: 1%;
  font-family: 'Poppins';
  font-size: 14px;
  color: #FAFAFA;
  background-color: #0E2944;
  top:45px;
  left: 90%;
  border-radius: 9.69444px;
  border: none;
  width: 100px;
  height: 43px;
  text-transform: capitalize;
  cursor: pointer;
}
.vertical{
  position: relative;
  width: 0.1%;
  height:25%;
  background-color: #FAFAFA;
  left: 80.5%;
  top: 12%;
}


.jedex-logo{
  position: absolute;
  width: 10%;
  height:10%;
  left: 100px;
  top: 20px;
}
.logo-context{
  position: absolute;
  width: 32.9%;
  height:40.3%;
  left: -1em;
  top: -4.3em;
}
.menu{

}

.top-header{
position: absolute;
top: 100%;
left: 22%;
}
label{
  position: relative;
  margin-left: 40px;
  left: 70px;
  color: #353535;
  font-family: 'Poppins';
  font-size: 15px;
  cursor: pointer;
}
.input-tabs{
  display: none;
}
input:checked + label{
  color: #ED4445;
}
.lan{
  position: absolute;
  top:46px;
  left: 80%;
  font-size: 17px;
  font-weight: 700px;
  font-family: 'SF Arabic Rounded';
  cursor: pointer;
}
.log{
  position: inherit;
  left: 83%;
  top: 53%;
  font-size: 12px;
  font-weight: 500px;
  font-family: 'Poppins';
  background-color: #0E2944;
  color: #FAFAFA;
  box-sizing: border-box;
  border: none;
  border-radius: 10px;
  padding-top: 7px;
  padding-bottom: 8px;
  padding-left: 25px;
  padding-right: 25px;
  cursor: pointer;
  text-transform: capitalize;
}
a:link{
  text-decoration: none;
}
.safe{
  position: absolute;
  left: 35%;
  top: 30%;
  color: #FAFAFA;
  font-size: 60px;
  text-transform: capitalize;
  font-family: 'poppins';
}
.logi{
  position: absolute;
  left: 40%;
  top: 50%;
  color: #FAFAFA;
  font-size: 30px;
  text-transform: capitalize;
  font-family: 'poppins';
}
.order-id{
  position: absolute;
  width: 29.8%;
  height: 8%;
  left: 35%;
  top: 68%;
  font-size: 16px;
  font-family: 'Poppins';
  border-radius: 10px 0 0 10px;
  border: none;
}
.track{
  position: absolute;
  width: 8%;
  height: 8.5%;
  left: 62%;
  top: 68%;
  border: none;
  font-size: 16px;
  font-family: 'Poppins';
  text-transform: capitalize;
  background-color: #ED4445;
  color: #FAFAFA;
  border-radius: 0 10px 10px 0;
  cursor: pointer;
}
.icon{
  position: absolute;
  width: 10%;
  height: 10%;
  top:2px;
  left: 390px;
}
.icon2{
  position: absolute;
  height: 11%;
  width: 11%;
  top:1px;
  left: 590px;
}
.icon3{
  position: absolute;
  width: 7%;
  height: 7%;

  top:10px;
  left: 970px;
}
.icon4{
  position: absolute;
  width: 6%;
  height: 6%;

  top:11px;
  left: 1030px;
}
.icon5{
  position: absolute;
  width: 3%;
  height: 3%;

  top:18px;
  left: 1070px;
}
.icon6{
  position: absolute;
  width: 3%;
  height: 3%;

  top:18px;
  left: 1120px;
}
.icon7{
  position: absolute;
  width: 3%;
  height: 3%;

  top:18px;
  left: 1180px;
}
</style>