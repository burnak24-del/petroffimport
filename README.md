<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Petroff Import — прямой импорт из Китая</title>
  <meta name="description" content="Petroff Import — прямой импорт товаров из Китая: снижение закупочных цен на 15–30%, доставка от 20 дней, полный цикл услуг под ключ." />

  <!-- Fonts: Manrope -->
  <link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;600;700&display=swap" rel="stylesheet">
  <link rel="icon" href="favicon.ico">

  <style>
    :root{
      --brand:#0B3D91;
      --ink:#101828;
      --muted:#667085;
      --bg:#ffffff;
      --bg-alt:#f5f7fb;
      --ring: 0 10px 30px rgba(11,61,145,.12);
      --card: #fff;
    }
    *{box-sizing:border-box}
    html,body{margin:0;padding:0;background:var(--bg);color:var(--ink);font-family: 'Manrope', system-ui, -apple-system, Segoe UI, Roboto, 'Helvetica Neue', Arial;}
    a{color:var(--brand);text-decoration:none}
    .container{max-width:1160px;margin:0 auto;padding:0 20px}
    header{position:sticky;top:0;z-index:50;background:rgba(255,255,255,.85);backdrop-filter:saturate(180%) blur(14px);border-bottom:1px solid #eef2f7}
    .nav{display:flex;align-items:center;justify-content:space-between;padding:14px 0}
    .brand img{display:block;height:56px}
    .menu{display:flex;gap:18px;align-items:center}
    .btn{display:inline-flex;gap:10px;align-items:center;justify-content:center;padding:12px 16px;border-radius:12px;border:1px solid #dbe3ef;background:#fff;color:var(--ink);font-weight:700;transition:.2s ease;}
    .btn:hover{transform:translateY(-1px);box-shadow:0 6px 18px rgba(16,24,40,.08)}
    .btn.primary{background:var(--brand);border-color:var(--brand);color:#fff}
    .btn.primary:hover{background:#073a86}
    .hero{padding:80px 0 56px}
    .hero .wrap{display:grid;grid-template-columns:1fr;gap:24px;align-items:center}
    .kicker{display:inline-block;padding:6px 12px;background:#e9efff;color:#274690;border-radius:999px;font-weight:700;font-size:12px;letter-spacing:.4px}
    h1{font-size:44px;line-height:1.12;margin:16px 0 12px}
    p.lead{font-size:18px;color:var(--muted);margin:0 0 24px}
    .section{padding:72px 0}
    .grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
    .grid-4{display:grid;grid-template-columns:repeat(4,1fr);gap:18px}
    .card{background:var(--card);border:1px solid #e6ebf4;border-radius:18px;padding:20px;box-shadow:var(--ring)}
    .icon{width:40px;height:40px;border-radius:10px;background:#ecf2ff;display:grid;place-items:center;color:var(--brand);font-weight:800}
    h3{margin:10px 0 8px;font-size:20px}
    .muted{color:var(--muted)}
    .pill{display:inline-block;padding:6px 10px;border-radius:999px;background:#eef4ff;color:#1d3f8a;font-size:12px;font-weight:800}
    .steps{display:grid;grid-template-columns:repeat(4,1fr);gap:18px}
    .step{position:relative;padding:18px;border-radius:18px;border:1px dashed #dbe3ef;background:#fafcff}
    .step .nr{position:absolute;top:-12px;left:-12px;background:var(--brand);color:#fff;width:32px;height:32px;display:grid;place-items:center;border-radius:10px;box-shadow:0 6px 18px rgba(11,61,145,.35);font-weight:800}
    .footer{background:#0b1220;color:#d1d7e5}
    .footer a{color:#d1d7e5}
    @media (max-width:960px){
      .grid-3,.grid-4,.steps{grid-template-columns:1fr}
      .brand img{height:48px}
      h1{font-size:34px}
    }
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <div class="brand">
        <a href="/">
          <img src="./petroff_logo_full_horizontal.png" alt="Petroff Import" height="56">
        </a>
      </div>
      <nav class="menu">
        <a href="#about">О компании</a>
        <a href="#services">Услуги</a>
        <a href="#benefits">Преимущества</a>
        <a href="#process">Схема</a>
        <a href="#contact">Контакты</a>
        <a class="btn primary" href="#lead">Рассчитать поставку</a>
      </nav>
    </div>
  </header>

  <section class="hero">
    <div class="container wrap">
      <div>
        <span class="kicker">Прямой импорт из Китая</span>
        <h1>Снижаем закупочные цены на 15–30%. Доставка от 20 дней. Полный цикл «под ключ».</h1>
        <p class="lead">Поиск и проверка поставщиков, образцы перед заказом, логистика (авиа/авто/жд/море), таможенное оформление и доставка до вашего склада.</p>
        <div style="display:flex; gap:12px; flex-wrap:wrap">
          <a class="btn primary" href="#lead">Рассчитать поставку</a>
          <a class="btn" href="#services">Наши услуги</a>
        </div>
      </div>
    </div>
  </section>

  <!-- остальные секции сайта остаются как в предыдущей версии -->
  <footer class="footer">
    <div class="container" style="display:flex;align-items:center;justify-content:space-between;padding:22px 0">
      <div>© <span id="y"></span> Petroff Import. Все права защищены.</div>
      <div style="display:flex;gap:14px"><a href="#">Политика конфиденциальности</a><a href="#">Договор оферты</a></div>
    </div>
  </footer>

  <script>
    document.getElementById('y').textContent = new Date().getFullYear();
  </script>
</body>
</html>
