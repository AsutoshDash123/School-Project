<html>
<head>
	<title>DAV Birgunj</title>
	<style>
#left{
	display: inline-block;
}
.hello{
	float: right;
	margin-right: 15%;
	margin-top: 6%;
}
.search{
	text-align: right;
}
#textstyle{
 height: 35px;
	border-radius: 8px; 
	text-align: center;
}
#bottonstyle{
background-color: red;
color: white;
	padding: 7px;
	border-radius: 8px;
	width: 90px;
border: 1px solid red;
}
#bottonstyle:hover{
border: 3px dotted white;
}
.menu{
	background-color: blue;
	height: 40px;

}
.aa ul li{
	background-color: blue;
	width: 185px;
	display: inline-block;
	height: 35px;
	line-height: 35px;
	text-align: center;
	border-right: 1px solid #bbb;
}
.aa ul li a{
	color: white;
	text-decoration: none;
	display: block;
}
li a.active {
	background-color: red;
	color: white;
	height: 40px;
}
@keyframes bounce{
	0%, 20%, 60%, 100% {
		-webkit-transform: translateY(0);
		transform: translateY(0);
	}
	40%{
        -webkit-transform: translateY(-20px);
        transform: translateY(-20px);
	}
	80%{
		-webkit-transform: translateY(-10px);
		transform: translateY(-10px);
	}
}
.aa ul li a:hover:not(.active){
    background-color: red;
	color: white;
	height: 40px;
	animation: bounce 1s;

}
img:hover{
border-radius: 100% 100%;
}
hr{
	width: 100%;
}
.footer{
	background-color: e9edf2;
	color: black;
	width: 100%
}
.happy{
	text-align: center;
	margin: auto;
}
</style>
</head>
<body>
	<div class="h3m">
	<div id="dav logo">
		<div id="left">
		<img src="img\logo2.jpg">
	</div>
<DIV class="hello">
<marquee><h1>D.A.V R.B KEDIA HIGHER SECONDARY SCHOOL</h1></marquee>
</DIV>
</div>
<div class="search">
<form>
<input id="textstyle" type="text" name="textbox"placeholder="search...">
<input id="bottonstyle" type="button"name="search"value="Search"/>
</form>
</div>
</div>
<div class="menu">
	<div class="aa">
	<ul>
		<li><a href="index.html">HOME</a></li>
				<li><a href="activities.html">ACTIVITIES</a></li>
				<li><a href="teachers.html">TEACHER</a></li>
				<li><a href="examtype.html">EXAM TYPE</a></li>
				<li><a href="contact us.html">CONTACT US</a></li>
				<li><a class="active"href="feedback.html">FEEDBACK</a></li>
</ul>
</div>
</div>
<div class="feedback">
<h1> Feedback Form</h1>

<form action="URL to form script" method="POST">

Your name: <br>
<input type="text" name="realname" placeholder="Enter your name..."><br>
<br>

Your email: <br>
<input type="text" name="email" placeholder="Enter your email..."><br>
<br>

Your comments: <br>
<textarea name="comments" rows="15" cols="50" placeholder="Enter your comment..."></textarea><br><br>

<input type="submit" value="Submit" >
 
</form>
</div>
<hr>
<footer>
<div class="footer">
	<div class="happy">
		The DAV School,2017.All rights reserved.<br>
		| Disclamer| Privacy policy | Sitemap | Vacancy at DAV<br>
		The DAV School website has been designed by<br>
		<b>Aayush singh,Raj pachauri,Asutosh dash and Aditya singh</b><br>
		of standerd-8(2017/2018) <br><b>Special Thanks To,</b><br>
		<b>Mrs kemika singh</b>(computer teacher)/<b>Mr Roshan shah</b>(computer teacher)/<b>Mr P.chatterji</b>(Principal)<br><br>
		The DAV School,Parwanipur(Near kedia hospital),Birgunj,Parsa,Nepal,Pin-******<br>
		Direct Number- +977-51-690107/525500,Email:######,<br>
		

</div>
</div>



</footer>
</body>
</html>
