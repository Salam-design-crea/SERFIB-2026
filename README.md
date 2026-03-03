<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SERFIB 2026 | Inscription Officielle</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">

<style>
body {
    margin:0;
    font-family: 'Roboto', sans-serif;
    background: #eaf4ea;
    color:#333;
}

.hero{
    text-align:center;
    padding:80px 20px;
    background: linear-gradient(135deg,#2f7a2f,#1f5c1f);
    color:white;
    border-bottom:5px solid #1f5c1f;
}

.hero h1{
    font-size:42px;
    margin-bottom:10px;
}

.hero p{
    font-size:18px;
}

.container{
    max-width:900px;
    margin:-40px auto 40px auto;
    background:white;
    padding:40px;
    border-radius:15px;
    box-shadow:0 10px 30px rgba(0,0,0,0.2);
}

h2{
    color:#2f7a2f;
    margin-bottom:20px;
}

label{
    font-weight:700;
    color:#1f5c1f;
}

input, select{
    width:100%;
    padding:12px;
    margin:8px 0 20px 0;
    border-radius:8px;
    border:1px solid #ddd;
    font-size:14px;
}

input:focus, select:focus{
    outline:none;
    border-color:#2f7a2f;
}

button{
    width:100%;
    padding:14px;
    border:none;
    border-radius:8px;
    background:#2f7a2f;
    color:white;
    font-size:16px;
    cursor:pointer;
    transition:0.3s;
    font-weight:700;
}

button:hover{
    background:#1f5c1f;
}

.footer{
    text-align:center;
    color:white;
    padding:20px;
    font-size:14px;
    background:#2f7a2f;
    margin-top:20px;
}

.payment-icons{
    display:flex;
    gap:20px;
    margin:10px 0 20px 0;
}

.payment-icons img{
    width:50px;
    height:auto;
}
</style>
</head>

<body>

<div class="hero">
    <h1>SERFIB 2026</h1>
    <p>Dianra Village | 01 au 06 Avril 2026</p>
    <p>6 jours de formation • Compétition • Leadership • Réseautage</p>
</div>

<div class="container">

<h2>À propos du SERFIB</h2>
<p>
Le SERFIB (Séminaire Régional de Formation Islamique du Béré) est une activité coutumière dans la région.  
La 5ème édition prévue pour ce mois d'avril s'annonce <strong>promoteur et explosif</strong> avec des formations théoriques, pratiques, mais aussi des activités de divertissement de haut niveau.  
Beaucoup de surprises vous attendent à cette 5ème édition.
</p>

<h2>Formulaire d'inscription</h2>

<form id="inscriptionForm">

<label>Nom & Prénoms *</label>
<input type="text" name="nom_prenom" required>

<label>Statut *</label>
<select name="statut" required>
<option value="">--Choisissez votre statut--</option>
<option value="AEEMCISTE">AEEMCISTE</option>
<option value="MEMBRE DE BUREAU">MEMBRE DE BUREAU</option>
<option value="SR(SERA)">SR(SERA)</option>
<option value="IMAM">IMAM</option>
<option value="FORMATEUR">FORMATEUR</option>
</select>

<label>Sous comité *</label>
<select name="sous_comite" id="sous_comite" required>
<option value="">--Choisissez votre sous comité--</option>
<option value="Dianra">Dianra</option>
<option value="Dianra Village">Dianra Village</option>
<option value="Sononzo">Sononzo</option>
<option value="Sarhala">Sarhala</option>
<option value="Mankono">Mankono</option>
<option value="Bouandougou">Bouandougou</option>
</select>

<label>Téléphone *</label>
<input type="tel" name="telephone" required>

<label>Contact WhatsApp *</label>
<input type="tel" name="whatsapp" required>

<label>Contact en cas d'urgence</label>
<input type="tel" name="urgence">

<label>Photo d'identité *</label>
<input type="file" name="photo_id" accept="image/*" required>

<label>Mode de paiement *</label>
<select name="paiement" id="paiement" required>
<option value="">--Choisissez un mode de paiement--</option>
<option
