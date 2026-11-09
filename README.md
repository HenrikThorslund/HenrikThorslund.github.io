<!DOCTYPE html>
<html lang="sv">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Henrik Thorslund | Elkonstruktion</title>

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
            padding: 60px;
        }

        .projects {
            max-width: 1200px;
            margin: auto;
            padding: 30px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .card-content {
            padding: 20px;
        }

        .button {
            display: inline-block;
            margin-top: 10px;
            background: #2563eb;
            color: white;
            text-decoration: none;
            padding: 10px 15px;
            border-radius: 5px;
        }

        footer {
            background: #1f2937;
            color: white;
            text-align: center;
            padding: 20px;
        }

    </style>
</head>

<body>

    <nav>
        <a href="index.html">Hem</a>
        <a href="#projekt">Projekt</a>
        <a href="kontakt.html">Kontakt</a>
    </nav>

    <header>
        <h1>Henrik Thorslund</h1>
        <p>Portfolio inom elkonstruktion och automation</p>
    </header>

    <section class="projects" id="projekt">

        <div class="card">
            <img src="grass.png" alt="Motorstart">

            <div class="card-content">
                <h2>Motorstart med kontaktor</h2>

                <p>
                    Konstruktion av styrkrets för trefasmotor.
                </p>

                <a href="projects/motorstart.html" class="button">
                    Öppna projekt
                </a>
            </div>
        </div>

        <div class="card">
            <img src="grass.png" alt="Pumpstyrning">

            <div class="card-content">
                <h2>Pumpstyrning</h2>

                <p>
                    Nivågivare, pump och larm.
                </p>

                <a href="projects/pumpstyrning.html" class="button">
                    Öppna projekt
                </a>
            </div>
        </div>

    </section>

    <footer>
        © 2026 Henrik Thorslund
    </footer>

</body>

</html>
