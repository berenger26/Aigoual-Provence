# Aigoual-Provence<html>

<head>
	  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">

	<title> Aigoual Provence </title> 
	<meta charset="utf-8">
	<link rel="stylesheet" type="text/css" href="style.css">
	<link href="https://fonts.googleapis.com/css?family=Indie+Flower" rel="stylesheet">
</head>

<body>

	<div>
 		<ul class="nav-nav-tabs">
  			<li class="nav-item">
    			 <a class="nav-link-active" href="#">Accueil</a>
  			</li>
 			 <li class="nav-item dropdown">
   				 <a class="nav-link dropdown-toggle" data-toggle="dropdown" href="#" role="button" aria-haspopup="true" aria-expanded="false">Services</a>
    <div class="dropdown-menu">
			     <a class="dropdown-item" href="#">Action</a>
			     <a class="dropdown-item" href="#">Another action</a>
			     <a class="dropdown-item" href="#">Something else here</a>
     <div class="dropdown-divider"></div>
      			 <a class="dropdown-item" href="#">something more </a>
    </div>
 		 	</li>
 		 	<li class="nav-item">
   				 <a class="nav-link" href="#">Histoire </a>
 			</li>
  			<li class="nav-item">
    			 <a class="nav-link disabled" href="#">Contact</a>
  			</li>
		</ul>
	

	<div class="title-landing-page"> 
		<h1> <div> <img src="logo.png" alt="Chariot"> </div>
	 Aigoual Provence <br/></h1>
	</div>


<div class="MenuServices"> 
	<div> Services </div>
	<div>Réparation</div>
	<div>Vente</div>
	<div>Traitement thermique</div> 
</div>

	<h3> Histoire </h3>
	

	<div> 
		<h4> Plusieurs générations de scieurs ont auparavant pratiqué l'activité de scierie et exploitation forestière à Meyrueis et dans le massif de l'Aigoual.

	Avec la forte demande de palettes des années 1970, l'activité s'est peu à peu déplacée vers la région <em>marseillaise </em> très <strong> demandeuse. </strong>

	Depuis la création, nous sommes également partenaires de nombreuses structures d'accompagnement de personnes en difficultés : ESAT (Esat La Farigoule,...), CHRS,  avec qui nous travaillons en étroite collaboration. </h4>  
	</div>



	<div class="contactus"> Nous contacter 
	
	</div>

	<div class="formulaire">
		<form id="contact_form" action="#" method="POST" enctype="multipart/form-data">
	<div class="row">
		<label for="name">Nom : </label><br />
		<input id="name" class="input" name="name" type="text" value="" size="30" /><br />
	</div>
	<div class="row">
		<label for="email">Email:</label><br />
		<input id="email" class="input" name="email" type="text" value="" size="30" /><br />
	</div>
	<div class="row">
		<label for="message"> Demande d'information :</label><br />
		<textarea id="message" class="input" name="message" rows="7" cols="30"></textarea><br />
	</div>
		<input id="submit_button" type="submit" value="Send email" />
		</form>						
 	</div>

	<div>
		<img src="wood.jpeg" alt="bois">
	</div>

</body>


</html>



/*Titres*/
body{background-image: url("Photo.jpeg");
	background-attachment: fixed;
	height: 110vh;
	background-size: cover;}
h1 {
	color: white;
	font-size: 65px;
	text-align: center;
	line-height: 200px; 
	font-family: 'Indie Flower', cursive;
	margin-bottom: 200px;
	
}
h2 {color:black
	font-size:30px;
	font-family: 'Indie Flower',cursive;
	}

h3{font-family: 'Indie Flower',cursive; 
color: white; 
text-align: center;
font-size:40px;
}

h4{font-family: 'Indie Flower',cursive; color: white}

.onglets{ 
	list-style-type: none; 
}
.MenuServices {text-align: center;
	font-family: 'Indie Flower'
font-size : 60px;
color: white}

.logo.png  {background-color: #FFFFFF;
	 color : #FFFFFF;
	 font-size: 40px;
	 position: center;
 	display: block;}

.nav-nav-tabs {
	font-family: 'Indie Flower', cursive; 
	color: white; 
	background-position: fixed; 
	background-image: url(wood.jpeg); 
	font-size: 44px; 
	position: fixed ;
	margin-top: -20px;

}
.title-landing-page{text-align: center;}

a {color: white;}

li{
	display: inline;
	margin-right: 238px;

}
.Services {color :white;
font-family: 'Indie Flower', cursive;
font-size: 50px;
text-align: center;
display}

 .contactus{text-align: center;
 	border: bottom}

 #name{text-align: center;}

 .formulaire{text-align: center;}

