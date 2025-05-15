# wedding
Пригласительные
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Свадебное приглашение</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      background: url('https://i.imgur.com/q0GvFb3.jpg') no-repeat center center fixed;
      background-size: cover;
      font-family: 'Playfair Display', serif;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      text-align: center;
    }
    .overlay {
      background: rgba(0, 0, 0, 0.4);
      padding: 40px 20px;
      border-radius: 20px;
      animation: fadeIn 2s ease-in-out;
    }
    h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 3em;
      margin: 0.2em 0;
    }
    .date {
      font-size: 1.2em;
      letter-spacing: 2px;
    }
    .names {
      font-size: 1.5em;
      margin-top: 2em;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="overlay">
    <div class="date">25 | 10 | 2025</div>
    <h1>Wedding Day</h1>
    <div class="names">Владимир & Елизавета</div>
  </div>
</body>
</html>
