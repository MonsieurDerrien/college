<html lang="fr">

<head>
	<meta charset="utf-8"/>
	<title>inscription code combat</title>	
	<style>
		a {
			text-decoration: none;
			color: green;
		}
		
		h3 {
			text-align: center;
		}
		
		h1 {
			color: red;
			text-align: center;
			text-transform: uppercase;
		}
		
		#conteneur {
			width: 80%;
			display: flex;
			justify-content: space-around;
		}
		
		.bouton {
			border-radius: 8px ;
			font-family: Arial,sans-serif;
			font-size: 1.6em;
			width: 50px;
			height: 30px;
			padding-top: 7px; /*permet le centrage vertical*/
			text-align: center;
			color: #000;
			background: #444;
		     	background: linear-gradient( #555, #2C2C2C);
			text-shadow: 0px 1px 0px rgba(255,255,255,0.2);
			box-shadow: 0 0 5px rgba( 0, 0, 0, 0.5),
				    0 -1px 0 rgba( 255, 255, 255, 0.4);
		
		}
		
		.bouton:hover{
		     color: #222;
		     background: #555;
		     background: linear-gradient( #777, #333);
		}
		
		.bouton:active{
		     color: #000;
		     background: #444;
		     background: linear-gradient( #555, #2C2C2C);
		     box-shadow: 1px 1px 10px black inset, 
		                 0 1px 0 rgba( 255, 255, 255, 0.4);
		}
	</style>
</head>

<body>
	
	<h1>Si tu es un élève de M. Derrien, pour t'inscrire à code combat, clique sur ta classe</h1>
	<h3>(et pas sur ton camarade de classe)</h3>
	<div id="conteneur">
		<div class="bouton">
			<a href="https://codecombat.com/students?_cc=PointPowerBus">403</a>
		</div>
		<div class="bouton">
			<a href="https://codecombat.com/students?_cc=LampColdThin">404</a>
		</div>
		<div class="bouton">
			<a href="https://codecombat.com/students?_cc=SadUnderPark">408</a>
		</div>
		
		<div class="bouton">
			<a href="https://codecombat.com/students?_cc=BoxShopRice">410</a>
		</div>
	</div>
</body>

</html>
