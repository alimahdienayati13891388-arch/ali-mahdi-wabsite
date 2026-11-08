<!--DOCTYPE html-->
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#071124"><meta name="description" content="وب‌سایت شخصی علی مهدی؛ علاقه‌مند به برنامه‌نویسی، کامپیوتر و هوش مصنوعی.">
<title>علی مهدی | دنیای فناوری</title>
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
<style>
:root{--bg:#071124;--mint:#62edc5;--mint2:#8bf5d8;--text:#f4f7ff;--muted:#aab7cc;--line:rgba(183,207,241,.15)}
*{box-sizing:border-box}html{scroll-behavior:smooth;scroll-padding-top:95px}
body{margin:0;background:radial-gradient(ellipse at 80% 20%,rgba(39,104,155,.28),transparent 38%),radial-gradient(ellipse at 12% 75%,rgba(44,204,177,.10),transparent 32%),var(--bg);color:var(--text);font-family:"Vazirmatn",Tahoma,sans-serif;overflow-x:hidden}
a{color:inherit;text-decoration:none}.wrap{width:min(1120px,calc(100% - 42px));margin:auto}
.topbar{position:sticky;top:0;z-index:20;background:rgba(7,17,36,.78);backdrop-filter:blur(18px);border-bottom:1px solid var(--line)}
.nav{height:82px;display:flex;align-items:center;justify-content:space-between;gap:20px}
.brand{font-size:24px;font-weight:900;letter-spacing:.4px;direction:ltr}.brand span{color:var(--mint)}
.navlinks{display:flex;gap:27px;color:var(--muted);font-size:14px}.navlinks a:hover{color:var(--mint)}
.menu-wrap{position:relative}.menu-btn{width:48px;height:48px;border:1px solid rgba(139,245,216,.38);border-radius:50%;background:rgba(119,238,207,.10);backdrop-filter:blur(12px);display:grid;place-items:center;cursor:pointer;transition:.25s;box-shadow:0 0 28px rgba(98,237,197,.09)}
.menu-btn:hover,.menu-btn[aria-expanded=true]{background:rgba(98,237,197,.22);transform:rotate(90deg);box-shadow:0 0 25px rgba(98,237,197,.2)}
.dots{display:flex;gap:4px}.dots i{width:4px;height:4px;border-radius:50%;background:var(--mint);display:block}
.dropdown{position:absolute;top:60px;left:0;width:205px;padding:9px;background:rgba(13,27,49,.94);border:1px solid rgba(139,245,216,.23);border-radius:18px;box-shadow:0 20px 55px #0008;backdrop-filter:blur(20px);opacity:0;visibility:hidden;transform:translateY(-8px);transition:.22s}
.dropdown.open{opacity:1;visibility:visible;transform:translateY(0)}.dropdown a{display:flex;gap:10px;padding:12px 13px;border-radius:12px;color:#dce7f6;font-size:14px}.dropdown a:hover{background:rgba(98,237,197,.12);color:var(--mint)}
.hero{min-height:690px;display:grid;grid-template-columns:1.1fr .9fr;align-items:center;gap:35px;padding:75px 0 55px}
.eyebrow{display:inline-flex;align-items:center;gap:10px;padding:10px 17px;border:1px solid rgba(98,237,197,.3);background:rgba(98,237,197,.07);border-radius:50px;color:var(--mint2);font-size:14px}
.pulse{width:9px;height:9px;background:var(--mint);border-radius:50%;box-shadow:0 0 0 6px rgba(98,237,197,.12);animation:pulse 1.8s infinite}
h1{font-size:clamp(37px,5vw,66px);line-height:1.45;margin:27px 0 17px;font-weight:900}h1 em{font-style:normal;color:var(--mint)}
.intro{font-size:18px;line-height:2.1;color:var(--muted);max-width:650px;margin:0 0 29px}
.actions{display:flex;gap:13px;flex-wrap:wrap}.btn{padding:14px 22px;border-radius:16px;font-weight:800;display:inline-flex;align-items:center;gap:10px;transition:.25s;border:1px solid var(--line)}
.btn.primary{background:linear-gradient(120deg,var(--mint),#79bfff);color:#071124;border:0}.btn.secondary{background:rgba(255,255,255,.035)}.btn:hover{transform:translateY(-4px);box-shadow:0 12px 30px #0003}
.visual{min-height:410px;display:grid;place-items:center;position:relative}.orbit{width:min(350px,78vw);aspect-ratio:1;border:1px solid rgba(154,190,235,.25);border-radius:50%;display:grid;place-items:center;position:relative;animation:float 6s ease-in-out infinite}
.orbit:before,.orbit:after{content:"";position:absolute;border:1px solid rgba(154,190,235,.13);border-radius:50%;inset:22px}.orbit:after{inset:-22px}
.monogram{width:72%;aspect-ratio:1;border-radius:34% 34% 42% 42%;background:linear-gradient(135deg,#5cebc0,#78b9ff);display:grid;place-items:center;color:#071124;font-size:clamp(75px,12vw,130px);font-weight:900;direction:ltr;box-shadow:0 25px 75px rgba(67,205,193,.2)}
.float-tag{position:absolute;padding:12px 18px;border:1px solid rgba(183,207,241,.17);background:rgba(17,30,52,.9);backdrop-filter:blur(15px);border-radius:17px;color:#dce7f6;font-size:17px;box-shadow:0 15px 40px #0003}.tag1{top:10%;right:-3%}.tag2{bottom:10%;left:-3%}.spark{position:absolute;width:13px;height:13px;border-radius:50%;background:var(--mint);right:5%;bottom:20%;box-shadow:0 0 20px var(--mint)}
section.content{padding:70px 0;border-top:1px solid var(--line)}.section-head{margin-bottom:28px}.kicker{color:var(--mint);font-size:13px;font-weight:800}.section-head h2{font-size:32px;margin:8px 0}.section-head p{color:var(--muted);line-height:1.9;margin:0}
.cards{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}.card{padding:24px;border:1px solid var(--line);border-radius:22px;background:linear-gradient(145deg,rgba(24,42,68,.72),rgba(12,25,45,.62));transition:.25s}.card:hover{transform:translateY(-6px);border-color:rgba(98,237,197,.42)}.icon{font-size:27px}.card h3{margin:12px 0 8px}.card p{color:var(--muted);line-height:1.9;margin:0;font-size:14px}.project-link{display:inline-flex;margin-top:16px;padding:8px 14px;border-radius:11px;background:rgba(98,237,197,.10);border:1px solid rgba(98,237,197,.25);color:var(--mint);font-size:13px;font-weight:800;transition:.2s}.project-link:hover{background:rgba(98,237,197,.2);transform:translateY(-2px)}
.skills{display:flex;flex-wrap:wrap;gap:11px}.skill{padding:10px 16px;border-radius:50px;border:1px solid rgba(98,237,197,.22);background:rgba(98,237,197,.06);color:#c8f9e9}
.contact{display:flex;justify-content:space-between;align-items:center;gap:20px;padding:28px;border-radius:24px;border:1px solid rgba(98,237,197,.22);background:linear-gradient(110deg,rgba(98,237,197,.10),rgba(120,185,255,.08))}
.contact p{color:var(--muted);margin:6px 0 0}.email{direction:ltr;color:var(--mint);font-weight:700;overflow-wrap:anywhere}
footer{padding:25px 0;color:#7f8da5;text-align:center;border-top:1px solid var(--line);font-size:13px}
.reveal{opacity:0;transform:translateY(22px);transition:.7s}.reveal.show{opacity:1;transform:none}
@keyframes pulse{50%{box-shadow:0 0 0 10px rgba(98,237,197,0)}}@keyframes float{50%{transform:translateY(-13px) rotate(2deg)}}
@media(max-width:760px){.wrap{width:min(100% - 30px,560px)}.nav{height:70px}.navlinks{display:none}.hero{grid-template-columns:1fr;text-align:center;padding:55px 0 35px;gap:12px}.eyebrow{font-size:13px}h1{margin-top:22px}.intro{font-size:16px;margin-inline:auto}.actions{justify-content:center}.visual{min-height:350px}.orbit{width:275px}.float-tag{font-size:14px}.tag1{right:0}.tag2{left:0}.cards{grid-template-columns:1fr}.contact{align-items:flex-start;flex-direction:column}.section-head h2{font-size:27px}}
@media(prefers-reduced-motion:reduce){*,*:before,*:after{animation:none!important;scroll-behavior:auto!important;transition:none!important}}
</style>
</head>
<body>
<header class="topbar"><div class="wrap nav">
<a class="brand" href="#home">ALI <span>MAHDI</span><span style="color:#fff">.</span></a>
<nav class="navlinks"><a href="#about">درباره من</a><a href="#skills">مهارت‌ها</a><a href="#projects">نمونه‌کارها</a><a href="#contact">ارتباط</a></nav>
<div class="menu-wrap"><button class="menu-btn" id="menuBtn" aria-label="باز کردن منو" aria-expanded="false" aria-controls="dropdown"><span class="dots"><i></i><i></i><i></i></span></button>
<div class="dropdown" id="dropdown"><a href="#about">👤 درباره من</a><a href="#skills">⚡ مهارت‌ها</a><a href="#projects">🧩 نمونه‌کارها</a><a href="#contact">✉️ ارتباط با من</a></div></div>
</div></header>
<main id="home"><div class="wrap hero">
<div class="reveal"><div class="eyebrow"><span class="pulse"></span> دانش‌آموز کامپیوتر و علاقه‌مند به فناوری</div>
<h1>سلام، من<br><em>علی مهدی</em> هستم.</h1>
<p class="intro">به دنیای کامپیوتر، برنامه‌نویسی و هوش مصنوعی علاقه دارم. اینجا فضای من برای معرفی مهارت‌هایی است که یاد می‌گیرم و پروژه‌هایی که با علاقه می‌سازم.</p>
<div class="actions"><a class="btn primary" href="#about">بیشتر درباره من <span>←</span></a><a class="btn secondary" href="#projects">مشاهده نمونه‌کارها</a></div></div>
<div class="visual reveal"><div class="orbit"><div class="monogram">AM</div></div><div class="float-tag tag1">💡 یادگیری مداوم</div><div class="float-tag tag2">🤖 هوش مصنوعی</div><span class="spark"></span></div>
</div>
<section class="content" id="about"><div class="wrap reveal"><div class="section-head"><span class="kicker">01 / ABOUT</span><h2>درباره من</h2><p>من علی مهدی هستم؛ دانش‌آموز رشته کامپیوتر و علاقه‌مند به ساختن چیزهای تازه با فناوری. هدفم یادگیری عمیق، تجربه‌کردن ایده‌ها و تبدیل آن‌ها به پروژه‌های کاربردی است.</p></div></div></section>
<section class="content" id="skills"><div class="wrap reveal"><div class="section-head"><span class="kicker">02 / SKILLS</span><h2>مهارت‌ها و مسیر یادگیری</h2><p>مهارت‌هایی که در حال یادگیری و تقویت آن‌ها هستم.</p></div><div class="skills"><span class="skill">Python</span><span class="skill">HTML</span><span class="skill">CSS</span><span class="skill">JavaScript</span><span class="skill">هوش مصنوعی</span><span class="skill">Microsoft Word</span><span class="skill">Excel</span><span class="skill">PowerPoint</span></div></div></section>
<section class="content" id="projects"><div class="wrap reveal"><div class="section-head"><span class="kicker">03 / PROJECTS</span><h2>نمونه‌کارها و ایده‌ها</h2><p>این بخش برای نمایش پروژه‌هایی است که می‌سازم و به‌مرور تکمیل می‌کنم.</p></div>
<div class="cards"><article class="card"><div class="icon">🌐</div><h3>طراحی وب‌سایت</h3><p>ساخت صفحه‌های وب با HTML، CSS و JavaScript و تمرکز بر طراحی واکنش‌گرا.</p></article><article class="card"><div class="icon">📊</div><h3>ابزارهای کاربردی</h3><p>ساخت جدول‌ها و ابزارهای ساده برای مدیریت اطلاعات و انجام کارهای روزمره.</p></article><article class="card"><div class="icon">🤖</div><h3>هوش مصنوعی</h3><p>یادگیری مفاهیم هوش مصنوعی و بررسی ایده‌هایی برای پروژه‌های آینده.</p></article><article class="card"><div class="icon">🎬</div><h3>AI Studio</h3><p>معرفی ابزارهای هوش مصنوعی برای ساخت ویدیو، شخصیت‌های سخنگو و انیمیشن.</p><a class="project-link" href="ai_studio_project.html" target="_blank" rel="noopener">مشاهده پروژه ↗</a></article></div></div></section>
<section class="content" id="contact"><div class="wrap reveal"><div class="contact"><div><span class="kicker">04 / CONTACT</span><h2 style="margin:7px 0">در ارتباط باشیم</h2><p>برای پیام و پیشنهاد همکاری می‌توانی از طریق ایمیل با من در ارتباط باشی.</p></div><a class="email" href="mailto:alimahdienayati13881389@gmail.com">alimahdienayati13881389@gmail.com</a></div></div></section>
</main>
<footer><div class="wrap">ساخته‌شده با علاقه به فناوری · علی مهدی © <span id="year"></span></div></footer>
<script>
const menuBtn=document.getElementById('menuBtn'),dropdown=document.getElementById('dropdown');
menuBtn.addEventListener('click',()=>{const open=dropdown.classList.toggle('open');menuBtn.setAttribute('aria-expanded',String(open));});
dropdown.querySelectorAll('a').forEach(a=>a.addEventListener('click',()=>{dropdown.classList.remove('open');menuBtn.setAttribute('aria-expanded','false');}));
document.addEventListener('click',e=>{if(!e.target.closest('.menu-wrap')){dropdown.classList.remove('open');menuBtn.setAttribute('aria-expanded','false');}});
document.getElementById('year').textContent=new Date().getFullYear();
const observer=new IntersectionObserver(entries=>entries.forEach(entry=>{if(entry.isIntersecting){entry.target.classList.add('show');observer.unobserve(entry.target);}}),{threshold:.12});
document.querySelectorAll('.reveal').forEach(el=>observer.observe(el));
</script>
</body></html>
<!DOCTYPE html>
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
