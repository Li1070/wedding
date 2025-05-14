# wedding
Пригласительные
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Свадьба Елизаветы и Вадима</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: #fff7f3;
      color: #333;
    }

    header {
      background: #ffe0e6;
      text-align: center;
      padding: 50px 20px;
    }

    header h1 {
      font-size: 2.5em;
      margin: 0;
    }

    header p {
      font-size: 1.2em;
      margin-top: 10px;
    }

    section {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
    }

    h2 {
      color: #c94f7c;
      font-size: 1.8em;
    }

    .map iframe {
      width: 100%;
      height: 300px;
      border: 0;
    }

    form input, form textarea, form select {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border-radius: 8px;
      border: 1px solid #ccc;
      font-size: 1em;
    }

    form button {
      background: #c94f7c;
      color: white;
      border: none;
      padding: 12px 20px;
      border-radius: 8px;
      font-size: 1em;
      cursor: pointer;
    }

    footer {
      background: #ffe0e6;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      color: #555;
    }
  </style>
</head>
<body>
  <header>
    <h1>Елизавета & Вадим</h1>
    <p>Мы женимся! 08 августа 2025 года</p>
  </header>

  <section>
    <h2>Наша история</h2>
    <p>Мы познакомились в колледже, три года вместе, и теперь настал наш день 💍</p>
  </section>

  <section>
    <h2>Программа</h2>
    <ul>
      <li>17:30 — Сбор гостей</li>
      <li>18:00 — Церемония</li>
      <li>18:30 — Ужин и праздник</li>
    </ul>
  </section>

  <section class="map">
    <h2>Место</h2>
    <p>Алма-Ата, озеро Большое Алматинское</p>
    <iframe src=..." allowfullscreen></iframe>
  </section>

  <section>
    <h2>Подтвердите участие</h2>
    <form action="https://formspree.io/f/mwpoavwp" method="POST">
      <input type="text" name="name" placeholder="Ваше имя" required />
      <select name="attendance" required>
        <option value="">Вы придёте?</option>
        <option value="Да">Да, буду обязательно!</option>
        <option value="Нет">К сожалению, не смогу</option>
      </select>
      <textarea name="message" placeholder="Пожелания или вопросы"></textarea>
      <button type="submit">Отправить</button>
    </form>
  </section>

  <footer>
    С любовью, Лиза и Вадим 💕
  </footer>
</body>
</html>
