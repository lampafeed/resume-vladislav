<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Кузнецов Владислав — Специалист поддержки / SMM / Видеомонтаж</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>
  <style>
    :root {
      --bg: #0f0f1a;
      --text: #e0e0ff;
      --accent: #00ff9d;
      --card: #1a1a2e;
    }
    body {
      margin: 0;
      font-family: 'Segoe UI', system-ui, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }
    .container { max-width: 1000px; margin: 0 auto; padding: 20px; }
    header {
      text-align: center;
      padding: 80px 20px 40px;
      background: linear-gradient(to bottom, #000, transparent);
    }
    h1 { font-size: 3.5rem; margin: 0; color: var(--accent); }
    .subtitle { font-size: 1.5rem; margin: 10px 0; }
    .contact { font-size: 1.2rem; margin: 15px 0; }
    .contact a { color: var(--accent); text-decoration: none; }
    section { margin: 60px 0; }
    h2 {
      font-size: 2.2rem;
      color: var(--accent);
      border-bottom: 3px solid var(--accent);
      display: inline-block;
      padding-bottom: 8px;
    }
    .timeline { position: relative; max-width: 800px; margin: 0 auto; }
    .timeline::before {
      content: ''; position: absolute; width: 4px; background: var(--accent);
      top: 0; bottom: 0; left: 50%; margin-left: -2px;
    }
    .item {
      padding: 20px 40px;
      position: relative;
      background: var(--card);
      margin: 20px 0;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0,255,157,0.1);
    }
    .item.left { margin-right: 55%; }
    .item.right { margin-left: 55%; }
    .item::before {
      content: ''; position: absolute; width: 20px; height: 20px;
      background: var(--accent); border-radius: 50%;
      top: 25px;
    }
    .item.left::before { right: -10px; }
    .item.right::before { left: -10px; }
    .skills { display: flex; flex-wrap: wrap; gap: 15px; justify-content: center; }
    .skill { background: var(--card); padding: 12px 20px; border-radius: 30px; border: 1px solid var(--accent); }
    footer { text-align: center; padding: 40px; background: #000; font-size: 0.9rem; }
    @media (max-width: 768px) {
      .timeline::before { left: 30px; }
      .item { margin: 20px 0 20px 70px !important; }
      .item::before { left: -10px !important; }
    }
  </style>
</head>
<body>

  <header>
    <h1>Кузнецов Владислав</h1>
    <div class="subtitle">Специалист службы поддержки | SMM-менеджер | Видеомонтажёр</div>
    <div class="contact">
      <i class="fas fa-phone"></i> +7 (937) 219-57-37<br>
      <i class="fas fa-envelope"></i> <a href="mailto:crash823@yandex.ru">crash823@yandex.ru</a> (предпочитаемый)<br>
      Самара | 28 лет | Готов к работе на месте
    </div>
  </header>

  <div class="container">

    <section>
      <h2>Обо мне</h2>
      <p>Целеустремлённый, ответственный и трудолюбивый специалист. Долгое время работал в продажах, но перегорел и теперь развиваюсь в digital: поддержка пользователей, SMM, видеомонтаж и создание креативов. Фрилансую уже 7+ лет. В свободное время — видеоигры и техника.</p>
    </section>

    <section>
      <h2>Опыт работы (7 лет 8 месяцев)</h2>
      <div class="timeline">

        <div class="item left">
          <h3>Старший специалист поддержки SMM</h3>
          <p><strong>Яндекс Крауд</strong> • Декабрь 2022 — н.в. (3 года 2 мес)</p>
          <ul>
            <li>Консультации пользователей по сервисам Яндекса в соцсетях</li>
            <li>Мониторинг и поддержание имиджа компании</li>
          </ul>
        </div>

        <div class="item right">
          <h3>Видеомонтажёр (фриланс)</h3>
          <p><strong>ИП / Фриланс</strong> • Июнь 2018 — н.в. (7 лет 8 мес)</p>
          <ul>
            <li>Lyric видео, TikTok/Instagram, lifestyle, игровые, имиджевые и рекламные видео</li>
            <li>Креативы для таргета • Vegas Pro, Premiere Pro, After Effects, Photoshop</li>
          </ul>
        </div>

        <div class="item left">
          <h3>Продавец-консультант</h3>
          <p><strong>GamePark</strong> • Май 2020 — Декабрь 2022 (2 года 8 мес)</p>
          <p>Консультации, продажи игровой техники и аксессуаров</p>
        </div>

        <div class="item right">
          <h3>SMM-менеджер</h3>
          <p><strong>Школа вокала</strong> • Март — Август 2022 (6 мес)</p>
          <p>Ведение соцсетей, таргетированная реклама, дизайн</p>
        </div>

        <div class="item left">
          <h3>Продавец-кассир</h3>
          <p><strong>МЕГА</strong> • Сентябрь 2018 — Май 2020 (1 год 9 мес)</p>
          <p>Консультации и продажи товаров</p>
        </div>

      </div>
    </section>

    <section>
      <h2>Навыки</h2>
      <div class="skills">
        <span class="skill">SMM</span>
        <span class="skill">Техническая поддержка</span>
        <span class="skill">Видеомонтаж</span>
        <span class="skill">Adobe Premiere Pro</span>
        <span class="skill">After Effects</span>
        <span class="skill">Photoshop</span>
        <span class="skill">Vegas Pro</span>
        <span class="skill">Таргетированная реклама</span>
        <span class="skill">1С: Предприятие 8</span>
        <span class="skill">Клиентоориентированность</span>
        <span class="skill">Грамотная речь</span>
        <span class="skill">Работа в команде</span>
      </div>
    </section>

    <section>
      <h2>Образование</h2>
      <p><strong>Тольяттинский Индустриальный Педагогический Колледж</strong><br>Среднее специальное • Строительство зданий и сооружений • 2017</p>
    </section>

  </div>

  <footer>
    <p>© 2026 Владислав Кузнецов | Готов к новым вызовам в digital</p>
  </footer>

</body>
</html>
