<!DOCTYPE html>
<html lang="sv">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Henrik Thorslund | Elkonstruktion & Automation</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f5f5f5;
        }

        nav {
            background: #111827;
            padding: 15px;
            text-align: center;
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

        header {
            background: #1f2937;
            color: white;
            text-align: center;
            padding: 70px 20px;
        }

        .about {
            max-width: 1000px;
            margin: 40px auto;
            padding: 25px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }

        .projects {
            max-width: 1200px;
            margin: auto;
            padding: 30px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px,1fr));
            gap: 20px;
        }

        .card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .placeholder {
            height: 200px;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 24px;
            font-weight: bold;
        }

        .motorstart {
            background: linear-gradient(135deg,#ea580c,#fb923c);
        }

        .pump {
            background: linear-gradient(135deg,#2563eb,#60a5fa);
        }

        .hallkrets {
            background: linear-gradient(135deg,#16a34a,#4ade80);
        }

        .card-content {
            padding: 20px;
        }

        .tag {
            background: #e5e7eb;
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 12px;
            margin-right: 5px;
        }

        .button {
            display: inline-block;
            margin-top: 15px;
            background: #2563eb;
            color: white;
            text-decoration: none;
            padding: 10px 15px;
            border-radius: 5px;
        }

        .button:hover {
            background: #1d4ed8;
        }

        footer {
            background: #1f2937;
            color: white;
            text-align: center;
            padding: 25px;
            margin-top: 40px;
        }

        footer a {
            color: #60a5fa;
            text-decoration: none;
        }

        footer a:hover {
            color: white;
        }
    </style>

</head>

<body>

    <nav>
        <a href="index.html">Hem</a>
        <a href="#projekt">Projekt</a>
        <a href="#kontakt">Kontakt</a>
    </nav>

    <header>
        <h1>Henrik Thorslund</h1>
        <p>Portfolio inom elkonstruktion och automation</p>
    </header>

    <section class="about">
        <h2>Om mig</h2>

        <p>
            Jag studerar elkonstruktion och har ett stort intresse för
            automation, PLC-programmering och elkonstruktion.

            På denna sida visar jag projekt skapade i TIA Portal,
            AutoCAD Electrical och praktiska automationslösningar.
        </p>
    </section>

    <section class="projects" id="projekt">

        <div class="card">

            <div class="placeholder motorstart">
                ⚡ Motorstart
            </div>

            <div class="card-content">

                <h2>Motorstart med kontaktor</h2>

                <p>
                    Konstruktion av styrkrets för trefasmotor.
                </p>

                <p>
                    <span class="tag">PLC</span>
                    <span class="tag">Kontaktor</span>
                    <span class="tag">Elschema</span>
                </p>

                <a href="projects/motorstart.html" class="button">
                    Öppna projekt
                </a>

            </div>

        </div>

        <div class="card">

            <div class="placeholder pump">
                💧 Pumpstyrning
            </div>

            <div class="card-content">

                <h2>Pumpstyrning</h2>

                <p>
                    Nivågivare, pump och larm.
                </p>

                <p>
                    <span class="tag">PLC</span>
                    <span class="tag">Pump</span>
                    <span class="tag">Givare</span>
                </p>

                <a href="projects/pumpstyrning.html" class="button">
                    Öppna projekt
                </a>

            </div>

        </div>

        <div class="card">

            <div class="placeholder hallkrets">
                💡 Hållkrets
            </div>

            <div class="card-content">

                <h2>Hållkrets i TIA Portal</h2>

                <p>
                    Start- och stoppfunktion med minnesbit.
                </p>

                <p>
                    <span class="tag">TIA Portal</span>
                    <span class="tag">S7-1200</span>
                    <span class="tag">PLC</span>
                </p>

                <a href="projects/hallkrets.html" class="button">
                    Öppna projekt
                </a>

            </div>

        </div>

    </section>

    <footer id="kontakt">

        <p>© 2026 Henrik Thorslund</p>

        <p>
            LinkedIn:
            <a href="https://www.linkedin.com/" target="_blank">
                Min profil
            </a>
        </p>

        <p>
            GitHub:
            <a href="https://github.com/" target="_blank">
                Mina projekt
            </a>
        </p>

    </footer>

</body>
</html>
