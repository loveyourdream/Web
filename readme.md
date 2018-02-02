<!DOCTYPE html>
<html>
<head>
<title>ONLINE LIBRARY FOR ENGINEERS</title>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.0/jquery.min.js"></script>
<link rel="stylesheet" type="text/css" href="First_Page.css">
<style>

body{
	background-image: url("signinimg (2).jpg");
    background-repeat:repeat ; 
	background-attachment:fixed;
	color:black;
}

ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
    position: fixed;
    top: 0;
    width: 100%;
}

li {
    float: left;
}

li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

li a:hover:not(.active) {
    background-color: #111;
}

.active {
    background-color: #4CAF50;
}
.continer{
   width: 100px;
   height: 450px;
   margin: 40px auto;
   padding: 10px;
   box-sizing: border-box;
   background-image: tip2.jpg;
   box-shadow: 0 10px 15px -8px #000;
   border: 2px black;
   -webkit-border-radius:5px;
   text-align: center;
}

</style>
</head>
<body>
<ul>
<li><a href="registration.html" title="Sign In">SignIn</a></li> 
<li><a href="Login.php" title="Log In">LogIn</a></li> 
<li><a href="ContactUs.html" title="Contact Us">Contact Us</a> </li> 
<li><a href="Submit1.html" title="About_us">About_us</a></li>
<li><a href="Help.html" title="Help">Help</a></li>
<li><a href="Librarian.php" title="Librarian">Librarian</a>
</ul>

<div class="intro" align=center>
<h2 style="color:darkslategrey; font-size:50px; font-family:serif;"> WELCOME TO SOMAIYA LIBRARY...</h2>
</div>    <hr>

<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 3</div>
  <img src="plain(1).jpg" style="width:100%">
  <div class="text"></div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="plain(2).jpg" style="width:100%">
  <div class="text"></div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 5</div>
  <img src="plain(3).jpg" style="width:100%">
  <div class="text"></div>
</div>

<div class="mySlides fade">
  <div class="numbertext">4 / 5</div>
  <img src="plain(4).jpg" style="width:100%">
  <div class="text"></div>
</div>
    
<div class="mySlides fade">
  <div class="numbertext">5 / 5</div>
  <img src="plain(5).jpg" style="width:100%">
  <div class="text"></div>
</div>

</div>
<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
</div>

<script>
var slideIndex = 0;
showSlides();

function showSlides() {
    var i;
    var slides = document.getElementsByClassName("mySlides");
    var dots = document.getElementsByClassName("dot");
    for (i = 0; i < slides.length; i++) {
       slides[i].style.display = "none";  
    }
    slideIndex++;
    if (slideIndex > slides.length) {slideIndex = 1}    
    for (i = 0; i < dots.length; i++) {
        dots[i].className = dots[i].className.replace(" active", "");
    }
    slides[slideIndex-1].style.display = "block";  
    dots[slideIndex-1].className += " active";
    setTimeout(showSlides, 2000); // Change image every 2 seconds
   // window.setTimeout ("slideShow ("+slides+")",1000);
 //window.setTimeout("slideShow("+slides+")",1000);
}
</script>
<br>

<footer align="bottom"><b>
<p style="font-size:20px;">Posted by:Devanshi Doshi       Shivani Garud</p>
<p style="font-size:20px;">Contact Information 1 :<a href="#">doshi.d@somaiya.edu</a></p>
<p style="font-size:20px;">Contact Information 2 :<a href="#">s.garud@somaiya.edu</a></p></b>
</footer>
</body>
</html>



