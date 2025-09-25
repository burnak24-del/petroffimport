<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Petroff Import — прямой импорт из Китая</title>
  <meta name="description" content="Petroff Import — прямой импорт товаров из Китая: снижение закупочных цен на 15–30%, доставка от 20 дней, полный цикл услуг под ключ." />

  <!-- Fonts: Manrope (строго, современно) -->
  <link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;600;700&display=swap" rel="stylesheet">

  <!-- Favicon (поместите favicon.ico рядом с index.html) -->
  <link rel="icon" href="favicon.ico">

  <style>
    :root{
      --brand:#0B3D91; /* премиальный синий */
      --ink:#101828;   /* тёмный текст */
      --muted:#667085; /* вторичный текст */
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
        <!-- Заменили на логотип с текстом -->
        <img src="petroff_logo_full_horizontal.png" alt="Petroff Import">
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

  <section id="about" class="section">
    <div class="container">
      <div class="grid-3">
        <div class="card">
          <div class="icon">★</div>
          <h3>О компании</h3>
          <p class="muted">Petroff Import — ваш партнёр по прямому импорту из Китая. Работаем под ключ: от поиска производителя и образцов до растаможки и доставки.</p>
        </div>
        <div class="card">
          <div class="icon">✓</div>
          <h3>Контроль качества</h3>
          <p class="muted">Предоставляем фото/видео‑инспекцию и образцы перед основной поставкой. Проверяем партии перед отправкой.</p>
        </div>
        <div class="card">
          <div class="icon">⚑</div>
          <h3>Прозрачные условия</h3>
          <p class="muted">Чёткие сроки (от 20 дней) и понятные расчёты. Персональный менеджер сопровождает сделку на каждом этапе.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="services" class="section" style="background:var(--bg-alt)">
    <div class="container">
      <h3 style="font-size:28px;margin:0 0 18px">Услуги</h3>
      <div class="grid-4">
        <div class="card">
          <div class="pill">Поиск товаров</div>
          <h3>Подбор и проверка поставщиков</h3>
          <p class="muted">Анализ номенклатуры, проверка контрагентов, аудиты фабрик, согласование условий и MOQ.</p>
        </div>
        <div class="card">
          <div class="pill">Качество</div>
          <h3>Образцы и инспекция</h3>
          <p class="muted">Заказываем образцы, делаем инспекцию перед отгрузкой, согласовываем упаковку и брендинг.</p>
        </div>
        <div class="card">
          <div class="pill">Логистика</div>
          <h3>Доставка и страхование</h3>
          <p class="muted">Авиа, авто, ж/д, море. Консолидация на складе, страхование груза, трекинг статуса.</p>
        </div>
        <div class="card">
          <div class="pill">Таможня</div>
          <h3>Оформление ВЭД</h3>
          <p class="muted">Коды ТН ВЭД, сертификация, расчёт пошлин и НДС, «белое» оформление и юридическое сопровождение.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="benefits" class="section">
    <div class="container">
      <h3 style="font-size:28px;margin:0 0 18px">Преимущества</h3>
      <div class="grid-3">
        <div class="card">
          <h3>Экономия 15–30%</h3>
          <p class="muted">За счёт прямого импорта и оптимизации логистики снижаем закупочные цены.</p>
        </div>
        <div class="card">
          <h3>Сроки 20–40 дней</h3>
          <p class="muted">Подбираем маршрут под задачу: скорость или стоимость.</p>
        </div>
        <div class="card">
          <h3>Персональный менеджер</h3>
          <p class="muted">Единая точка контакта и контроль качества на всех этапах.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="process" class="section" style="background:var(--bg-alt)">
    <div class="container">
      <h3 style="font-size:28px;margin:0 0 18px">Как мы работаем (4 шага)</h3>
      <div class="steps">
        <div class="step"><div class="nr">1</div><h4>Заявка</h4><p class="muted">Вы присылаете номенклатуру и требования.</p></div>
        <div class="step"><div class="nr">2</div><h4>Подбор</h4><p class="muted">Находим и проверяем поставщиков, согласуем условия.</p></div>
        <div class="step"><div class="nr">3</div><h4>Образцы</h4><p class="muted">Доставляем образцы и утверждаем качество.</p></div>
        <div class="step"><div class="nr">4</div><h4>Поставка</h4><p class="muted">Отгрузка, таможня и доставка до вашего склада.</p></div>
      </div>
    </div>
  </section>

  <section id="lead" class="section">
    <div class="container">
      <div class="grid-3">
        <div class="card" style="grid-column: span 2">
          <h3 style="font-size:24px;margin:0 0 12px">Заявка на расчёт поставки</h3>
          <form id="leadForm" class="calc" autocomplete="off">
            <div class="grid-3">
              <div class="field"><label>Имя</label><input required placeholder="Иван" /></div>
              <div class="field"><label>Компания</label><input required placeholder="ООО «Пример»" /></div>
              <div class="field"><label>Телефон</label><input required type="tel" placeholder="+7 (___) ___‑__‑__" /></div>
            </div>
            <div class="grid-3">
              <div class="field"><label>Email</label><input required type="email" placeholder="name@company.ru" /></div>
              <div class="field"><label>Категория</label>
                <select required>
                  <option value="">Выберите</option>
                  <option>Автозапчасти</option>
                  <option>Электроника</option>
                  <option>Текстиль</option>
                  <option>Мебель</option>
                  <option>Иное</option>
                </select>
              </div>
              <div class="field"><label>Приоритет</label>
                <select>
                  <option>Скорость</option>
                  <option>Стоимость</option>
                </select>
              </div>
            </div>
            <div class="field">
              <label>Описание товара / артикулы</label>
              <textarea rows="4" placeholder="Кратко опишите позиции, объёмы, требования к качеству и упаковке"></textarea>
            </div>
            <button class="btn primary" type="submit">Отправить заявку</button>
            <p class="small" id="leadOut"></p>
          </form>
        </div>
        <div class="card">
          <h3 style="font-size:18px;margin-top:0">Контакты</h3>
          <p class="muted">Тел.: <a href="tel:+7XXXXXXXXXX">+7 (___) ___‑__‑__</a><br>Почта: <a href="mailto:info@petroffimport.ru">info@petroffimport.ru</a><br>Адрес: Москва</p>
          <hr style="border:0;border-top:1px solid #e6ebf4;margin:16px 0">
          <p class="muted">Работаем по РФ. Возможна поставка в СНГ. Языковые версии EN/ZH — по запросу.</p>
        </div>
      </div>
    </div>
  </section>

  <footer class="footer">
    <div class="container" style="display:flex;align-items:center;justify-content:space-between;padding:22px 0">
      <div>© <span id="y"></span> Petroff Import. Все права защищены.</div>
      <div style="display:flex;gap:14px"><a href="#">Политика конфиденциальности</a><a href="#">Договор оферты</a></div>
    </div>
  </footer>

  <script>
    // Год в футере
    document.getElementById('y').textContent = new Date().getFullYear();

    // Форма лида (демо)
    const leadForm = document.getElementById('leadForm');
    const leadOut = document.getElementById('leadOut');
    leadForm.addEventListener('submit', function(e){
      e.preventDefault();
      leadOut.textContent = 'Спасибо! Мы свяжемся с вами в ближайшее время.';
      leadForm.reset();
    });
  </script>
</body>
</html>
