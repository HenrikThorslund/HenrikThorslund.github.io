<!DOCTYPE html>
<html lang="sv">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Henrik Thorslund | Elkonstruktion</title>

<style>

body{
    font-family: Arial, sans-serif;
    margin:0;
    background:#f5f5f5;
    color:#333;
}

header{
    background:#1f2937;
    color:white;
    text-align:center;
    padding:50px;
}

nav{
    background:#374151;
    text-align:center;
    padding:15px;
}

nav a{
    color:white;
    text-decoration:none;
    margin:15px;
    font-weight:bold;
}

section{
    max-width:1000px;
    margin:20px auto;
    background:white;
    padding:30px;
    border-radius:10px;
}

.project{
    border:1px solid #ddd;
    border-radius:10px;
    overflow:hidden;
}

.project-header{
    background:#1f2937;
    color:white;
    padding:15px;
}

.project-body{
    padding:20px;
}

.project img{
    width:100%;
    border-radius:8px;
}

.button{
    display:inline-block;
    background:#2563eb;
    color:white;
    padding:10px 15px;
    text-decoration:none;
    border-radius:5px;
    margin-top:10px;
}

.button:hover{
    background:#1d4ed8;
}

.status{
    display:inline-block;
    background:green;
    color:white;
    padding:5px 10px;
    border-radius:5px;
}

footer{
    background:#1f2937;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:20px;
}

</style>

</head>

<body>

<header>
    <h1>Henrik Thorslund</h1>
    <p>Blivande Elkonstruktör & Automation</p>
</header>

<nav>
    <a href="#about">Om mig</a>
    <a href="#projects">Projekt</a>
    <a href="#contact">Kontakt</a>
</nav>

<section id="about">

<h2>Om mig</h2>

<p>
Jag bygger upp denna portfolio för att visa mina kunskaper inom
elkonstruktion, automation och teknisk dokumentation.
</p>

</section>

<section id="projects">

<h2>Projekt</h2>

<div class="project">

<div class="project-header">
<h3>Projekt 1 - Motorstart med kontaktor</h3>
</div>

<div class="project-body">

<span class="status">Färdig</span>

<h4>Elschema</h4>

<img src="motorstart.png" alt="Motorstartschema">

<h4>Beskrivning</h4>

<p>
Konstruktion av styrkrets för trefasmotor med kontaktor,
motorskydd och stoppfunktion.
</p>

<h4>Funktion</h4>

<p>
När startknappen trycks in aktiveras kontaktorn som
startar motorn. Stoppknappen bryter styrkretsen.
</p>

<a href="motorstart.png" class="button" target="_blank">
Visa ritning
</a>

</div>

</div>

</section>

<section id="contact">

<h2>Kontakt</h2>

<p>
LinkedIn: Din LinkedIn-profil
</p>

<p>
E-post: dinmail@example.com
</p>

</section>

<footer>

<p>
© 2026 Henrik Thorslund
</p>

</footer>

</body>
</html>

