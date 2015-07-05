# learn-html-css
i learn html and css from peter i feel very satisfied
peter teached me to cut pictures from ps and with my knowledge these days to make this web.

This web's address : http://little.gitcafe.io/day-7

This is html:

<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<title>day-7</title>
	<link rel="stylesheet" href="day-7.css">
	<link rel="stylesheet" href="fa/css/font-awesome.css">
	<style>
       @font-face { font-family: Gotham Rounded Bold; src: url('Gotham-Rounded-Bold_21016.ttf'); }
       @font-face { font-family: Gotham Rounded Light; src: url('Gotham-Rounded-Light_21020.ttf'); }
       @font-face { font-family: Action Man Extended Italic ; src: url('Action_Man_Extended_Italic.ttf');}
	</style>
</head>
<body>
	<div class="hero">
        <div class="hero-inner">
        	<div class="navbar">
        		<a class="three" href="#">HOME</a>
        		<a class="one" href="#">PHOTOAPP</a>
        		<img class="camera-one" src="照相机.png">
        		<a class="two" href="#">DESIGN</a>
        		<a class="four" href="#">DOWNLOAD</a>
        	</div>
        	<div class="your">
        		<span>YOUR LIFE, A PHOTO<span>
                   <h5 style="font-size: 17px">print your life in a simple photo</h5>
        	</div>
        	<div class="get">
        		<a class="started" href="#">
        			<h3 style="color: white" "font-size: 15px"  >GET STARTED</h3>
        		</a>
        	</div>
	        <div class="icon">
		    	<a href="#">
		    		<i class="fa fa-twitter"></i>
		    	</a>
		    	<a href="#">
		    		<i class="fa fa-users"></i>
		    	</a>
		        <a href="#">
		        	<i class="fa fa-dribbble"></i>
		        </a>
		    </div>	
		</div>
	</div>
	<div class="iphone">
		<div class="iphone-inner">
			<div class="rappresent">
				<h3 style="color:teal" "font-size:15px">RAPPPASENT YOUR LIFE WITH A SIMPLE PHOTO</h3>
			</div>
			<img class="corem" src="corem.png" alt="sorry">
			<div class="gettwo">
				<a class="started" href="#">
        		 	<h3 style="color: white" "font-size: 15px"  >GET STARTED</h3>
        		</a>
        	</div>
		</div>
	</div>
	<div class="design">
		<div class="design-inner">
			<div class="design-title">
				<h3 style="color:teal" "font-size:13px">DESIGN</h3>
			</div>
			<img class="coremtwo" src="coremtwo.png" alt="sorry">
			<div class="one-to-five">
				<img src="01-05.png" alt="sorry"><br>
				<i class="fa fa-chevron-left"></i>
				<i class="fa fa-chevron-right"></i>
			</div>
		</div>
	</div>
	<div class="community">
		<div class="community-inner">
			<div class="arrow">
				<i class="fa fa-chevron-left"></i>
				<i class="fa fa-chevron-right"></i>
			</div>
			<div class="blue-camera">
				<img class="bluecamera" src="camera-three.png" alt="sorry">
				<h1>OUR CMMUNITY</h1>
				<img src="coremthree.png" alt="sorry">
			</div>
 			<div class="leaf">
 				<img class="leaf" src="叶子.png">
 			</div>
		</div>
	</div>
	<div class="download">
		<div class="sub">
			<h1>SUBSCRIBE TO US COMMUNITY</h1>
			<div class="your-email">
				<div class="true">
					<a href="#">
						<i class="fa fa-check"></i>
					</a>
				</div>
				<input type="text" placeholder="YOUR EMAIL">
			</div>
		</div>
	</div>
	<div class="footer">
		<div class="dow-i">
			DOWNLOAD IT<br>
			<img src="dow-i.png" alt="sorry">
			<div class="app-and">
				<div class="left">
				    <div class="apple">
				    	<a href="#">
				    		<i class="fa fa-apple"></i>
				    	</a>
				    </div>
					<div class="apple-store">
						APPLE STORE
					</div>
			    </div>
				<div class="right">
					<div class="android">
						<a href="#">
							<i class="fa fa-android"></i>
						</a>
					</div>
					<div class="play">PLAY STORE</div>
			    </div>
			</div>
		</div>
		<div class="ai">
		        <img class="credit" src="credit.png" alt="sorry"><br>
		        <img class="copy" src="copy.png" alt="sorry">
		        <img class="blue-c" src="camera-three.png" alt="sorry">
		</div>
	</div>
</body>
</html>


This is css:

body{
	margin: 0;
	font-family: Gotham Rounded Bold;
}
h5{
  margin: 0 0;
  color: white;
  font-family: Gotham Rounded Light; 
}	

.started{
	line-height: 50px;
	text-decoration: none;
}
span{
	font-size: 40px;
    color: white;
}
.hero-inner{
  height: 780px;
  background-position: center center;
  background-color: #90CAF9;
  background-image: url(hero.png);
  background-repeat: no-repeat;
  background-size: cover;
  padding-top: 40px;
}
.navbar{
    height: 62px;
    width: 777px;
    margin: 0 auto;
    text-align: center;
}
.your{
	height: 66px;
	width: 500px;
    margin: 0 auto;
    text-align: center;
    margin-top: 260px;
}
.get{
	height: 50px;
	width: 167px;
	margin: 0 auto;
	margin-top: 30px;
	border-radius: 5px;
	background-color: teal;
	text-align: center;
}
.get:hover{
	background-color: #009688;
}
.rappresent{
	height: 36px;
	width: 376px;
	background-color: white;
	padding-top: 113px;
}
.corem{
	display: block;
	margin-top: 47px;
}
.icon{
	height: 27px;
	width: 110px;
    margin-left: 656px;
    margin-top: 276px;
}
.icon i:hover{
	color: #cddc39;
}
.icon .fa{
	font-size: 25px;
	color: white;
    margin-right: 5px;
}
.one-to-five .fa{
	margin-left: 2px;
	margin-right: 18px;
} 
.gettwo{
    height: 50px;
    width: 167px;
    background-color: teal;
    text-align: center;
    margin-top: 30px;
    border-radius: 5px;
}
.gettwo:hover{
	background-color: #009688;
}
.iphone{
	background-color: white;
}
.design{
	background-color: white;
}
.community{
	background-color: rgb(223, 224, 227);
}
.download{
	height: 439px;
    background-color: #448AFF;
    background-image: url(phone.png);
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    padding-top: 397px;
}
.sub{
    height: 113px;
    width: 490px;
    margin-left: 461px;
}
.download h1{
    font-size: 28px;
    color: white;
}
.your-email{
    height: 60px;
    width: 338px;
    background-color: #fff;
    margin-left: 66px;
    font-family: 
}
input{
    height: 60px;
    width: 271px;
    font-size: 20px;
    color: black;
    line-height: 60px;
    font-family: Action Man Extended Italic;
}
.true{
    height: 66px;
    width: 63px;
    background-color: teal;
    float: right;
    font-size: 35px;
    text-align: center;
    line-height: 60px;
}
.true a{
    color: white;
}
.true:hover{
   background-color: #009688;
}
.footer{
    height: 417px;
    background-color: white; 
    padding-top: 90px; 
}
.dow-i{
    font-size: 30px;
    font-family: Action Man Extended Italic;
    text-align: center;
}
.dow-i img{
    margin-top: 20px;
}
.app-and{
    width: 618px;
    height: 56px;
    background-color: white;
    margin-left: 363px;
    margin-top: 47px;
}
.left{
    width: 296px;
    float: left;
}
.apple-store{
    height: 56px;
    width: 240px;
    background-color: #4DB6AC;
    font-family: Gotham Rounded Bold;
    font-size: 20px;
    line-height: 56px;
}
.apple{
    width: 56px;
    height: 56px;
    background-color: teal;
    float: right;
    font-size: 35px;
    line-height: 56px;
}
.apple a{
    color: white;
}
.android a:hover{
    color: black;
}
.apple a:hover{
    color: black;
}
.right{
    width: 296px;
    height: 56px;
    background-color: white;
    float: right;
}
.android{
    height: 56px;
    width: 56px;
    background-color: teal;
    float: right;
    font-size: 35px;
    line-height: 56px;
}
.android a{
    color: white;
}
.play{
    font-family: Gotham Rounded Bold;
    font-size: 20px;
    line-height: 56px;
    background-color: #4DB6AC;
}
.ai{
    height: 80px;
    width: 100%;
    position: relative;
    background-color: white; 
    margin-top: 161px;
}
.blue-c{
    position: absolute;
    bottom: 14px;
    right: 129px;
}
.copy{
    position: absolute;
    bottom: 20px;
    left: 20px;
}
.credit{
    position: absolute;
    top: 10px;
    left: 20px;
}
.one,.two,.three,.four{
	display: block;
    text-decoration: none;
    color: white;
    float: left;
    line-height: 62px;
}
.one{
    margin-left: 72px;
    margin-right: 103px; 
    line-height: 62px;
}
.two{
    margin-left: 104px;
    margin-right: 84px;
}
.three{
    margin-left: 34px;
}
.two,.four{
    line-height: 62px;
}
.navbar a:hover{
    color:  #ffcc80;
}
.design-inner{
	width: 1132px;
	height: 411px;
	margin: 0 auto;
	background-image: url(flat-iphone.png);
    background-repeat: no-repeat;
    background-position: 0 189px;
    background-color: white;
    padding-top: 147px;
}
.design-title{
	height: 59px;
	width: 443px;
	background-color: white;
	margin-left: 736px;
}
.coremtwo{
	margin-left: 736px;
	margin-top: 11px;
}
.learn{
	height: 51px;
	width: 192px;
	background-color: teal;
	margin-left: 736px;
	margin-top: 44px;
	text-align: center;
	border-radius: 5px;
}
.learn:hover{
    background-color: #4db6ac;
}
.learn-a{
	line-height: 51px;
	font-size: 11px;
	color: white;
	text-decoration: none;
}
.one-to-five{
	height: 35px;
	width: 90px;
	background-color: white;
	margin-left: 736px;
	margin-top: 45px;
	font-size: 10px;
}
.iphone-inner{
	width: 1132px;
	height: 492px;
	margin: 0 auto;
	background-image: url(iphone&hand.png);
	background-repeat: no-repeat;
	background-position: 381px 91px;
}
.community-inner{
    background-image: url(car.png);
    background-position: 386px 117px;
    height: 319px;
    width: 1132px; 
    margin: 0 auto;
    background-repeat: no-repeat;
    background-color: rgb(223, 224, 227);
    padding-top: 165px;
    text-align: center;
    position: relative;
}
.blue-camera{
	height: 163px;
	width: 177px;
	background-color: rgb(223, 224, 227);
	margin-left: 129px;
    text-align: center;
    color: teal;
}
.blue-camera h1{
	font-size: 13px;
	text-align: center;
	margin-top: 28px;
	margin-bottom: 20px;
	color: black;
}
.arrow{
	height: 25px;
	width: 50px;
	font-size: 15px;
	color: black;
	text-align: center;
	line-height: 25px;
	position: absolute;
	top: 86px;
	right: -12px;
}
.leaf{
	height: 244px;
	width: 370px;
	position: absolute;
	top: 58px;
	right: -9px;
}
.camera-two{
	display: block;
	height: 57px;
	width: 55px;
	margin: 0 auto;
	padding-top: 40px;
}
.life{
	display: block;
	margin:0 auto;
	padding-top: 297px;
}
.camera-one{
	display: block;
	float: left;
}
