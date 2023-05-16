<template>
  <header>
    <div class="red-header"></div>
    <div class="white-header">
     
     
      

    </div>

    <img class="logo-context" src="@/assets/j.svg">
    <img class="jedex-logo" src="@/assets/logo.svg">
    <div class="vertical"></div>
    <div class="menu">
        
    <router-link to='/main'>
      <input class="input-tabs" type="radio" id="home" name="header">
      <label for="home">Home</label>
    </router-link>
    <router-link to='/about'>
      <input class="input-tabs" type="radio" id="about" name="header" checked >
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

    <div ><img class="icon" src="@/assets/call.svg"></div>
    <div ><img class="icon2" src="@/assets/loc.svg"></div>
    <div ><img class="icon3" src="@/assets/login.svg"></div>
    <div ><img class="icon4" src="@/assets/Line.svg"></div>
    <div ><img class="icon5" src="@/assets/what.svg"></div>
    <div ><img class="icon6" src="@/assets/ins.svg"></div>
    <div ><img class="icon7" src="@/assets/t.svg"></div>


    <div class="p"><h1>JEDEX PROVIDNG A REIABLE<br> SERVICES</h1></div>
    <div class="t">
      <p>An electronic platform established in 2017 that seeks to be<br> the first platform in logistics services and the leader in<br> delivery and freight services through a wide network of<br> companies and individuals and a fleet of drivers available<br> around the clock throughout the region</p>
    </div>
    <div ><img class="img" src="@/assets/about.svg"></div>

    
    </header>
</template>

<style scoped>
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
a:link{
  text-decoration: none;
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
.p{
  position: absolute;
  top: 150px;
  left:40px;
  color: black;
font-size: 12px;
font-family: 'Poppins';
}
.t{
  position: absolute;
  top:40%;
  left:3%;
  color:black;
  width: 544px;
  height: 205px;
  font-weight: 500;
  font-size: 17px;
  text-transform: capitalize;

color: #686868;

  line-height: 40px;
  font-family:'poppins';
 
}
.img{
  position: absolute;
  top:150px;
  left:900px;
  height: 70%;
}

</style>