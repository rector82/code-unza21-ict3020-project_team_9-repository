# code-unza21-ict3020-project_team_9-repository<!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>How to Create responsive Homepage</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="anie.css">   
</head>
<body>
    <header>
    <div class="wrapper">
        <div class="logo">
            
            <h1>Web Tech</h1>
      </div>
<ul class="nav-area">
<li><a href="#">Home</a></li>
<li><a href="about.html">About</a></li>
<li><a href="">browse</a></li>
<li><a href="contact.html">Contact</a></li>
<li><a href="login.html">Login</a></li>
<li><a href="reg.html">Create Account</a></li>
</ul>
</div>
<div class="welcome-text">
        <h1>
Welcome <span>Home</span></h1>
<a href="#">Contact US</a>
    </div>
</header>

</body>
</html>


* {
	margin: 0;
	padding: 0;
}
body {
	font-family: 'Poppins', sans-serif;
}
.wrapper {
	width: 1170px;
	margin: auto;
}
header {
	background: linear-gradient(rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)), url(https://i.postimg.cc/YjcJg24M/aa.jpg);
	height: 100vh;
	-webkit-background-size: cover;
	background-size: cover;
	background-position: center center;
	position: relative;
}
.nav-area {
	float: right;
	list-style: none;
	margin-top: 30px;
}
.nav-area li {
	display: inline-block;
}
.nav-area li a {
	color: #fff;
	text-decoration: none;
	padding: 5px 20px;
	font-family: poppins;
	font-size: 16px;
	text-transform: uppercase;
}
.nav-area li a:hover {
	background: #fff;
	color: #333;
}
.logo {
	float: left;
}
.logo h1 {
	width: 100%;
	padding: 15px 0;
	color: whitesmoke;
}
.welcome-text {
	position: absolute;
	width: 600px;
	height: 300px;
	margin: 20% 30%;
	text-align: center;
}
.welcome-text h1 {
	text-align: center;
	color: #fff;
	text-transform: uppercase;
	font-size: 60px;
}
.welcome-text h1 span {
	color: #00fecb;
}
.welcome-text a {
	border: 1px solid #fff;
	padding: 10px 25px;
	text-decoration: none;
	text-transform: uppercase;
	font-size: 14px;
	margin-top: 20px;
	display: inline-block;
	color: #fff;
}
.welcome-text a:hover {
	background: #fff;
	color: #333;
}
/*resposive*/

@media (max-width:600px) {
	.wrapper {
		width: 100%;
	}
	.logo {
		float: none;
		width: 50%;
		text-align: center;
		margin: auto;
	}
	img {
		width: ;
	}
	.nav-area {
		float: none;
		margin-top: 0;
	}
	.nav-area li a {
		padding: 5px;
		font-size: 11px;
	}
	.nav-area {
		text-align: center;
	}
	.welcome-text {
		width: 100%;
		height: auto;
		margin: 30% 0;
	}
	.welcome-text h1 {
		font-size: 30px;
	}
}



<--about css-->

@import url('https://fonts.googleapis.com/css?family=Allura|Josefin+Sans');

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body{
  background: #81c644;
  font-family: 'Josefin Sans', sans-serif;
}

.wrapper{
  margin-top: 50px;
}

.wrapper h1{
  font-family: 'Allura', cursive;
  font-size: 52px;
  margin-bottom: 60px;
  text-align: center;
}

.team{
  display: flex;
  justify-content: center;
  width: auto;
  text-align: center;
  flex-wrap: wrap;
}

.team .team_member{
  background: #fff;
  margin: 5px;
  margin-bottom: 50px;
  width: 300px;
  padding: 20px;
  line-height: 20px;
  color: #8e8b8b;  
  position: relative;
}

.team .team_member h3{
  color: #81c644;
  font-size: 26px;
  margin-top: 50px;
}

.team .team_member p.role{
  color: #ccc;
  margin: 12px 0;
  font-size: 12px;
  text-transform: uppercase;
}

.team .team_member .team_img{
  position: absolute;
  top: -50px;
  left: 50%;
  transform: translateX(-50%);
  width: 100px;
  height: 100px;
  border-radius: 50%;
  background: #fff;
}

.team .team_member .team_img img{
  width: 100px;
  height: 100px;
  padding: 5px;
}


<!DOCTYPE html>
<html>
<head>
	<title>registration form</title>
	<link rel="stylesheet" type="text/css" href="stylee.css">
</head>
<body>
<div class="registration-form">
	<h3>create account</h3>
	<form action="#" method="post">
		<p>Full Name:</p>
		<input type="text" name="fullname" placeholder="Full Name" required="">
		<p>User Name:</p>
		<input type="text" name="username" placeholder="User Name" required="">
		<p>Email:</p>
		<input type="email" name="email" placeholder="Email" required="">
		<p>Password:</p>
		<input type="password" name="password" placeholder="Password" required="">
		<button type="submit">Register</button>
	
	</form>
</body>
</html>
    
    *{
	padding: 0;
	margin: 0;
	font-family: sans-serif;
}
body{
	background: url(hello1.jpg) no-repeat;
	background-size: cover;
	color: #fff; 

}
.registration-form{
	position: absolute;
	top: 50%;
	left: 50%; 
	transform: translate(-50%, -50%);
	width: 350px;

}
.registration-form h1{
	font-size: 40px;
	text-align: center;
	text-transform: uppercase;
   
}
.registration-form p{
	font-size: 20px;
	margin: 15px 0;
}
.registration-form input{
	font-size: 16px;
	padding: 15px 10px;
	width: 100%;
	border: 0;
	border-radius: 5px;
	outline: none;
	
}
.registration-form button{
	font-size: 18px;
	font-weight: bold;
	margin: 20px 0;
	padding: 10px 15px;
	width: 50%;
	border: 0;
	border-radius: 5px;
	background-color: darkgrey;
   }
   .registration-form button:hover{
   	color: red;
   	
   }
   .registration-form input:hover{
   	color: red;
   }
    
<!DOCTYPE html>
<html>
<head>
	<title>login</title>
	<link rel="stylesheet" type="text/css" href="fontawesome/css/all.min.css">
	<link rel="stylesheet" type="text/css" href="mi.css">
</head>
<body>
<div class="container">
	<div class="header">
		<h1>login</h1>
	</div>
	<div class="main">
		<form>
			<span>
				<i class="fafa-user"></i>
				<input type="text" placeholder="Username" name="" required="">
			</span><br>
			<span>
				<i class="fafa-lock"></i>
				<input type="password" placeholder="password" name="" required="">
			</span><br>
				<button><a href="www.google.com"></a> login</button>

		</form>
	</div>
</div>
	body {
	font-family: sans-serif;	
	background-image: url(hello3.jpg);
	background-repeat: no-repeat;
	overflow: hidden;
	background-size: cover;
	width:100%;
}

.container {
	width: 380px;
	margin:7% auto;
	border-radius: 25px;
	background-color: rgba(0,0,0,0.1);
	box-shadow: 0 0 17px #333;
}

.header {
	text-align: center;
	padding-top: 75px;
}

.header h1 {
	color: #333;
	font-size: 45px;
	margin-bottom: 80px;
}

.main {
	text-align: center;
}

.main input, button {
	width: 300px;
	height: 40px;
	border:none;
	outline: none;
	padding-left: 40px;
	box-sizing: border-box;
	font-size: 15px;
	color: #333;
	margin-bottom: 40px;
}

.main button {
	padding-left: 0;
	background-color: #83acf1;
	letter-spacing: 1px;
	font-weight: bold;
	margin-bottom: 70px;
}

.main button:hover {
	box-shadow: 2px 2px 5px #555;
	background-color: #7799d4;
}
.main input:hover {
	box-shadow: 2px 2px 5px #555;
	background-color: #ddd;
}

.main span {
	position: relative;
}

.main i {
	position: absolute;
	left: 15px;
	color: #333;
	font-size: 16px;
	top: 2px;
}
	
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>About page</title>
  <link rel="stylesheet" type="text/css" href="anie.css">
</head>
<body>

  <div class="wrapper">
  <h1>Our Team</h1>
  <div class="team">
    <div class="team_member">
      <div class="team_img">
        <img src="a.jpg" alt="Team_image">
      </div>
      <h3>Annie Shapi</h3>
      <p class="role">Front-end developer</p>
      <p>To ensure that the website visitors can easily interact with the page.</p>
    </div>
    <div class="team_member">
      <div class="team_img">
        <img src="e.jpg" alt="Team_image">
      </div>
      <h3>Elias Jere</h3>
      <p class="role">Full-stack developer</p>
      <p>Who works with the backend or server side of the application as well as the front-end or client side.</p></div>
    <div class="team_member">
      <div class="team_img">
        <img src="r.jpg" alt="Team_image">
      </div>

<h3>Rector Njobvu</h3>
      <p class="role">Manager</p>
      <p> responsible for coordinating the team members and the client, allocating the resources, and streamlining the processes.</p></div>
    <div class="team_member">
      <div class="team_img">
        <img src="t.jpg" alt="Team_image">
      </div>




      <h3>Thandiwe Khondowe</h3>
      <p class="role">Scribe</p>
      <p>Records all decisions, actions and issues noted by the group during meetings, as well as recording significant discussion so that topics need to be revisited.</p></div>
    <div class="team_member">
      <div class="team_img">
        <img src="g.jpg" alt="Team_image">
      </div>


      <h3>Geoffrey Ngoma</h3>
      <p class="role">Back-end developer</p>
      <p>Builds and maintains the technology that powers those components which together, enable the user facing side of the website to even exist in the first place.</p>
    

</body>
</html>
	  
	  <!DOCTYPE html>
<html>
<head>
	<title>Contact</title>
	<link rel="stylesheet" type="text/css" href="ad.css">
	<link href="https://fonts.googleapis.com/css?family=Quicksand&display=swap" rel="stylesheet">
	<meta name="viewport" content="width=device-width,initial-scale=1.0,minimum-scale=1.0,maximum-scale=1.0">
</head>
<body>
	<div class="container">
		<div class="contact-box">
			<div class="left"></div>
			<div class="right">
				<h2>Contact Us</h2>
				<input type="text" class="field" placeholder="Your Name">
				<input type="text" class="field" placeholder="Your Email">
				<input type="text" class="field" placeholder="Phone">
				<textarea placeholder="Message" class="field"></textarea>
				<button class="btn">Send</button>
			</div>
		</div>
	</div>
</body>*{
	padding: 0;
	margin: 0;
	box-sizing: border-box;
	font-family: 'Quicksand', sans-serif;
}

body{
	height: 100vh;
	width: 100%;
}

.container{
	position: relative;
	width: 100%;
	height: 100%;
	display: flex;
	justify-content: center;
	align-items: center;
	padding: 20px 100px;
}

.container:after{
	content: '';
	position: absolute;
	width: 100%;
	height: 100%;
	left: 0;
	top: 0;
	background: url("img/bg.jpg") no-repeat center;
	background-size: cover;
	filter: blur(50px);
	z-index: -1;
}
.contact-box{
	max-width: 850px;
	display: grid;
	grid-template-columns: repeat(2, 1fr);
	justify-content: center;
	align-items: center;
	text-align: center;
	background-color: #fff;
	box-shadow: 0px 0px 19px 5px rgba(0,0,0,0.19);
}

.left{
	background: url("img/bg.jpg") no-repeat center;
	background-size: cover;
	height: 100%;
}

.right{
	padding: 25px 40px;
}

h2{
	position: relative;
	padding: 0 0 10px;
	margin-bottom: 10px;
}

h2:after{
	content: '';
    position: absolute;
    left: 50%;
    bottom: 0;
    transform: translateX(-50%);
    height: 4px;
    width: 50px;
    border-radius: 2px;
    background-color: #2ecc71;
}

.field{
	width: 100%;
	border: 2px solid rgba(0, 0, 0, 0);
	outline: none;
	background-color: rgba(230, 230, 230, 0.6);
	padding: 0.5rem 1rem;
	font-size: 1.1rem;
	margin-bottom: 22px;
	transition: .3s;
}

.field:hover{
	background-color: rgba(0, 0, 0, 0.1);
}

textarea{
	min-height: 150px;
}

.btn{
	width: 100%;
	padding: 0.5rem 1rem;
	background-color: #2ecc71;
	color: #fff;
	font-size: 1.1rem;
	border: none;
	outline: none;
	cursor: pointer;
	transition: .3s;
}

.btn:hover{
    background-color: #27ae60;
}

.field:focus{
    border: 2px solid rgba(30,85,250,0.47);
    background-color: #fff;
}

@media screen and (max-width: 880px){
	.contact-box{
		grid-template-columns: 1fr;
	}
	.left{
		height: 200px;
	}
}
	
	
</html>
	  


