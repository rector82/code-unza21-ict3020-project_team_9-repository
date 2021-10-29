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
<li><a href="#">About</a></li>
<li><a href="#">Services</a></li>
<li><a href="#">Contact</a></li>
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


</body>
</html>
