<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">

<title>معماری و راز جاودانگی</title>

<link href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Vazirmatn',sans-serif;
}

body{
background:#0d1117;
color:white;
overflow-x:hidden;
}

.hero{
min-height:100vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
padding:40px;
background:
radial-gradient(circle at top,#6d28d9 0%,transparent 40%),
radial-gradient(circle at bottom,#2563eb 0%,transparent 40%),
#0d1117;
}

.hero-content{
max-width:900px;
}

.badge{
display:inline-block;
padding:10px 20px;
border:1px solid rgba(255,255,255,.15);
background:rgba(255,255,255,.05);
backdrop-filter:blur(20px);
border-radius:100px;
margin-bottom:25px;
}

h1{
font-size:clamp(3rem,8vw,6rem);
line-height:1.1;
margin-bottom:20px;
}

.subtitle{
font-size:1.3rem;
opacity:.8;
line-height:2;
max-width:700px;
margin:auto;
}

.buttons{
margin-top:40px;
display:flex;
gap:15px;
justify-content:center;
flex-wrap:wrap;
}

.btn{
padding:15px 30px;
border-radius:15px;
text-decoration:none;
font-weight:600;
transition:.3s;
}

.primary{
background:linear-gradient(135deg,#7c3aed,#2563eb);
color:white;
}

.secondary{
border:1px solid rgba(255,255,255,.15);
color:white;
}

.btn:hover{
transform:translateY(-4px);
}

.section{
max-width:1200px;
margin:auto;
padding:120px 25px;
}

.section-title{
font-size:2.5rem;
margin-bottom:50px;
text-align:center;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
}

.card{
background:rgba(255,255,255,.04);
border:1px solid rgba(255,255,255,.08);
backdrop-filter:blur(20px);
padding:30px;
border-radius:25px;
transition:.3s;
}

.card:hover{
transform:translateY(-10px);
}

.card h3{
margin-bottom:15px;
}

.featured{
background:linear-gradient(135deg,#1f2937,#111827);
padding:50px;
border-radius:35px;
text-align:center;
}

.featured h2{
font-size:3rem;
margin-bottom:20px;
}

.featured p{
max-width:700px;
margin:auto;
opacity:.8;
line-height:2;
}

.team{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
}

.member{
padding:25px;
border-radius:20px;
background:#161b22;
text-align:center;
}

.member img{
width:80px;
height:80px;
border-radius:50%;
margin-bottom:15px;
}

footer{
padding:80px 20px;
text-align:center;
opacity:.7;
}

</style>
</head>

<body>

<section class="hero">

<div class="hero-content">

<div class="badge">
🎙️ پروژه جمعی خوانش کتاب
</div>

<h1>
معماری و راز جاودانگی
</h1>

<p class="subtitle">

هر اپیزود توسط یک نفر خوانده می‌شود.

تجربه‌ای جمعی برای خواندن، شنیدن و اندیشیدن درباره یکی از مهم‌ترین کتاب‌های معماری معاصر.

</p>

<div class="buttons">
<a href="#" class="btn primary">🎧 آخرین اپیزود</a>
<a href="#" class="btn secondary">📚 همه اپیزودها</a>
</div>

</div>

</section>

<section class="section">

<div class="featured">

<h2>اپیزود اول</h2>

<p>

مقدمه کتاب و مفهوم جاودانگی در معماری

راوی: نام خواننده

مدت: ۳۲ دقیقه

</p>

</div>

</section>

<section class="section">

<h2 class="section-title">
📖 فصل‌های کتاب
</h2>

<div class="cards">

<div class="card">
<h3>فصل اول</h3>
<p>کیفیت بی‌نام</p>
</div>

<div class="card">
<h3>فصل دوم</h3>
<p>نظم و زندگی</p>
</div>

<div class="card">
<h3>فصل سوم</h3>
<p>الگوها و معنا</p>
</div>

<div class="card">
<h3>فصل چهارم</h3>
<p>معماری زنده</p>
</div>

</div>

</section>

<section class="section">

<h2 class="section-title">
👥 مشارکت‌کنندگان
</h2>

<div class="team">

<div class="member">
<h3>نام راوی</h3>
<p>اپیزود ۱</p>
</div>

<div class="member">
<h3>نام راوی</h3>
<p>اپیزود ۲</p>
</div>

<div class="member">
<h3>نام راوی</h3>
<p>اپیزود ۳</p>
</div>

<div class="member">
<h3>نام راوی</h3>
<p>اپیزود ۴</p>
</div>

</div>

</section>

<footer>

🏛️ Architecture & The Timeless Way of Building

<br><br>

ساخته شده توسط جامعه خوانندگان کتاب

</footer>

</body>
</html>