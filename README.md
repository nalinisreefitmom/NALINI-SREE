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
		}

		.btn a:hover {
			background-color: orange;
			transform: translateY(-2px);
			box-shadow: 0px 5px 10px rgba(0,0,0,0.5);
		}
	</style>
</head>

<body>
	<div class="center">
		<button class="btn">
			<a href="https://www.youtube.com/channel/UCcA6GyoRrRcWTUIHx2O9evw?sub_confirmation=1" target="_blank">❃ YOUTUBE</a>
			<a href="https://www.myherbalife.com/" target="_blank">❃ Herbalife Home Page</a>
			<a href="https://www.instagram.com/nalinisree.24/" target="_blank">❃ INSTAGRAM</a>
			<a href="https://docs.google.com/forms/d/e/1FAIpQLScfHgh4qxjfgQLEewLuf6UJC2c4lTXrJfJi-zhX6GZZqPpZ0A/viewform" target="_blank">❃ GOOGLE FORM</a>
			<a href="https://t.me/+U4diHV1mbIWMGPIw" target="_blank">❃ TELEGRAM</a>
		</button>
	</div>
</body>
</html>
