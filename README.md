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
    
