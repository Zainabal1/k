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
      <input class="input-tabs" type="radio" id="about" name="header"  >
      <label for="about">About Us</label>
    </router-link>
    <router-link to="/featur">
      <input class="input-tabs" type="radio" id="feature" name="header" checked>
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

    <div class="box">

      <div class="p"><h1>WHAT MAKE AS SPECIAL</h1></div>
      <div class="p1"><P>Inside And Out Side The Region</P></div>
      <div class="p2"><P>FULL Coverge</P></div>
      <div class="p3"><P>ALL KINDS OF PRODUCT</P></div>
      <div class="p4"><P>ONLINE PAMENT</P></div>
      <div class="p5"><P>DELIVERY IN LESS THAN HOUR</P></div>
      <div class="p6"><P>DOOR PICKUP</P></div>
    </div>

    
    <div ><img class="i" src="@/assets/lo.svg"></div>
    <div ><img class="i2" src="@/assets/f.svg"></div>
    <div ><img class="i3" src="@/assets/a.svg"></div>
    <div ><img class="i4" src="@/assets/on.svg"></div>
    <div ><img class="i5" src="@/assets/de.svg"></div>
    <div ><img class="i6" src="@/assets/d.svg"></div>

    <div><img class="img" src="@/assets/img.svg"></div>
    

    <div class="containr"></div>
    <div class="text"><h1>PRICES START FROM 15 PER 150 KILOGRAMS OUTSIDE<br>AND INSIDE THE CITY</h1></div>
    <button class="btn">Order A Captain Now </button>
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
.box{
position: absolute;
width: 500px;
height: 430px;
left: 400px;
top: 140px;

background: #F9F9F9;
}
.p{
  position: absolute;
  top: 9px;
  left:40px;
  color: black;
font-size: 10px;
font-family: 'Poppins';
}
.p1{
  position: absolute;
  top: 60px;
  left:60px;
  color: #686868;
font-size: 14px;
font-family: 'Poppins';
}
.p2{
  position: absolute;
  top: 110px;
  left:60px;
  color: #686868;
font-size: 14px;
font-family: 'Poppins';
}
.p3{
  position: absolute;
  top: 170px;
  left:60px;
  color: #686868;
font-size: 14px;
font-family: 'Poppins';
}
.p4{
  position: absolute;
  top: 230px;
  left:60px;
  color: #686868;
font-size: 14px;
font-family: 'Poppins';
}
.p5{
  position: absolute;
  top: 300px;
  left:60px;
  color: #686868;
font-size: 14px;
font-family: 'Poppins';
}
.p6{
  position: absolute;
  top: 370px;
  left:60px;
  color: #686868;
font-size: 14px;
font-family: 'Poppins';
}
.i{
  position: absolute;
  top:200px;
  left:420px;
}
.i2{
  position: absolute;
  top:260px;
  left:420px;
}
.i3{
  position: absolute;
  top:320px;
  left:420px;
}
.i4{
  position: absolute;
  top:380px;
  left:420px;
}
.i5{
  position: absolute;
  top:450px;
  left:420px;
}
.i6{
  position: absolute;
  top:520px;
  left:420px;
}
.img{
  position: absolute;


  width: 1450px;
height: 280px;
left: -10em;
top: 700px;
 }
 .containr{
position: absolute;
bottom: 100;
background: rgba(14, 41, 68, 0.87);
color: white;
width: 1390px;
height: 240px;
left: -10em;
top: 700px;
padding:20px;
}
.text{
  position: relative;
  top: 680px;
  text-align: center;
  color:#FAFAFA;
  font-family:'poppins';
  font-size: 16px;
}
.btn{
 
 box-sizing: border-box;
 position: absolute;
 width: 300px;
 height: 50px;
 left: 40%;
 border:none;
 top: 890px;
 background: #ED4445;

 border-radius: 9.69444px;
 font-family: 'Poppins';
 font-style: normal;
 font-weight: 500;
 font-size: 20px;
 line-height: 30px;
 text-transform: capitalize;
 color: #FFFFFF;
}

</style>