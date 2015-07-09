<?php
// Algemene gegevens
$companyname 	= "Het Hooghuis";
$companyslogan	= "kleurt je leven";
$companyurl 	= "http://www.hethooghuis.nl";
$project		= "Handtekening generator";
$projectversie	= "1.1";

// Kleur codes huisstijl
//		Oranje	#f57215	f57215
//		Blauw	#0994dd	0994dd
//		Groen	#41b23b	41b23b
//		Paars	#7a1e8b	7a1e8b





// Koppel de waarden voor fomulier
$aanhef 		= $_POST["aanhef"];
$voorvoegsel 	= $_POST["voorvoegsel"];
$voornaam 		= $_POST["voornaam"];
$achternaam 	= $_POST["achternaam"];
$functie 		= $_POST["functie"];
$geslacht 		= $_POST["geslacht"];
$email 			= $_POST["email"];
$website 		= $_POST["website"];
$telefoon 		= $_POST["telefoon"];
$telefoon2 		= $_POST["telefoon2"];
$locatie 		= $_POST["locatie"];
$onderschrift 	= $_POST["onderschrift"];
$twitter 		= $_POST["twitter"];
$linkedin 		= $_POST["linkedin"];


/* twitter feeds individuele locaties
 * ------
https://twitter.com/HooghuisHeesch
https://twitter.com/HHzuidwest
https://twitter.com/HHdenbongerd
https://twitter.com/hethooghuis
https://twitter.com/tbl_oss
*/




?>


<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<meta name="description"		content="HTML Generator voor digitale handtekening">
	<meta name="keywords" 			content="HTML,PHP,ICT,Email">
	<meta name="author" 			content="Klomp, Derk - het Hooghuis 2015">
	<meta name="contact" 			content="webmaster@hethooghuis.nl">
<title><?php echo $companyname . ' • ' . $project . ' ' . $projectversie ;?></title>
	<link href="http://www.hethooghuis.nl/favicon.ico" rel="shortcut icon" type="image/x-icon" >
	<link rel="stylesheet" type="text/css" href="view.css" media="all">
	<script type="text/javascript" src="view.js"></script>
	<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">
</head>
<body id="main_body" >
	<img id="top" src="img/top.png" alt="">
	<div id="form_container">
	<img id="header" src="img/header.png">
		<h1><a href="<?php print $url;?>"><?php print $companyname; ?></a></h1>
		<form id="form_signature" class="appnitro"  method="post" action="<?php echo htmlspecialchars($_SERVER["PHP_SELF"]); ?>">
		<div class="form_description">
			<h2><?php print $companyname ?></h2>
			<p>Genereer handtekening voor email</p>
		</div>						
			<ul >
			<li id="aanhef" >
			<p class="guidelines" id="guide_2"><small>Mannen komen van Mars, vrouwen van Venus</small></p> 
				<label class="description" for="aanhef">Aanhef</label>
					<span>
					<input <?php if ($aanhef=="Dhr. ") echo "CHECKED"; ?> id="aanhef" name="aanhef" class="element radio" type="radio" value="Dhr. " />
						<label class="choice" for="meneer"> Dhr <i class="fa fa-mars"></i></label>
					
					<input <?php if ($aanhef=="Mevr. ") echo "CHECKED"; ?> id="aanhef" name="aanhef" class="element radio" type="radio" value="Mevr. " />
						<label class="choice" for="mevrouw"> Mevr. <i class="fa fa-venus"></i></label>
					
					<input <?php if ($aanhef==" ") echo "CHECKED"; ?> id="aanhef" name="aanhef" class="element radio" type="radio" value=" " />
						<label class="choice" for="geen"> nvt <i class="fa fa-circle-thin"></i></label>	
					
					</span>
			</li>
			
			<li id="naam" >
					<label class="description" for="naam"><i class="fa fa-user "></i> Naam </label>
					<span>
						<input id="voornaam" name= "voornaam" class="element text" maxlength="255" size="16" value="<?php echo $voornaam; ?>"/>
						<label>Voornaam of voorletters</label>
					</span>
					<span>
						<input id="voorvoegsel" name= "voorvoegsel" class="element text" maxlength="255" size="6" value="<?php echo $voorvoegsel; ?>"/>
						<label>tussenvoegsel</label>
					</span>
					<span>
						<input id="achternaam" name= "achternaam" class="element text" maxlength="255" size="16" value="<?php echo $achternaam; ?>"/>
						<label>Achternaam</label>
					</span>
					
			</li>
			
			<li id="functie" >
				<label class="description" for="functie"><i class="fa fa-pencil "></i> Functie </label>
					<div>
						<input id="functie" name="functie" class="element text" type="text" maxlength="255" size="50" value="<?php echo $functie; ?>"/>
						<p class="guidelines" id="email"><small>bijv. Teamleider Bovenbouw / Docent Natuurkunde</small></p>
					</div> 
			</li>
			
			<li id="email" >
				<label class="description" for="email"><i class="fa fa-envelope-o "></i> Email </label>
					<div>
						<input id="email" name="email" class="element text " type="text" maxlength="255" size="25" value="<?php echo $email; ?>"/>@hethooghuis.nl
					</div>
					<p class="guidelines" id="email"><small>Jouw mail address, bijv. john.doe@hethooghuis.nl</small></p>
			</li>
			
			<li id="website" >
				<label class="description" for="email"><i class="fa fa-home " ></i> Website </label>
					<div>
						<input id="website" name="website" class="element text " type="text" maxlength="255" size="50" value="<?php echo $website; ?>"/>
					</div>
					<p class="guidelines" id="email"><small>bijv. http://mooiwerk.hethooghuis.nl</small></p>
			</li>			
			
					
			<li id="telefoon" >
				<label class="description" for="telefoon"><i class="fa fa-phone-square "></i> Telefoon </label>
				<div>
					<input id="telefoon" placeholder="0612345678" name="telefoon" class="element text medium" type="tel" maxlength="255" size="25" value="<?php echo $telefoon; ?>"/>
					<input id="telefoon2" placeholder="17001" name="telefoon2" class="element text medium" type="tel" maxlength="255" size="25" value="<?php echo $telefoon2; ?>"/> 
				</div>
						<p class="guidelines" id="guide_2">
							<small>Intern toestel- of mobielnummer</small>
						</p> 
			</li>
					
			
			<li id="locatie" >
				<label class="description" for="locatie"><i class="fa fa-university "></i> Locatie </label>
					<div>
						<select class="element select medium" id="locatie" name="locatie"> 
							<option value="" >kies locatie</option>
							<option value="1" <?php if ($locatie==1) echo "selected='selected'"; ?>>Den Bongerd</option>
							<option value="2" <?php if ($locatie==2) echo "selected='selected'"; ?>>Heesch</option>
							<option value="3" <?php if ($locatie==3) echo "selected='selected'"; ?>>Centrale Dienst</option>
							<option value="4" <?php if ($locatie==4) echo "selected='selected'"; ?>>Mondriaan</option>
							<option value="5" <?php if ($locatie==5) echo "selected='selected'"; ?>>Ravenstein</option>
							<option value="6" <?php if ($locatie==6) echo "selected='selected'"; ?>>Stadion</option>
							<option value="7" <?php if ($locatie==7) echo "selected='selected'"; ?>>De Singel</option>
							<option value="8" <?php if ($locatie==8) echo "selected='selected'"; ?>>TBL</option>
							<option value="9" <?php if ($locatie==9) echo "selected='selected'"; ?>>West</option>
							<option value="10"<?php if ($locatie==10) echo "selected='selected'"; ?>>Zuid</option>
						</select>
					</div> <p class="guidelines" id="guide_2"><small>Kies jouw 'thuis' locatie</small></p> 
			</li>
			
			<li id="twitter">
				<div>
					<!--- <input type="checkbox" name="checktwitter" value="yes"> ---> <font color="#0099FF"><i class="fa fa-twitter"></i></font> twitter.com/ &nbsp; 
					<input id="twitter" name= "twitter" placeholder="hethooghuis" class="element text" maxlength="255" size="16" value="<?php echo $twitter; ?>"/>
					<br>
					<!---  <input type="checkbox" name="checklinkedin" value="yes"> ---> <font color="#0099FF"><i class="fa fa-linkedin"></i></font> linkedin.com/in/ 
					<input id="linkedin" name= "linkedin" placeholder="hethooghuis" class="element text" maxlength="255" size="16" value="<?php echo $linkedin; ?>"/>
				</div>
			</li>
			
				
			
			
			<li id="onderschrift" >
				<label class="description" for="onderschrift">Onderschrift </label>
					<div>
						<input id="onderschrift" name="onderschrift" class="element text large" type="text" maxlength="255" value="<?php echo $onderschrift; ?>"/> 
					</div>
					<p class="guidelines" id="guide_2">
						<small>Noteer een opmerking of aanvullende informatie, bijv. werktijden of neven-locatie</small>
					</p>
			</li>
			<center>
			<li class="buttons">
				<input id="saveForm" class="button_text" type="submit" name="submit" value="Genereer handtekening" />
			</li>
			</center>
			</ul>
		</form>
		
		<?php
		
if (!isset($_POST['submit'])) { // nadat pagina verstuurd is toon input

} else { /* OUD VOORBEELD - RUWE DATA
		  * 
    echo "<h2>Testing data:</h2>";
    
	if ($aanhef==TRUE)		echo '<br>Aanhef: ' 	 . $aanhef; 		else echo '<br> geen <i>aanhef</i> ingevuld';
	if ($voornaam==TRUE) 	echo '<br>Voornaam: ' 	 . $voornaam; 		else echo '<br> geen <i>voornaam</i> ingevuld ';
	if ($voorvoegsel==TRUE) echo '<br>voorvoegsel: ' . $voorvoegsel; 	else echo '<br> geen <i>voorvoegsel</i> ingevuld';
	if ($achternaam==TRUE)	echo '<br>Achternaam: '  . $achternaam; 	else echo '<br> geen <i>achternaam</i> ingevuld';
    if ($functie==TRUE)		echo '<br>Functie: ' 	 . $functie; 		else echo '<br> geen <i>functie</i> ingevuld';
    if ($email==TRUE)		echo '<br><i class="fa fa-envelope-o"></i> Email: ' . $email; else echo '<br> geen <i>mail</i> ingevuld';
	if ($website==TRUE)		echo '<br><i class="fa fa-link"></i></i> Website: <a href="' . $website .'" target="_blanc">' . $website . "</a>"; else echo '<br> geen <i>website</i> ingevuld';
    if ($telefoon==TRUE)	echo '<br><i class="fa fa-whatsapp"></i> Telefoon: ' . $telefoon; else echo '<br> geen <i>mobiel telefoon nummer</i> ingevuld';
	if ($telefoon2==TRUE)	echo '<br><i class="fa fa-phone"></i> Telefoon: ' . $telefoon2; else echo '<br> geen <i>intern toestel nummer</i> ingevuld';
	if ($locatie==FALSE) 	echo '<br>geen <i>locatie</i> ingevuld'; else {
							echo "<br><font color='FF7272'><i class=\"fa fa-university\"></i></font> Locatie: " . $locatie ." - " ;
			if ($locatie==1) echo'Bongerd | Staringstraat 4 5343 GH Oss Tel. 0412-224120';
			if ($locatie==2) echo'Heesch | Schoonstraat 34 5384 AP Heesch Tel. 0412-224130';
			if ($locatie==3) echo'Centrale Dienst | Nieuwe Hescheweg 11 5342 EB Oss Tel. 0412-224100';
			if ($locatie==4) echo'Mondriaan | Mondriaanlaan 1 5342 CN Oss Tel. 0412-224190';
			if ($locatie==5) echo'Ravenstein | Middingstraat 1 5371 EJ Ravenstein Tel. 0412-224170';
			if ($locatie==6) echo'Stadion | Mondriaanlaan 6 5342 CN Oss Tel. 0412-224140 ';
			if ($locatie==7) echo'Singel | Kapelaan Nausstraat 2 5348 TH Oss Tel. 0412-224110 ';
			if ($locatie==8) echo'Titus Brandsmalyceum | Molenstraat 30 5341 GD Oss Tel. 0412-224180';
			if ($locatie==9) echo'West | Verdistraat 75 5343 VC Oss Tel. 0412-224150 ';
			if ($locatie==10) echo'Zuid | De Ruivert 5 5342 CM Oss Tel. 0412-224160';
		}

	if ($twitter==TRUE)		 echo '<br><font color="#0099FF"><i class="fa fa-twitter" ></i></font> twitter.com/' . $twitter; else echo '<br> geen <i>twitter</i>';
    if ($linkedin==TRUE)	 echo '<br><font color="#0099FF"><i class="fa fa-linkedin"></i></font> linkedin.com/' . $linkedin; else echo '<br> geen <i>linkedin</i>';
	if ($onderschrift==TRUE) echo "<br>Onderschrift: " . $onderschrift; else echo '<br> geen <i>onderschrift</i>';
	if ($twitter==TRUE)		echo '<br>tweet: '.$twitter; else {
																if($locatie==1) echo 'https://twitter.com/HHdenbongerd';
																if($locatie==2) echo 'https://twitter.com/HooghuisHeesch';
																if($locatie==3) echo 'https://twitter.com/hethooghuis';
																if($locatie==4) echo 'https://twitter.com/hethooghuis';
																if($locatie==5) echo 'https://twitter.com/hethooghuis';
																if($locatie==6) echo 'https://twitter.com/hethooghuis';
																if($locatie==7) echo 'https://twitter.com/hethooghuis';
																if($locatie==8) echo 'https://twitter.com/tbl_oss'; 
																if($locatie==9) echo 'https://twitter.com/HHzuidwest';
																if($locatie==10) echo 'https://twitter.com/HHzuidwest';																
																}
    echo '<br><hr>';
	}
?>*/

?>

<!--- HTML TABEL TESTING  Courier New", Courier, monospace  --->

<h2>Voorbeeld handtekening</h2>

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;margin:0px auto; background: #FFFFDB;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:0px 0px;border-style:solid;border-width:0px;overflow:hidden;border-color:#E0E0EB;word-break:normal;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:0px 0px;border-style:solid;border-width:0px;border-color:#E0E0EB;overflow:hidden;word-break:normal;}
.tg .tg-logo{font-size:13px;font-family:Tahoma, Geneva, sans-serif !important;}
.tg .tg-naam{font-size:13px;font-family:Tahoma, Geneva, sans-serif !important;}
.tg .tg-details{font-size:12px;font-family:Tahoma, Geneva, sans-serif !important;}
.tg .tg-locatie{font-size:11px;font-family:Tahoma, Geneva, sans-serif !important;padding: 0px 0px;}
.tg .tg-opmerking{font-size:11px;font-family:Tahoma, Geneva, sans-serif !important;padding:0px 0px}
th.tg-sort-header::-moz-selection { background:transparent; }th.tg-sort-header::selection      { background:transparent; }th.tg-sort-header { cursor:pointer; }table th.tg-sort-header:after {  content:'';  float:right;  margin-top:7px;  border-width:0 4px 4px;  border-style:solid;  border-color:#404040 transparent;  visibility:hidden;  }table th.tg-sort-header:hover:after {  visibility:visible;  }table th.tg-sort-desc:after,table th.tg-sort-asc:after,table th.tg-sort-asc:hover:after {  visibility:visible;  opacity:0.4;  }table th.tg-sort-desc:after {  border-bottom:none;  border-width:4px 4px 0;  }</style>
<table id="tg-signature" class="tg" style="undefined;table-layout: fixed; width: 450px">
<colgroup>
<col style="width: 150px">
<col style="width: 350px">
</colgroup>
  <tr>
    <th class="tg-logo"><img src="img/logo_HetHooghuis_v2.png" alt="logo Het Hooghuis" title="logo Het Hooghuis"></th>
    <th class="tg-naam" style="text-align: left;"><b><?php echo $aanhef.' '.$voornaam.' '.$voorvoegsel.' '.$achternaam.'</b><br><i><font color="5E5E5E">'.$functie.'</font></i>';?><br></th>
  </tr>
  <tr>
    <td class="tg-details" colspan="2">
	<?php if ($website==TRUE)	echo '<a href="' . $website .'" title="Bezoek: '.$website.'" target="_blanc" style="text-decoration: none; color: #7a1e8b;"><img src="img/icon_website.png" alt="website" title="Bezoek de website" style="vertical-align:bottom;"></a> &nbsp;'; else echo '<a href="'.$companyurl.'" title="Surf naar algemene website" target="_blanc" style="text-decoration: none; color: #7a1e8b;"><img src="img/icon_website.png" alt="website" title="Bezoek de website" style="vertical-align:bottom;"></a> &nbsp;'?>
	<?php if ($email==TRUE)		echo '<a href="mailto:'.$email.'@hethooghuis.nl?subject=contact" title="Verstuur mail aan: '.$voornaam.' '.$voorvoegsel.' '.$achternaam.'" style="text-decoration: none; color: #f57215;"><img src="img/icon_mail.png" alt="mail" title="Verstuur mail aan: '.$voornaam.' '.$voorvoegsel.' '.$achternaam.'" style="vertical-align:bottom;"></a> &nbsp; ';?>
	<?php if ($twitter==TRUE)	echo '<a href="https://www.twitter.com/'.$twitter.'" target="_blanc" title="Persoonlijk twitter account" style="text-decoration: none; color: #0099FF;"><img src="img/icon_twitter.png" alt="Twitter" title="Persoonlijk twitter account" style="vertical-align:bottom;"></a> &nbsp;';
		else {
																if($locatie==1) echo '<a href="https://twitter.com/HHdenbongerd" target="_blanc" title="Twitter lokatie: Bongerd" style="text-decoration: none; color: #0099FF;"><img src="img/icon_twitter.png" alt="Twitter" title="Twitter account: Den Bongerd" style="vertical-align:bottom;"></a> &nbsp;';
																if($locatie==2) echo '<a href="https://twitter.com/HooghuisHeesch" target="_blanc" title="Twitter lokatie: Heesch" style="text-decoration: none; color: #0099FF;"><img src="img/icon_twitter.png" alt="Twitter" title="Twitter account: Heesch" style="vertical-align:bottom;"></a> &nbsp;';
																if($locatie==3) echo '<a href="https://twitter.com/hethooghuis" target="_blanc" title="Twitter @HetHooghuis" style="text-decoration: none; color: #0099FF;"><img src="img/icon_twitter.png" alt="Twitter" title="Twitter account: @HetHooghuis" style="vertical-align:bottom;"></a> &nbsp;';
																if($locatie==4) echo '<a href="https://twitter.com/hethooghuis" target="_blanc" title="Twitter @HetHooghuis" style="text-decoration: none; color: #0099FF;"><img src="img/icon_twitter.png" alt="Twitter" title="Twitter account: @HetHooghuis" style="vertical-align:bottom;"></a> &nbsp;';
																if($locatie==5) echo '<a href="https://twitter.com/hethooghuis" target="_blanc" title="Twitter @HetHooghuis" style="text-decoration: none; color: #0099FF;"><img src="img/icon_twitter.png" alt="Twitter" title="Twitter account: @HetHooghuis" style="vertical-align:bottom;"></a> &nbsp;';
																if($locatie==6) echo '<a href="https://twitter.com/hethooghuis" target="_blanc" title="Twitter @HetHooghuis" style="text-decoration: none; color: #0099FF;"><img src="img/icon_twitter.png" alt="Twitter" title="Twitter account: @HetHooghuis" style="vertical-align:bottom;"></a> &nbsp;';
																if($locatie==7) echo '<a href="https://twitter.com/hethooghuis" target="_blanc" title="Twitter @HetHooghuis" style="text-decoration: none; color: #0099FF;"><img src="img/icon_twitter.png" alt="Twitter" title="Twitter account: @HetHooghuis" style="vertical-align:bottom;"></a> &nbsp;';
																if($locatie==8) echo '<a href="https://twitter.com/tbl_oss" target="_blanc" title="Twitter locatie: Titus Brandsmalyceum" style="text-decoration: none; color: #0099FF;"><img src="img/icon_twitter.png" alt="Twitter" title="Twitter account: TBL" style="vertical-align:bottom;"></a> &nbsp;'; 
																if($locatie==9) echo '<a href="https://twitter.com/HHzuidwest" target="_blanc" title="Twitter locatie: West" style="text-decoration: none; color: #0099FF;"><img src="img/icon_twitter.png" alt="Twitter" title="Twitter account: West - Zuid" style="vertical-align:bottom;"></a> &nbsp;';
																if($locatie==10) echo '<a href="https://twitter.com/HHzuidwest" target="_blanc" title="Twitter locatie: Zuid" style="text-decoration: none; color: #0099FF;"><img src="img/icon_twitter.png" alt="Twitter" title="Twitter account: West - Zuid" style="vertical-align:bottom;"></a> &nbsp;';																
																}
		?>
  
	<?php if ($linkedin==TRUE)	echo '<a href="https://nl.linkedin.com/in/'.$linkedin.'" target="_blanc" title="Persoonlijk LinkedIN account: '.$voornaam.' '.$voorvoegsel.' '.$achternaam.'"><img src="img/icon_linkedin.png" alt="LinkedIN" title="LinkedIN account: '.$voornaam.' '.$voorvoegsel.' '.$achternaam.'" style="vertical-align:bottom;"></a> &nbsp;';?>
	<?php if ($telefoon==TRUE)	echo '<img src="img/icon_phone.png" alt="telefoon" title="telefoon nummer" style="vertical-align:middle;"> '.$telefoon.' &nbsp;';?>
	<?php if ($telefoon2==TRUE)	echo '<img src="img/icon_phone.png" alt="telefoon" title="intern nummer" style="vertical-align:middle;"><font color="#5E5E5E"> intern: </font>'.$telefoon2.' &nbsp;';?>
  </td>
  </tr>
  <tr>
    <td class="tg-locatie" colspan="2"><br><?php
			if ($locatie==1) echo'<a href="https://www.google.nl/maps/place/Het+Hooghuis+-+Locatie+Den+Bongerd/" target="_blanc" alt="Locatie Bongerd"><img src="img/icon_location.png" alt="Locatie Bongerd" title="Locatie: Bongerd" style="vertical-align:bottom;"></a> <b>Den Bongerd</b> | Staringstraat 4 5343 GH Oss &nbsp; <img src="img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;"> 0412-224120';
			if ($locatie==2) echo'<a href="https://www.google.nl/maps/place/Het+Hooghuis+Heesch/" target="_blanc" alt="Locatie Heesch"><img src="img/icon_location.png" alt="Locatie Heesch" title="Locatie: Heesch" style="vertical-align:bottom;"></a> <b>Heesch</b> | Schoonstraat 34 5384 AP Heesch&nbsp; <img src="img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;"> 0412-224130';
			if ($locatie==3) echo'<a href="https://www.google.nl/maps/place/Het+Hooghuis/" target="_blanc" alt="Locatie Centrale Dienst"><img src="img/icon_location.png" alt="Locatie Centrale Dienst" title="Locatie: Centrale Dienst" style="vertical-align:bottom;"></a> <b>Centrale Dienst</b> | Nieuwe Hescheweg 11 5342 EB Oss &nbsp; <img src="img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;">0412-224100';
			if ($locatie==4) echo'<a href="https://www.google.nl/maps/place/Mondriaan+College/" target="_blanc" alt="Locatie Mondriaan"><img src="img/icon_location.png" alt="Locatie Mondriaan" title="Locatie: Mondriaan" style="vertical-align:bottom;"></a> <b>Mondriaan</b> | Mondriaanlaan 1 5342 CN Oss &nbsp;<img src="img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;"> 0412-224190';
			if ($locatie==5) echo'<a href="https://www.google.nl/maps/place/Het+Hooghuis/@51.791766,5.65229,17z/" target="_blanc" alt="Locatie Ravenstein"><img src="img/icon_location.png" alt="Locatie Ravenstein" title="Locatie: Ravenstein" style="vertical-align:bottom;"></a> <b>Ravenstein</b> | Middingstraat 1 5371 EJ Ravenstein &nbsp;<img src="img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;"> 0412-224170';
			if ($locatie==6) echo'<a href="https://www.google.nl/maps/place/Mondriaanlaan+6,+5342+Oss/@51.7538598,5.5279389,17z/" target="_blanc" alt="Locatie Stadion"><img src="img/icon_location.png" alt="Locatie Stadion" title="Locatie: Stadion" style="vertical-align:bottom;"></a>  <b>Stadion</b> | Mondriaanlaan 6 5342 CN Oss &nbsp;<img src="img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;"> 0412-224140 ';
			if ($locatie==7) echo'<a href="https://www.google.nl/maps/place/Het+Hooghuis+-+Locatie+De+Singel/@51.771714,5.542561,17z/" target="_blanc" alt="Locatie Singel"><img src="img/icon_location.png" alt="Locatie Singel" title="Locatie: Singel" style="vertical-align:bottom;"></a>  <b>De Singel</b> | Kapelaan Nausstraat 2 5348 TH Oss &nbsp;<img src="img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;"> 0412-224110 ';
			if ($locatie==8) echo'<a href="https://www.google.nl/maps/place/Titus+Brandsmalyceum/@51.7673095,5.5265132,18z/" target="_blanc" alt="Locatie TBL"><img src="img/icon_location.png" alt="Locatie Titus Brandsmalyceum" title="Locatie: Titus Brandsmalyceum" style="vertical-align:bottom;"></a>  <b>Titus Brandsmalyceum</b> | Molenstraat 30 5341 GD Oss &nbsp;<img src="img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;"> 0412-224180';
			if ($locatie==9) echo'<a href="https://www.google.nl/maps/place/Het+Hooghuis+-+Locatie+Oss-West/@51.75335,5.519817,17z/" target="_blanc" alt="Locatie West"><img src="img/icon_location.png" alt="Locatie West" title="Locatie: West" style="vertical-align:bottom;"></a>  <b>West</b> | Verdistraat 75 5343 VC Oss &nbsp;<img src="img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;"> 0412-224150 ';
			if ($locatie==10) echo'<a href="https://www.google.nl/maps/place/Het+Hooghuis+-+Locatie+Oss-Zuid/@51.752556,5.530653,17z/" target="_blanc" alt="Locatie Zuid"><img src="img/icon_location.png" alt="Locatie Zuid" title="Locatie: Zuid" style="vertical-align:bottom;"></a>  <b>Zuid</b> | De Ruivert 5 5342 CM Oss &nbsp;<img src="img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;"> 0412-224160';?><br></td>
  </tr>
  <?php if ($onderschrift==TRUE) echo '
  <tr>
    <td class="tg-opmerking" colspan="2"><font color="7AC976"><img src="img/icon_comments.png" alt="opmerking" title="opmerking" style="vertical-align:bottom;"> <i>&nbsp;'. $onderschrift.'</i></font></td>
  </tr>';?>
</table>
<hr>
<?php } ?>

<!---- EINDE HTML TABEL TESTING ---->

<h2>Resultaat:</h2>
<span><label>kopieer en plak in de email toepassing</label></span><br>
<textarea cols="60" rows="8" name="htmlsignature">
	
	<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;margin:0px auto; background: #FFFFFF;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:0px 0px;border-style:solid;border-width:0px;overflow:hidden;border-color:#E0E0EB;word-break:normal;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:0px 0px;border-style:solid;border-width:0px;border-color:#E0E0EB;overflow:hidden;word-break:normal;}
.tg .tg-logo{font-size:13px;font-family:Tahoma, Geneva, sans-serif !important;}
.tg .tg-naam{font-size:13px;font-family:Tahoma, Geneva, sans-serif !important;}
.tg .tg-details{font-size:12px;font-family:Tahoma, Geneva, sans-serif !important;}
.tg .tg-locatie{font-size:11px;font-family:Tahoma, Geneva, sans-serif !important;padding: 0px 0px;}
.tg .tg-opmerking{font-size:11px;font-family:Tahoma, Geneva, sans-serif !important;padding:0px 0px}
th.tg-sort-header::-moz-selection { background:transparent; }th.tg-sort-header::selection      { background:transparent; }th.tg-sort-header { cursor:pointer; }table th.tg-sort-header:after {  content:'';  float:right;  margin-top:7px;  border-width:0 4px 4px;  border-style:solid;  border-color:#404040 transparent;  visibility:hidden;  }table th.tg-sort-header:hover:after {  visibility:visible;  }table th.tg-sort-desc:after,table th.tg-sort-asc:after,table th.tg-sort-asc:hover:after {  visibility:visible;  opacity:0.4;  }table th.tg-sort-desc:after {  border-bottom:none;  border-width:4px 4px 0;  }</style>
<table id="tg-signature" class="tg" style="undefined;table-layout: fixed; width: 450px">
<colgroup>
<col style="width: 150px">
<col style="width: 350px">
</colgroup>
  <tr>
    <th class="tg-logo"><img src="http://10.20.171.56/signature/v2/img/logo_HetHooghuis_v2.png" alt="logo Het Hooghuis" title="logo Het Hooghuis"></th>
    <th class="tg-naam" style="text-align: left;"><b><?php echo $aanhef.' '.$voornaam.' '.$voorvoegsel.' '.$achternaam.'</b><br><i><font color="5E5E5E">'.$functie.'</font></i>';?><br></th>
  </tr>
  <tr>
    <td class="tg-details" colspan="2">
	<?php if ($website==TRUE)	echo '<a href="' . $website .'" title="Bezoek: '.$website.'" target="_blanc" style="text-decoration: none; color: #7a1e8b;"><img src="http://10.20.171.56/signature/v2/img/icon_website.png" alt="website" title="Bezoek de website" style="vertical-align:bottom;"></a> &nbsp;'; else echo '<a href="'.$companyurl.'" title="Surf naar algemene website" target="_blanc" style="text-decoration: none; color: #7a1e8b;"><img src="http://10.20.171.56/signature/v2/img/icon_website.png" alt="website" title="Bezoek de website" style="vertical-align:bottom;"></a> &nbsp;'?>
	<?php if ($email==TRUE)		echo '<a href="mailto:'.$email.'@hethooghuis.nl?subject=contact" title="Verstuur mail aan: '.$voornaam.' '.$voorvoegsel.' '.$achternaam.'" style="text-decoration: none; color: #f57215;"><img src="http://10.20.171.56/signature/v2/img/icon_mail.png" alt="mail" title="Verstuur mail aan: '.$voornaam.' '.$voorvoegsel.' '.$achternaam.'" style="vertical-align:bottom;"></a> &nbsp; ';?>
	<?php if ($twitter==TRUE)	echo '<a href="https://www.twitter.com/'.$twitter.'" target="_blanc" title="Persoonlijk twitter account" style="text-decoration: none; color: #0099FF;"><img src="http://10.20.171.56/signature/v2/img/icon_twitter.png" alt="Twitter" title="Persoonlijk twitter account" style="vertical-align:bottom;"></a> &nbsp;';
		else {
																if($locatie==1) echo '<a href="https://twitter.com/HHdenbongerd" target="_blanc" title="Twitter lokatie: Bongerd" style="text-decoration: none; color: #0099FF;"><img src="http://10.20.171.56/signature/v2/img/icon_twitter.png" alt="Twitter" title="Twitter account: Den Bongerd" style="vertical-align:bottom;"></a> &nbsp;';
																if($locatie==2) echo '<a href="https://twitter.com/HooghuisHeesch" target="_blanc" title="Twitter lokatie: Heesch" style="text-decoration: none; color: #0099FF;"><img src="http://10.20.171.56/signature/v2/img/icon_twitter.png" alt="Twitter" title="Twitter account: Heesch" style="vertical-align:bottom;"></a> &nbsp;';
																if($locatie==3) echo '<a href="https://twitter.com/hethooghuis" target="_blanc" title="Twitter @HetHooghuis" style="text-decoration: none; color: #0099FF;"><img src="http://10.20.171.56/signature/v2/img/icon_twitter.png" alt="Twitter" title="Twitter account: @HetHooghuis" style="vertical-align:bottom;"></a> &nbsp;';
																if($locatie==4) echo '<a href="https://twitter.com/hethooghuis" target="_blanc" title="Twitter @HetHooghuis" style="text-decoration: none; color: #0099FF;"><img src="http://10.20.171.56/signature/v2/img/icon_twitter.png" alt="Twitter" title="Twitter account: @HetHooghuis" style="vertical-align:bottom;"></a> &nbsp;';
																if($locatie==5) echo '<a href="https://twitter.com/hethooghuis" target="_blanc" title="Twitter @HetHooghuis" style="text-decoration: none; color: #0099FF;"><img src="http://10.20.171.56/signature/v2/img/icon_twitter.png" alt="Twitter" title="Twitter account: @HetHooghuis" style="vertical-align:bottom;"></a> &nbsp;';
																if($locatie==6) echo '<a href="https://twitter.com/hethooghuis" target="_blanc" title="Twitter @HetHooghuis" style="text-decoration: none; color: #0099FF;"><img src="http://10.20.171.56/signature/v2/img/icon_twitter.png" alt="Twitter" title="Twitter account: @HetHooghuis" style="vertical-align:bottom;"></a> &nbsp;';
																if($locatie==7) echo '<a href="https://twitter.com/hethooghuis" target="_blanc" title="Twitter @HetHooghuis" style="text-decoration: none; color: #0099FF;"><img src="http://10.20.171.56/signature/v2/img/icon_twitter.png" alt="Twitter" title="Twitter account: @HetHooghuis" style="vertical-align:bottom;"></a> &nbsp;';
																if($locatie==8) echo '<a href="https://twitter.com/tbl_oss" target="_blanc" title="Twitter locatie: Titus Brandsmalyceum" style="text-decoration: none; color: #0099FF;"><img src="http://10.20.171.56/signature/v2/img/icon_twitter.png" alt="Twitter" title="Twitter account: TBL" style="vertical-align:bottom;"></a> &nbsp;'; 
																if($locatie==9) echo '<a href="https://twitter.com/HHzuidwest" target="_blanc" title="Twitter locatie: West" style="text-decoration: none; color: #0099FF;"><img src="http://10.20.171.56/signature/v2/img/icon_twitter.png" alt="Twitter" title="Twitter account: West - Zuid" style="vertical-align:bottom;"></a> &nbsp;';
																if($locatie==10) echo '<a href="https://twitter.com/HHzuidwest" target="_blanc" title="Twitter locatie: Zuid" style="text-decoration: none; color: #0099FF;"><img src="http://10.20.171.56/signature/v2/img/icon_twitter.png" alt="Twitter" title="Twitter account: West - Zuid" style="vertical-align:bottom;"></a> &nbsp;';																
																}
		?>
  
	<?php if ($linkedin==TRUE)	echo '<a href="https://nl.linkedin.com/in/'.$linkedin.'" target="_blanc" title="Persoonlijk LinkedIN account: '.$voornaam.' '.$voorvoegsel.' '.$achternaam.'"><img src="http://10.20.171.56/signature/v2/img/icon_linkedin.png" alt="LinkedIN" title="LinkedIN account: '.$voornaam.' '.$voorvoegsel.' '.$achternaam.'" style="vertical-align:bottom;"></a> &nbsp;';?>
	<?php if ($telefoon==TRUE)	echo '<img src="http://10.20.171.56/signature/v2/img/icon_phone.png" alt="telefoon" title="telefoon nummer" style="vertical-align:middle;"> '.$telefoon.' &nbsp;';?>
	<?php if ($telefoon2==TRUE)	echo '<img src="http://10.20.171.56/signature/v2/img/icon_phone.png" alt="telefoon" title="intern nummer" style="vertical-align:middle;"><font color="#5E5E5E"> intern: </font>'.$telefoon2.' &nbsp;';?>
  </td>
  </tr>
  <tr>
    <td class="tg-locatie" colspan="2"><br><?php
			if ($locatie==1) echo'<a href="https://www.google.nl/maps/place/Het+Hooghuis+-+Locatie+Den+Bongerd/" target="_blanc" alt="Locatie Bongerd"><img src="http://10.20.171.56/signature/v2/img/icon_location.png" alt="Locatie Bongerd" title="Locatie: Bongerd" style="vertical-align:bottom;"></a> <b>Den Bongerd</b> | Staringstraat 4 5343 GH Oss &nbsp; <img src="http://10.20.171.56/signature/v2/img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;"> 0412-224120';
			if ($locatie==2) echo'<a href="https://www.google.nl/maps/place/Het+Hooghuis+Heesch/" target="_blanc" alt="Locatie Heesch"><img src="http://10.20.171.56/signature/v2/img/icon_location.png" alt="Locatie Heesch" title="Locatie: Heesch" style="vertical-align:bottom;"></a> <b>Heesch</b> | Schoonstraat 34 5384 AP Heesch&nbsp; <img src="http://10.20.171.56/signature/v2/img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;"> 0412-224130';
			if ($locatie==3) echo'<a href="https://www.google.nl/maps/place/Het+Hooghuis/" target="_blanc" alt="Locatie Centrale Dienst"><img src="http://10.20.171.56/signature/v2/img/icon_location.png" alt="Locatie Centrale Dienst" title="Locatie: Centrale Dienst" style="vertical-align:bottom;"></a> <b>Centrale Dienst</b> | Nieuwe Hescheweg 11 5342 EB Oss &nbsp; <img src="http://10.20.171.56/signature/v2/img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;">0412-224100';
			if ($locatie==4) echo'<a href="https://www.google.nl/maps/place/Mondriaan+College/" target="_blanc" alt="Locatie Mondriaan"><img src="http://10.20.171.56/signature/v2/img/icon_location.png" alt="Locatie Mondriaan" title="Locatie: Mondriaan" style="vertical-align:bottom;"></a> <b>Mondriaan</b> | Mondriaanlaan 1 5342 CN Oss &nbsp;<img src="http://10.20.171.56/signature/v2/img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;"> 0412-224190';
			if ($locatie==5) echo'<a href="https://www.google.nl/maps/place/Het+Hooghuis/@51.791766,5.65229,17z/" target="_blanc" alt="Locatie Ravenstein"><img src="http://10.20.171.56/signature/v2/img/icon_location.png" alt="Locatie Ravenstein" title="Locatie: Ravenstein" style="vertical-align:bottom;"></a> <b>Ravenstein</b> | Middingstraat 1 5371 EJ Ravenstein &nbsp;<img src="http://10.20.171.56/signature/v2/img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;"> 0412-224170';
			if ($locatie==6) echo'<a href="https://www.google.nl/maps/place/Mondriaanlaan+6,+5342+Oss/@51.7538598,5.5279389,17z/" target="_blanc" alt="Locatie Stadion"><img src="http://10.20.171.56/signature/v2/img/icon_location.png" alt="Locatie Stadion" title="Locatie: Stadion" style="vertical-align:bottom;"></a>  <b>Stadion</b> | Mondriaanlaan 6 5342 CN Oss &nbsp;<img src="http://10.20.171.56/signature/v2/img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;"> 0412-224140 ';
			if ($locatie==7) echo'<a href="https://www.google.nl/maps/place/Het+Hooghuis+-+Locatie+De+Singel/@51.771714,5.542561,17z/" target="_blanc" alt="Locatie Singel"><img src="http://10.20.171.56/signature/v2/img/icon_location.png" alt="Locatie Singel" title="Locatie: Singel" style="vertical-align:bottom;"></a>  <b>De Singel</b> | Kapelaan Nausstraat 2 5348 TH Oss &nbsp;<img src="http://10.20.171.56/signature/v2/img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;"> 0412-224110 ';
			if ($locatie==8) echo'<a href="https://www.google.nl/maps/place/Titus+Brandsmalyceum/@51.7673095,5.5265132,18z/" target="_blanc" alt="Locatie TBL"><img src="http://10.20.171.56/signature/v2/img/icon_location.png" alt="Locatie Titus Brandsmalyceum" title="Locatie: Titus Brandsmalyceum" style="vertical-align:bottom;"></a>  <b>Titus Brandsmalyceum</b> | Molenstraat 30 5341 GD Oss &nbsp;<img src="http://10.20.171.56/signature/v2/img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;"> 0412-224180';
			if ($locatie==9) echo'<a href="https://www.google.nl/maps/place/Het+Hooghuis+-+Locatie+Oss-West/@51.75335,5.519817,17z/" target="_blanc" alt="Locatie West"><img src="http://10.20.171.56/signature/v2/img/icon_location.png" alt="Locatie West" title="Locatie: West" style="vertical-align:bottom;"></a>  <b>West</b> | Verdistraat 75 5343 VC Oss &nbsp;<img src="http://10.20.171.56/signature/v2/img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;"> 0412-224150 ';
			if ($locatie==10) echo'<a href="https://www.google.nl/maps/place/Het+Hooghuis+-+Locatie+Oss-Zuid/@51.752556,5.530653,17z/" target="_blanc" alt="Locatie Zuid"><img src="http://10.20.171.56/signature/v2/img/icon_location.png" alt="Locatie Zuid" title="Locatie: Zuid" style="vertical-align:bottom;"></a>  <b>Zuid</b> | De Ruivert 5 5342 CM Oss &nbsp;<img src="http://10.20.171.56/signature/v2/img/icon_phone_square.png" alt="telefoon" title="Algemeen nummer locatie" style="vertical-align:middle;"> 0412-224160';?><br></td>
  </tr>
  <?php if ($onderschrift==TRUE) echo '
  <tr>
    <td class="tg-opmerking" colspan="2"><font color="7AC976"><img src="http://10.20.171.56/signature/v2/img/icon_comments.png" alt="opmerking" title="opmerking" style="vertical-align:bottom;"> <i>&nbsp;'. $onderschrift.'</i></font></td>
  </tr>';?>
</table>
</textarea>
		
		<div id="footer">
			Gebakken door <a href="<?php echo $companyurl;?>" target='_blanc'><?php echo $companyname;?></a> 2014 - <?php echo date("Y"); ?> 
		</div>
	</div>
		<img id="bottom" src="img/bottom.png" alt="">
	</body>
</html>

