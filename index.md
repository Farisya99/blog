<!DOCTYPE html>
<html>
<head>
<title> Reading </title>
<meta name="viewport" content="width=device-width, initial-scale=1">


<!-- Add icon library -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
.playAudio() {
  background-color: DodgerBlue;
  border: none;
  color: white;
  padding: 12px 16px;
  font-size: 16px;
  cursor: pointer;
}

/* Darker background on mouse-over */
.btn:hover {
  background-color: RoyalBlue;
}
</style>




</head>
<style>
* {box-sizing: border-box}

.navbar {
  width: 100%;
  background-color: #000000;
  overflow: auto;
}

.navbar a {
  float: left;
  padding: 15px;
  color: white;
  text-decoration: none;
  font-size: 15px;
  width: 15%; 
  text-align: right;
}

.navbar a:hover {
  background-color: #000000;
}

.navbar a.active {
  background-color: #000000;
}

@media screen and (max-width: 500px) {
  .navbar a {
    float: center;
    display: block;
    width: 100%;
    text-align: center;
  }
}

A {text-decoration: none;}

a.one:link {color:#ff0000;}
a.one:visited {color:#0000ff;}
a.one:hover {color:#CCCCCC;}


</style>

<body style="background-color:DarkSeaGreen;">

<center>
<img src="read.jpg" alt="reading" class="center" width="400" height="150"></center>


<div class="navbar">
  <a class="active" href="indexhomepage.html">HOME</a>
  <a href="about us.html">ABOUT US</a>
  <a href="character.html">CHARACTER</a>
  <a href="Spelling.html">SPELLING</a>
  <a href="reading.html">READING</a>
  <a href="#">CONTACT</a>
</div>



<body>

<audio id="myAudio">

  <source src="reading.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

<h4> READ THE TEXT </h4>

<button onclick="playAudio()";margin-left:auto;margin-right:auto;display:block;margin-top:22%;margin-bottom:0%"> <h2> PLAY </h2></button>
<button onclick="pauseAudio()";margin-left:auto;margin-right:auto;display:block;margin-top:22%;margin-bottom:0%"><h2> PAUSE </h2></button> 

<script>
var x = document.getElementById("myAudio"); 

function playAudio() { 
  x.play(); 
} 

function pauseAudio() { 
  x.pause(); 
} 
</script>


  
<center>
<img src="text.jpeg" alt="alphabet" class="center" width="600" height="400"></center>
  
 </body>
</html>
