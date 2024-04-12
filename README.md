<!DOCTYPE html>
<html>
<head>
	<style>
		body {
			margin: 0;
			padding: 0;
			height: 100%;
			width: 100%;
			background-color: #0066cc;
			position: absolute;
		}
		h1 {
			position: absolute;
			top: 50%;
			left: 50%;
			transform: translate(-50%, -50%);
			font-family: sans-serif;
			word-spacing: 2px;
			color: #fff;
			font-size: 2rem;
			font-weight: 900;
		}
		.dot {
			height: 5px;
			width: 5px;
			border-radius: 50px;
			background: rgba(255, 255, 255, 0.5);
			position: absolute;
			top: 20%;
			right: 20%;
		}
		.wrapper {
			height: 100%;
			width: 100%;
			position: relative;
		}
		.wrapper div {
			height: 60px;
			width: 60px;
			border: 2px solid rgba(255, 255, 255, 0.7);
			border-radius: 100px;
			position: absolute;
			top: 10%;
			left: 10%;
			animation: animate 4s linear infinite;
		}
		.wrapper div:nth-child(2) {
			top: 20%;
			left: 20%;
			animation: animate 8s linear infinite;
		}
		.wrapper div:nth-child(3) {
			top: 60%;
			left: 80%;
			animation: animate 10s linear infinite;
		}
		.wrapper div:nth-child(4) {
			top: 40%;
			left: 40%;
			animation: animate 3s linear infinite;
		}
		.wrapper div:nth-child(5) {
			top: 66%;
			left: 30%;
			animation: animate 7s linear infinite;
		}
		.wrapper div:nth-child(6) {
			top: 90%;
			left: 10%;
			animation: animate 9s linear infinite;
		}
		.wrapper div:nth-child(7) {
			top: 30%;
			left: 60%;
			animation: animate 5s linear infinite;
		}
		.wrapper div:nth-child(8) {
			top: 70%;
			left: 20%;
			animation: animate 8s linear infinite;
		}
		.wrapper div:nth-child(9) {
			top: 75%;
			left: 60%;
			animation: animate 10s linear infinite;
		}
		.wrapper div:nth-child(10) {
			top: 50%;
			left: 50%;
			animation: animate 6s linear infinite;
		}
		.wrapper div:nth-child(11) {
			top: 45%;
			left: 20%;
			animation: animate 10s linear infinite;
		}
		@keyframes animate {
			0% {
				height: 60px;
				width: 60px;
				border-radius: 100px;
				background-color: rgba(255, 255, 255, 0.5);
			}
			100% {
				height: 20px;
				width: 20px;
				border-radius: 50px;
				background-color: rgba(255, 255, 255, 0.7);
			}
		}
	</style>
</head>
<body>
	<div class="wrapper">
		<div></div>
		<div></div>
		<div></div>
		<div></div>
		<div></div>
		<div></div>
		<div></div>
		<div></div>
		<div></div>
		<div></div>
		<div></div>
	</div>
	<h1>Website Rules</h1>
</body>
</html>
