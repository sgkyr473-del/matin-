# matin-





<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#070b14">
<title>DABIR NAB AI ULTIMATE</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Vazirmatn:wght@400;500;600;700;800&display=swap');

:root{
  --bg:#070b14;
  --panel:#0e1625;
  --panel2:#111e31;
  --blue:#168cff;
  --cyan:#47e2ff;
  --text:#eff7ff;
  --muted:#91a4bd;
  --border:#22334b;
  --green:#40e0a0;
  --red:#ff6078;
}
*{box-sizing:border-box;margin:0;padding:0}
body{
  background:radial-gradient(ellipse at 50% -20%,#173b68 0,transparent 50%),var(--bg);
  color:var(--text);
  font-family:Vazirmatn,Tahoma,sans-serif;
  min-height:100vh;
}
button,input,textarea,select{font:inherit}
button{cursor:pointer}
button:focus-visible,input:focus-visible,textarea:focus-visible,select:focus-visible{
  outline:2px solid var(--cyan);outline-offset:3px
}
header{
  height:72px;padding:0 5%;
  display:flex;align-items:center;justify-content:space-between;gap:15px;
  position:sticky;top:0;z-index:20;
  background:#070b14eF;backdrop-filter:blur(18px);
  border-bottom:1px solid var(--border)
}
.brand{display:flex;align-items:center;gap:11px;font-weight:800}
.logo{
  width:43px;height:43px;border-radius:14px;display:grid;place-items:center;
  background:linear-gradient(140deg,var(--blue),#1742a5);
  box-shadow:0 0 24px #168cff45;font-size:22px
}
.brand small{display:block;color:var(--cyan);font-size:10px;letter-spacing:1px}
.header-right{display:flex;align-items:center;gap:12px}
.pill{padding:7px 12px;border:1px solid var(--border);border-radius:30px;font-size:11px;color:var(--muted)}
.dot{color:var(--green)}
button{transition:.2s}
button:hover{filter:brightness(1.12)}
.app{display:grid;grid-template-columns:235px minmax(0,1fr);max-width:1500px;margin:auto}
aside{
  min-height:calc(100vh - 72px);padding:22px 14px;
  border-left:1px solid var(--border);
  background:#080d17aa
}
.side-label{font-size:10px;color:#627994;padding:10px 12px}
.nav{
  width:100%;display:flex;align-items:center;gap:12px;text-align:right;
  padding:12px;border:1px solid transparent;border-radius:12px;
  background:transparent;color:var(--muted);margin-bottom:5px;font-size:13px
}
.nav.active,.nav:hover{background:#168cff18;border-color:#168cff3c;color:white}
.nav .ico{width:24px;text-align:center;font-size:17px}
.side-bottom{margin-top:30px;border:1px solid var(--border);border-radius:15px;padding:14px;background:var(--panel)}
.side-bottom p{font-size:11px;line-height:2;color:var(--muted);margin-top:6px}
main{padding:28px;min-width:0}
.page{display:none;animation:fade .25s ease}
.page.active{display:block}
@keyframes fade{from{opacity:0;transform:translateY(5px)}to{opacity:1;transform:translateY(0)}}
.welcome{
  position:relative;overflow:hidden;padding:29px;border-radius:22px;
  background:linear-gradient(115deg,#102d50,#10182b 65%,#0c1321);
  border:1px solid #254a70
}
.welcome:after{
  content:"AI";position:absolute;left:35px;top:-38px;
  font-size:155px;font-weight:800;color:#ffffff08;pointer-events:none
}
.eyebrow{color:var(--cyan);font-size:11px;font-weight:700}
h1{font-size:clamp(24px,3.4vw,36px);line-height:1.7;margin:8px 0}
p{line-height:1.9}
.muted{color:var(--muted);font-size:13px}
.primary{
  background:linear-gradient(110deg,#0878e9,#19baff);color:white;
  border:0;border-radius:11px;padding:11px 16px;font-weight:700
}
.secondary{
  background:#ffffff08;color:#d9e9ff;border:1px solid var(--border);
  border-radius:11px;padding:10px 14px
}
.welcome-actions{display:flex;gap:10px;flex-wrap:wrap;margin-top:18px}
.section-head{display:flex;align-items:center;justify-content:space-between;gap:12px;margin:28px 0 15px}
.section-head h2{font-size:17px}
.section-head span{font-size:11px;color:var(--muted)}
.stats{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:13px;margin-top:18px}
.stat,.card,.surface{
  background:linear-gradient(145deg,#111d2e,#0b111d);
  border:1px solid var(--border);border-radius:17px;padding:18px;min-width:0
}
.stat .icon{font-size:21px}
.stat strong{display:block;font-size:24px;margin:10px 0 2px}
.stat small{color:var(--muted);font-size:11px}
.grid3{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:13px}
.card{transition:.22s}
.card:hover{transform:translateY(-3px);border-color:#277bc2}
.card-icon{font-size:27px;margin-bottom:14px}
.card h3{font-size:14px;margin-bottom:7px}
.card p{font-size:12px;color:var(--muted)}
.card button{margin-top:15px;width:100%}
.progress{height:6px;background:#1d2a3c;border-radius:20px;overflow:hidden;margin:12px 0}
.progress div{height:100%;background:linear-gradient(90deg,var(--blue),var(--cyan));border-radius:20px}
.select,input,textarea{
  width:100%;background:#080e18;border:1px solid #263a54;border-radius:11px;
  color:var(--text);padding:12px;outline:none
}
select option{background:#0e1625}
textarea{resize:vertical;min-height:90px}
label{font-size:12px;color:#c0d0e4;display:block;margin-bottom:7px}
.field{margin-bottom:15px}
.chat-layout{display:grid;grid-template-columns:minmax(0,1fr) 220px;gap:14px}
.chatbox{min-height:440px;display:flex;flex-direction:column}
.chat-title{padding-bottom:14px;border-bottom:1px solid var(--border)}
.messages{flex:1;min-height:280px;max-height:460px;overflow-y:auto;padding:18px 0;display:flex;flex-direction:column;gap:12px}
.msg{max-width:92%;padding:12px 14px;border-radius:13px;font-size:13px;line-height:2;white-space:pre-wrap;overflow-wrap:anywhere}
.msg.bot{align-self:flex-start;background:#142238;border:1px solid #263d5a}
.msg.user{align-self:flex-end;background:#0e4776;border:1px solid #267db8}
.composer{display:flex;gap:9px;align-items:flex-end}
.composer textarea{min-height:48px;max-height:120px}
.composer button{height:48px;min-width:70px}
.chips{display:flex;gap:7px;flex-wrap:wrap;margin-bottom:12px}
.chip{background:#111f31;color:#cde7ff;border:1px solid var(--border);border-radius:10px;padding:7px 10px;font-size:11px}
.chat-side button{width:100%;text-align:right;margin-top:7px}
.lesson{margin-top:12px}
.lesson h3{font-size:14px;margin-bottom:8px}
.lesson ul{padding-right:18px;color:var(--muted);font-size:12px;line-height:2.4}
.quiz-option{
  display:block;width:100%;text-align:right;margin-top:9px;padding:12px;
  background:#0b1421;color:var(--text);border:1px solid var(--border);border-radius:10px
}
.quiz-option:hover{border-color:var(--blue)}
.quiz-option:disabled{cursor:default;opacity:1}
.quiz-option.correct{border-color:var(--green);background:#123729}
.quiz-option.wrong{border-color:var(--red);background:#3b1824}
.note-list{display:grid;gap:10px;margin-top:16px}
.note{padding:13px;border:1px solid var(--border);border-radius:12px;background:#0b1320}
.note p{font-size:13px;white-space:pre-wrap;overflow-wrap:anywhere}
.note small{display:block;color:var(--muted);margin-top:7px}
.note button{margin-top:9px}
.empty{padding:25px;text-align:center;color:var(--muted);font-size:13px}
footer{border-top:1px solid var(--border);padding:22px;text-align:center;color:var(--muted);font-size:11px;line-height:2.2}
.hidden{display:none!important}
@media(max-width:1050px){
 .stats{grid-template-columns:repeat(2,minmax(0,1fr))}
 .grid3{grid-template-columns:repeat(2,minmax(0,1fr))}
 .chat-layout{grid-template-columns:1fr}
 .chat-side{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:7px}
 .chat-side h3{grid-column:1/-1}
 .chat-side button{margin:0}
}
@media(max-width:760px){
 header{height:64px;padding:0 14px}
 .brand{font-size:13px}.logo{width:37px;height:37px}
 .pill{font-size:10px;padding:6px 8px}
 .app{display:block}
 aside{
   min-height:auto;position:sticky;top:64px;z-index:15;
   padding:8px;display:flex;gap:5px;overflow-x:auto;
   border-left:0;border-bottom:1px solid var(--border)
 }
 .side-label,.side-bottom{display:none}
 .nav{width:auto;flex:0 0 auto;margin:0;padding:9px 11px;font-size:11px;gap:6px}
 .nav .ico{font-size:15px}
 main{padding:15px}
 .welcome{padding:21px}
 .stats{gap:9px}
 .stat,.card{padding:13px}
 .grid3{grid-template-columns:1fr}
 .section-head{margin-top:23px}
 .chat-side{grid-template-columns:repeat(2,minmax(0,1fr))}
}
</style>
</head>

<body>
<header>
  <div class="brand">
    <div class="logo">ن</div>
    <div>دبیر ناب <span style="color:var(--cyan)">AI</span>
      <small>ULTIMATE LEARNING SYSTEM</small>
    </div>
  </div>
  <div class="header-right">
    <div class="pill"><span class="dot">●</span> سامانه آموزشی</div>
    <div class="pill" id="headerGrade">پایه دهم</div>
  </div>
</header>

<div class="app">
<aside>
  <div class="side-label">منوی اصلی</div>
  <button class="nav active" data-page="home"><span class="ico">⌂</span> داشبورد</button>
  <button class="nav" data-page="ai"><span class="ico">✧</span> دستیار AI</button>
  <button class="nav" data-page="courses"><span class="ico">▤</span> آموزش کامپیوتر</button>
  <button class="nav" data-page="quiz"><span class="ico">◎</span> آزمون هوشمند</button>
  <button class="nav" data-page="notes"><span class="ico">▧</span> دفتر یادداشت</button>
  <button class="nav" data-page="profile"><span class="ico">◉</span> پروفایل من</button>

  <div class="side-bottom">
    <div style="color:var(--cyan);font-weight:700">✦ یادگیری روزانه</div>
    <p>هر روز یک موضوع جدید یاد بگیر و تمرین کن.</p>
  </div>
</aside>

<main>
<!-- DASHBOARD -->
<section class="page active" id="page-home">
  <div class="welcome">
    <div class="eyebrow">SMART EDUCATION • نسخه ویژه</div>
    <h1>آینده‌ات را با دانش <span style="color:var(--cyan)">بساز.</span></h1>
    <p class="muted">یک محیط آموزشی برای یادگیری کامپیوتر، برنامه‌نویسی و آمادگی امتحانات.</p>
    <div class="welcome-actions">
      <button class="primary" onclick="showPage('ai')">شروع گفت‌وگو با AI ←</button>
      <button class="secondary" onclick="showPage('courses')">مشاهده درس‌ها</button>
    </div>
  </div>

  <div class="stats">
    <div class="stat"><div class="icon">📚</div><strong id="statNotes">0</strong><small>یادداشت ذخیره‌شده</small></div>
    <div class="stat"><div class="icon">🎯</div><strong id="statQuiz">0</strong><small>آزمون انجام‌شده</small></div>
    <div class="stat"><div class="icon">⚡</div><strong id="statPoints">0</strong><small>امتیاز تمرین‌ها</small></div>
    <div class="stat"><div class="icon">💻</div><strong id="statGrade">دهم</strong><small>پایه تحصیلی</small></div>
  </div>

  <div class="section-head"><h2>مرکز یادگیری</h2><span>دسترسی سریع</span></div>
  <div class="grid3">
    <div class="card"><div class="card-icon">🤖</div><h3>دستیار آموزشی</h3><p>سؤال بپرس و مفاهیم را مرحله‌به‌مرحله تمرین کن.</p><button class="secondary" onclick="showPage('ai')">ورود به دستیار</button></div>
    <div class="card"><div class="card-icon">🧠</div><h3>آزمون کامپیوتر</h3><p>دانسته‌هایت را با سؤال‌های چهارگزینه‌ای بررسی کن.</p><button class="secondary" onclick="showPage('quiz')">شروع آزمون</button></div>
    <div class="card"><div class="card-icon">📝</div><h3>دفتر یادداشت</h3><p>نکات مهم درسی را ذخیره کن تا بعداً مرور کنی.</p><button class="secondary" onclick="showPage('notes')">بازکردن دفتر</button></div>
  </div>

  <div class="section-head"><h2>مسیر آموزشی پیشنهادی</h2><span>مقدماتی تا پیشرفته</span></div>
  <div class="surface">
    <div style="display:flex;justify-content:space-between;gap:10px"><strong style="font-size:13px">مبانی کامپیوتر</strong><span class="muted">مرحله ۱</span></div>
    <div class="progress"><div style="width:30%"></div></div>
    <p class="muted">با سخت‌افزار، نرم‌افزار، سیستم‌عامل و شیوه پردازش اطلاعات آشنا شو.</p>
    <button class="primary" onclick="openLesson('computer')">شروع درس</button>
  </div>
</section>

<!-- AI -->
<section class="page" id="page-ai">
  <div class="section-head" style="margin-top:0"><h2>✧ دستیار آموزشی DABIR NAB AI</h2><span>حالت نمایشی</span></div>
  <div class="chat-layout">
    <div class="surface chatbox">
      <div class="chat-title"><strong>گفت‌وگوی آموزشی</strong><p class="muted" id="chatInfo">پایه دهم • کامپیوتر</p></div>
      <div class="messages" id="messages" aria-live="polite">
        <div class="msg bot">به دبیر ناب AI خوش آمدی.

می‌توانی درباره کامپیوتر، الگوریتم، برنامه‌نویسی، شبکه و امنیت اطلاعات سؤال بپرسی.

برای پاسخ هوشمند واقعی، اتصال API لازم است؛ پاسخ‌های این نسخه نمایشی هستند.</div>
      </div>
      <div class="chips">
        <button class="chip" onclick="quickAsk('کامپیوتر چیست؟')">کامپیوتر چیست؟</button>
        <button class="chip" onclick="quickAsk('الگوریتم را توضیح بده')">الگوریتم</button>
        <button class="chip" onclick="quickAsk('HTML چیست؟')">HTML</button>
        <button class="chip" onclick="quickAsk('یک آزمون تمرینی بساز')">آزمون تمرینی</button>
      </div>
      <div class="composer">
        <textarea id="chatInput" rows="1" placeholder="سؤال خود را بنویس..."></textarea>
        <button class="primary" id="sendButton" onclick="sendChat()">ارسال</button>
      </div>
      <p class="muted" style="font-size:10px;margin-top:10px">اطلاعات مهم شخصی یا رمزهای عبور را در چت وارد نکن.</p>
    </div>
    <div class="surface chat-side">
      <h3 style="font-size:14px">ابزارهای سریع</h3>
      <button class="secondary" onclick="quickAsk('CPU چه کاری انجام می‌دهد؟')">⚙️ سخت‌افزار</button>
      <button class="secondary" onclick="quickAsk('متغیر در برنامه‌نویسی چیست؟')">⌨️ برنامه‌نویسی</button>
      <button class="secondary" onclick="quickAsk('شبکه کامپیوتری چیست؟')">🌐 شبکه</button>
      <button class="secondary" onclick="quickAsk('اصول امنیت اطلاعات را توضیح بده')">🛡️ امنیت</button>
      <button class="secondary" onclick="quickAsk('برای امتحان کامپیوتر چگونه مطالعه کنم؟')">📖 برنامه مطالعه</button>
    </div>
  </div>
</section>

<!-- COURSES -->
<section class="page" id="page-courses">
  <div class="section-head" style="margin-top:0"><h2>💻 آکادمی کامپیوتر</h2><span>پایه‌های دهم تا دوازدهم</span></div>
  <div class="field">
    <label for="courseGrade">پایه تحصیلی</label>
    <select id="courseGrade" onchange="changeGrade(this.value)">
      <option value="دهم">پایه دهم</option>
      <option value="یازدهم">پایه یازدهم</option>
      <option value="دوازدهم">پایه دوازدهم</option>
    </select>
  </div>
  <div class="grid3" id="courseGrid"></div>
  <div class="surface lesson hidden" id="lessonDetail">
    <h3 id="lessonTitle">عنوان درس</h3>
    <div id="lessonBody" class="muted"></div>
    <button class="primary" style="margin-top:15px" onclick="askAboutLesson()">تمرین این درس با دستیار AI</button>
  </div>
</section>

<!-- QUIZ -->
<section class="page" id="page-quiz">
  <div class="section-head" style="margin-top:0"><h2>🧠 مرکز آزمون</h2><span>آزمون تمرینی</span></div>
  <div class="surface">
    <div id="quizStart">
      <div style="font-size:40px">🎯</div>
      <h3 style="margin:12px 0">چالش دانش کامپیوتر</h3>
      <p class="muted">به ۵ سؤال چهارگزینه‌ای پاسخ بده. در پایان، امتیازت نمایش داده می‌شود.</p>
      <button class="primary" onclick="startQuiz()">شروع آزمون</button>
    </div>
    <div id="quizGame" class="hidden">
      <div class="progress"><div id="quizProgress" style="width:0%"></div></div>
      <p class="muted" id="quizCount"></p>
      <h3 id="quizQuestion" style="margin-top:12px;font-size:17px"></h3>
      <div id="quizOptions" style="margin-top:12px"></div>
      <p id="quizFeedback" class="muted" style="margin-top:12px"></p>
      <button id="quizNext" class="primary hidden" onclick="nextQuestion()">سؤال بعدی ←</button>
    </div>
    <div id="quizResult" class="hidden">
      <div style="font-size:40px">🏆</div>
      <h3 style="margin:12px 0">نتیجه آزمون</h3>
      <p id="quizScore" style="font-size:24px;color:var(--cyan)"></p>
      <p id="quizMessage" class="muted"></p>
      <button class="primary" onclick="startQuiz()">تکرار آزمون</button>
    </div>
  </div>
</section>

<!-- NOTES -->
<section class="page" id="page-notes">
  <div class="section-head" style="margin-top:0"><h2>📝 دفتر یادداشت من</h2><span>ذخیره روی همین دستگاه</span></div>
  <div class="surface">
    <div class="field"><label for="noteTitle">عنوان یادداشت</label><input id="noteTitle" maxlength="80" placeholder="مثلاً نکات مهم HTML"></div>
    <div class="field"><label for="noteText">متن یادداشت</label><textarea id="noteText" maxlength="5000" placeholder="نکات درسی خود را اینجا بنویس..."></textarea></div>
    <button class="primary" onclick="saveNote()">ذخیره یادداشت</button>
    <p class="muted" style="margin-top:10px;font-size:11px">یادداشت‌ها با ذخیره‌سازی محلی مرورگر نگهداری می‌شوند.</p>
  </div>
  <div class="note-list" id="noteList"></div>
</section>

<!-- PROFILE -->
<section class="page" id="page-profile">
  <div class="section-head" style="margin-top:0"><h2>◉ پروفایل دانش‌آموز</h2></div>
  <div class="surface">
    <div class="field"><label for="studentName">نام نمایشی</label><input id="studentName" maxlength="50" placeholder="نام خود را وارد کن"></div>
    <div class="field"><label for="profileGrade">پایه تحصیلی</label>
      <select id="profileGrade">
        <option value="دهم">دهم</option>
        <option value="یازدهم">یازدهم</option>
        <option value="دوازدهم">دوازدهم</option>
      </select>
    </div>
    <button class="primary" onclick="saveProfile()">ذخیره پروفایل</button>
  </div>
  <div class="surface" style="margin-top:14px">
    <h3 style="margin-bottom:10px">درباره پروژه</h3>
    <p class="muted">نام سامانه: دبیر ناب AI ULTIMATE</p>
    <p class="muted">سازنده: محمد متین آرام‌تن</p>
    <p class="muted">محدوده فعالیت: بخش شیب‌کوه، استان فارس</p>
    <p class="muted">هدف: پشتیبانی آموزشی برای دانش‌آموزان پایه‌های دهم، یازدهم و دوازدهم.</p>
  </div>
</section>
</main>
</div>

<footer>
  <strong style="color:var(--cyan)">DABIR NAB AI ULTIMATE</strong><br>
  سازنده: محمد متین آرام‌تن | بخش شیب‌کوه، استان فارس<br>
  نسخه نمایشی آموزشی • برای پاسخ هوشمند واقعی به اتصال امن بک‌اند نیاز است.
</footer>

<script>
const $ = id => document.getElementById(id);
const safeStore = {
  get(key, fallback) {
    try {
      const value = localStorage.getItem(key);
      return value === null ? fallback : JSON.parse(value);
    } catch (e) { return fallback; }
  },
  set(key, value) {
    try {
      localStorage.setItem(key, JSON.stringify(value));
      return true;
    } catch (e) {
      alert("ذخیره‌سازی در مرورگر در دسترس نیست.");
      return false;
    }
  }
};

let grade = safeStore.get("dn_grade", "دهم");
let student = safeStore.get("dn_student", "");
let points = safeStore.get("dn_points", 0);
let quizCount = safeStore.get("dn_quiz_count", 0);
let notes = safeStore.get("dn_notes", []);
let currentLesson = null;
let quizIndex = 0, quizCorrect = 0, quizLocked = false;

const courses = {
  "دهم": [
    ["مبانی کامپیوتر","آشنایی با اجزای اصلی رایانه.","computer"],
    ["سخت‌افزار و نرم‌افزار","تفاوت قطعات فیزیکی و برنامه‌ها.","hardware"],
    ["سیستم‌عامل","مدیریت فایل، پوشه و برنامه‌ها.","os"],
    ["الگوریتم","حل مسئله به کمک مراحل منطقی.","algorithm"],
    ["اینترنت و امنیت","آشنایی با وب و حفاظت از اطلاعات.","security"],
    ["مقدمات برنامه‌نویسی","ورودی، خروجی و منطق برنامه.","programming"]
  ],
  "یازدهم": [
    ["متغیرها و داده‌ها","ذخیره و استفاده از اطلاعات.","variables"],
    ["شرط‌ها و حلقه‌ها","کنترل مسیر اجرای برنامه.","conditions"],
    ["HTML و CSS","ساختار و ظاهر صفحات وب.","html"],
    ["شبکه‌های کامپیوتری","ارتباط میان دستگاه‌ها.","network"],
    ["پایگاه داده","آشنایی با ذخیره‌سازی اطلاعات.","database"],
    ["الگوریتم و فلوچارت","طراحی مرحله‌به‌مرحله راه‌حل.","algorithm"]
  ],
  "دوازدهم": [
    ["توابع","تقسیم برنامه به بخش‌های قابل استفاده مجدد.","functions"],
    ["SQL مقدماتی","کار با داده‌ها و پرس‌وجوها.","sql"],
    ["JavaScript","افزودن رفتار تعاملی به وب.","javascript"],
    ["مبانی هوش مصنوعی","مدل‌ها، داده‌ها و کاربردهای AI.","ai"],
    ["امنیت سایبری","اصول دفاع از حساب‌ها و داده‌ها.","security"],
    ["پروژه عملی","ترکیب دانش در یک پروژه کوچک.","project"]
  ]
};

const lessonData = {
  computer: ["مبانی کامپیوتر",
    "کامپیوتر دستگاهی الکترونیکی است که داده‌ها را طبق دستور پردازش می‌کند.\n\nمراحل کلی:\n۱. دریافت ورودی\n۲. پردازش داده‌ها توسط پردازنده\n۳. نگهداری داده‌ها در حافظه\n۴. ارائه خروجی\n\nمثال: صفحه‌کلید ورودی، CPU پردازش و نمایشگر خروجی را فراهم می‌کند."],
  hardware: ["سخت‌افزار و نرم‌افزار",
    "سخت‌افزار بخش‌های فیزیکی مانند CPU، RAM، صفحه‌کلید و نمایشگر است.\n\nنرم‌افزار مجموعه دستورهایی است که روی رایانه اجرا می‌شود؛ مانند سیستم‌عامل و مرورگر.\n\nتمرین: سه نمونه سخت‌افزار و دو نمونه نرم‌افزار نام ببر."],
  os: ["سیستم‌عامل",
    "سیستم‌عامل منابع رایانه را مدیریت می‌کند و رابطی میان کاربر، برنامه‌ها و سخت‌افزار است.\n\nنمونه‌ها: Windows، Linux و Android.\n\nتمرین: تفاوت فایل و پوشه را توضیح بده."],
  algorithm: ["الگوریتم",
    "الگوریتم مجموعه‌ای مرتب از مراحل برای حل یک مسئله است.\n\nمثال جمع دو عدد:\n۱. دریافت عدد اول\n۲. دریافت عدد دوم\n۳. جمع دو عدد\n۴. نمایش نتیجه\n\nالگوریتم باید روشن، محدود و دارای ترتیب منطقی باشد."],
  security: ["امنیت اطلاعات",
    "برای محافظت از اطلاعات:\n۱. رمز عبور قوی و متفاوت استفاده کن.\n۲. تأیید دومرحله‌ای را فعال کن.\n۳. پیوندهای مشکوک را باز نکن.\n۴. نرم‌افزارها را به‌روز نگه دار.\n۵. از اطلاعات مهم نسخه پشتیبان بگیر."],
  programming: ["مقدمات برنامه‌نویسی",
    "برنامه‌نویسی یعنی نوشتن دستورهایی برای انجام کار توسط رایانه.\n\nمفاهیم اولیه:\n• ورودی: اطلاعاتی که دریافت می‌شود.\n• پردازش: عملیات روی داده‌ها.\n• خروجی: نتیجه عملیات.\n• متغیر: محلی برای نگهداری مقدار."],
  variables: ["متغیرها و داده‌ها",
    "متغیر نامی برای دسترسی به یک مقدار در برنامه است. نوع داده می‌تواند عدد، متن یا مقدار منطقی باشد.\n\nمثال JavaScript:\nlet age = 16;\nlet name = 'Ali';\n\nمقدار متغیر می‌تواند با اجرای برنامه تغییر کند."],
  conditions: ["شرط‌ها و حلقه‌ها",
    "شرط اجازه می‌دهد برنامه بر اساس یک وضعیت تصمیم بگیرد. حلقه برای تکرار دستورها استفاده می‌شود.\n\nمثال:\nif (score >= 10) {\n  console.log('قبول');\n}\n\nحلقه‌ها برای انجام کارهای تکراری مفیدند."],
  html: ["HTML و CSS",
    "HTML ساختار محتوای صفحه وب را مشخص می‌کند و CSS ظاهر آن را تنظیم می‌کند.\n\nنمونه HTML:\n<h1>سلام دنیا</h1>\n<p>این اولین صفحه من است.</p>\n\nنمونه CSS:\nh1 { color: blue; }\n\nبرای تعامل با صفحه از JavaScript استفاده می‌شود."],
  network: ["شبکه‌های کامپیوتری",
    "شبکه امکان ارتباط دستگاه‌ها و اشتراک اطلاعات را فراهم می‌کند.\n\nLAN معمولاً یک محیط محلی را پوشش می‌دهد؛ WAN محدوده وسیع‌تری دارد. اینترنت نمونه‌ای از شبکه بسیار گسترده است.\n\nتمرین: مودم و روتر چه کاربردی دارند؟"],
  database: ["پایگاه داده",
    "پایگاه داده روشی سازمان‌یافته برای نگهداری و بازیابی اطلاعات است.\n\nدر یک جدول، ردیف‌ها معمولاً رکورد و ستون‌ها ویژگی‌ها را نشان می‌دهند.\n\nSQL زبانی برای پرس‌وجو و مدیریت بسیاری از پایگاه‌های داده رابطه‌ای است."],
  functions: ["توابع",
    "تابع بخش مستقلی از کد است که می‌توان آن را برای انجام یک کار فراخوانی کرد.\n\nمثال JavaScript:\nfunction sum(a, b) {\n  return a + b;\n}\n\nتابع بالا مجموع دو مقدار را برمی‌گرداند."],
  sql: ["SQL مقدماتی",
    "SQL برای کار با پایگاه داده‌های رابطه‌ای استفاده می‌شود.\n\nنمونه:\nSELECT name FROM students;\n\nاین دستور ستون name را از جدول students انتخاب می‌کند. برای اجرا باید پایگاه داده و جدول مناسب وجود داشته باشند."],
  javascript: ["JavaScript",
    "JavaScript به صفحات وب امکان تعامل می‌دهد؛ مانند بررسی فرم، تغییر محتوا و پاسخ به کلیک‌ها.\n\nمثال:\nconst button = document.querySelector('button');\nbutton.addEventListener('click', () => alert('سلام!'));\n\nاین نمونه هنگام کلیک روی دکمه پیام نشان می‌دهد."],
  ai: ["مبانی هوش مصنوعی",
    "هوش مصنوعی به روش‌هایی گفته می‌شود که به سیستم‌ها امکان انجام وظایفی مانند تشخیص الگو، تولید متن یا پاسخ‌گویی می‌دهد.\n\nکیفیت پاسخ مدل‌ها تضمین‌شده نیست؛ اطلاعات مهم را بررسی کن و داده‌های شخصی را وارد سرویس‌های ناشناس نکن."],
  project: ["پروژه عملی",
    "یک پروژه کوچک با سه مرحله شروع کن:\n۱. مسئله را تعریف کن.\n۲. رابط کاربری و منطق برنامه را طراحی کن.\n۳. آن را آزمایش و خطاهایش را اصلاح کن.\n\nپروژه پیشنهادی: دفتر یادداشت درسی با HTML، CSS و JavaScript."]
};

function showPage(name) {
  document.querySelectorAll(".page").forEach(p => p.classList.remove("active"));
  const target = $("page-" + name);
  if (target) target.classList.add("active");
  document.querySelectorAll(".nav").forEach(b => b.classList.toggle("active", b.dataset.page === name));
  window.scrollTo({top:0,behavior:"smooth"});
  if (name === "courses") renderCourses();
  if (name === "notes") renderNotes();
}
document.querySelectorAll(".nav").forEach(b => b.addEventListener("click", () => showPage(b.dataset.page)));

function changeGrade(value) {
  grade = value;
  safeStore.set("dn_grade", grade);
  $("headerGrade").textContent = "پایه " + grade;
  $("statGrade").textContent = grade;
  $("profileGrade").value = grade;
  $("chatInfo").textContent = `پایه ${grade} • آموزش کامپیوتر`;
  renderCourses();
}

function renderCourses() {
  const grid = $("courseGrid");
  grid.replaceChildren();
  (courses[grade] || courses["دهم"]).forEach(item => {
    const article = document.createElement("article");
    article.className = "card";
    const icon = document.createElement("div");
    icon.className = "card-icon";
    icon.textContent = "▣";
    const title = document.createElement("h3");
    title.textContent = item[0];
    const desc = document.createElement("p");
    desc.textContent = item[1];
    const button = document.createElement("button");
    button.className = "secondary";
    button.textContent = "مشاهده درس";
    button.addEventListener("click", () => openLesson(item[2]));
    article.append(icon,title,desc,button);
    grid.appendChild(article);
  });
}

function openLesson(key) {
  const data = lessonData[key];
  if (!data) return;
  currentLesson = {key, title:data[0], body:data[1]};
  $("lessonTitle").textContent = data[0];
  $("lessonBody").textContent = data[1];
  $("lessonDetail").classList.remove("hidden");
  $("lessonDetail").scrollIntoView({behavior:"smooth",block:"nearest"});
}
function askAboutLesson() {
  if (!currentLesson) return;
  showPage("ai");
  $("chatInput").value = `درس «${currentLesson.title}» را در سطح پایه ${grade} بیشتر توضیح بده و سه تمرین ارائه کن.`;
  $("chatInput").focus();
}

function addMessage(type,text) {
  const div = document.createElement("div");
  div.className = "msg " + type;
  div.textContent = text;
  $("messages").appendChild(div);
  $("messages").scrollTop = $("messages").scrollHeight;
}
function quickAsk(text) {
  $("chatInput").value = text;
  sendChat();
}
function answerLocal(text) {
  const q = text.toLowerCase();
  if (q.includes("کامپیوتر چیست")) return lessonData.computer[1];
  if (q.includes("الگوریتم")) return lessonData.algorithm[1];
  if (q.includes("html")) return lessonData.html[1];
  if (q.includes("شبکه")) return lessonData.network[1];
  if (q.includes("امنیت")) return lessonData.security[1];
  if (q.includes("متغیر")) return lessonData.variables[1];
  if (q.includes("cpu")) return "CPU یا واحد پردازش مرکزی دستورهای برنامه را اجرا می‌کند و عملیات محاسباتی و منطقی را انجام می‌دهد.\n\nRAM حافظه موقت برای داده‌های موردنیاز برنامه‌های در حال اجراست.";
  if (q.includes("امتحان") || q.includes("آزمون")) return "برای آمادگی امتحان:\n۱. مفاهیم اصلی را مرور کن.\n۲. مثال‌های هر درس را خودت حل کن.\n۳. پاسخ‌ها را بدون نگاه‌کردن به کتاب بنویس.\n۴. اشتباه‌ها را یادداشت و دوباره تمرین کن.\n\nبرای آزمون چهارگزینه‌ای سایت، از منوی آزمون هوشمند استفاده کن.";
  if (q.includes("برنامه‌نویسی") || q.includes("برنامه نویسی")) return lessonData.programming[1];
  if (q.includes("هوش مصنوعی")) return lessonData.ai[1];
  return `سؤال شما دریافت شد.\n\nموضوع: ${text}\nپایه: ${grade}\n\nاین نسخه به مدل هوش مصنوعی آنلاین متصل نیست؛ پاسخ‌های موجود محدود به نمونه‌های آموزشی هستند. برای پاسخ‌گویی آزاد و دقیق، باید API از طریق یک بک‌اند امن راه‌اندازی شود.`;
}
function sendChat() {
  const input = $("chatInput");
  const text = input.value.trim();
  if (!text) return;
  addMessage("user",text);
  input.value = "";
  $("sendButton").disabled = true;
  $("sendButton").textContent = "...";
  setTimeout(() => {
    addMessage("bot",answerLocal(text));
    $("sendButton").disabled = false;
    $("sendButton").textContent = "ارسال";
  },250);
}
$("chatInput").addEventListener("keydown",e => {
  if(e.key==="Enter" && !e.shiftKey){e.preventDefault();sendChat();}
});

const questions = [
  {q:"CPU چه وظیفه‌ای دارد؟",o:["پردازش دستورها و داده‌ها","چاپ کاغذ","ذخیره دائمی همه فایل‌ها","اتصال فیزیکی مانیتور"],a:0},
  {q:"HTML بیشتر برای چه کاری است؟",o:["مدیریت برق رایانه","ساختار صفحات وب","ویرایش سیستم‌عامل","ساخت قطعات سخت‌افزاری"],a:1},
  {q:"کدام مورد یک سیستم‌عامل است؟",o:["HTML","CSS","Linux","SQL"],a:2},
  {q:"الگوریتم چیست؟",o:["نوعی نمایشگر","مجموعه مراحل حل مسئله","یک حافظه فیزیکی","نوعی کابل شبکه"],a:1},
  {q:"کدام رفتار امنیتی بهتر است؟",o:["استفاده از یک رمز برای همه حساب‌ها","بازکردن هر پیوند ناشناس","خاموش‌کردن همه به‌روزرسانی‌ها","فعال‌کردن تأیید دومرحله‌ای"],a:3}
];
function startQuiz() {
  quizIndex=0;quizCorrect=0;quizLocked=false;
  $("quizStart").classList.add("hidden");
  $("quizResult").classList.add("hidden");
  $("quizGame").classList.remove("hidden");
  renderQuestion();
}
function renderQuestion() {
  quizLocked=false;
  const q=questions[quizIndex];
  $("quizCount").textContent=`سؤال ${quizIndex+1} از ${questions.length}`;
  $("quizProgress").style.width=(quizIndex/questions.length*100)+"%";
  $("quizQuestion").textContent=q.q;
  $("quizFeedback").textContent="";
  $("quizNext").classList.add("hidden");
  const options=$("quizOptions");
  options.replaceChildren();
  q.o.forEach((option,index)=>{
    const btn=document.createElement("button");
    btn.className="quiz-option";
    btn.textContent=String.fromCharCode(1575+index)+") "+option;
    btn.addEventListener("click",()=>chooseAnswer(index,btn));
    options.appendChild(btn);
  });
}
function chooseAnswer(index,button) {
  if(quizLocked)return;
  quizLocked=true;
  const q=questions[quizIndex];
  [...$("quizOptions").children].forEach((btn,i)=>{
    btn.disabled=true;
    if(i===q.a)btn.classList.add("correct");
  });
  if(index===q.a){
    quizCorrect++;
    button.classList.add("correct");
    $("quizFeedback").textContent="پاسخ درست است.";
  }else{
    button.classList.add("wrong");
    $("quizFeedback").textContent="این پاسخ درست نیست؛ گزینه سبزرنگ پاسخ صحیح است.";
  }
  $("quizNext").textContent=quizIndex===questions.length-1?"مشاهده نتیجه":"سؤال بعدی ←";
  $("quizNext").classList.remove("hidden");
}
function nextQuestion() {
  if(quizIndex<questions.length-1){
    quizIndex++;
    renderQuestion();
    return;
  }
  $("quizGame").classList.add("hidden");
  $("quizResult").classList.remove("hidden");
  $("quizProgress").style.width="100%";
  const score=Math.round(quizCorrect/questions.length*100);
  $("quizScore").textContent=`${quizCorrect} از ${questions.length} • ${score}%`;
  $("quizMessage").textContent=score>=80?"عملکرد خوبی داشتی؛ برای یادگیری بیشتر ادامه بده.":"درس‌ها را مرور کن و دوباره آزمون بده.";
  quizCount++;
  points+=quizCorrect*10;
  safeStore.set("dn_quiz_count",quizCount);
  safeStore.set("dn_points",points);
  updateStats();
}

function saveNote() {
  const title=$("noteTitle").value.trim();
  const text=$("noteText").value.trim();
  if(!title||!text){alert("عنوان و متن یادداشت را وارد کن.");return;}
  notes.unshift({id:Date.now(),title,text,date:new Date().toLocaleDateString("fa-IR")});
  if(!safeStore.set("dn_notes",notes))return;
  $("noteTitle").value="";
  $("noteText").value="";
  renderNotes();
  updateStats();
}
function renderNotes() {
  const list=$("noteList");
  list.replaceChildren();
  if(!notes.length){
    const empty=document.createElement("div");
    empty.className="surface empty";
    empty.textContent="هنوز یادداشتی ذخیره نکرده‌ای.";
    list.appendChild(empty);
    return;
  }
  notes.forEach(note=>{
    const box=document.createElement("article");
    box.className="note";
    const title=document.createElement("strong");
    title.textContent=note.title;
    const body=document.createElement("p");
    body.textContent=note.text;
    const date=document.createElement("small");
    date.textContent="تاریخ: "+note.date;
    const del=document.createElement("button");
    del.className="secondary";
    del.textContent="حذف یادداشت";
    del.addEventListener("click",()=>{
      if(!confirm("این یادداشت حذف شود؟"))return;
      notes=notes.filter(n=>n.id!==note.id);
      safeStore.set("dn_notes",notes);
      renderNotes();updateStats();
    });
    box.append(title,body,date,del);
    list.appendChild(box);
  });
}
function saveProfile() {
  student=$("studentName").value.trim();
  if(!safeStore.set("dn_student",student))return;
  changeGrade($("profileGrade").value);
  alert("تنظیمات پروفایل در همین مرورگر ذخیره شد.");
}
function updateStats() {
  $("statNotes").textContent=notes.length;
  $("statQuiz").textContent=quizCount;
  $("statPoints").textContent=points;
  $("statGrade").textContent=grade;
}
function init() {
  $("courseGrade").value=grade;
  $("profileGrade").value=grade;
  $("studentName").value=student;
  changeGrade(grade);
  renderNotes();
  updateStats();
}
init();
</script>
</body>
</html>
