# RevolutionChurch
Work in progress.
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Revolution Church</title>

<style type="text/css">

#body {
	position: fixed;
	top: -50%;
	left: -50%;
	width: 200%;
	height: 200%;
}

#body img {
	position: absolute;
	top: o;
	left: 0;
	right: 0;
	bottom: 0;
	margin: auto;
	min-width: 50%;
	min-height: 100%;
}
#exactcenter {
	width: 700px;
	height: 600px;
	position: fixed;
	background-color: white;
	top: 50%;
	left: 40%;
	margin-top: -200px;
	margin-left: -200px;
	
}

h1 {
	color: black;
	text-align: center;
	font-size: 50px;
	font-family: Gotham, "Helvetica Neue", Helvetica, Arial, sans-serif;
	text-shadow: 2px 2px #ff0000;
}
 p  {
	color: black;
	text-align: center;
	font-size: 35px;
	font-family: Gotham, "Helvetica Neue", Helvetica, Arial, sans-serif;
	text-shadow: 2px 2px #ff0000; 
 }


.main-header {
  position: fixed;
  top: 950px;
  width: 56%;
  background-color: grey;
  margin-left: 293px;
  /*min-height: 50px;*/
}

#logo {
  height: 50px;
  padding-top: 20px;
  padding-bottom: 20px;
  margin-left: 20px;
  margin-top: 0;
  float: left;
}

/************************
Navigation
************************/

.main-nav {
  float: left;
  padding: 10px;
  margin-left: 143px;
  /*display: inline-block;*/
}

.main-nav li {
  margin: 15px 10px;
  float: left;
  display: inline-block;
}

/************************
Clearfix
************************/

.group::after {
  content: " ";
  display: table;
  clear: both;
}
</style>

</head>

<body>



<div id="body">

<img src="C:\Users\kevin\Desktop\revolutionchurch\images/ashevilleb-w.jpg"  alt="">

</div>



<div id="exactcenter">
<h1>Revolution Church</h1>
<p>Aheville, NC</p>

</div>
<header class="main-header group">
          <a href="index.html">
          <img src="C:\Users\kevin\Desktop\revolutionchurch\images\revolutionchurch.jpg" id="logo">
          </a>
        <nav>
          <ul class="main-nav">
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="Ministries">Ministries</a></li>
            <li><a href="contact.html">Contact</a></li>
          </ul>
        </nav>
      </header>





</body>
</html>
