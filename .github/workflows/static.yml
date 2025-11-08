<!doctype html>
<html lang="ru">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Invest in Kids — Центр подготовки</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root {
      --accent:#00a86b;
      --accent2:#0b8bd6;
      --muted:#6b7280;
      --bg:#f6fbf9;
      --card:#ffffff;
      --radius:14px;
      --container:1100px;
    }
    *{box-sizing:border-box}
    body {
      margin:0;
      font-family:Inter,system-ui,sans-serif;
      background:linear-gradient(180deg,#f6fbf9,#ecf9f6);
      color:#0b1220;
    }
    .wrap{max-width:var(--container);margin:0 auto;padding:0 20px}
    header{padding:22px 0}
    .nav{display:flex;align-items:center;justify-content:space-between}
    .brand{display:flex;align-items:center;gap:14px}
    .brand img{width:64px;height:64px;border-radius:10px;object-fit:contain}
    .brand h1{font-size:20px;margin:0}
    nav a{margin-left:16px;text-decoration:none;color:var(--muted);font-weight:600}

    .hero{display:flex;flex-wrap:wrap;gap:30px;align-items:center;padding:40px 0}
    .hero-left{flex:1;min-width:280px}
    .hero-left .eyebrow{background:rgba(11,139,214,0.1);padding:6px 10px;border-radius:999px;color:var(--accent2);font-size:13px;font-weight:700}
    .hero-left h2{font-size:34px;margin:18px 0 10px}
    .hero-left p{color:var(--muted);max-width:600px}
    .cta{display:flex;gap:12px;margin-top:18px}
    .btn{padding:12px 18px;border-radius:10px;border:0;font-weight:700;cursor:pointer}
    .btn-primary{background:linear-gradient(90deg,var(--accent),var(--accent2));color:#fff}
    .btn-ghost{background:transparent;border:2px solid #d1d5db;color:var(--muted)}

    .hero-right{flex:1;display:flex;justify-content:center}
    .card{background:var(--card);border-radius:18px;box-shadow:0 12px 30px rgba(2,6,23,0.08);padding:20px;text-align:center;max-width:320px}
    .card img{max-width:220px}

    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:18px;margin:40px 0}
    .course{background:var(--card);padding:20px;border-radius:14px;box-shadow:0 8px 18px rgba(2,6,23,0.06)}
    .course h3{margin:6px 0 8px}
    .course p{color:var(--muted);margin:0}

    footer{padding:30px 0;text-align:center;color:var(--muted)}
  </style>
</head>
<body>
  <header class="wrap">
    <div class="nav">
      <div class="brand">
        <img src="logo.png" alt="Invest in Kids">
        <div>
          <h1>Invest in Kids</h1>
          <small style="color:var(--muted)">English School</small>
        </div>
      </div>
      <nav>
        <a href="#courses">Курсы</a>
        <a href="#contact">Контакты</a>
      </nav>
    </div>
  </header>

  <main class="wrap">
    <section class="hero">
      <div class="hero-left">
        <span class="eyebrow">Подготовительные курсы</span>
        <h2>Английский, арабский и русский — ключ к будущему успеху</h2>
        <p>Центр <strong>Invest in Kids</strong> предлагает современные и эффективные программы обучения для детей и подростков. Мы развиваем языковые навыки и уверенность в себе!</p>
        <div class="cta">
          <button class="btn btn-primary" onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})">Записаться</button>
          <button class="btn btn-ghost" onclick="document.getElementById('courses').scrollIntoView({behavior:'smooth'})">Подробнее</button>
        </div>
      </div>
      <div class="hero-right">
        <div class="card">
          <img src="logo.png" alt="Логотип">
          <p style="color:var(--muted)">Invest in Kids — English School</p>
        </div>
      </div>
    </section>

    <section id="courses">
      <h2>Наши курсы</h2>
      <div class="grid">
        <div class="course">
          <h3>🇬🇧 Английский язык</h3>
          <p>Развитие разговорных навыков, грамматики и подготовка к экзаменам Cambridge.</p>
        </div>
        <div class="course">
          <h3>🇸🇦 Арабский язык</h3>
          <p>Изучение арабского алфавита, разговорная практика и понимание культуры.</p>
        </div>
        <div class="course">
          <h3>🇷🇺 Русский язык</h3>
          <p>Подготовка к школе и помощь в изучении грамматики и письма.</p>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Контакты</h2>
      <p><strong>Телефон:</strong> +7 (XXX) XXX-XX-XX</p>
      <p><strong>Адрес:</strong> г. Ваш город, ул. Примерная, 10</p>
      <p><strong>Email:</strong> info@example.com</p>

      <h3>QR-код для записи</h3>
      <p>Если вы заинтересовались — просто отсканируйте QR-код:</p>
      <img src="qrcode.png" alt="QR code" style="width:180px;border-radius:10px;box-shadow:0 8px 20px rgba(0,0,0,0.1)">
    </section>
  </main>

  <footer>
    <p>© <span id="year"></span> Invest in Kids. Все права защищены.</p>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
