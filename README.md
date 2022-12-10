# about-me
hystch repository
<!DOCTYPE html>
<html>
<head>
	<meta name="viewport" content="with=device-width, initial-scale=1.0">
	<title>Engineer Ambitiously - Savmor</title>
	<link rel="stylesheet" href="Sv_style.css">
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="http://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="http://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.1.2/css/fontawesome.min.css">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.3.1/css/all.css" integrity="sha384-mzrmE5qonljUremFsqc01SB46JvROS7bZs3IO2EmfFsd15uHvIt+Y8vEf7N7fWAU" crossorigin="anonymous">
</head>
<body>
<section class="header">
	<nav>
		<a href="savmor.html"><img src="image/bgs - advanvced-4.png"></a>
		<div class="nav-links" id="navLinks">
		<i class="fa fa-times" onclick="hideMenu()"></i>
			<ul>
				<li><a href="savmor.html">HOME</a></li>
				<li><a href="aboutsv.html">ABOUT</a></li>
				<li><a href="coursesv.html">COURSE</a></li>
				<li><a href="blogsv.html">BLOG</a></li>
				<li><a href="contactsv.html">CONTACT</a></li>
			</ul>
		</div>	
		<i class="fa fa-bars" onclick="showMenu()"></i>
	</nav>

<div class="text-box">
	<h1>Excellence and Innovation are built into every Design</h1>
	<p>Engineers like to solve problems if there are no problems handily available. <br>THEY WILL CREATE THEIR OWN PROBLEMS.</p>
	<a href="" class="hero-btn">Visit Us To Know More</a>
</div>

</section>

<!------Course-------->

<section class="course">
	<h1>Course We Offer</h1>
	<p> Honeywell Instruction-------------------------------------------------------------
	---------------- </p>

	<div class="row">
		<div class="course-col">
			<h3>Intermediate</h3>
			<p> Sensor ----------
			---------.</p>
		</div>
		<div class="course-col">
			<h3>Degree</h3>
			<p> Sensor ---------------------------
			----------.</p>
		</div>
		<div class="course-col">
			<h3>Post Graduation</h3>
			<p> Sensor -----------------------
			-----------.</p>
		</div>
	</div>

</section>


<!------- campus ------>

<section class="campus">
	<h1>Our Global Campus</h1>
	<p> Honeywell Instruction-------------------------------------------------------------
	---------------- </p>

	<div class="row">
		<div class="campus-col">
			<img src="image/S.png">
			<div class="layer">
				<h3>SAVMOR</h3>
			</div>
		</div>
		<div class="campus-col">
			<img src="image/Screenshot (943).png">
			<div class="layer">
				<h3>SAVMOR LOGO</h3>
			</div>
		</div>
		<div class="campus-col">
			<img src="image/link.png">
			<div class="layer">
				<h3>SAVMOR LINK</h3>
			</div>
		</div>
	</div>

</section>

<!---------Facilities-------->

<section class="facilities">
	<h1>Our Facilities</h1>
	<p>Testing - For Savmor. </p>
	
	<div class="row">
		<div class="facilities-col">
			<img src="image/bgl.png">
			<h3>Test Savmor - World Class Library</h3>
			<p>This is text over here for savmor. </p>
		</div>
		<div class="facilities-col">
			<img src="image/svv_bg.png">
			<h3>Test Savmor - Test 1</h3>
			<p>This is text over here for savmor. </p>
		</div>
		<div class="facilities-col">
			<img src="image/6241184.jpg">
			<h3>Test Savmor - Test 1</h3>
			<p>This is text over here for savmor. </p>
		</div>
	</div>

</section>

<!----- testimonials ----->

<section class="testimonials">
	<h1>What Our Student Says</h1>
	<p>Testing 123. </p>

	<div class="row">
		<div class="testimonial-col">
			<img src="image/1.png">
			<div>
				<p>add image description</p>
				<h3>Image name</h3>
				<i class="fa fa-star"></i>
				<i class="fa fa-star"></i>
				<i class="fa fa-star"></i>
				<i class="fa fa-star"></i>
				<i class="fa fa-star-o"></i>
			</div>
		</div>
		<div class="testimonial-col">
			<img src="image/1.png">
			<div>
				<p>add image description</p>
				<h3>Image name</h3>
				<i class="fa fa-star"></i>
				<i class="fa fa-star"></i>
				<i class="fa fa-star"></i>
				<i class="fa fa-star"></i>
				<i class="fa fa-star-half"></i>
			</div>
		</div>
	</div>
</section>

<!--- Call To Action ---->

<section class="cta">
	<h1>Enroll For Our Various Online Courses<br>Anywhere From The
	World</h1>
	<a href="" class="hero-btn">CONTACT US</a>
</section>

<!----Footer----->

<section class="footer">
	<h4>About Us. If long sentence <br>therefore add br on here. </h4>
	<p>About Our Company. </p>
	<div class="icons">
		<i class="fab fa-facebook"></i>
		<i class="fab fa-twitter"></i>
		<i class="fab fa-instagram"></i>
		<i class="fab fa-linkedin"></i>
	</div>
	<p>Made with <i class="fa fa-heart"></i> by Savmor Tutorials</p>
</section>

<!--------JavaScript for Toggle Menu------->
<script>
	
	var navlinks = document.getElementById("navLinks");
	
	function showMenu(){
		navLinks.style.right = "0";
	}
	function hideMenu(){
		navLinks.style.right = "-200px";
	}

</script>


</body>
</html>
