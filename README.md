<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Website</title>
    <style>
        body {
            margin: 0;
        }
        header {
            background-color: seagreen;
            color: #fff;
            padding: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-radius: 40px;
        }
        nav {
            display: flex;
            gap: 30px;
            margin-right: 30px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
        }
        .poster {
    display: block;
    margin-left: 20px;
    margin-right: auto;
    width: 50%;
}
        
        .head {
            margin-left: 30px;
        }
        .div2 {
            
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-radius: 40px;
        }
        a {
            text-decoration: ;
        }
        .right1 {
            margin-right: 10px;
            font-size: 40px;
            font-style: italic;
        }
        aside a {
            font-size: 20px;
        }
    </style>
</head>
<body>

<header>
    <div class="head">
        <h1><i>न्यायGPT</i></h1>
    </div>
    <nav>
        <a href="htmlpart.html">Home</a>
        <a href="#">Contact Us</a>
        <a href="#">About Us</a>
        <a href="signin.html">Login</a>
    </nav>
</header>
<br>
<div class="div2">
    <div class="poster">
        <img src="side.jpg" height="700">
    </div>
<aside class="right1">
    <font>24/7 legal assistance <br>at your fingertips<br>
    <a href="signin.html">Log In to get started...</a></font>
    </aside>
</div>
</body>
</html>




CSS PART


<!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Responsive Login and Signup Form </title>
	
<style>

* {
	box-sizing: border-box;
}

body {
	
	display: flex;
	justify-content: center;
	align-items: center;
	flex-direction: column;
	height: 100vh;
	margin: -20px 0 50px;
}

h1 {
	font-weight: bold;
	margin: 0;
	text-align: center;
}

h2 {
	text-align: center;
	color: white;
}

p {
	font-size: 14px;
	font-weight: 100;
	line-height: 20px;
	letter-spacing: 0.5px;
	margin: 20px 0 30px;
}



a {
	color: #333;
	font-size: 14px;
	text-decoration: none;
	margin: 15px 0;
}

button {
	border-radius: 20px;
	border: 1px solid #FF4B2B;
	background-color: #FF4B2B;
	color: #FFFFFF;
	font-size: 12px;
	font-weight: bold;
	padding: 12px 45px;
	letter-spacing: 1px;
	text-transform: uppercase;
	transition: transform 80ms ease-in;
}


form {
	background-color: #FFFFFF;
	display: flex;
	align-items: center;
	justify-content: center;
	flex-direction: column;
	padding: 0 50px;
	height: 100%;
	text-align: center;
}

input {
	background-color: #eee;
	border: none;
	padding: 12px 15px;
	margin: 8px 0;
	width: 100%;
}
.up{
	margin-top: 10px;
}
.down{
	margin-top: 100px;
}
</style>
    </head>
    <body>
        <h2>Get Started</h2>
		<div class="up">
			<h1>Hello, Friend!</h1>
			<p>Enter your personal details and know your rights</p>
		</div>
	<div class="down">
		<form action="#">
			<h1>Sign in</h1>
			<br>
			<input type="email" placeholder="Email" />
			<input type="password" placeholder="Password" />
			<a href="#">Forgot your password?</a>
			<button>Sign In</button>
		</form>
	</div>
    </body>
</html>
