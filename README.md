# day1
i have started 100 days css challenge

HTML//
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>first day challenge</title>
	<link rel="stylesheet" type="text/css" href="h2.css">
</head>
<body>
	<div class="container">
		<div class="number">
			<div class="one-stroke"></div>
			<div class="one"></div>
			<div class=" zero zero1"></div>
			<div class="zero ero2"></div>
		</div>
		<p class="text-big">days</p>
		<p class="text-small">css challenge</p>
	</div>


</body>
</html>


CSS///

*{
	margin: 0;
	padding: 0;
	box-sizing: border-box;
	font-family: monospace;
}

.container{

	width: 350px;
	height: 350px;
	background-image: linear-gradient(to bottom left, #4ec6ca,#43389f);
	border-radius: 10px;
	display: flex;
	flex-direction: column;
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	align-items: center;
	justify-content: center;
}
.number{
	display: flex;
}
.one{
	width: 24px;
	height: 100px;
	background-color: #fff;
	border-radius: 4px;
	transform: translateX(15px);
	box-shadow: 0px 0px 20px 0px rgba(0, 0, 0, 0.3);
	z-index: 6;

}
.one-stroke{
	width: 24px;
	height: 45px;
	background-color: #fff;
	position: absolute;
	border-radius: 4px;
	transform: rotate(45deg);

}
 .zero{
 	width: 100px;
 	height: 100px;
 	border: 24px solid #fff;
 	border-radius: 50%;


 }

 .zero1{
 	box-shadow: 0px 0px 20px 0px rgba(0, 0, 0, 0.3);
 	transform: translateX(6px);
 	z-index-4;
 }

 .zero2{
 	box-shadow: 0px 0px 20px 0px rgba(0, 0, 0, 0.3);
 	transform: translateX(-12px);
 }

 .text-big{
 	font-size: 5.3rem;
 	font-weight: bold;
 	text-transform: uppercase;
 	color: #fff;
 	margin-top: -10px;

 }

 .text-small{
 	font-size: 1.6rem;
 	text-transform: uppercase;
 	font-weight: bold;
 	color: #fff;
 	margin: -20px;

 }
