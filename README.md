# google-homepage
Yep, yet another first repository on GitHub

The title of the project is "Google homepage" on www.theodinproject.com

<!DOCTYPE html>
<html>

<head>
	<title>Google</title>
	
<style type="text/css"> body {
    font-family: sans-serif;
    height: 100%;
    margin: 0;
}

/*header styling*/

.header {
	border: 1px solid white;
}

.header > ul > li {
    display: inline;
    float: right;
    text-decoration: none;
    margin: 25px 10px 0px 3px;
    font-size: 14px;
}

.header ul {
    list-style-type: none;
    margin: 0 auto;
    padding: 0 auto;
} 

#username {
	color: #8f8f8f;
}

#username:hover {
	text-decoration: none;
}

#user-photo {
	border-radius: 100px 100px;
	height: 40px;
	width: 40px;
}

img {
	height: 200px;
	width: 320px;
	margin: auto;
}

/*main section styling*/
.main {
    margin: 180px auto;
    position: relative;
    text-align: center;
    width: 600px;

}
.header a {
	text-decoration: none;
	color: black;
	padding: 3px 3px 3px 3px;
}

.header a:hover {
	text-decoration: underline;
}

input { 
	width: 500px;
	outline: none;
	padding: 5px 0px 5px 5px;
	margin: 5px 1px 15px 0px;
	border: 1px solid #DDDDDD;
}

input:focus {
	border: 1px solid rgba(63, 123, 236, 1);
}

.main a {
	border: 1px solid #a5a5a5;
	display: inline-block;
	padding: 5px 5px;
	background-color: #f0f0f0;
	margin: 0px 5px 0px 5px;
	border-radius: 3px 3px;
	font-size: 12px;
	font-family: Arial;
	font-weight: normal;
	color: #636363;
	text-decoration: none;
}

/*footer styling*/
.footer {
  position: absolute;
  right: 0;
  bottom: 0;
  left: 0;
  padding: 15px;
  background-color: #efefef;
  text-align: center;
  height: 30px;
  border-top: 1px solid #d1d1d1;
}

.footer a {
	color: #636363;
}

.footer a:hover {
	text-decoration: underline;
}	

.footer-left {
	padding-top: 10px;
	padding-bottom: 0px;
	height: 35px;
	display: inline;
	float: left;
	margin-right: 30px;
}

.footer-right {
	padding-top: 10px;
	padding-bottom: 0px;
	height: 35px;
	display: inline;
	float: right;
	margin-right: 30px;

}

.footer-left a {
	
	font-size: 13px;
	font-family: Arial, sans-serif;
	text-decoration: none;
	color: #636363;
	padding-left: 25px;
	padding-right: 10px;
}

.footer-right a {
	font-size: 13px;
	font-family: arial, sans-serif;
	text-decoration: none;
	color: #636363;
	padding-left: 25px;
	padding-right: 10px;
	margin: 0px;
}

</style>
</head>

<body>
	<div class="header">
		<ul>
			<li><a href="#"><img id="user-photo" src="http://www.pupileo.pl/attachment.php?attachmentid=70508&d=1431239263" /></a></li>
			<li><a href="#">Grafika</a></li>
			<li><a href="#">Gmail</a></li>
			<li><a id="username" href="#">Wojtek</a></li>
		</ul>
	</div>

	<div class="main">
			<img src="http://fineprintnyc.com/images/blog/history-of-logos/google/google-logo.png"><br>
			<input type="text" name="search-bar"><br>
			<a href="#">Search in Google</a>
			<a href="#">I'm feeling lucky</a>
	</div>
	
	<div class="footer">
		<div class="footer-right">
			<a href="#">Prywatność</a>
			<a href="#">Warunki</a>
			<a href="#">Ustawienia</a>
		</div>
		<div class="footer-left">
			<a href="#">Reklamuj się</a>
			<a href="#">Dla firm</a>
			<a href="#">O nas</a>
		</div>	
    </div>
</body>

</html>