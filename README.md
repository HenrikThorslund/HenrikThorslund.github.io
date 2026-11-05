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
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f5f5f5;
            color: #333;
        }

        header {
            background: #1f2937;
            color: white;
            text-align: center;
            padding: 60px 20px;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        header p {
            margin-top: 10px;
            color: #cbd5e1;
        }

        nav {
            background: #374151;
            text-align: center;
            padding: 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: #60a5fa;
        }

        section {
            max-width: 1000px;
            margin: 20px auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
        }

        h2 {
            color: #1f2937;
        }

        .project-card {
            margin-top: 25px;
            border: 1px solid #ddd;
            border-radius: 10px;
            overflow: hidden;
        }

        .project-header {
            background: #1f2937;
            color: white;
            padding: 15px 20px;
        }

        .project-body {
            padding: 20px;
        }

        .project-image {
            width: 100%;
            border-radius: 8px;
            border: 1px solid #ddd;
        }

        .status {
            display: inline-block;
            margin-top: 10px;
            background: #16a34a;
            color: white;
            padding: 5px 10px;
            border-radius: 5px;
            font-size: 12px;
        }

        .status-progress {
            background: #f59e0b;
        }

        .button {
            display: inline-block;
            background: #2563eb;
            color: white;
            text-decoration: none;
            padding: 10px 15px;
            border-radius: 5px;
            margin-right: 10px;
            margin-top: 10px;
        }

        .button:hover {
            background: #1d4ed8;
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
            background: #f3f4f6;
        }

        footer {
            background: #1f2937;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
        }
    </style>
</head>

<body>

    <header>
        <h1>Henrik Thorslund</h1>
        <p>Blivande Elkonstruktör | Automation | Industriella Styrsystem</p>
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
            Jag bygger denna portfolio för att visa och utveckla mina
            kunskaper inom elkonstruktion, automation och teknisk
            dokumentation.
        </p>

        <p>
            Syftet är att samla egna projekt, elscheman,
            funktionsbeskrivningar och konstruktionslösningar för att
            utvecklas som elkonstruktör.
        </p>
    </section>

    <section id="projects">

        <h2>Projekt</h2>

        <div class="project-card">

            <div class="project-header">
                <h3>Projekt 1 - Motorstart med kontaktor</h3>
            </div>

            <div class="project-body">

                <span class="status">
                    Färdig
                </span>

                <br><br>

                <img src="images/motorstart.png"
                    alt="Motorstartschema"
                    class="project-image">

                <h4>Beskrivning</h4>

                <p>
                    Konstruktion av styrkrets för trefasmotor med
                    kontaktor, motorskydd och stoppfunktion.
                </p>

                <h4>Funktion</h4>

                <p>
                    Startknappen aktiverar kontaktorn som startar
                    motorn. Stoppknappen bryter styrkretsen och
                    stannar motorn.
                </p>

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

                <a href="pdf/motorstart.pdf"
                    class="button">
                    Visa PDF
                </a>

                <a href="pdf/motorstart.pdf"
                    download
                    class="button">
                    Ladda ner PDF
                </a>

            </div>

        </div>

        <div class="project-card">

            <div class="project-header">
                <h3>Projekt 2 - Pumpstyrning</h3>
            </div>

            <div class="project-body">

                <span class="status status-progress">
                    Pågår
                </span>

                <p>
                    Styrning av pump med nivågivare och larmfunktion.
                </p>

            </div>

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
            <li>GitHub Pages</li>
            <li>Git</li>
            <li>QElectroTech</li>
        </ul>

    </section>

    <section id="contact">

        <h2>Kontakt</h2>

        <p>
            E-post: dinmail@example.com
        </p>

        <p>
            LinkedIn:
            <a href="https://www.linkedin.com/"
                target="_blank">
                Besök min profil
            </a>
        </p>

    </section>

    <footer>
        <p>© 2026 Henrik Thorslund</p>
    </footer>

</body>

</html>
