# semaine-3
semaine 3 de la prairie
<!DOCTYPE html>
<head></head>
<body>
<a href = "https://www.codecademy.com/fr/users/lagneau/achievements">badges</a>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<html>
	<head>
		<meta charset="utf-8">
		<link type="text/css" rel="stylesheet" href="stylesheet.css"/>
		<title>CV html and CSS.</title>
	</head>
	<body>
		<div id="header">
         <p id="name">Lagneau Mathieu</p>
         <a href="mailto:you@yourdomain.com"><p id="email">mathieu.lagneau86@laposte.net</p></a>
         </div>
	    <div class="left"></div>
	    <div class="right">
	    <h4>Poste rechercher.</h4>
	    <p>Codeur informatique.</p>
	    <h4>Expérience professionnelle</h4>
	    <ul>
            <li>Cuisinier "le Noirlac"Saint Amand Montrond.</li>
	    	<li>Entretiens Espace-vert. "Clarisse-Environnement"le Muy.</li>
            <li>Téléconseiller/Back office. "Armatis-Châteauroux".</li>
	    </ul>
	    <h4>Diplômes et formations.</h4>
	    <ol>
	    	<li>BEP Hôtellerie;Spécialisation pâtisserie" lycée Jean Guehenno".</li>
	    	<li>BEP Horticulture spécialitée maraîchère."lycée de Chateauroux".</li>
	    	<li>Formation Games of codes."simplonline" avec"les codeurs indriens".</li>
	    </ol>
	    <h4>Mes compétences:</h4>
	    <p>Compétences en maintenance informatique</p>
	    <p>Base en langages HTML/CSS/PHP/JS/Ruby/git</p>
	    </div>
	    <div id="footer">
	    	<p>Mes coordonnées:25 rue d'anjou,36000 Chateauroux./TEL:06.59.52.71.37.</p>
	    </div>
	</body>
</html>
div{
	border-radius: 5px;
}

#header{
	z-index: 1;
	position:fixed;
	background-color: #668284;
	width:97.5%;
    height: 60px;
    margin-top: -20px;
    margin-bottom: 10px;
    }
 #name{
 	float:left;
	margin-left: 5px;
	padding-top: 5px;
	font-size: 16px;
	font-family: Verdana, sans-serif;
	color: #ffffff;
 } 
 #email{
 	float:right;
	margin-right: 5px;
	padding-top: 5px;
	font-size: 16px;
	font-family: impact,Verdana, sans-serif;
	color: #ffffff;
 }
 h4{
 	color:red;
 	margin-left: 5px;
	margin-bottom: 15px;
	font-family: Impact,Verdana, sans-serif;
 }
 .right p{
 	margin-left: 5px;
	margin-right: 5px;
	margin-top: -10px;
	font-family: Garamond, serif;
	color: #000000;
 }
 li{
 	list-style-type: circle;
 }
 a:hover{
 	font-weight: bold;
 }  

.left{
	position:relative;
	margin-top: 50px;
	margin-bottom: 10px;
	float:left;
	background-color: #B9D7D9;
	width: 10%;
	height: 400px;
    }

.right{
	position: relative;
	margin-top: 50px;
	margin-bottom: 10px;
	float:right;
	background-color: #F4EBC3;
	width: 88%;
	height: 400px;
    }

#footer{
	position: relative;
	background-color: #668284;
	height: 50px;
	clear: both;
    font-family: Verdana, sans-serif;
	font-size: 14px;
	text-align: center;
	color: #ffffff;
    }

    #footer p{
    	position: relative;
        padding-top: 15px;
    }
