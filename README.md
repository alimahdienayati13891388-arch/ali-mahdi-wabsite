<!--DOCTYPE html-->
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="آشنایی با ابزارهای هوش مصنوعی برای ساخت ویدیوهای خلاقانه، شخصیت‌های سخنگو و انیمیشن.">
  <title>AI Studio | دنیای ویدیوهای هوش مصنوعی</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Vazirmatn:wght@400;500;600;700;800;900&display=swap');
    :root{--bg:#080b16;--panel:#11172a;--muted:#9aa5c2;--text:#f5f7ff;--a:#8b7cff;--b:#35d6c4;--line:rgba(255,255,255,.1)}
    *{box-sizing:border-box}html{scroll-behavior:smooth}
    body{margin:0;background:radial-gradient(ellipse at 15% 0%,rgba(111,83,255,.2),transparent 35%),radial-gradient(ellipse at 90% 30%,rgba(29,211,190,.12),transparent 30%),var(--bg);color:var(--text);font-family:Vazirmatn,Tahoma,sans-serif;line-height:1.8}
    a{color:inherit;text-decoration:none}.wrap{width:min(1120px,92%);margin:auto}
    header{display:flex;align-items:center;justify-content:space-between;padding:22px 0;border-bottom:1px solid var(--line)}
    .brand{font-weight:900;font-size:1.2rem;letter-spacing:-.5px}.brand span{color:var(--b)}
    nav{display:flex;gap:24px;color:var(--muted);font-size:.92rem}nav a:hover{color:white}
    .hero{padding:88px 0 66px;text-align:center}.pill{display:inline-flex;align-items:center;gap:8px;border:1px solid rgba(139,124,255,.35);background:rgba(139,124,255,.1);color:#c7c0ff;border-radius:999px;padding:6px 15px;font-size:.82rem}
    h1{font-size:clamp(2.2rem,6vw,4.6rem);line-height:1.25;margin:22px auto 16px;max-width:850px;letter-spacing:-1.5px}
    h1 em{font-style:normal;background:linear-gradient(90deg,var(--b),#a99dff);-webkit-background-clip:text;background-clip:text;color:transparent}
    .intro{color:var(--muted);max-width:680px;margin:0 auto 28px;font-size:1.04rem}
    .actions{display:flex;justify-content:center;gap:12px;flex-wrap:wrap}.btn{display:inline-block;padding:11px 22px;border-radius:13px;font-weight:700;transition:.2s}.primary{background:linear-gradient(100deg,#7666ff,#4b9dff);box-shadow:0 10px 30px rgba(106,103,255,.25)}.secondary{border:1px solid var(--line);background:rgba(255,255,255,.04)}.btn:hover{transform:translateY(-3px)}
    .section-head{display:flex;align-items:end;justify-content:space-between;gap:15px;margin:24px 0}.section-head h2{margin:0;font-size:1.65rem}.section-head p{margin:0;color:var(--muted);font-size:.9rem}
    .cards{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:18px}
    .card{position:relative;overflow:hidden;background:linear-gradient(145deg,rgba(24,32,57,.96),rgba(14,19,35,.96));border:1px solid var(--line);border-radius:22px;padding:23px;transition:.25s}
    .card:hover{transform:translateY(-5px);border-color:rgba(139,124,255,.55);box-shadow:0 18px 45px rgba(0,0,0,.22)}
    .card-top{display:flex;align-items:center;justify-content:space-between;gap:10px}.icon{width:52px;height:52px;display:grid;place-items:center;border-radius:16px;background:linear-gradient(135deg,rgba(139,124,255,.22),rgba(53,214,196,.13));font-size:1.6rem}
    .tag{font-size:.75rem;color:#b8f8ef;background:rgba(53,214,196,.1);border:1px solid rgba(53,214,196,.2);padding:4px 10px;border-radius:999px}
    .card h3{font-size:1.35rem;margin:17px 0 4px}.card p{color:var(--muted);margin:0 0 16px;font-size:.93rem}.features{display:flex;flex-wrap:wrap;gap:7px;margin:12px 0 19px}.features span{font-size:.77rem;padding:4px 9px;border-radius:8px;background:rgba(255,255,255,.06);color:#d6dcf2}
    .card-link{display:inline-flex;align-items:center;gap:7px;color:#bcb3ff;font-weight:700;font-size:.9rem}.card-link:hover{color:white}
    .how{margin:72px 0 50px;padding:28px;border:1px solid var(--line);border-radius:24px;background:rgba(255,255,255,.025)}
    .steps{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:20px}.step{padding:17px;border-radius:16px;background:rgba(255,255,255,.035)}.num{color:var(--b);font-weight:900;font-size:1.2rem}.step h3{margin:5px 0;font-size:1rem}.step p{margin:0;color:var(--muted);font-size:.87rem}
    .note{margin:24px 0 55px;padding:17px 20px;border-right:3px solid var(--b);background:rgba(53,214,196,.06);border-radius:12px;color:#c8d5e5;font-size:.9rem}
    footer{border-top:1px solid var(--line);padding:24px 0;color:var(--muted);font-size:.83rem;display:flex;justify-content:space-between;gap:12px;flex-wrap:wrap}
    @media(max-width:700px){nav{gap:12px;font-size:.8rem}.hero{padding:62px 0 45px}.cards{grid-template-columns:1fr}.steps{grid-template-columns:1fr}.section-head{display:block}.section-head p{margin-top:5px}}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <a class="brand" href="#">AI<span>Studio</span> ✦</a>
      <nav><a href="#tools">ابزارها</a><a href="#guide">راهنمای شروع</a><a href="#about">درباره پروژه</a></nav>
    </header>

    <main>
      <section class="hero">
        <span class="pill">✦ دنیای خلاقیت با هوش مصنوعی</span>
        <h1>ایده‌ات رو به <em>ویدیو</em> تبدیل کن</h1>
        <p class="intro">با ابزارهای هوش مصنوعی، از عکس شخصیت‌های سخنگو بساز، تصاویر رو متحرک کن و صحنه‌های سینمایی خلق کن. اینجا با چند ابزار محبوب آشنا می‌شی.</p>
        <div class="actions"><a class="btn primary" href="#tools">دیدن ابزارها ↓</a><a class="btn secondary" href="#guide">از کجا شروع کنم؟</a></div>
      </section>

      <section id="tools">
        <div class="section-head"><div><h2>ابزارهای پیشنهادی</h2><p>هر ابزار برای یک نوع خلاقیت ساخته شده است.</p></div></div>
        <div class="cards">
          <article class="card">
            <div class="card-top"><div class="icon">🎬</div><span class="tag">ویدیوسازی و انیمیشن</span></div>
            <h3>Kling AI</h3>
            <p>تبدیل متن یا تصویر به ویدیو و جان‌دادن به عکس‌ها با حرکت‌های طبیعی و صحنه‌های خلاقانه.</p>
            <div class="features"><span>عکس به ویدیو</span><span>متن به ویدیو</span><span>حرکت طبیعی</span></div>
            <a class="card-link" href="https://klingai.com/" target="_blank" rel="noopener">ورود به وب‌سایت رسمی ↗</a>
          </article>
          <article class="card">
            <div class="card-top"><div class="icon">🗣️</div><span class="tag">شخصیت سخنگو</span></div>
            <h3>Hedra</h3>
            <p>ساخت ویدیو از یک شخصیت که حرف می‌زند؛ مناسب برای کاراکترهای خیالی، آواتارها و ایده‌های داستانی.</p>
            <div class="features"><span>عکس سخنگو</span><span>هماهنگی لب و صدا</span><span>کاراکترسازی</span></div>
            <a class="card-link" href="https://www.hedra.com/" target="_blank" rel="noopener">ورود به وب‌سایت رسمی ↗</a>
          </article>
          <article class="card">
            <div class="card-top"><div class="icon">🌌</div><span class="tag">ساخت و ویرایش ویدیو</span></div>
            <h3>Runway</h3>
            <p>ساخت ویدیوهای خلاقانه با متن و تصویر و استفاده از ابزارهای هوشمند برای ویرایش و تغییر صحنه‌ها.</p>
            <div class="features"><span>تولید ویدیو</span><span>ویرایش هوشمند</span><span>صحنه سینمایی</span></div>
            <a class="card-link" href="https://runwayml.com/" target="_blank" rel="noopener">ورود به وب‌سایت رسمی ↗</a>
          </article>
          <article class="card">
            <div class="card-top"><div class="icon">🎙️</div><span class="tag">مجری و آواتار مجازی</span></div>
            <h3>HeyGen</h3>
            <p>ساخت آواتارهای سخنگو و ویدیوهای معرفی یا آموزشی با کمک متن، صدا و هماهنگی حرکت لب‌ها.</p>
            <div class="features"><span>آواتار هوشمند</span><span>متن به گفتار</span><span>ویدیوی آموزشی</span></div>
            <a class="card-link" href="https://www.heygen.com/" target="_blank" rel="noopener">ورود به وب‌سایت رسمی ↗</a>
          </article>
        </div>
      </section>

      <section class="how" id="guide">
        <div class="section-head"><div><h2>شروع کار در ۳ قدم</h2><p>برای اولین ویدیوی هوش مصنوعی‌ات این مسیر ساده رو امتحان کن.</p></div></div>
        <div class="steps">
          <div class="step"><span class="num">۰۱</span><h3>ایده‌ات رو انتخاب کن</h3><p>مثلاً یک حیوان سخنگو، شخصیت کارتونی یا یک منظره سینمایی.</p></div>
          <div class="step"><span class="num">۰۲</span><h3>ابزار مناسب رو باز کن</h3><p>برای شخصیت سخنگو Hedra و برای ساخت صحنه ویدیویی Kling یا Runway رو بررسی کن.</p></div>
          <div class="step"><span class="num">۰۳</span><h3>خروجی رو بررسی کن</h3><p>صدا، حرکت لب و کیفیت تصویر رو چک کن و اگر لازم بود دوباره بساز.</p></div>
        </div>
      </section>

      <div class="note">💡 نکته: امکانات، محدودیت استفاده و قیمت پلن‌ها ممکنه تغییر کنن. قبل از ثبت‌نام، شرایط هر سرویس رو در وب‌سایت رسمی بررسی کن. برای تصویر و صدای افراد واقعی هم حتماً رضایت و حریم خصوصی‌شون رو رعایت کن.</div>
    </main>

    <footer id="about"><span>© 2026 AI Studio — یک پروژه معرفی ابزارهای هوش مصنوعی</span><span>طراحی و توسعه: علی مهدی ✦</span></footer>
  </div>
</body>
</html>
