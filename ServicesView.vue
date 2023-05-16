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
      <input class="input-tabs" type="radio" id="feature" name="header" >
      <label for="feature">Feature</label>
    </router-link>
    <router-link to="service">
      <input class="input-tabs" type="radio" id="service" name="header" checked>
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
    <div class="box"></div>

    <div class="p2">
    <h1> DO YOU WANT TO INCREASE YOUR INCOME BY<br>JOINING JEDEX?

    </h1>
    </div>

    <div class="star"><img src="@/assets/star1.svg"></div>
    <div class="star2"><img src="@/assets/star1.svg"></div>
    <div class="star3"><img src="@/assets/star1.svg"></div>
    <div class="star4"><img src="@/assets/star1.svg"></div>
    <div class="star5"><img src="@/assets/star1.svg"></div>
    <div class="star6"><img src="@/assets/star1.svg"></div>
    <div class="star7"><img src="@/assets/star1.svg"></div>



    <div class="t1">
    Unlimited Reception Of Requests
</div>

<div class="t2">
 Requests From Stores And Individuals
</div>

<div class="t3">
Sort As Per Your Wish Accurate Delivery Confirmation
</div>

<div class="t4">
Rewarding Profits For Each Request
</div>

<div class="t5">
Arrived The Order With Your Car Or Bike
</div>

<div class="t6">
  Branch Delivery Support
</div>
<div class="t7">
100% Advance Payment
</div>

<div ><img class="google" src="@/assets/google1.svg"></div>
<div><img  class="app2" src="@/assets/apple1.svg"></div>

<div ><img class="mo1" src="@/assets/First.svg"></div>
<div><img  class="mo2" src="@/assets/Second.svg"></div>

<div class="p3">
    <h1> OUR AWESOME PARTNER </h1>
    </div>

    <div><img  class="box-one" src="@/assets/kk.svg"></div>
  <div> <img  class="box-two" src="@/assets/kk.svg"></div>
  <div><img class="box-tree" src="@/assets/kk.svg"></div>
  <div ><img class="box-for" src="@/assets/kk.svg"></div>
  <div><img class="box-five" src="@/assets/kk.svg"></div>

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
.p2{
  position: absolute;
  top:130px;
  left:58%;
  color:black;
  width: 522.96px;
 height: 22.82px;
  font-family:'poppins';
  font-size: 10px;
}
.star{
    position: absolute;
    height: 50%;
    top:220px;
    left:46em;

}
.star2{
    position: absolute;
    height: 50%;
    top:280px;
    left:46em;

}
.star3{
    position: absolute;
    height: 50%;
    top:330px;
    left:46em;

}
.star4{
    position: absolute;
    height: 50%;
    top:380px;
    left:46em;



}
.star5{
    position: absolute;
    height: 50%;
    top:430px;
    left:46em;


}
.star6{
    position: absolute;
    height: 50%;
    top:480px;
    left:46em;


}
.star7{
    position: absolute;
    height: 50%;
    top:530px;
    left:46em;


}
.t1{
    position: absolute;
    height: 50%;
    top:230px;
    left:50em;
    font-family: 'poppins';
    font-size: 16px;  
}
.t2{
    position: absolute;
    height: 50%;
    top:290px;
    left:50em;
    font-family: 'poppins';
    font-size: 16px;  
}
.t3{
    position: absolute;
    height: 50%;
    top:340px;
    left:50em;
    font-family: 'poppins';
    font-size: 16px;  
}
.t4{
    position: absolute;
    height: 50%;
    top:390px;
    left:50em;
    font-family: 'poppins';
    font-size: 16px;  
}
.t5{
    position: absolute;
    height: 50%;
    top:440px;
    left:50em;
    font-family: 'poppins';
    font-size: 16px;  
}
.t6{
    position: absolute;
    height: 50%;
    top:490px;
    left:50em;
    font-family: 'poppins';
    font-size: 16px;  
}
.t7{
    position: absolute;
    height: 50%;
    top:540px;
    left:50em;
    font-family: 'poppins';
    font-size: 16px;  
}

.google{
    position: absolute;
    top:100%;
    left:740px;
    height: 7%;
}
.app2{
    position: absolute;
    top:100%;
    left:930px;
    height: 7%;
}
.box{
position: absolute;
width: 1230px;
height: 490px;
left: 10px;
top: 140px;

background: #F9F9F9;
}
.mo1{
  position: absolute;
  height: 60%;
  top:150px;
  left:40px;
}
.mo2{
  position: absolute;
  height: 60%;
  top:200px;
  left:210px;
}
.p3{
  position: absolute;
  top:700px;
  left:1%;
  color:black;
  width: 522.96px;
 height: 22.82px;
  font-family:'poppins';
  font-size: 10px;
}
.box-one{
    position: absolute;
    top:800px;
    left:30px;
    height:  20%;
}

.box-two{
    position: absolute;
    top:800px;
    left:270px;
    height:  20%;
}
.box-tree{
    position: absolute;
    top:800px;
    left:500px;
    height:  20%;
}
.box-for{
    position: absolute;
    top:800px;
    left:730px;
    height:  20%;
}
.box-five{
    position: absolute;
    top:800px;
    left:970px;
    height:  20%;
   
}

</style>