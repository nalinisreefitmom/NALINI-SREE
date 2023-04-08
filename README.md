<!DOCTYPE html>
<html>
<head>
	<title>Vertical Links in Centered Button</title>
	<style>
		body {
			background-image: url('https://images.pexels.com/photos/1261728/pexels-photo-1261728.jpeg?cs=srgb&dl=pexels-stephan-seeber-1261728.jpg&fm=jpg');
			background-size: cover;
			background-repeat: no-repeat;
			background-position: center;
			height: 100%;
			margin: 0;
			padding: 0;
			color: #fff;
			font-family: Arial, sans-serif;
		}

		.center {
			display: flex;
			flex-direction: column;
			align-items: center;
			justify-content: center;
			height: 100%;
		}

		.btn {
			display: inline-block;
			padding: 30px 50px;
			background: linear-gradient(180deg, #00c3ff 0%, #ffffff 100%);
			color: white;
			text-align: center;
			text-decoration: none;
			font-size: 24px;
			margin: 5px;
			border-radius: 30px;
			box-shadow: 0px 2px 5px rgba(0,0,0,0.5);
			border: none;
			cursor: pointer;
			transition: all 0.3s ease;
			letter-spacing: 1px;
			position: relative;
		}

		.btn::before {
			content: '';
			position: absolute;
			top: -10px;
			right: -10px;
			bottom: -10px;
			left: -10px;
			background-color: #fff;
			border-radius: 50%;
			transform: scale(0);
			transition: transform 0.3s ease;
			z-index: -1;
		}

		.btn:hover::before {
			transform: scale(1);
		}

		.btn:hover {
			transform: translateY(-2px);
			background-color: #00c3ff;
			box-shadow: 0px 5px 10px rgba(0,0,0,0.5);
		}

		.btn:hover a {
			color: white;
		}

		.btn a {
			display: block;
			margin: 20px 0;
			padding: 20px;
			background-color: #333;
			color: #fff;
			text-decoration: none;
			border-radius: 20px;
			transition: all 0.3s ease;
			box-shadow: 0px 2px 5px rgba(0,0,0,0.5);
			font-size: 20px;
			letter-spacing: 1px;
			position: relative;
			z-index: 1;
		}

		.btn a::before {
			content: '';
			position: absolute;
			top: 0;
			right: 0;
			bottom: 0;
			left: 0;
			background-color: white;
			transform: scaleX(0);
			transform-origin: left;
			transition: transform 0.3s ease;
			z-index: -1;
		}

		.btn a:hover::before {
			transform: scaleX(1);
		}

		.btn a:hover {
			background-color: orange;
			transform: translateY(1x);
			box


			.btn span {
			font-size: 14px;
			position: absolute;
			top: 10px;
			left: 50%;
			transform: translateX(-50%);
			text-transform: uppercase;
			letter-spacing: 2px;
			font-weight: bold;
		}

		.nalini-sree {
			font-size: 30px;
			text-align: center;
			margin-top: 50px;
			text-transform: uppercase;
			letter-spacing: 5px;
			font-weight: bold;
			color: #fff;
			text-shadow: 0px 2px 5px rgba(0,0,0,0.5);
		}
	</style>
</head>
<body>
	
		

	<div class="center">
		<button class="btn">
			<a href="https://www.youtube.com/channel/UCcA6GyoRrRcWTUIHx2O9evw?sub_confirmation=1" target="_blank">?YOUTUBE</a>
			<a href="https://www.myherbalife.com/" target="_blank">?Herbalife Home Page</a>
			<a href="https://www.instagram.com/nalinisreefitmom/?hl=en" target="_blank">?INSTAGRAM</a>
			<a href="https://docs.google.com/forms/d/1vWA7QwrdpdzK1N1LgmDEuvLODC-faeXbrH-q9DYddVY/prefill" target="_blank">?GOOGLE FORM</a>
			<a href="https://t.me/+U4diHV1mbIWMGPIw" target="_blank">?TELEGRAM</a>
		</button>
	</div>
</body>
</html>
 to this 
