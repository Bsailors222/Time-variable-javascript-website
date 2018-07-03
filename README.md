# Time-variable-javascript-website
<!DOCTYPE html>
<!-- This website template was created by: Braeden Sailors 5/21/2018 -->
<html>
<head>
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" href="css/stylesheet.css">
	<title>Braeden's Website</title>
	<meta charset="utf-8">
</head>

<header>
	<h1>My name is Braeden</h1>
	<h2>Have a good day!</h2>
</header>

<body>

    <script type="text/javascript">
    var d = new Date();
    var time = d.getHours();

    if (time < 12) 
      {
      document.write("<b>Good morning!</b>");
      }
    if (time > 12) 
      {
      document.write("<b>Good afternoon!</b>");
      }
    if (time == 12) 
      {
      document.write("<b>Go eat lunch!</b>");
      }
    </script>

    </body>
	
	<!-- Load an icon library to show a hamburger menu (bars) on small screens -->
<div class="nav" id="mynav">
  <a href="index.html" class="active">Home</a>
  <a href="Interests.html">Interests</a>
  <a href="about.html">About</a>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</div>
	
<main>

	<h1><b>Braeden Sailors</b></h1>

	<p>First started taking guitar lessons at Moore Brothers' Music in Sammamish</p>

	<p>Guitar teacher's name was <b>Mick Radford</b></p>
	
	<img src="images/mick_radford_940x600.jpg" alt="Mick Radford" width="940" height="600" class="center">

	<h2><sub>Taught me songs like <i>Crazy Train</i> and <i>Smoke On The Water</i></sub></h2>

	<h3><sub>Left this teacher after awhile and started taking lessons instead at Northwest Guitars in Bellevue.</sub></h3>

	<a href="https://www.northwestguitars.com/">This is the link to North West Guitars's website</a>

</main>

<footer>

	<p>Your ad here for only $4.75</p>
	
	<b>Limited time offer! $3.50</b>
	<p>Offer expires on the sunday of my birthday.</p>
	<p>(July 15th, 2018)</p>

</footer>

</html>
