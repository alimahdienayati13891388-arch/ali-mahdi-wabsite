<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="وب‌سایت شخصی علی مهدی؛ معرفی، مهارت‌ها و مسیر یادگیری در دنیای کامپیوتر و هوش مصنوعی.">
  <title>علی مهدی | وب‌سایت شخصی</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;500;600;700;800&display=swap');
    :root {
      --bg: #0b1020; --panel: #121a2e; --panel2: #17223a;
      --text: #edf3ff; --muted: #a9b6ce; --accent: #71e0c0;
      --accent2: #7da7ff; --line: rgba(255,255,255,.10);
    }
    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
      margin: 0; font-family: "Vazirmatn", Tahoma, sans-serif;
      background: radial-gradient(circle at 85% 5%, #1a3150 0, transparent 32%), var(--bg);
      color: var(--text); line-height: 1.9;
    }
    a { color: inherit; text-decoration: none; }
    .wrap { width: min(1080px, 90%); margin: auto; }
    header { padding: 22px 0; border-bottom: 1px solid var(--line); }
    nav { display: flex; justify-content: space-between; align-items: center; gap: 18px; }
    .brand { font-weight: 800; letter-spacing: -.5px; }
    .brand span { color: var(--accent); }
    .navlinks { display: flex; gap: 22px; color: var(--muted); font-size: .92rem; }
    .navlinks a:hover { color: var(--accent); }
    .hero { display: grid; grid-template-columns: 1.4fr .8fr; gap: 42px; align-items: center; padding: 90px 0 76px; }
    .eyebrow { color: var(--accent); font-weight: 600; }
    h1 { font-size: clamp(2.3rem, 6vw, 4.3rem); line-height: 1.25; margin: 12px 0 18px; }
    h1 span { color: var(--accent); }
    .lead { color: var(--muted); font-size: 1.08rem; max-width: 650px; }
    .actions { display: flex; flex-wrap: wrap; gap: 12px; margin-top: 28px; }
    .btn { padding: 11px 20px; border-radius: 12px; font-weight: 700; border: 1px solid var(--line); }
    .primary { background: var(--accent); color: #092018; border-color: var(--accent); }
    .secondary { background: rgba(255,255,255,.04); }
    .profile-card {
      background: linear-gradient(145deg, rgba(113,224,192,.13), rgba(125,167,255,.10)), var(--panel);
      border: 1px solid var(--line); border-radius: 26px; padding: 28px; text-align: center;
      box-shadow: 0 25px 70px rgba(0,0,0,.22);
    }
    .avatar { width: 118px; height: 118px; margin: 0 auto 18px; border-radius: 34px;
      display: grid; place-items: center; font-size: 2.5rem; font-weight: 800;
      color: #092018; background: linear-gradient(135deg, var(--accent), var(--accent2)); }
    .profile-card p { color: var(--muted); margin-bottom: 0; }
    section { padding: 55px 0; }
    .section-title { font-size: 1.8rem; margin: 0 0 10px; }
    .section-sub { color: var(--muted); margin: 0 0 26px; }
    .grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 16px; }
    .card { background: var(--panel); border: 1px solid var(--line); border-radius: 18px; padding: 22px; }
    .card h3 { margin: 5px 0 8px; }
    .card p { color: var(--muted); margin: 0; font-size: .95rem; }
    .icon { font-size: 1.7rem; }
    .about { background: rgba(255,255,255,.025); border-block: 1px solid var(--line); }
    .skills { display: flex; flex-wrap: wrap; gap: 10px; }
    .tag { border: 1px solid rgba(113,224,192,.25); color: #c9f7e9; background: rgba(113,224,192,.07);
      border-radius: 999px; padding: 7px 14px; font-size: .9rem; }
    .project-note { display: inline-block; margin-top: 12px; color: var(--accent); font-size: .82rem; }
    .contact-box { background: linear-gradient(120deg, rgba(113,224,192,.12), rgba(125,167,255,.10)); border: 1px solid var(--line); border-radius: 22px; padding: 28px; }
    footer { border-top: 1px solid var(--line); padding: 22px 0; color: var(--muted); font-size: .88rem; text-align: center; }
    @media (max-width: 760px) {
      .hero { grid-template-columns: 1fr; padding: 58px 0; }
      .profile-card { max-width: 390px; }
      .grid { grid-template-columns: 1fr; }
      .navlinks { gap: 11px; font-size: .8rem; }
    }
    @media (max-width: 420px) { .navlinks a:nth-child(2) { display: none; } }
  </style>
</head>
<body>
  <header>
    <div class="wrap">
      <nav>
        <a class="brand" href="#home">ALI <span>MAHDI.</span></a>
        <div class="navlinks">
          <a href="#about">درباره من</a>
          <a href="#skills">مهارت‌ها</a>
          <a href="#projects">نمونه‌کارها</a>
          <a href="#contact">ارتباط</a>
        </div>
      </nav>
    </div>
  </header>

  <main>
    <div class="wrap">
      <section class="hero" id="home">
        <div>
          <div class="eyebrow">دانش‌آموز کامپیوتر | علاقه‌مند به فناوری و هوش مصنوعی</div>
          <h1>سلام، من <span>علی مهدی</span> هستم.</h1>
          <p class="lead">
            به دنیای کامپیوتر، برنامه‌نویسی و هوش مصنوعی علاقه دارم.
            همیشه سعی می‌کنم چیزهای تازه یاد بگیرم، مهارت‌هایم را بهتر کنم
            و ایده‌هایم را به پروژه‌های واقعی تبدیل کنم.
          </p>
          <div class="actions">
            <a class="btn primary" href="#about">بیشتر درباره من</a>
            <a class="btn secondary" href="#projects">دیدن نمونه‌کارها</a>
          </div>
        </div>
        <aside class="profile-card">
          <div class="avatar">AM</div>
          <h2 style="margin:0">علی مهدی</h2>
          <p>یادگیری امروز، ساختن فردا 🚀</p>
        </aside>
      </section>
    </div>

    <section class="about" id="about">
      <div class="wrap">
        <h2 class="section-title">درباره من</h2>
        <p class="section-sub">مسیر من در دنیای فناوری</p>
        <div class="card">
          من دانش‌آموز رشته کامپیوتر هستم و به یادگیری برنامه‌نویسی، ابزارهای دیجیتال
          و به‌خصوص هوش مصنوعی علاقه دارم. از کار با نرم‌افزارهای کاربردی مثل Word،
          PowerPoint و Excel لذت می‌برم و در کنار یادگیری، روی ساخت نمونه‌کارهای
          شخصی و تقویت مهارت حل مسئله تمرکز دارم.
        </div>
      </div>
    </section>

    <section id="skills">
      <div class="wrap">
        <h2 class="section-title">مهارت‌ها و علاقه‌مندی‌ها</h2>
        <p class="section-sub">چیزهایی که بلدم و در حال یادگیری آن‌ها هستم</p>
        <div class="skills">
          <span class="tag">Microsoft Word</span>
          <span class="tag">Microsoft PowerPoint</span>
          <span class="tag">Microsoft Excel</span>
          <span class="tag">تایپ فارسی</span>
          <span class="tag">مهارت‌های پایه کامپیوتر</span>
          <span class="tag">Python — در حال یادگیری</span>
          <span class="tag">هوش مصنوعی</span>
          <span class="tag">حل مسئله</span>
        </div>
      </div>
    </section>

    <section id="projects" class="about">
      <div class="wrap">
        <h2 class="section-title">نمونه‌کارها</h2>
        <p class="section-sub">این بخش با آماده شدن پروژه‌ها تکمیل می‌شود.</p>
        <div class="grid">
          <article class="card">
            <div class="icon">📊</div>
            <h3>پروژه Excel</h3>
            <p>ساخت جدول‌های منظم، ثبت اطلاعات و گزارش‌گیری ساده.</p>
            <span class="project-note">نمونه‌کار در حال آماده‌سازی</span>
          </article>
          <article class="card">
            <div class="icon">📽️</div>
            <h3>پروژه PowerPoint</h3>
            <p>طراحی ارائه‌های آموزشی با ساختار مرتب و ظاهر حرفه‌ای.</p>
            <span class="project-note">نمونه‌کار در حال آماده‌سازی</span>
          </article>
          <article class="card">
            <div class="icon">📄</div>
            <h3>پروژه Word</h3>
            <p>تنظیم و صفحه‌آرایی اسناد، متن‌ها و جدول‌ها.</p>
            <span class="project-note">نمونه‌کار در حال آماده‌سازی</span>
          </article>
        </div>
      </div>
    </section>

    <section id="contact">
      <div class="wrap">
        <div class="contact-box">
          <h2 class="section-title">ارتباط با من</h2>
          <p class="section-sub" style="margin-bottom:0">
            برای همکاری یا آشنایی بیشتر، می‌توانی از راه ارتباطی امنی که بعداً در این بخش قرار می‌دهم استفاده کنی.
          </p>
          <p style="color:var(--muted);font-size:.88rem;margin-bottom:0">
            پیش از انتشار عمومی سایت، اطلاعات تماس را با کمک خانواده بررسی و اضافه کن.
          </p>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="wrap">© 2026 علی مهدی — ساخته‌شده با علاقه به دنیای فناوری</div>
  </footer>
</body>
</html># ali-mahdi-wabsite
