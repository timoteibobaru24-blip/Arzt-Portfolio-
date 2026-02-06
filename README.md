<!DOCTYPE html>
<html lang="ro">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portofoliu Artă</title>

<style>
body{
font-family: Arial, sans-serif;
margin:0;
background:#f5f5f5;
color:#222;
}

header{
background:#111;
color:white;
padding:20px;
text-align:center;
}

section{
padding:40px;
max-width:1000px;
margin:auto;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.gallery img{
width:100%;
border-radius:8px;
}

.card{
background:white;
padding:15px;
border-radius:10px;
box-shadow:0 2px 5px rgba(0,0,0,0.1);
}

footer{
background:#111;
color:white;
text-align:center;
padding:20px;
}
</style>

</head>
<body>

<header>
<h1>Numele Tău</h1>
<p>Artist vizual</p>
</header>

<section>
<h2>Despre mine</h2>
<p>
Scrie aici despre tine: artist, tehnici, inspirație etc.
</p>
</section>

<section>
<h2>Lucrări</h2>

<div class="gallery">

<div class="card">
<img src="https://via.placeholder.com/400" alt="">
<p>Titlu lucrare</p>
</div>

<div class="card">
<img src="https://via.placeholder.com/400" alt="">
<p>Titlu lucrare</p>
</div>

<div class="card">
<img src="https://via.placeholder.com/400" alt="">
<p>Titlu lucrare</p>
</div>

</div>
</section>

<section>
<h2>Contact</h2>
<p>Email: exemplu@email.com</p>
</section>

<footer>
<p>© 2026 Portofoliu Artă</p>
</footer>

</body>
</html>
