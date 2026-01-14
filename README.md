<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <title>VoxTube – Support</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --primary: #6C63FF;
      --secondary: #8F94FB;
      --text-dark: #1c1c1e;
      --text-light: #6e6e73;
      --bg: #f5f5f7;
      --card: #ffffff;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
      background: linear-gradient(180deg, var(--secondary), var(--bg));
      color: var(--text-dark);
    }

    header {
      padding: 80px 20px 60px;
      text-align: center;
      color: white;
    }

    header h1 {
      font-size: 48px;
      font-weight: 700;
      letter-spacing: -1px;
    }

    header p {
      margin-top: 12px;
      font-size: 18px;
      opacity: 0.9;
    }

    .container {
      max-width: 900px;
      margin: -40px auto 0;
      padding: 0 20px 60px;
    }

    .card {
      background: var(--card);
      border-radius: 20px;
      padding: 40px;
      box-shadow: 0 30px 60px rgba(0, 0, 0, 0.12);
      margin-bottom: 30px;
    }

    h2 {
      font-size: 26px;
      margin-bottom: 14px;
    }

    p {
      font-size: 17px;
      line-height: 1.7;
      color: var(--text-light);
    }

    .contact {
      margin-top: 20px;
      display: flex;
      align-items: center;
      gap: 12px;
      font-size: 17px;
    }

    .contact span {
      font-size: 22px;
    }

    a {
      color: var(--primary);
      font-weight: 500;
      text-decoration: none;
    }

    footer {
      text-align: center;
      color: #8e8e93;
      font-size: 14px;
      margin-top: 40px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 36px;
      }

      .card {
        padding: 28px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>VoxTube</h1>
    <p>Regardez n’importe quelle vidéo dans votre langue</p>
  </header>

  <div class="container">

    <div class="card">
      <h2>Besoin d’assistance ?</h2>
      <p>
        VoxTube vous permet de comprendre des vidéos du monde entier en les traduisant
        automatiquement dans votre langue.
        <br><br>
        Si vous avez un problème, une question ou une suggestion,
        notre équipe est là pour vous aider.
      </p>

      <div class="contact">
        <span>📧</span>
        <a href="mailto:asamathseck@gmail.com">asamathseck@gmail.com</a>
      </div>
    </div>

    <div class="card">
      <h2>À propos</h2>
      <p>
        VoxTube est développée par <strong>touba 7G</strong>.
        <br>
        Notre objectif est de rendre les vidéos accessibles à tous,
        sans barrière de langue.
      </p>
    </div>

    <footer>
      © 2026 VoxTube · Développé par touba 7G
    </footer>

  </div>

</body>
</html>
