<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Benvenuti alla Fiera Walden</title>
  <style>
    /* Reset base */
    body, html {
      margin: 0;
      padding: 0;
      font-family: 'Arial', sans-serif;
      height: 100%;
    }

    /* Sfondo generale e layout centrale */
    body {
      background-color: #f4f4f4;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      min-height: 100vh;
    }

    /* Intestazione */
    header {
      background-color: #333;
      color: #fff;
      width: 100%;
      padding: 40px 0;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    header h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
      font-weight: bold;
    }

    header p {
      font-size: 1.2em;
      margin-top: 0;
    }

    /* Logo */
    .logo {
      margin-top: 20px;
      width: 250px;
      max-width: 100%;
    }

    /* Sezione pulsanti */
    .buttons {
      display: flex;
      flex-direction: column;
      justify-content: center;
      gap: 20px;
      margin-top: 40px;
      width: 100%;
      max-width: 400px;
    }

    .button {
      padding: 18px 40px;
      font-size: 18px;
      text-decoration: none;
      color: #fff;
      background-color: #008CBA;
      border-radius: 8px;
      transition: background 0.3s ease;
      width: 100%;
      text-align: center;
    }

    .button:hover {
      background-color: #005f73;
    }

    /* Layout per desktop */
    @media (min-width: 768px) {
      .buttons {
        flex-direction: row;
        gap: 30px;
        max-width: none;
      }
      .button {
        width: 250px;
        font-size: 20px;
      }
    }
  </style>
</head>
<body>

  <!-- Intestazione con testo di benvenuto -->
  <header>
    <h1>Benvenuti alla Fiera Walden</h1>
    <p>Scopri il nostro mondo di mobili unici e funzionali</p>
  </header>

  <!-- Logo -->
  <img src="logo.webp" alt="Walden Logo" class="logo">

  <!-- Pulsanti -->
  <div class="buttons">
    <a href="URL_DEL_SITO" class="button">Visita il nostro Sito</a>
    <a href="URL_FACEBOOK" class="button">Seguici su Facebook</a>
    <a href="URL_INSTAGRAM" class="button">Seguici su Instagram</a>
  </div>

</body>
</html>
