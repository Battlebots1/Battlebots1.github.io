<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Example HTML5 Document</title>
	<style>
		body {
			font-family: Arial, sans-serif;
		}
		header, nav, main, footer {
			padding: 20px;
			box-sizing: border-box;
		}
		header, footer {
			background-color: #f8f9fa;
			text-align: center;
		}
		nav ul {
			list-style-type: none;
			padding: 0;
			display: flex;
			justify-content: space-around;
		}
		nav a {
			text-decoration: none;
			color: #007bff;
		}
		main {
			display: flex;
			justify-content: space-around;
		}
		canvas {
			border: 1px solid black;
		}
		audio, video {
			display: block;
			margin: 0 auto;
		}
	</style>
</head>
<body>
	<header>
		<h1>Welcome to My Website</h1>
	</header>
	<nav>
		<ul>
			<li><a href="#">Home</a></li>
		for website <br> <br> For a website, we need to have a structure that includes the main elements such as header, 
		<li><a href="#">About</a></li> 
		<li><a href="#">Contact</a></li>
		</ul>
	</nav>
	<main>
		<div>
			<h2>Content 1</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed fermentum, ante et elementum cursus, quam dolor vestibulum velit, vel consequat eros lorem et dui.</p>
		</div>
		<div>
			<h2>Content 2</h2>
			<p>Curabitur vitae eros eu nisl fermentum ullamcorper vel id ex. Integer convallis justo quis sem posuere, non interdum est consequat. Sed sit amet nibh vel nibh fermentum pharetra.</p>
		</div>
	</main>
	<footer>
		<p>Copyright © 2023 My Website</p>
	</footer>
</body>
</html>
