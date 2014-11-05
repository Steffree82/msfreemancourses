<!doctype html>
<!--[if lt IE 7]> <html class="ie6 oldie"> <![endif]-->
<!--[if IE 7]>    <html class="ie7 oldie"> <![endif]-->
<!--[if IE 8]>    <html class="ie8 oldie"> <![endif]-->
<!--[if gt IE 8]><!-->
<html class="">
<!--<![endif]-->
<head>
<script src="first javescript.js"></script>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>index.ms.freeman</title>

<link href="cell.css" rel="stylesheet" type="text/css">
<!-- 
To learn more about the conditional comments around the html tags at the top of the file:
paulirish.com/2008/conditional-stylesheets-vs-css-hacks-answer-neither/

Do the following if you're using your customized build of modernizr (http://www.modernizr.com/):
* insert the link to your js here
* remove the link below to the html5shiv
* add the "no-js" class to the html tags at the top
* you can also remove the link to respond.min.js if you included the MQ Polyfill in your modernizr build 
-->
<!--[if lt IE 9]>
<script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->
<script src="respond.min.js"></script>
<script src="index.js" type="text/javascript"></script>


<script src=_js/jquery-1.7.2.min.js></script>
<script>
$(document).ready(function() {
 $('.answer').hide();
 $('.main h2').toggle(
		function() {
	       $(this).next('.answer').slideDown();
		   $(this).addClass('close');
		},
		function() {
		   $(this).next('.answer').fadeOut();
		   $(this).removeClass('close');
	  }
	); // end toggle
}); // end ready
</script>
</head>
<body>
<div class="gridContainer clearfix">
  <div id="header" class="fluid"><img src="Images/MsFreemansClass.jpg" alt="banner image" width="98%" height="151"/></div>
  
 <div id="cssmenu" class="fluid"><ul>
      <li class='active'><a href="Index.html">Home</a></li>
      <li class='active'><a href="Computer_7.html">Computer 7</a></li>
      <li class='active'><a href="Computer_8.html">Computer 8</a></li>
      <li class='has-sub'><a href="Computer_9.html">Computer 9</a>
        
      <li class='last'><a href="Yearbook.html">Yearbook</a>
      <ul>
          <li><a href="form.html">Form</a></li>
        
        </ul>
      </li>
 </ul>
 </div>
</div>
<div id="main"> <br>

 
 <h1><script>
		document.write('<p>Welcome ' + name +  '</p>');
		</script> </div>



<p>Hello! My name is Ms. Freeman and if you are accessing my page you are more than likely a student or a parent. Each page will have infomation about the class.</p>

<p class="heading2">A little about me:</p>
<ul>
<li>I am a mother of 2 girls their names are Mackenzie (11 years old) &amp; Kendra (7 years old)</li>
<li>So I have a seven eleven.</li>
<li>I am a veteran; I served as a Dentalman/Corpsman in the Untied States Navy for 5 years and 4 months (But who is counting)</li>
<li>I have a Bachlors of Business Administration with a concentration in Marketing &amp; a Masters in Educational Leadership, I recieved my teaching certification at University of Pittsubuirgh at Bradford</li>
<li>I have recieved my education in many different ways: military, online and in a traditional college classroom.</li>
<li>I am certified to teach Marketing, Home Ec., and Business/Computer education</li>
</ul>
<h1 class="me"><img src="Images/me.jpg" alt="Ms. Freeman" width="176" height="140" /></h1>
</div>

<div class="content">
	<div class="main">
<h1>Let's Talk About Facts!</h1>
<h2>I've heard that JavaScript is the long-lost fountain of youth. Is this true?</h2>
      <div class="answer">
        <p>Why, yes it is! Studies prove that learning JavaScript freshens the mind and extends life span by several hundred years. (Note: some scientists disagree with these claims.)</p>
      </div>
      <h2>Can JavaScript really solve all of my problems?</h2>
      <div class="answer">
        <p>Why, yes it can! It's the most versatile programming language ever created and is trained to provide financial management advice, life-saving CPR, and even to take care of household pets.</p>
      </div>
      <h2>Is there nothing JavaScript <em>can&#8217;t</em> do?</h2>
      <div class="answer">
        <p>Why, no there isn&#8217;t! It&#8217;s even able to write its own public relations-oriented Frequently Asked Questions pages. Now that&#8217;s one smart programming language!</p>
      </div>
<h2>This why you should do what?</h2>
      <div class="answer">
        <p>Take a Computer Class</p>
      </div>
</div>

 <div id="footer">
 <p><center><a href="http://www.johnsonburgareaschooldistrict.net/elementary-school.html">JASD Home Page</a><br>
    <a href="mailto:stefanief@jasd.k12.pa.us">Email Ms. Freeman</a></center> </p>
</div>
</div>
</body>
</html>

