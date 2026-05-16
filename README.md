# parking-montagne-verte1
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Parking Montagne Verte - Colmar</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">

<style>

*{
    box-sizing:border-box;
}

body{
    margin:0;
    font-family:'Inter',sans-serif;
    background:
    radial-gradient(circle at top,#1f2937 0%,#0f172a 60%);
    color:white;
    display:flex;
    justify-content:center;
    align-items:center;
    min-height:100vh;
    padding:24px;
}

.card{
    width:100%;
    max-width:430px;
    background:rgba(255,255,255,0.06);
    border:1px solid rgba(255,255,255,0.12);
    backdrop-filter:blur(14px);
    border-radius:32px;
    padding:36px 28px;
    box-shadow:0 18px 45px rgba(0,0,0,0.45);
}

.badge{
    display:inline-block;
    background:rgba(255,255,255,0.08);
    border:1px solid rgba(255,255,255,0.12);
    padding:8px 14px;
    border-radius:999px;
    font-size:13px;
    color:#d1d5db;
    margin-bottom:20px;
}

h1{
    margin:0;
    font-size:30px;
    line-height:1.1;
}

.subtitle{
    margin-top:14px;
    color:#cbd5e1;
    line-height:1.6;
    font-size:15px;
}

.buttons{
    margin-top:32px;
    display:flex;
    flex-direction:column;
    gap:16px;
}

.btn{
    display:flex;
    align-items:center;
    gap:14px;
    text-decoration:none;
    color:white;
    padding:18px 20px;
    border-radius:20px;
    transition:0.2s ease;
    font-weight:600;
    font-size:17px;
}

.btn:hover{
    transform:translateY(-2px);
}

.logo{
    width:28px;
    height:28px;
    display:flex;
    align-items:center;
    justify-content:center;
    flex-shrink:0;
}

.waze{
    background:#38bdf8;
}

.google{
    background:#ffffff;
    color:#111827;
}

.apple{
    background:#2b2f36;
}

.footer{
    margin-top:28px;
    text-align:center;
    color:#94a3b8;
    font-size:13px;
}

</style>
</head>

<body>

<div class="card">

<div class="badge">
📍 Colmar • Parking Montagne Verte
</div>

<h1>Choisissez votre GPS</h1>

<div class="subtitle">
Ouvrez directement l’itinéraire vers le parking de la Montagne Verte à Colmar avec votre application préférée.
</div>

<div class="buttons">

<a class="btn waze"
href="https://waze.com/ul?q=Parking+Montagne+Verte+Colmar">

<div class="logo">🚗</div>
<div>Waze</div>

</a>

<a class="btn google"
href="https://www.google.com/maps/search/?api=1&query=Parking+Montagne+Verte+Colmar">

<div class="logo">

<svg viewBox="0 0 48 48" width="28" height="28">

<path fill="#EA4335"
d="M24 4C16.3 4 10 10.3 10 18c0 10.5 14 26 14 26s14-15.5 14-26C38 10.3 31.7 4 24 4z"/>

<circle cx="24" cy="18" r="6.5" fill="#4285F4"/>

<path fill="#FBBC05"
d="M24 11.5a6.5 6.5 0 0 1 6.5 6.5h-6.5z"/>

<path fill="#34A853"
d="M17.5 18A6.5 6.5 0 0 1 24 11.5V18z"/>

</svg>

</div>

<div>Google Maps</div>

</a>

<a class="btn apple"
href="http://maps.apple.com/?q=Parking+Montagne+Verte+Colmar">

<div class="logo"></div>
<div>Apple Plans</div>

</a>

</div>

<div class="footer">
Scannez • Choisissez • Partez
</div>

</div>

</body>
</html>