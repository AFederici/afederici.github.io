<?php

//check for submit
$msg = "none";
$name = "";
$subj = "";
$email = "";

		if(filter_has_var(INPUT_POST, 'submit')){
			//get form database
			$name = htmlspecialchars($_POST['name']);
			$email = htmlspecialchars($_POST['email']);
			$subj = htmlspecialchars($_POST['subj']);
			$message = htmlspecialchars($_POST['message']);
			//check required
			if(!empty($email) && !empty($name) && !empty($message)){
				//passed
				if(filter_var($email, FILTER_VALIDATE_EMAIL) === false){
					//failed
					$msg = "Please use a valid email";
					$email = "";
					$msgClass = 'alert-danger';
				}
				else{
					//passed
					$toEmail = 'alexanderfederici@hotmail.com';
					$subject = 'Website form - ' . $subj . " from " . $name;
					$body = '<h2>Conctact Request</h2>
						<h4>Name</h4><p>' .$name. '</p>
						<h4>Email</h4><p>' .$email. '</p>
						<h4>Message</h4><p>' .$message. '</p>
						';

					//email header
					$headers = "MIME-Version: 1.0" . "\r\n";
					$headers .= "Content-Type: text/html; charset=UTF-8" . "\r\n";

					$headers .= "From: " .$name.  "<".$email.">" . "\r\n";

					if(mail($toEmail, $subject, $body, $headers)){
							//email sent
							$msg = "Your email has been sent";
							$msgClass = 'alert-success';
					} else{
						//failed
						$msg = "Your email was not sent";
						$msgClass = 'alert-danger';
					}

				}
			} else{
				//failed
				$msg = "Please fill in all of the fields";
				$msgClass = 'alert-danger';
			}
		}

 ?>

<!doctype html>
<html lang="en" class="no-js">
<head>
	<meta charset="UTF-8">
	<meta name="author" content="Alexander(AJ) Federici">
	<meta name="viewport" content="width=device-width,height=device-height, initial-scale=1.0">

	<link href='https://fonts.googleapis.com/css?family=Playfair+Display:700italic,700' rel='stylesheet' type='text/css'>

	<link rel="stylesheet" href="css/reset.css"> <!-- CSS reset -->
	<link rel="stylesheet" href="css/style.css"> <!-- Resource style -->
	<script src="js/modernizr.js"></script> <!-- Modernizr -->

	<title>Personal Website</title>
</head>
<body>
	<header>
		<a href="#0" class="cd-logo"><img src="img/logo6.jpg"></a>

		<button class="cd-nav-trigger">Menu<span aria-hidden="true" class="cd-icon"></span></button>
	</header>

	<nav class="cd-primary-nav">
		<ul>
			<?php if($msg == "Your email has been sent"): ?>
				 <center>
				 <br>
			<div class = "alert2 <?php echo $msgClass; ?>"><?php echo $msg; ?></div>
			</center>
			<?php elseif($msg == "none"): ?>

			<?php elseif($msg != ''): ?>
				 <center>
				 <br>
			<div class = "alert <?php echo $msgClass; ?>" ><?php echo $msg; ?></div>
			</center>

			<?php endif; ?>
			<li class="cd-label" onclick="location='index.html'">BACK HOME</li>
			<li><a href="home.php" class = "selected">About Me</a></li>
			<li><a href="fun.html">Fun Projects</a></li>
			<li><a href="ml.html">ML Projects</a></li>
			<li><a href="financeproj.html">Finance Projects</a></li>
		</ul>
	</nav> <!-- .cd-primary-nav -->

	<div class="cd-projects-container">


		<ul>
			<li class="single-project one">
				<div class="cd-title">
					<h2>About Me</h2>
				</div> <!-- .cd-title -->

				<div class="cd-project-info">
					<button class="cd-scroll">Scroll down</button>

					<div class="content-wrapper">
							<p>
								Hey! My name is AJ Federici and this is the fun part of my website where I intend to showcase different projects that I am working on.
							</p>
							<p>
								But first, I want to take some time to talk a little bit about myself.  I grew up in Dekalb, Illinois and lived there until I was about 15.  At the end of my freshman year I was accepted into a residential highschool, the
								<span class="pseudolink2" onclick="location='https://www.imsa.edu/'">Illinois Mathematics and Science Academy</span>.  I enjoy things like going for a run, playing chess, basketball, videogames, or the piano in my free time.  I love traveling and being outdoors but I also enjoy quiet days indoors watching some Rick and Morty.
								Computer science is my main passion - there are tons of sub-categories and uses for tools in cs that have caught my interest!
							</p>
							<hr>
							<p>Computation Finance:</p>
							<p>
							This school year I have been interning at TransMarket Group, a proprietary trading firm based in Chicago for about 8 hours every week.  Here I work on many small projects in python ranging from database manipulation to data analytics.  As far as personal projects go, I have a huge fan of cryptocurrency which meets at the roads of finance, crpytography, and computer science.  While it is a recent fad, I have been interested and involved since 2016 (the boom where popularity skyrocketed was the end of 2017).  So, I am working on a simple bot that will trade crpytocurrency based on analytics and algorithms.
							</p>
							<hr>
							<p>Cryptography and cyber-security: </p>
							<p>
								I have been interested in cryptography since the course I took in number theory and was amazed by its practicality, especially with the rise of cryptocurrency.  I have been working on different encrpytion and decryption programs that I hope to host on this site.
								Recently, I have also gotten into cyber-security, for which my team ranked #1 in the Midwest and we went on to compete at NYU's national Highschool Forensics competition.
							</p>
							<hr>
							<p>Machine Learning and Artificial Inteligence: </p>
							<p>
								This is hands down the most cutting edge and interesting topic in my opinion.  I have some experience working with neural networks from a summer I spent at MIT working on computer vision, voice recognition, and natural language processing.  Here, my team placed 2nd against highschoolers across the country, competing for the best autonomous cognitive assistant.
								Currently, I am hopin to develop an AI to not beat any old game, but the Tower Defense game that I am designing currently.
							</p>
							<br>
							<br>
							<br />
					</div>
				</div> <!-- .cd-project-info -->
			</li>

			<li class="single-project two">
				<div class="cd-title">
					<h2>Contact Me</h2>
				</div> <!-- .cd-title -->

				<div class="cd-project-info">
					<button class="cd-scroll">Scroll down</button>

					<div class="content-wrapper">
						<p>
							Feel free to contact me using this form whether it is to give feedback on the site or to just reach out to me!  You can also visit any on my media pages linked on my home page (GitHub, LinkedIn, Facebook)
							<br />
							<br />
						</p>
						<p>
						<center>
						<form class = "contact-form" action = "<?php echo $_SERVER['PHP_SELF']; ?>" method = "post">
							<input type = "text" name = "name" placeholder="Full Name" value = "<?php echo htmlspecialchars($name); ?>"/>
							<input type = "text" name = "email" placeholder="Your E-mail" value = "<?php echo htmlspecialchars($email); ?>"/>
							<input type = "text" name = "subj" placeholder="Subject" value = "<?php echo htmlspecialchars($subj); ?>"/>
							<textarea name="message" rows="8" cols="80" placeholder = "Enter your message here" value = "<?php echo htmlspecialchars($message); ?>"></textarea>
							<br />
							<button type="submit" name = "submit" class = "button-blue button-extra"> SEND </button>
						</form>
						</center>
					</p>
					</div>
				</div> <!-- .cd-project-info -->
			</li>

			<li class="single-project three">
				<div class="cd-title">
					<h2> Résumé </h2>
				</div> <!-- .cd-title -->

				<div class="cd-project-info">
					<button class="cd-scroll">Scroll down</button>

					<div class="content-wrapper">


													<p>

														My Resume was written halfway through my senior year in highschool and will likely be updated again before I begin my first year in college. If you have any questions feel free to reach out to me via the contact me page or through any of my media links on my home page.
													</p>

													<p>
														My Resume is currently catered towards what I have done in terms of CS.  Not listed are all of my projects, some of the service I have done such as acting as a residential assistant with over 150 logged hours and tutoring underpriveledged kids for around 50 hours.
														Class I have taken include Calculus (including Multivariable), Linear Algebra, Discrete Math, Number Theory, AP CS, Object Orientated Programming, and computational science.
														<br />
														<br />
														<a href = "img/FedericiResume.pdf" target="_blank">
															<button type="button" class = "button-blue"> View Resume</button>
														</a>
													</p>

					</div>
				</div> <!-- .cd-project-info -->
			</li>
		</ul>
	</div> <!-- .cd-projects-container -->
	<center>
			<div class = "jv" id = "jv"></div>
	</center>
	<script type="text/javascript">
	<!--
	var m = "This page was last updated: " + document.lastModified;
	var p = m.length-8;
	document.getElementById("jv").innerHTML = m.substring(p, 0);
	 -->
	</script>
<script src="js/jquery-2.1.4.js"></script>
<script src="js/main.js"></script> <!-- Resource jQuery -->
</body>
</html>
