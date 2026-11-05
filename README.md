<!DOCTYPE html>
<html lang="sv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Henrik Thorslund | Elkonstruktion</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f5f5f5;
            color: #333;
        }

        header {
            background-color: #1f2937;
            color: white;
            text-align: center;
            padding: 40px;
        }

        nav {
            background-color: #374151;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 15px;
            font-weight: bold;
        }

        section {
            max-width: 1000px;
            margin: auto;
            padding: 30px;
            background: white;
            margin-top: 20px;
            border-radius: 10px;
        }

        .project {
            border-left: 5px solid #2563eb;
            padding-left: 15px;
            margin-bottom: 25px;
        }

        footer {
            text-align: center;
            padding: 20px;
            margin-top: 30px;
            background-color: #1f2937;
            color: white;
        }

        .button {
            display: inline-block;
            background-color: #2563eb;
            color: white;
            padding: 10px 15px;
            text-decoration: none;
            border-radius: 5px;
        }

        .button:hover {
            background-color: #1d4ed8;
        }
    </style>

</head>
<body>

<header>
    <h1>Henrik Andersson</h1>
    <p>Blivande Elkonstruktör & Automationsintresserad</p>
</header>

<nav>
    <a href="#about">Om mig</a>
    <a href="#projects">Projekt</a>
    <a href="#skills">Kunskaper</a>
    <a href="#contact">Kontakt</a>
</nav>

<section id="about">
    <h2>Om mig</h2>

    <p>
        Jag utvecklar mina kunskaper inom elkonstruktion,
        automation och industriella styrsystem.
        På denna sida samlar jag egna projekt,
        elscheman och teknisk dokumentation.
    </p>

</section>

<section id="projects">

    <h2>Projekt</h2>

    <div class="project">
        <h3>Motorstart med kontaktor</h3>

        <p>
            Konstruktion av start/stopp-krets med nödstopp,
            motorskydd och kontaktor.
        </p>

        <a href="pdf/motorstart.pdf" class="button">
            Visa ritning
        </a>
    </div>

    <div class="project">
        <h3>Pumpstyrning</h3>

        <p>
            Enkel styrning för pump med nivågivare och larm.
        </p>

        <a href="#" class="button">
            Kommer snart
        </a>
    </div>

</section>

<section id="skills">

    <h2>Kunskaper</h2>

    <ul>
        <li>Elscheman</li>
        <li>Styrkretsar</li>
        <li>Motorstyrning</li>
        <li>PLC-grunder</li>
        <li>Automation</li>
        <li>Teknisk dokumentation</li>
        <li>Git & GitHub</li>
    </ul>

</section>

<section id="contact">

    <h2>Kontakt</h2>

    <p>Email: dinmail@example.com</p>

    <p>
        LinkedIn:
        <a href="https://linkedin.com">
            Besök profil
        </a>
    </p>

</section>

<footer>
    <p>© 2026 Henrik Andersson</p>
</footer>

</body>
</html>
