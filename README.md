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
      background-color: #ffffff; /* Sfondo bianco */
    }

    /* Layout centrale */
    body {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      min-height: 100vh;
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

  <!-- Logo -->
  <img src="logo.png" alt="Walden Logo" class="logo">

  <!-- Pulsanti -->
  <div class="buttons">
    <a href="URL_DEL_SITO" class="button">Visita il nostro Sito</a>
    <a href="URL_FACEBOOK" class="button">Seguici su Facebook</a>
    <a href="https://www.instagram.com/waldenvintage?igsh=MWMxZ201bGltZGpnbA==&utm_source=ig_contact_invite" class="button">Seguici su Instagram</a>
  </div>

</body>
</html>
