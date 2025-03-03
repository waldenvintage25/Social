<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Seguici sui Social</title>
    <style>
        /* Stile generale */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #87ceeb, #ffffff);
            color: #333;
            text-align: center;
        }

        /* Header */
        header {
            background-color: #1e90ff;
            color: white;
            padding: 20px 0;
        }

        header img {
            max-width: 100px;
            margin-bottom: 10px;
        }

        header h1 {
            margin: 10px 0 0;
            font-size: 28px;
        }

        header p {
            margin: 5px 0 0;
            font-size: 18px;
            font-style: italic;
        }

        /* Contenitore principale */
        .container {
            padding: 30px 20px;
        }

        h2 {
            font-size: 24px;
            color: #1e90ff;
        }

        /* Pulsanti */
        .social-button {
            display: inline-block;
            text-decoration: none;
            padding: 15px 30px;
            margin: 20px 10px;
            font-size: 20px;
            font-weight: bold;
            border-radius: 10px;
            color: white;
            transition: transform 0.2s, box-shadow 0.2s;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
        }

        .social-button:hover {
            transform: scale(1.1);
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.3);
        }

        .facebook {
            background-color: #4267B2;
        }

        .instagram {
            background-color: #C13584;
        }

        /* Footer */
        footer {
            margin-top: 30px;
            background-color: #1e90ff;
            color: white;
            padding: 10px 0;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <img src="logo.png" alt="Logo" /> <!-- Aggiungi qui il tuo logo -->
        <h1>Seguici sui Social</h1>
        <p>Connettiti con noi su Facebook e Instagram</p>
    </header>

    <!-- Contenuto principale -->
    <div class="container">
        <h2>Segui i nostri profili social</h2>
        <a href="https://www.facebook.com/tuoProfilo" class="social-button facebook" target="_blank">Facebook</a>
        <a href="https://www.instagram.com/tuoProfilo" class="social-button instagram" target="_blank">Instagram</a>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 La tua Azienda. Tutti i diritti riservati.</p>
    </footer>
</body>
</html>
