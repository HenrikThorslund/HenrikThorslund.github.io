<!DOCTYPE html>
<html lang="sv">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Henrik Thorslund | Elkonstruktion</title>

    <style>
        * {
            box-sizing: border-box;
        }

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
            padding: 50px 20px;
        }

        header h1 {
            margin: 0;
        }

        nav {
            background-color: #374151;
            text-align: center;
            padding: 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: #60a5fa;
        }

        section {
            background: white;
            max-width: 1000px;
            margin: 20px auto;
            padding: 30px;
            border-radius: 10px;
        }

        .project {
            margin-top: 30px;
            border-left: 5px solid #2563eb;
            padding-left: 20px;
        }

        .project img {
            width: 100%;
            max-width: 800px;
            margin: 15px 0;
            border-radius: 8px;
            border: 1px solid #ddd;
        }

        .status {
            display: inline-block;
            background-color: #16a34a;
            color: white;
            padding: 5px 10px;
            border-radius: 5px;
            font-size: 12px;
            margin-bottom: 10px;
        }

        .button {
            display: inline-block;
            background-color: #2563eb;
            color: white;
            padding: 10px 15px;
            text-decoration: none;
            border-radius: 5px;
            margin-right: 10px;
        }

        .button:hover {
            background-color: #1d4ed8;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
        }

        table th,
        table td {
            border: 1px solid #ddd;
            padding: 10px;
        }

        table th {
            background-color: #f1f5f9;
        }

        footer {
            text-align: center;
            background-color: #1f2937;
            color: white;
            padding: 20px;
            margin-top: 30px;
        }
    </style>
</head>

<body>

    <header>
        <h1>Henrik Thorslund</h1>
        <p>Junior Elkonstruktör | Automation | Industriella Styrsystem</p>
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
            Jag bygger upp denna portfolio för att visa mina kunskaper
            inom elkonstruktion, automation och teknisk dokumentation.
        </p>

        <p>
            Här samlar jag egna projekt, elscheman,
            funktionsbeskrivningar och konstruktionslösningar för att
            utvecklas som elkonstruktör.
        </p>

    </section>

    <section id="projects">

        <h2>Projekt</h2>

        <div class="project">

            <span class="status">Färdig</span>

            <h3>Projekt 1 - Motorstart med kontaktor</h3>

            <img src="images/motorstart.png"
                alt="Motorstartschema">

            <p>
                Konstruktion av styrkrets för trefasmotor med kontaktor,
                motorskydd och stoppfunktion.
            </p>

            <h4>Funktion</h4>

            <p>
                Startknappen aktiverar kontaktorn som driver motorn.
                Stoppknappen bryter styrkretsen och stannar motorn.
                Motorskyddet skyddar mot överbelastning.
            </p>

            <h4>Säkerhetsfunktioner</h4>

            <ul>
                <li>Motorskydd</li>
                <li>Stoppfunktion</li>
                <li>Manuell återstart</li>
            </ul>

            <h4>Komponentlista</h4>

            <table>

                <tr>
                    <th>Beteckning</th>
                    <th>Komponent</th>
                </tr>

                <tr>
                    <td>K1</td>
                    <td>Kontaktor</td>
                </tr>

                <tr>
                    <td>F1</td>
                    <td>Motorskydd</td>
                </tr>

                <tr>
                    <td>S1</td>
                    <td>Startknapp</td>
                </tr>

                <tr>
                    <td>S0</td>
                    <td>Stoppknapp</td>
                </tr>

            </table>

            <br>

            <a href="pdf/motorstart.pdf" class="button">
                Visa PDF
            </a>

            <a href="pdf/motorstart.pdf" download class="button">
                Ladda ner PDF
            </a>

        </div>

        <div class="project">

            <span class="status">Pågår</span>

            <h3>Projekt 2 - Pumpstyrning</h3>

            <p>
                Enkel styrning med nivågivare, pump och larmfunktion.
            </p>

        </div>

    </section>

    <section id="skills">

        <h2>Kunskaper</h2>

        <ul>
            <li>Elscheman</li>
            <li>Motorstyrning</li>
            <li>Styrkretsar</li>
            <li>PLC-grunder</li>
            <li>Automation</li>
            <li>Teknisk dokumentation</li>
            <li>Git & GitHub</li>
            <li>QElectroTech</li>
        </ul>

    </section>

    <section id="contact">

        <h2>Kontakt</h2>

        <p>Email: dinmail@exempel.se</p>

        <p>
            LinkedIn:
            <a href="https://www.linkedin.com"
                target="_blank">
                Besök profil
            </a>
        </p>

    </section>

    <footer>
        <p>© 2026 Henrik Thorslund</p>
    </footer>

</body>

</html>
