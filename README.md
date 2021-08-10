


<!DOCTYPE html>
<html>
    <head>
        <title>shopping web app</title>
        <meta charset="utf-8">
<link rel="stylesheet" href="style1.css">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
<link href='https://fonts.googleapis.com/css?family=Poppins' rel='stylesheet' type='text/css'>
   <style>
   				
   				 
  /* Make the image fully responsive */
  .carousel-inner img {
      width: %;
      height: %;
  }
  
  <!-- slide -->
  
  <style>
body {
  user-select: none;
  cursor:none;
}

body a {
  user-select: none;
  cursor:none;
}

.tooltip2 {
  position: relative;
  display: inline-block;
  border-radius: 0px;
  padding: 0px;
  margin-top: 0px;
  color: black;
  margin-left: 0px;
  margin-right: 0px;
  width: 24%;
  font-size: 10px;
  margin-bottom: 15px;
}

.tooltip2 a {
  cursor: none;
}

.tooltip2 .tooltiptext2 {
  visibility: hidden;
  width: 400%;
  background-color: #f1f1f1;
  color: #000;
  text-align: center;
  border-radius: 10px 10px 10px 10px;
  padding: 5px 0;
  position: absolute;
  z-index: 1;
  top: 150%;
  left: 0%;
  margin-left: 0px;
  opacity: 0;
  transition: opacity 0.5s;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}


.tooltip2:hover .tooltiptext2 {
  visibility: visible;
  opacity: 1;
}

*, *:before, *:after {
  box-sizing: inherit;
}

.column5 {
  float: left;
  margin-bottom: 16px;
  padding: 0 18px;
}

.column5 a {
  cursor: none;
}

@media screen and (max-width: 650px) {
  .column5 {
    width: 13.5%;
    display: block;
  }
}

.card5 {
  box-shadow: 0px 0px 0px 0px rgba(0, 0, 0, 0.2);
  border-radius: 0px;
  cursor: none;
  user-select: none;
}

.container5 {
  padding: 0 0px;
}

.row5 {
  margin-top: 20px;
  margin-bottom: -20px;
}

.container5::after, .row5::after {
  content: "";
  clear: both;
  display: table;
}

.title5 {
  color: black;
  font-size: 10px;
  text-align: center;
}

.rounded-image5 {
    border-radius: 2px;
    width: 70%;
    box-shadow:  0px 0px 0px 0px rgba(0, 0, 0, 0);
}

.ppob {
  margin-top: 15px;
  margin-bottom: 20px;
  float: left;
  width: 100%;
}

.imgs11 {
  padding: 0px;
  margin-top: 0px;
  border-radius: 0px;
  margin-bottom: 5px;
  width:50%;
  transition: 0.3s;
}

.imgs11:hover {
  background-color: #f1f1f1;
  border-radius: 100px;
  box-shadow: 1px 2px 4px 1px rgba(0, 0, 0, 0.2);
  transition: 0.3s;
}
<!-- menu -->
  
  
  
   *{
    margin: 0;
    padding: 0;
    text-decoration: none;
    font-family: 'Poppinsggg', sans-serif;
    box-sizing:border-box;
}

.main{
    height:162px;
    background-position: center;
    background-size: cover;
    overflow-x: hidden;
    position: relative;
    width: 100%;
    background:#fff;
    box-shadow:0 0 5px rgba(0,0,0,0.2);
   -webkit-box-shadow:0 0 5px rgba(0,0,0,0.2);
}
html,body{
    width:100%;
    overflow-x:hidden;
    scroll-behavior:smooth;
}
.nav-bar{
    display: flex;
    padding:17px 23px;
    width: 100%;
    background:white;
    line-height: 25px;
    box-shadow: 0 0 3px 0 #ccc;
    -webkit-box-shadow:0 0 3px 0 #ccc;
    
}
.nav-bar form{
    margin:5px 30px;
}
.nav-bar form input{
    outline:none;
    text-indent:10px;
    line-height:30px;
}
input:active,input:focus{
    border-color: transparent;
    border-bottom: 2px solid deeppink;
}
.nav-bar .fa-close,.nav-bar .fa-bars{
    display: none;
}
.icon{
    color:#000;
    font-size:23px;
    font-weight: bold;
    right:0px;
    padding:5px;
    position:absolute ;
    margin:10px 19px;
}
.super{
    height:20px;
    width:20px;
    border-radius:50%;
    background:deeppink;
    position:absolute ;
    margin-top:-36px;
    margin-left:15px;
    color:#fff;
    font-size:10px;
    align-items:center;
    justify-content:center;
    display:flex;
}
.nav-links{
    flex: 1;
}
.nav-links ul{
   
    display: inline;
}
.nav-links ul li{
    list-style: none;
    display: inline-block;
    padding: 8px 25px;
}
.nav-links ul a{
    text-decoration: none;
    font-size: 17px;
    padding: 7px 13px;
    text-transform: uppercase;
    float:left;
    font-weight: 400;
   
}
.nav-links ul a:hover{
    transition: .5s;
    color:deeppink;
    animation:rb 1s ;
  //animation-iteration-count:2;
}

@keyframes rb {
  0% {transform: scale3d(1, 1, 1);}
  30% { transform: scale3d(1.25, 0.75, 1);}
  40% { transform: scale3d(0.75, 1.25, 1);}
  50% { transform: scale3d(1.15, 0.85, 1);}
  65% { transform: scale3d(.95, 1.05, 1);}
  75% { transform: scale3d(1.05, .95, 1);}
  100% { transform: scale3d(1, 1, 1);}
}
.categories{
    height:auto;
    width:100%;
    position:absolute ;
    background:transparent ;
    border-radius:5px 5px;
    overflow:auto;
    white-space:nowrap ;
}
.images {
  overflow-x: scroll;
  overflow-y: hidden;
  white-space: nowrap;
  padding-top:15px;
  padding-left:3px;
}
 .img_1{
    display: inline-block;
  }
 .img_1 img{
     height:50px;
     width:50px;
     border-radius:50%;
    margin:0 15px; 
    background:white;
    padding:5px;
    box-shadow:0 0 5px 0px rgba(0,0,0,0.25);
    -webkit-box-shadow:0 0 5px 0px rgba(0,0,0,0.25);
 }
 .img_1 img:hover{
     border:2px solid deeppink;
 }
 .img_1 h6{
     margin-left:20px;
     text-transform:capitalize;
     font-size:12px;
     font-weight:bold;
     padding-top:8px;
 }
 .images .img_1::after{
    content: '';
    width: 0%;
    height: 3px;
    background:deeppink;
    display:block ;
    margin: auto;
    transition: .5s;
}
.images .img_1:hover::after{
    width: 100%;
}
.img_1:hover  h6{
    color:deeppink;
}
.men_related{
    height:auto;
    width:100%;
    background-color:white;
   overflow:auto;
    white-space:nowrap ;
    box-shadow:0 0 5px 0 rgba(0,0,0,0.2);
    -webkit-box-shadow:0 0 5px 0px rgba(0,0,0,0.2);
    position:absolute ;
    margin-top:7px;
    text-transform:capitalize;
}
.list{
    overflow-x: scroll;
  overflow-y: hidden;
  white-space: nowrap;
  padding-top:15px;
  padding-left:15px;
}
.mensware{
    display:inline-block ;
}
.mensware h5{
    font-size:15px;
   font-weight:400;
   margin:0 20px;
   line-height:33px;
}
.list h5::after{
    content: '';
    width: 0%;
    height: 3px;
    background:deeppink;
    display: block;
    margin: auto;
    transition: .5s;
}
.list h5:hover::after{
    width: 100%;
}
.list h5:hover{
    animation: shake 0.82s cubic-bezier(.36,.07,.19,.97) both;
}
@keyframes shake {
  10%, 90% {transform: translate3d(-1px, 0, 0);} 
  20%, 80% {transform: translate3d(2px, 0, 0);}
  30%, 50%, 70% { transform: translate3d(-4px, 0, 0);}
  40%, 60% { transform: translate3d(4px, 0, 0);}
 }
.list h5:hover::after .mensware h5{
    transition: .5s;
    color:deeppink;
}
.products_section{
    height:630px;
    width:100%;
    position:absolute ;
    //background-color:#aaa;
    margin-top:50px;
}
.product{
    height:210px;
    float:left;
    width:150px;
    background:#eee;
    margin-top:40px;
    margin-right:10px;
    margin-left:2px;
    border:0.3px solid rgba(0,0,0,0.1);
}
.product:hover{
    box-shadow:0 0 10px 0 #ccc;
    -webkit-box-shadow:0 0 10px 0 #ccc;
}
.img_2  img{
    height:120px;
    width:100%;
}
.product h6{
    font-size:15px;
    font-weight:bold;
    padding:10px;
}
.product h6 span{
    font-size:10px;
    float:right;
    padding-top:3px;
}
.product h5 {
    font-weight:400;
    font-size:11px;
    text-decoration:line-through ;
    margin-top:-15px;
    margin-left:9px;
}
.star{
    display: inline-block;
    font-weight:bold;
    font-size:10px;
    margin-top:-7px;
    position:absolute ;
    padding:0 9px;
}
.star .fa{
    padding:1px;
}
.slider{
    height:150px;
    width:90%;
    background:pink;
    border-radius:5px;
    display:flex;
    margin:auto;
    margin-top:7px;
}
.dis{
  height:20px;
  width:50px;
  position:absolute ;
  background:deeppink;
  margin:5px 0;
  }
  .dis p{
  color:#fff;
  font-size:12px;
  font-weight:bold;
  margin-left:5px;
  margin-top:2px;
}
.dis:before{
    content:"";
    position:absolute ;
    border-top:10px solid deeppink;
    border-left:10px solid transparent ;
    border-right:10px solid transparent ;
    transform:rotate(-90deg);
    margin-left:45px;
    margin-top:5px;
}
.pic img{
    height:120px;
    width:150px;
    margin-top:30px;
}
.text{
    float:right;
    margin-top:10px;
    padding:10px;
    font-size:15px;
    text-transform:capitalize ;
}
.btn-primary{
    background:deeppink;
    margin-top:-8px;
    border:1px solid deeppink;
}
.bottom{
    height:70px;
    width:100%;
    background-color:#fff;
   overflow:auto;
    white-space:nowrap ;
    box-shadow:0 0 5px 0 rgba(0,0,0,0.2);
    -webkit-box-shadow:0 0 5px 0 rgba(0,0,0,0.2);
    position:fixed;
    bottom:0;
    text-transform:capitalize;
    align-items:center;
    text-align:center;
}
.fa-icons{
   display:inline-block ;
    margin-left:15px;
}
.fa-icons .fa{
    font-size:22px;
    margin:auto;
    height:47px;
    width:47px;
    border-radius:50%;
   -webkit-box-shadow: 9px 19px 16px rgba(163, 177, 198, 0.4), -9px -9px 16px white;
    box-shadow: 9px 19px 16px rgba(163, 177, 198, 0.4), -9px -9px 16px white;
    margin-right:20px;
    margin-top:8px;
    padding-top:5px;
}
.fa-icons:hover .fa{
   -webkit-box-shadow: inset 9px 9px 19px #e9e9e9, -9px -9px 19px #ffffff;
    box-shadow: inset 9px 9px 19px #e9e9e9, -9px -9px 19px #ffffff;
         
}
.fa-icons:hover .fa{
    color:deeppink;
}
.fa-icons p{
    font-size:8px;
    padding:2px;
}

#cart{
    height:auto;
    width:auto;
    background:deeppink;
    padding:9px 15px;
    color:white;
    border-radius:5px;
}

.profile{
    height:80px;
    width:80px;
    position:absolute ;
    background:white;
    border-radius:50%;
    margin-left:60px;
    text-align:center;padding-top:10px;
    margin-top:20px;
}
.profile .fa{
    font-size:60px;
}
.down_1{
   margin-top:30px;
}
.line,.line1{
    position:absolute;
    height:.5px;
    width:80%;
    background:gray;
    margin-top:160px;
    margin-left:10px;
}
.line1{
    margin-top:275px;
}
.profile p{
    color:deeppink;
    padding-top:30px;
}
.buy{
        height:30px;
        width:100%;
        background:deeppink;
        text-align:center;
        margin-top:20px;
       padding-top:2px;
       color:white;
       display:flex;
    }
    .buy p{
        font-size:11px;
        font-weight:bold;
        margin:auto;
    }
    .countdown{
    display:flex;
    margin-top:20px ;
    margin-left:20px;
}
.countdown h6{
   margin-top:10px;
   font-weight:bold;
   font-size:10px;
}
.countdown h6 .fa{
    padding-left:5px;
}
.sale p{
   // margin:5px 20px;
    font-size:15px;
    margin-top:4px;
}
.countdown div{
    position:relative ;
    height:30px;
    width:30px;
    line-height:30px;
    text-align:center ;
    background:rgba(0,0,0,0.7);
    background-color:#000;
    color:#fff;
    margin:0 3px;
    font-size:10px;
    font-weight:bold;
    border-radius:50%;
}
.countdown  #day:after{
    content:"D";
    padding-left:2px;
}

.countdown  #hours:after{
    content:"H";
    padding-left:2px;
}

.countdown  #minutes:after{
    content:"M";
    padding-left:2px;
}

.countdown  #seconds:after{
    content:"S";
    padding-left:2px;
}
.loader {
    position: fixed;
    left: 0px;
    top: 0px;
    width: 100%;
    height: 100%;
    z-index: 9999;
    background-color:#fff;
    background:rgba(255,255,255,0.95);
    background-repeat:no-repeat ;
    display:flex;
    align-items:center;
    justify-content:center;
}
.loader .load{
    height:50px;
    width:50px;
    position:absolute ;
    transform:rotate(45deg);
    background:deeppink;
    animation:2s expand  linear infinite forwards;
}
.loader .load:before{
    height:50px;
    width:50px;
    position:absolute ;
    transform:rotate(-45deg);
    background:#fff;
    content:"";
}
.loader .text{
    font-size:18px;
    margin-top:35%;
    
}
@keyframes expand{
    0%{transform:scale(0)rotate(360deg);}
    50%{transform:scale(1)rotate(-360deg);}
    100%{transform:scale(0)rotate(360deg);}
}
@media screen and (max-width: 768px){
    .nav-bar{
        padding: 10px 30px;
    }
    .fa-bars{
        position: absolute;
        left: 0px;
        top: 10px;
    }
    .nav-logo input[type="text"]{
        width:100%;
    }
    .nav-logo i{
        font-size: 25px;
        right:0;
    }
    .nav-bar .fa-close,.nav-bar .fa-bars{
        display: block;
        color:#000;
        margin: 10px 25px;
        font-size: 22px;
        cursor: pointer;
    }
    .nav-bar .fa-close{
        color: #fff;
    }
    .fa-close{
        float:right;
    }
    .nav-links{
        height: 100vh;
        width:220px;
        background-color:#000;
        background:rgba(0,0,0,0.9);
        top: 0;
        left:-220px;
        position:fixed;
        text-align: left;
        z-index: 10;
        transition: 0.5s;
        font-weight:700;
    }
    .nav-links span{
        font-size: 30px;
        color:#fff;
        margin: 10px 25px;
        cursor: pointer;
    }
    .nav-links ul a{
        display: block;
        color:#fff;
    }
  }
  
  
 . Img{ width:"600px"

           

/*-------------- Main Page -----------*/

/*--*/




   
     </style>
    </head>
    <body>

</div>
        <div id="header" class="header-div">
            
            <div id="bg" class="bg">
                
                <div class="grid header-nav">
                   
                </div>

         
                
                
                
                
                <div class="main" id="main">
        <div class="nav-bar">
           <div class="nav-logo">
             <form>
              <input type="text" placeholder="Search by product,brand ">
             </form>
           </div>
        <div class="nav-links" id="nav-links">
         <i class="fa fa-close"onclick="closeNav()"></i>
           <ul>
           <div class="profile">
               <i class="fa fa-user"></i>
               <p>Hello,User</p>
           </div><br><br><br><br>
<br><br>
            <a href="#"><i class="fa fa-shopping-cart"><li>My orders</li></i></a>
            <a href="#"><i class="fa fa-shopping-bag"><li>My wishlist</li></i></a>
            <a href="#"><i class="fa fa-user"><li>My Account</li></i></a>
            <div class ="line"></div>
            <a href="#"><i class="fa fa-th-list"><li class="down_1"> Language</li></i></a>
            <a href="#"><i class="fa fa-gear"><li>settings</li></i></a>
            <div class="line1"></div>
           <a href="#"><i class="fa fa-envelope"><li class="down_1">sign in</li></i></a>
           </ul>
        </div>
<div class="icon" ><i class="fa fa-shopping-cart"></i><span class="super">3</span></div>
<i class="fa fa-bars"onclick="show()"></i></div>
                
                
                
                
                
                
</div>
     <div class="main" id="main">
        <div class="nav-bar">
           <div class="nav-logo">
             <form>
         Now
             </form>
           </div>
     </div>

                
                
                
                
                
                
                <div id="demo" class="carousel slide" data-ride="carousel">
 
  <!-- Indicators -->
  <ul class="carousel-indicators" style="margin-left:-35%;margin-bottom:0pc;">
    <li data-target="#demo" data-slide-to="1" class="active"></li>
    <li data-target="#demo" data-slide-to="2"></li>
    <li data-target="#demo" data-slide-to="3"></li>
    <li data-target="#demo" data-slide-to="4"></li>
    <li data-target="#demo" data-slide-to="5"></li>
    

  </ul>
  
  <!-- The slideshow -->
  <div class="carousel-inner">
    <div class="carousel-item active">
    <img src="https://lh3.googleusercontent.com/-vbSx05NF5R0/X-NTeRjeAaI/AAAAAAAAZeY/EWgfCLiaO7kE7Jkh8qOuN7NnPsK-N4izwCLcBGAsYHQ/s1600/1608733541529541-2.png" alt="pict1" width="100%" height="auto">
    </div>
 <div class="carousel-item">
    <img src="https://lh3.googleusercontent.com/-ZNA2ANexOrU/X-NTf7DVehI/AAAAAAAAZec/cloZl4nzS8AVN-iDMx6gsqSMq8UbPvLRgCLcBGAsYHQ/s1600/1608733562146396-1.png" alt="pict2" width="100%" height="auto">
    </div>
    <div class="carousel-item">
    <img src="https://lh3.googleusercontent.com/-ByObQQ6Sq4E/X-NThrVGvsI/AAAAAAAAZeg/eINC-uQK1TwjZt1uk0nqxSd529ImxOQDwCLcBGAsYHQ/s1600/1608733567709792-0.png" alt="pict2" width="100%" height="auto">
    </div>
    <div class="carousel-item">
     <img src="https://lh3.googleusercontent.com/-vbSx05NF5R0/X-NTeRjeAaI/AAAAAAAAZeY/EWgfCLiaO7kE7Jkh8qOuN7NnPsK-N4izwCLcBGAsYHQ/s1600/1608733541529541-2.png" alt="pict3" width="100%" height="auto">
    </div>
    <div class="carousel-item">
    <img src="https://lh3.googleusercontent.com/-ZNA2ANexOrU/X-NTf7DVehI/AAAAAAAAZec/cloZl4nzS8AVN-iDMx6gsqSMq8UbPvLRgCLcBGAsYHQ/s1600/1608733562146396-1.png" alt="pict3" width="100%" height="auto">
    </div>
   
  </div>

</div></div>
                
                
                
                
                
                
                <div class="ppob">
    
<div class="tooltip2"><center><img class="imgs11" src="https://lh3.googleusercontent.com/-0dTy3213_FA/YAMf8CRg2TI/AAAAAAAAa_0/u_nqtshXczQSSIfDsa3b_dMxV_aEV8TPACLcBGAsYHQ/s1600/1610817517543032-2.png" alt=""><br/>Pulsa</center>
  <span class="tooltiptext2" style="margin-left:9%;border-radius:10px;">
      
      <b>PULSA</b> 
      <br/>
      <br/>
      
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/715/715794.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Rp 5.000</b></p>
      </div>
    </div>
  </div>

   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/715/715794.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Rp 10.000</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/715/715794.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Rp 25.000</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/715/715794.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Rp 50.000</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/715/715794.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Rp 75.000</b></p>
      </div>
    </div>
  </div>

   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/715/715794.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Rp 100.000</b></p>
      </div>
    </div>
  </div>
      
  </span>
</div>    

<div class="tooltip2"><center><img class="imgs11" src="https://lh3.googleusercontent.com/-QxI4nJAXgc8/YAMf8yhoUVI/AAAAAAAAa_4/Qr4SmRbM7xoaaSwB0ziOfIph-zu3Iq5IACLcBGAsYHQ/s1600/1610817520938118-1.png" alt=""><br/>Pascabayar</center>
  <span class="tooltiptext2" style="margin-left:-95%;border-radius:10px;">
      
      <b>PASCABAYAR</b> 
      <br/>
      <br/>

   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/694/694059.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>PDAM</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/33/33145.svg" alt="elektronik"></center></a>

<div class="container5">
        <p class="title5"><b>PLN</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/2389/2389778.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Etoll</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/2904/2904203.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>BPJS</b></p>
      </div>
    </div>
  </div>
      
  </span>
</div>    

<div class="tooltip2"><center><img class="imgs11" src="https://lh3.googleusercontent.com/-4caQKpW2b-I/YAMf9njzeYI/AAAAAAAAa_8/xPYcXrGIsk8UM-9c1DhQWLgL7TlYOVjlwCLcBGAsYHQ/s1600/1610817523785653-0.png" alt=""><br/>Internet</center>
  <span class="tooltiptext2" style="margin-left:-200%;border-radius:10px;">
      
      <b>INTERNET</b> 
      <br/>
      <br/>

   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/1332/1332700.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>OVO</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/1332/1332700.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Dana</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/1332/1332700.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Gopay</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/1332/1332700.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Linkaja</b></p>
      </div>
    </div>
  </div>
      
  </span>
</div>    

<div class="tooltip2"><center><img class="imgs11" src="https://lh3.googleusercontent.com/-zZZRn0Fo8e4/YAO5J8EYiaI/AAAAAAAAbCg/qGDMlpdGVTgNS4nu8espsbpRiM5GpFyEACLcBGAsYHQ/s1600/1610856739963979-0.png" alt=""><br/>SMS Telepon</center>
  <span class="tooltiptext2" style="margin-left:-300%;border-radius:10px;">
      
      <b>SMS TELEPON</b> 
      <br/>
      <br/>

   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://cdn1.codashop.com/S/content/mobile/images/product-tiles/mlbb_tile.jpg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Mobile L</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://cdn1.codashop.com/S/content/mobile/images/product-tiles/pubgm_rps_tile.jpg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>PUBGM</b></p>
      </div>
    </div>
  </div>
      
  </span>
</div>

<div class="tooltip2"><center><img class="imgs11" src="https://lh3.googleusercontent.com/-dGFrdUspDIQ/YAJXXMfOMrI/AAAAAAAAa8I/apdoDHwG55EdRXWW4amQUF1MKBeFgp1zwCLcBGAsYHQ/s1600/1610766170070709-1.png" alt=""><br/>Voucher Game</center>
  <span class="tooltiptext2" style="margin-left:9%;border-radius:10px;">
      
      <b>VOUCHER GAME</b> 
      <br/>
      <br/>
      
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/715/715794.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Rp 5.000</b></p>
      </div>
    </div>
  </div>

   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/715/715794.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Rp 10.000</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/715/715794.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Rp 25.000</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/715/715794.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Rp 50.000</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/715/715794.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Rp 75.000</b></p>
      </div>
    </div>
  </div>

   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/715/715794.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Rp 100.000</b></p>
      </div>
    </div>
  </div>
      
  </span>
</div>    

<div class="tooltip2"><center><img class="imgs11" src="https://lh3.googleusercontent.com/-yWkySxvf-og/YAJXX7xYtgI/AAAAAAAAa8M/8_YA5gv8rxwrT6P2jp7EUux08Zz-B3_PgCLcBGAsYHQ/s1600/1610766173197323-0.png" alt=""><br/>Feature Game</center>
  <span class="tooltiptext2" style="margin-left:-95%;border-radius:10px;">
      
      <b>FEATURE GAME</b> 
      <br/>
      <br/>

   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/694/694059.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>PDAM</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/33/33145.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>PLN</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/2389/2389778.svg" alt="elektronik"></center></a>

<div class="container5">
        <p class="title5"><b>Etoll</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/2904/2904203.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>BPJS</b></p>
      </div>
    </div>
  </div>
      
  </span>
</div>    

<div class="tooltip2"><center><img class="imgs11" src="https://lh3.googleusercontent.com/-wfNC4r9CMxc/YAJ0sD2hpII/AAAAAAAAa9c/ryv3PZ22BLgY3Ou83tr8hr-qpLXZoCqrQCLcBGAsYHQ/s1600/1610773677651522-0.png" alt=""><br/>Ewalet</center>
  <span class="tooltiptext2" style="margin-left:-200%;border-radius:10px;">
      
      <b>EWALET</b> 
      <br/>
      <br/>

   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/1332/1332700.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>OVO</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/1332/1332700.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Dana</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/1332/1332700.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Gopay</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://www.flaticon.com/svg/static/icons/svg/1332/1332700.svg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Linkaja</b></p>
      </div>
    </div>
  </div>
      
  </span>
</div>    

<div class="tooltip2"><center><img class="imgs11" src="https://lh3.googleusercontent.com/-33c6N_Sq1No/YAJnO2sdk8I/AAAAAAAAa84/MuaodT-KPooVrfWAkrxzskXAw4yySsxIACLcBGAsYHQ/s1600/1610770233964025-0.png" alt=""><br/>Token PLN</center>
  <span class="tooltiptext2" style="margin-left:-300%;border-radius:10px;">
      
      <b>TOKEN PLN</b> 
      <br/>
      <br/>

   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://cdn1.codashop.com/S/content/mobile/images/product-tiles/mlbb_tile.jpg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>Mobile L</b></p>
      </div>
    </div>
  </div>
  
   <div class="column5">
    <a
href="#" style="text-decoration:none" target="_blank">
    <div class="card5">
      <center><img class="rounded-image5" src="https://cdn1.codashop.com/S/content/mobile/images/product-tiles/pubgm_rps_tile.jpg" alt="elektronik"></center></a>
      <div class="container5">
        <p class="title5"><b>PUBGM</b></p>
      </div>
    </div>
  </div>
      
  </span>
</div>

</div>

         
        </div>
            
                
                
                
                
</div>
     <div class="main" id="main">
        <div class="nav-bar">
           <div class="nav-logo">
             <form>
         Now
             </form>
           </div>
     </div>

                
                
                
                <div id="curve" class="header-curve">
                
                <div class="grid travel-meta">
                    <p class="dtod">
      
         

                
         
  <div class="slider">
        <div class="dis">
            <p>50% off</p>
        </div>
    <div class="pic">
        <img src="https://i.ibb.co/JRtbGHr/fa.png">
    </div>
    <div class="text">
        <p>shop essential products for you and your family </p>
        <div class="btn btn-primary">shop now <i class="fa fa-angle-double-right"></i></div>
    </div>
    </div>


</div>
     <div class="main" id="main">
        <div class="nav-bar">
           <div class="nav-logo">
             <form>
         Now
             </form>
           </div>
     </div>



<div class="categories">
    <div class="images">
        <div class="img_1" id="men">    
            <img src="https://i.ibb.co/Sw629Sw/men.png" alt="men">
            <h6>men</h6> 
        </div>
        <div class="img_1"id="women">    
            <img src="https://i.ibb.co/Tk0QHTr/dress.png" alt="women">
            <h6>women</h6> 
        </div>
        <div class="img_1"id="beauty">    
            <img src="https://i.ibb.co/gdPYpZT/l5.png" alt="beauty">
            <h6>Beauty </h6> 
        </div>
        <div class="img_1"id="gadgets">    
            <img src="https://i.ibb.co/p05NmZJ/g.png" alt="gadgets">
            <h6>gadgets</h6> 
        </div>
        <div class="img_1"id="home">    
            <img src="https://i.ibb.co/9Y9hjgL/h5.png" alt="home">
            <h6>home</h6> 
        </div>
        <div class="img_1"id="furniture">    
            <img src="https://i.ibb.co/qp8wBpp/Screenshot-20200412-055921.png"alt="furniture">
            <h6>furniture</h6> 
        </div>
        <div class="img_1"id="kids">    
            <img src="https://i.ibb.co/RjJDgJK/c.png" alt="kids">
            <h6>kids</h6> 
        </div>
    </div>
</div>  
</div>
  

    
        
         
        
        
        
<!-----------------men ware starts------------>
    <div id="men_click">
        <div class="men_related">
        <div class="list">i 
            <div class="mensware" id="suits">
               <h5>suits</h5>
           </div>
           <div class="mensware"id="tshirts">
               <h5>T-shirts</h5>
           </div>
           <div class="mensware"id="watches">
               <h5>watches</h5>
           </div>
           <div class="mensware"id="shoes">
               <h5>shoes</h5>
           </div>
           <div class="mensware"id="shirts">
               <h5>shirts</h5>
           </div>
           </div>
        </div>
<div id="first">
    <div class="products_section"id="pr_1">
        <div class="container">
            <div class="product">
                <div class="img_2">    
                    <img src="https://i.ibb.co/jbmN71W/Screenshot-20200413-060926.png">
                    <h6>$15<span>300+ sold</span></h6>
                    <h5>$32</h5>
                <div class="star">
 <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>   
               </div>
               <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
</div>
</div>
  
 <div class="product">
    <div class="img_2">    
        <img src="https://i.ibb.co/1n75WCd/Screenshot-20200413-060646.png"alt="suite1">
        <h6>$15<span>300+ sold</span></h6>
        <h5>$32</h5>
        <div class="star">
<i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>             </div>

<div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/gJgCzbf/Screenshot-20200411-165850.png"alt="suite1">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
  <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/z5q5q2T/Screenshot-20200413-061119.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>         
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
              
        </div>
    </div>
    <div class="products_section" id="pr_2">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/hFQ8TV9/Screenshot-20200413-064755.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>         
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/rHV806G/Screenshot-20200413-064531.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>            </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/RjFbMLt/Screenshot-20200413-064013.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   
<div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/1fX5RJg/Screenshot-20200413-063633.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  </div>
  </div>
 <div class="products_section"id="pr_3">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/wSWcF09/watch.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>           
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/fCrXG4H/Screenshot-20200413-071720.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>             
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/sHwh5f9/Screenshot-20200413-071612.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>         
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
<div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/JjRBkw4/Screenshot-20200413-071457.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  </div>
  </div>
  <div class="products_section" id="pr_4">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/zfPghgv/Screenshot-20200413-074350.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/k6Wwv8Q/Screenshot-20200413-074325.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
 <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/rHJP4cv/Screenshot-20200413-074222.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
<div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/3Bw957c/Screenshot-20200413-074121.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  </div>
  </div>
  <div class="products_section"id="pr_5">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/gb0HCp9/Screenshot-20200413-075448.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
 <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/M64H2R4/Screenshot-20200413-075315.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
  <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/RB7nPd4/Screenshot-20200413-075242.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
  <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/kMgf39K/Screenshot-20200413-075043.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
  <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  </div>
  </div>
  </div>
</div>
<!----------men ware ends------------------>
<!-----------women ware starts------------->
  <div id="women_click">
        <div class="men_related">
        <div class="list">
            <div class="mensware" id="ornaments">
               <h5>Ornaments</h5>
           </div>
           <div class="mensware"id="tops">
               <h5>tops</h5>
           </div>
           <div class="mensware"id="handbags">
               <h5>Handbags</h5>
           </div>
           <div class="mensware"id="footware">
               <h5>footware</h5>
           </div>
           <div class="mensware"id="kurthis">
               <h5>kurthis</h5>
           </div>
           </div>
        </div>
  
    <div id="second">
    <div class="products_section" id="pr_6">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/t2QRpxj/Screenshot-20200413-103747.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/dPmm26W/Screenshot-20200413-103704.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
 <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/2sKkDgm/Screenshot-20200413-103631.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/MVqBQqH/Screenshot-20200413-103345.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
  <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  </div>
  </div>
  <div class="products_section"id="pr_7">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/QFvmCzF/Screenshot-20200331-160358.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/kS8MSFY/Screenshot-20200414-143122.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/LPNwgbx/Screenshot-20200414-143311.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
<div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/3YQm75d/Screenshot-20200414-143503.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  </div>
  </div>
  <div class="products_section"id="pr_8">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/2YMfnM5/bag.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/rmDhQDc/Screenshot-20200414-143653.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/4gxBnLJ/Screenshot-20200414-143854.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
  <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/gMKMpjQ/Screenshot-20200414-143941.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  </div>
  </div>
  <div class="products_section"id="pr_9">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/k2rPmzW/ft1.jpg" alt="ft1">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/LP4t5CY/ft2.png" alt="ft2">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/bbYJjnw/ft3.jpg" alt="ft3">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
  <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/g72FHBz/ft4.jpg" alt="ft4">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  </div>
  </div>
  
  <div class="products_section"id="pr_10">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/86Dr1HV/Screenshot-20200414-172714.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/8Mfs488/Screenshot-20200414-202425.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/QbncLFs/Screenshot-20200414-175546.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
  <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/4156btH/Screenshot-20200414-175604.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  </div>
  </div>
  
  
  </div>
  </div>
  <!------------women ware ends----->
  <!------------beauty section starts---------->
  <div id="beauty_click">
        <div class="men_related">
        <div class="list">
           <div class="mensware"id="menn">
               <h5>men</h5>
           </div>
           <div class="mensware"id="womenn">
               <h5>women</h5>
           </div>
           </div>
        </div>
    <div id="third">
    <div class="products_section"id="pr_11">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/Qr2LqPc/m1.jpg" alt="m1">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>             
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/b6zV7jr/m.png" alt="m" >
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>           
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/NF6BJc5/m3.jpg"alt="suite1">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
  <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/ZBVDv9n/mm.png" alt="mm">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>         
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
              
        </div>
    </div>
    <div class="products_section" id="pr_12">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/3szvJR2/b1.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>         
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/cb90rHj/b2.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>            </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/Rp2Sy9D/b3.jpg">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/6DsPXgR/b4.jpg">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  </div>
  </div>
  </div>
</div>
  <!------------beauty section ends------------>
  <!-----------gadget section starts---------->
  <div id="gadget_click">
        <div class="men_related">
        <div class="list">
            <div class="mensware" id="laptops">
               <h5>laptops</h5>
           </div>
           <div class="mensware"id="mobiles">
               <h5>mobiles</h5>
           </div>
           <div class="mensware"id="hp">
               <h5>headphones</h5>
           </div>
           <div class="mensware"id="sw">
               <h5>smart wearables</h5>
           </div>
           </div>
        </div>
    <div id="four">
    <div class="products_section"id="pr_13">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/3NxCpzS/l1.jpg">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>             
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/558ZSbB/l2.jpg"alt="suite1">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>           
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/txFfm5d/l3.jpg"alt="suite1">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
  <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/18zSWWH/l4.jpg">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>         
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
              
        </div>
    </div>
    <div class="products_section" id="pr_14">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/R2Shf1J/Screenshot-20200417-111236.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>         
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/k1h5vN4/Screenshot-20200417-111820.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>            </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/6y7BQcc/Screenshot-20200417-112201.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/x3qH4NL/Screenshot-20200417-112442.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  </div>
  </div>
 <div class="products_section"id="pr_15">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/RQXjFFg/h1.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>           
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/s2gJJ2V/h2.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>             
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/M82BhP7/h3.jpg">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>         
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
<div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/8BDwDTW/h4.jpg" alt="h4">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  </div>
  </div>
  <div class="products_section" id="pr_16">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/XfB7RrG/sm1.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/rZDXvJB/sw2.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
 <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/H7pnMLj/sw3.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
<div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/NYdCfR2/sw4.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  </div>
  </div>
  </div>
</div>
  <!-----------gadget section ends------------>
  <!----------home section starts------------>
  <div id="home_click">
        <div class="men_related">
        <div class="list">
            <div class="mensware" id="hd">
               <h5>home decor</h5>
           </div>
           <div class="mensware"id="ka">
               <h5>kitchen appliances</h5>
           </div>
           <div class="mensware"id="cs">
               <h5>cookware&serveware</h5>
           </div>
           <div class="mensware"id="pf">
               <h5>pooja&festive</h5>
           </div>
           </div>
        </div>
    <div id="five">
    <div class="products_section"id="pr_17">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/CzjCCrh/hm1.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>             
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/0sxkYBX/hm2.png"alt="suite1">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>           
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/wLfMxkn/hm3.png"alt="suite1">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
  <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/vvTJZzR/hm4.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>         
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
              
        </div>
    </div>
    <div class="products_section" id="pr_18">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/YNsgVhY/k1.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>         
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/pwBtxgQ/k2.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>            </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/rv97W1R/k3.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/b6X8sDx/k4.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  </div>
  </div>
 <div class="products_section"id="pr_19">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/BL3PyNq/c1.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>           
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/4NNtWYC/c2.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>             
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/tDKqZHz/c3.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>         
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
<div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/2dwR8G2/c4.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  </div>
  </div>
  <div class="products_section" id="pr_20">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/m9t7hGR/p3.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/dD39TZT/p4.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
 <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/8PdzNZ2/p1.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  
<div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/xjCzXJX/p2.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
         <p>Add to cart</p>
    </div>
  </div>
  </div>
  </div>
  </div>
  </div>
</div>
  <!---health section ends------------->
  <!---furniture section starts---------->
  <div id="furniture_click">
        <div class="men_related">
        <div class="list">
            <div class="mensware" id="sofas">
               <h5>sofas</h5>
           </div>
           <div class="mensware"id="dt">
               <h5>dining tables</h5>
           </div>
           <div class="mensware"id="tables">
               <h5>tables</h5>
           </div>
           <div class="mensware"id="ac">
               <h5>accent chairs</h5>
           </div>
           </div>
        </div>
    <div id="six">
    <div class="products_section"id="pr_21">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/1fcrrK3/s1.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>             
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/6syrWmx/s2.png"alt="suite1">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>           
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/6WPm8VG/s3.jpg"alt="suite1">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
  <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/RY56cyd/s4.jpg">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>         
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
              
        </div>
    </div>
    <div class="products_section" id="pr_22">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/933w3c9/d1.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>         
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
   </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/HDYvNZL/d2.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>            </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/nMSHf8t/d3.jpg">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/rsJWTDQ/d4.jpg">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  </div>
  </div>
 <div class="products_section"id="pr_23">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/ZSCSBMs/t1.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>           
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/FqCJp0s/t2.jpg">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>             
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/BZJdS5y/t3.jpg">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>         
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
<div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/6nHtZKV/t4.jpg">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  </div>
  </div>
  <div class="products_section" id="pr_24">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/5GdFLjz/a1.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/47SgvmL/a2.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
 <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/sQxJpYR/a3.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
<div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
<div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/SXX0004/a4.jpg">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  </div>
  </div>
  </div>
</div>
  <!----furniture section ends---------->
  <!----kids section starts--------->
  <div id="kids_click">
        <div class="men_related">
        <div class="list">
            <div class="mensware" id="kw">
               <h5>kidswear</h5>
           </div>
           <div class="mensware"id="toys">
               <h5>Toys</h5>
           </div>
           </div>
        </div>
    <div id="seven">
    <div class="products_section"id="pr_25">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/zF4R7QG/Screenshot-20200417-101335.png"> 
<h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>             
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/1RD09y8/kw2.png"alt="suite1">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>           
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/6PgScDj/kw3.png"alt="suite1">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
  <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/FnsCX63/kw4.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>         
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
              
        </div>
    </div>
    <div class="products_section" id="pr_26">
        <div class="container">
      <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/tQ2cRsm/toy1.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>         
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/74g9B2V/toy2.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
   <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>            </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  
 <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/3mTxfyr/toy3.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  <div class="product">
    <div class="img_2">    
<img src="https://i.ibb.co/pJspfqr/toy4.png">
  <h6>$15<span>300+ sold</span></h6>
  <h5>$32</h5>
  <div class="star">
  <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
   </div>
   <div class ="buy" onclick="aler()">
                   <p>Add to cart</p>
               </div>
  </div>
  </div>
  </div>
  </div>
  </div>
</div>
  
      </div>
  </div>
    <script>
    
    var _0xa393=["\x67\x65\x74\x54\x69\x6D\x65","\x4A\x75\x6E\x20\x33\x30\x2C\x20\x32\x30\x32\x30\x20\x30\x30\x3A\x33\x30\x3A\x33\x30","\x66\x6C\x6F\x6F\x72","\x69\x6E\x6E\x65\x72\x54\x65\x78\x74","\x64\x61\x79","\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x42\x79\x49\x64","\x68\x6F\x75\x72\x73","\x6D\x69\x6E\x75\x74\x65\x73","\x73\x65\x63\x6F\x6E\x64\x73"];var countDownDate= new Date(_0xa393[1])[_0xa393[0]]();var x=setInterval(function(){var _0x8919x3= new Date()[_0xa393[0]]();var _0x8919x4=countDownDate- _0x8919x3;var _0x8919x5=1000;var _0x8919x6=_0x8919x5* 60;var _0x8919x7=_0x8919x6* 60;var _0x8919x8=_0x8919x7* 24;var _0x8919x9=Math[_0xa393[2]](_0x8919x4/ _0x8919x8);var _0x8919xa=Math[_0xa393[2]]((_0x8919x4% (_0x8919x8))/ (_0x8919x7));var _0x8919xb=Math[_0xa393[2]]((_0x8919x4% (_0x8919x7))/ (_0x8919x6));var _0x8919xc=Math[_0xa393[2]]((_0x8919x4% (_0x8919x6))/ _0x8919x5);document[_0xa393[5]](_0xa393[4])[_0xa393[3]]= _0x8919x9;document[_0xa393[5]](_0xa393[6])[_0xa393[3]]= _0x8919xa;document[_0xa393[5]](_0xa393[7])[_0xa393[3]]= _0x8919xb;document[_0xa393[5]](_0xa393[8])[_0xa393[3]]= _0x8919xc},1000)

 var _0x2739=["\x68\x69\x64\x65","\x23\x6D\x65\x6E\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x77\x6F\x6D\x65\x6E\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x62\x65\x61\x75\x74\x79\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x67\x61\x64\x67\x65\x74\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x68\x6F\x6D\x65\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x66\x75\x72\x6E\x69\x74\x75\x72\x65\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x6B\x69\x64\x73\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x66\x69\x72\x73\x74\x2C\x23\x73\x65\x63\x6F\x6E\x64\x2C\x23\x74\x68\x69\x72\x64\x2C\x23\x66\x6F\x75\x72\x2C\x23\x66\x69\x76\x65\x2C\x23\x73\x69\x78\x2C\x23\x73\x65\x76\x65\x6E","\x73\x68\x6F\x77","\x23\x6D\x65\x6E\x5F\x63\x6C\x69\x63\x6B","\x23\x77\x6F\x6D\x65\x6E\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x73\x65\x63\x6F\x6E\x64\x2C\x23\x62\x65\x61\x75\x74\x79\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x67\x61\x64\x67\x65\x74\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x68\x6F\x6D\x65\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x66\x75\x72\x6E\x69\x74\x75\x72\x65\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x6B\x69\x64\x73\x5F\x63\x6C\x69\x63\x6B","\x63\x6C\x69\x63\x6B","\x23\x6D\x65\x6E","\x23\x6D\x65\x6E\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x66\x69\x72\x73\x74\x2C\x23\x62\x65\x61\x75\x74\x79\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x67\x61\x64\x67\x65\x74\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x68\x6F\x6D\x65\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x66\x75\x72\x6E\x69\x74\x75\x72\x65\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x6B\x69\x64\x73\x5F\x63\x6C\x69\x63\x6B","\x23\x77\x6F\x6D\x65\x6E\x5F\x63\x6C\x69\x63\x6B","\x23\x77\x6F\x6D\x65\x6E","\x23\x6D\x65\x6E\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x67\x61\x64\x67\x65\x74\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x68\x6F\x6D\x65\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x66\x75\x72\x6E\x69\x74\x75\x72\x65\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x6B\x69\x64\x73\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x77\x6F\x6D\x65\x6E\x5F\x63\x6C\x69\x63\x6B","\x23\x62\x65\x61\x75\x74\x79\x5F\x63\x6C\x69\x63\x6B","\x23\x62\x65\x61\x75\x74\x79","\x23\x6D\x65\x6E\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x62\x65\x61\x75\x74\x79\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x77\x6F\x6D\x65\x6E\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x68\x6F\x6D\x65\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x66\x75\x72\x6E\x69\x74\x75\x72\x65\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x6B\x69\x64\x73\x5F\x63\x6C\x69\x63\x6B","\x23\x67\x61\x64\x67\x65\x74\x5F\x63\x6C\x69\x63\x6B","\x23\x67\x61\x64\x67\x65\x74\x73","\x23\x6D\x65\x6E\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x62\x65\x61\x75\x74\x79\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x67\x61\x64\x67\x65\x74\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x77\x6F\x6D\x65\x6E\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x66\x75\x72\x6E\x69\x74\x75\x72\x65\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x6B\x69\x64\x73\x5F\x63\x6C\x69\x63\x6B","\x23\x68\x6F\x6D\x65\x5F\x63\x6C\x69\x63\x6B","\x23\x68\x6F\x6D\x65","\x23\x6D\x65\x6E\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x77\x6F\x6D\x65\x6E\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x62\x65\x61\x75\x74\x79\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x67\x61\x64\x67\x65\x74\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x68\x6F\x6D\x65\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x6B\x69\x64\x73\x5F\x63\x6C\x69\x63\x6B","\x23\x66\x75\x72\x6E\x69\x74\x75\x72\x65\x5F\x63\x6C\x69\x63\x6B","\x23\x66\x75\x72\x6E\x69\x74\x75\x72\x65","\x23\x62\x65\x61\x75\x74\x79\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x67\x61\x64\x67\x65\x74\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x68\x6F\x6D\x65\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x66\x75\x72\x6E\x69\x74\x75\x72\x65\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x6D\x65\x6E\x5F\x63\x6C\x69\x63\x6B\x2C\x23\x77\x6F\x6D\x65\x6E\x5F\x63\x6C\x69\x63\x6B","\x23\x6B\x69\x64\x73\x5F\x63\x6C\x69\x63\x6B","\x23\x6B\x69\x64\x73","\x23\x66\x69\x72\x73\x74\x2C\x23\x70\x72\x5F\x31","\x23\x70\x72\x5F\x32\x2C\x23\x70\x72\x5F\x33\x2C\x23\x70\x72\x5F\x34\x2C\x23\x70\x72\x5F\x35","\x23\x73\x75\x69\x74\x73","\x23\x70\x72\x5F\x32\x2C\x23\x66\x69\x72\x73\x74","\x23\x70\x72\x5F\x31\x2C\x23\x70\x72\x5F\x33\x2C\x23\x70\x72\x5F\x34\x2C\x23\x70\x72\x5F\x35","\x23\x74\x73\x68\x69\x72\x74\x73","\x23\x70\x72\x5F\x33\x2C\x23\x66\x69\x72\x73\x74","\x23\x70\x72\x5F\x31\x2C\x23\x70\x72\x5F\x32\x2C\x23\x70\x72\x5F\x34\x2C\x23\x70\x72\x5F\x35","\x23\x77\x61\x74\x63\x68\x65\x73","\x23\x70\x72\x5F\x34\x2C\x23\x66\x69\x72\x73\x74","\x23\x70\x72\x5F\x31\x2C\x23\x70\x72\x5F\x32\x2C\x23\x70\x72\x5F\x33\x2C\x23\x70\x72\x5F\x35","\x23\x73\x68\x6F\x65\x73","\x23\x70\x72\x5F\x35\x2C\x23\x66\x69\x72\x73\x74","\x23\x70\x72\x5F\x31\x2C\x23\x70\x72\x5F\x32\x2C\x23\x70\x72\x5F\x33\x2C\x23\x70\x72\x5F\x34","\x23\x73\x68\x69\x72\x74\x73","\x23\x70\x72\x5F\x36\x2C\x23\x73\x65\x63\x6F\x6E\x64","\x23\x70\x72\x5F\x37\x2C\x23\x70\x72\x5F\x38\x2C\x23\x70\x72\x5F\x39\x2C\x23\x70\x72\x5F\x31\x30","\x23\x6F\x72\x6E\x61\x6D\x65\x6E\x74\x73","\x23\x70\x72\x5F\x37\x2C\x23\x73\x65\x63\x6F\x6E\x64","\x23\x70\x72\x5F\x36\x2C\x23\x70\x72\x5F\x38\x2C\x23\x70\x72\x5F\x39\x2C\x23\x70\x72\x5F\x31\x30","\x23\x74\x6F\x70\x73","\x23\x70\x72\x5F\x38\x2C\x23\x73\x65\x63\x6F\x6E\x64","\x23\x70\x72\x5F\x36\x2C\x23\x70\x72\x5F\x37\x2C\x23\x70\x72\x5F\x39\x2C\x23\x70\x72\x5F\x31\x30","\x23\x68\x61\x6E\x64\x62\x61\x67\x73","\x23\x70\x72\x5F\x39\x2C\x23\x73\x65\x63\x6F\x6E\x64","\x23\x70\x72\x5F\x36\x2C\x23\x70\x72\x5F\x37\x2C\x23\x70\x72\x5F\x38\x2C\x23\x70\x72\x5F\x31\x30","\x23\x66\x6F\x6F\x74\x77\x61\x72\x65","\x23\x70\x72\x5F\x31\x30\x2C\x23\x73\x65\x63\x6F\x6E\x64","\x23\x70\x72\x5F\x36\x2C\x23\x70\x72\x5F\x37\x2C\x23\x70\x72\x5F\x38\x2C\x23\x70\x72\x5F\x39","\x23\x6B\x75\x72\x74\x68\x69\x73","\x23\x70\x72\x5F\x31\x31\x2C\x23\x74\x68\x69\x72\x64","\x23\x70\x72\x5F\x31\x32","\x23\x6D\x65\x6E\x6E","\x23\x70\x72\x5F\x31\x32\x2C\x23\x74\x68\x69\x72\x64","\x23\x70\x72\x5F\x31\x31","\x23\x77\x6F\x6D\x65\x6E\x6E","\x23\x70\x72\x5F\x31\x33\x2C\x23\x66\x6F\x75\x72","\x23\x70\x72\x5F\x31\x34\x2C\x23\x70\x72\x5F\x31\x35\x2C\x23\x70\x72\x5F\x31\x36","\x23\x6C\x61\x70\x74\x6F\x70\x73","\x23\x70\x72\x5F\x31\x34\x2C\x23\x66\x6F\x75\x72","\x23\x70\x72\x5F\x31\x36\x2C\x23\x70\x72\x5F\x31\x35\x2C\x23\x70\x72\x5F\x31\x33","\x23\x6D\x6F\x62\x69\x6C\x65\x73","\x23\x70\x72\x5F\x31\x35\x2C\x23\x66\x6F\x75\x72","\x23\x70\x72\x5F\x31\x34\x2C\x23\x70\x72\x5F\x31\x33\x2C\x23\x70\x72\x5F\x31\x36","\x23\x68\x70","\x23\x70\x72\x5F\x31\x36\x2C\x23\x66\x6F\x75\x72","\x23\x70\x72\x5F\x31\x34\x2C\x23\x70\x72\x5F\x31\x35\x2C\x23\x70\x72\x5F\x31\x33","\x23\x73\x77","\x23\x70\x72\x5F\x31\x37\x2C\x23\x66\x69\x76\x65","\x23\x70\x72\x5F\x31\x38\x2C\x23\x70\x72\x5F\x31\x39\x2C\x23\x70\x72\x5F\x32\x30","\x23\x68\x64","\x23\x70\x72\x5F\x31\x38\x2C\x23\x66\x69\x76\x65","\x23\x70\x72\x5F\x31\x37\x2C\x23\x70\x72\x5F\x31\x39\x2C\x23\x70\x72\x5F\x32\x30","\x23\x6B\x61","\x23\x70\x72\x5F\x31\x39\x2C\x23\x66\x69\x76\x65","\x23\x70\x72\x5F\x31\x37\x2C\x23\x70\x72\x5F\x31\x38\x2C\x23\x70\x72\x5F\x32\x30","\x23\x63\x73","\x23\x70\x72\x5F\x32\x30\x2C\x23\x66\x69\x76\x65","\x23\x70\x72\x5F\x31\x37\x2C\x23\x70\x72\x5F\x31\x38\x2C\x23\x70\x72\x5F\x31\x39","\x23\x70\x66","\x23\x70\x72\x5F\x32\x31\x2C\x23\x73\x69\x78","\x23\x70\x72\x5F\x32\x32\x2C\x23\x70\x72\x5F\x32\x33\x2C\x23\x70\x72\x5F\x32\x34","\x23\x73\x6F\x66\x61\x73","\x23\x70\x72\x5F\x32\x32\x2C\x23\x73\x69\x78","\x23\x70\x72\x5F\x32\x31\x2C\x23\x70\x72\x5F\x32\x33\x2C\x23\x70\x72\x5F\x32\x34","\x23\x64\x74","\x23\x70\x72\x5F\x32\x33\x2C\x23\x73\x69\x78","\x23\x70\x72\x5F\x32\x31\x2C\x23\x70\x72\x5F\x32\x32\x2C\x23\x70\x72\x5F\x32\x34","\x23\x74\x61\x62\x6C\x65\x73","\x23\x70\x72\x5F\x32\x34\x2C\x23\x73\x69\x78","\x23\x70\x72\x5F\x32\x31\x2C\x23\x70\x72\x5F\x32\x32\x2C\x23\x70\x72\x5F\x32\x33","\x23\x61\x63","\x23\x70\x72\x5F\x32\x35\x2C\x23\x73\x65\x76\x65\x6E","\x23\x70\x72\x5F\x32\x36","\x23\x6B\x77","\x23\x70\x72\x5F\x32\x36\x2C\x23\x73\x65\x76\x65\x6E","\x23\x70\x72\x5F\x32\x35","\x23\x74\x6F\x79\x73","\x72\x65\x61\x64\x79"];$(document)[_0x2739[103]](function(){$(_0x2739[1])[_0x2739[0]]();$(_0x2739[6])[_0x2739[5]](function(){$(_0x2739[3])[_0x2739[2]]();$(_0x2739[4])[_0x2739[0]]()});$(_0x2739[9])[_0x2739[5]](function(){$(_0x2739[7])[_0x2739[0]]();$(_0x2739[8])[_0x2739[2]]()});$(_0x2739[12])[_0x2739[5]](function(){$(_0x2739[10])[_0x2739[0]]();$(_0x2739[11])[_0x2739[2]]()});$(_0x2739[15])[_0x2739[5]](function(){$(_0x2739[13])[_0x2739[0]]();$(_0x2739[14])[_0x2739[2]]()});$(_0x2739[18])[_0x2739[5]](function(){$(_0x2739[16])[_0x2739[0]]();$(_0x2739[17])[_0x2739[2]]()});$(_0x2739[21])[_0x2739[5]](function(){$(_0x2739[19])[_0x2739[0]]();$(_0x2739[20])[_0x2739[2]]()});$(_0x2739[24])[_0x2739[5]](function(){$(_0x2739[22])[_0x2739[0]]();$(_0x2739[23])[_0x2739[2]]()});$(_0x2739[27])[_0x2739[5]](function(){$(_0x2739[25])[_0x2739[2]]();$(_0x2739[26])[_0x2739[0]]()});$(_0x2739[30])[_0x2739[5]](function(){$(_0x2739[28])[_0x2739[2]]();$(_0x2739[29])[_0x2739[0]]()});$(_0x2739[33])[_0x2739[5]](function(){$(_0x2739[31])[_0x2739[2]]();$(_0x2739[32])[_0x2739[0]]()});$(_0x2739[36])[_0x2739[5]](function(){$(_0x2739[34])[_0x2739[2]]();$(_0x2739[35])[_0x2739[0]]()});$(_0x2739[39])[_0x2739[5]](function(){$(_0x2739[37])[_0x2739[2]]();$(_0x2739[38])[_0x2739[0]]()});$(_0x2739[42])[_0x2739[5]](function(){$(_0x2739[40])[_0x2739[2]]();$(_0x2739[41])[_0x2739[0]]()});$(_0x2739[45])[_0x2739[5]](function(){$(_0x2739[43])[_0x2739[2]]();$(_0x2739[44])[_0x2739[0]]()});$(_0x2739[48])[_0x2739[5]](function(){$(_0x2739[46])[_0x2739[2]]();$(_0x2739[47])[_0x2739[0]]()});$(_0x2739[51])[_0x2739[5]](function(){$(_0x2739[49])[_0x2739[2]]();$(_0x2739[50])[_0x2739[0]]()});$(_0x2739[54])[_0x2739[5]](function(){$(_0x2739[52])[_0x2739[2]]();$(_0x2739[53])[_0x2739[0]]()});$(_0x2739[57])[_0x2739[5]](function(){$(_0x2739[55])[_0x2739[2]]();$(_0x2739[56])[_0x2739[0]]()});$(_0x2739[60])[_0x2739[5]](function(){$(_0x2739[58])[_0x2739[2]]();$(_0x2739[59])[_0x2739[0]]()});$(_0x2739[63])[_0x2739[5]](function(){$(_0x2739[61])[_0x2739[2]]();$(_0x2739[62])[_0x2739[0]]()});$(_0x2739[66])[_0x2739[5]](function(){$(_0x2739[64])[_0x2739[2]]();$(_0x2739[65])[_0x2739[0]]()});$(_0x2739[69])[_0x2739[5]](function(){$(_0x2739[67])[_0x2739[2]]();$(_0x2739[68])[_0x2739[0]]()});$(_0x2739[72])[_0x2739[5]](function(){$(_0x2739[70])[_0x2739[2]]();$(_0x2739[71])[_0x2739[0]]()});$(_0x2739[75])[_0x2739[5]](function(){$(_0x2739[73])[_0x2739[2]]();$(_0x2739[74])[_0x2739[0]]()});$(_0x2739[78])[_0x2739[5]](function(){$(_0x2739[76])[_0x2739[2]]();$(_0x2739[77])[_0x2739[0]]()});$(_0x2739[81])[_0x2739[5]](function(){$(_0x2739[79])[_0x2739[2]]();$(_0x2739[80])[_0x2739[0]]()});$(_0x2739[84])[_0x2739[5]](function(){$(_0x2739[82])[_0x2739[2]]();$(_0x2739[83])[_0x2739[0]]()});$(_0x2739[87])[_0x2739[5]](function(){$(_0x2739[85])[_0x2739[2]]();$(_0x2739[86])[_0x2739[0]]()});$(_0x2739[90])[_0x2739[5]](function(){$(_0x2739[88])[_0x2739[2]]();$(_0x2739[89])[_0x2739[0]]()});$(_0x2739[93])[_0x2739[5]](function(){$(_0x2739[91])[_0x2739[2]]();$(_0x2739[92])[_0x2739[0]]()});$(_0x2739[96])[_0x2739[5]](function(){$(_0x2739[94])[_0x2739[2]]();$(_0x2739[95])[_0x2739[0]]()});$(_0x2739[99])[_0x2739[5]](function(){$(_0x2739[97])[_0x2739[2]]();$(_0x2739[98])[_0x2739[0]]()});$(_0x2739[102])[_0x2739[5]](function(){$(_0x2739[100])[_0x2739[2]]();$(_0x2739[101])[_0x2739[0]]()})})

var _0xd433=["\x6E\x61\x76\x2D\x6C\x69\x6E\x6B\x73","\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x42\x79\x49\x64","\x6C\x65\x66\x74","\x73\x74\x79\x6C\x65","\x2D\x32\x32\x30\x70\x78","\x30"];var sh=document[_0xd433[1]](_0xd433[0]);function closeNav(){sh[_0xd433[3]][_0xd433[2]]= _0xd433[4]}function show(){sh[_0xd433[3]][_0xd433[2]]= _0xd433[5]}
var _0x51dc=["\x6C\x6F\x61\x64","\x68\x69\x64\x65","\x2E\x6C\x6F\x61\x64\x65\x72","\x6F\x6E"];$(window)[_0x51dc[3]](_0x51dc[0],function(){$(_0x51dc[2])[_0x51dc[1]]()})
    </script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>

    </body>
</html>
