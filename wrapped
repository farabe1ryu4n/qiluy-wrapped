<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Qiluy Wrapped 2026</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;900&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:Poppins,sans-serif}
body{background:#0b1020;color:#fff;overflow-x:hidden}
.slide{
height:100vh;padding:40px;display:flex;flex-direction:column;
justify-content:center;align-items:center;text-align:center;
scroll-snap-align:start;
}
.container{scroll-snap-type:y mandatory;overflow-y:auto;height:100vh}
.s1,.s7{background:linear-gradient(135deg,#2563eb,#dc2626)}
.s2,.s4,.s6{background:#111827}
.s3{background:linear-gradient(180deg,#1e3a8a,#111827)}
.s5{background:linear-gradient(135deg,#7f1d1d,#1d4ed8)}
h1{font-size:clamp(3rem,8vw,6rem);font-weight:900}
h2{font-size:clamp(2rem,5vw,3rem);margin-bottom:20px}
.cardwrap{display:flex;gap:20px;flex-wrap:wrap;justify-content:center}
.card{width:280px;background:rgba(255,255,255,.08);padding:15px;border-radius:20px}
.photo{width:100%;height:220px;object-fit:cover;border-radius:15px}
.progress{position:fixed;top:0;left:0;height:6px;background:#fff;width:0;z-index:999}
.btn{padding:14px 28px;border:none;border-radius:999px;font-weight:700;cursor:pointer}
.stats{font-size:5rem;font-weight:900}
.form{width:min(500px,90%)}
input,textarea{width:100%;padding:12px;margin:8px 0;border-radius:12px;border:none}
.wish{background:#1f2937;padding:12px;border-radius:12px;margin:8px auto;max-width:500px;text-align:left}
.small{opacity:.8}
</style>
</head>
<body>
<div class="progress" id="progress"></div>

<div class="container" id="container">

<section class="slide s1">
<p>SPOTIFY WRAPPED STYLE</p>
<h1>QILUY</h1>
<h2>15 Years Wrapped</h2>
<p>Lahir 06 November 2011 🎧</p>
</section>

<section class="slide s2">
<h2>Your Most Played Memories</h2>
<div class="cardwrap">
<div class="card"><img src="foto1.jpg" class="photo"><h3>Moment #1</h3></div>
<div class="card"><img src="foto2.jpg" class="photo"><h3>Moment #2</h3></div>
<div class="card"><img src="foto3.jpg" class="photo"><h3>Moment #3</h3></div>
</div>
<p class="small">Ganti foto1.jpg, foto2.jpg, foto3.jpg dengan fotomu.</p>
</section>

<section class="slide s3">
<h2>By The Numbers</h2>
<div class="stats">5479+</div>
<p>Hari hidup dan banyak kenangan yang tercipta.</p>
</section>

<section class="slide s4">
<h2>My Favorite People</h2>
<p>Tambahkan nama teman-teman terbaikmu di sini.</p>
<div class="cardwrap">
<div class="card">🥇 Teman 1</div>
<div class="card">🥈 Teman 2</div>
<div class="card">🥉 Teman 3</div>
</div>
</section>

<section class="slide s5">
<h2>A Message From Qiluy</h2>
<p style="max-width:800px">
Hai semuanya. Terima kasih sudah hadir dalam hidupku selama 15 tahun ini.
Aku menghargai setiap cerita, tawa, dan kenangan yang kita buat bersama.
Semoga kita bisa terus berteman dan membuat banyak cerita baru.
❤️
</p>
</section>

<section class="slide s6">
<h2>Leave Your Wishes</h2>
<div class="form">
<input id="name" placeholder="Nama">
<textarea id="msg" placeholder="Ucapan untuk Qiluy"></textarea>
<button class="btn" onclick="addWish()">Kirim 🎂</button>
</div>
<div id="wishes"></div>
</section>

<section class="slide s7">
<h1>Thanks For Listening</h1>
<h2>Qiluy Wrapped 2026</h2>
<p>More memories coming soon ✨</p>
</section>

</div>

<script>
const c=document.getElementById('container');
const p=document.getElementById('progress');
c.addEventListener('scroll',()=>{
const h=c.scrollHeight-c.clientHeight;
p.style.width=((c.scrollTop/h)*100)+'%';
});

function addWish(){
const n=document.getElementById('name').value;
const m=document.getElementById('msg').value;
if(!n||!m)return;
const d=document.createElement('div');
d.className='wish';
d.innerHTML='<b>'+n+'</b><br>'+m;
document.getElementById('wishes').prepend(d);
document.getElementById('name').value='';
document.getElementById('msg').value='';
}
</script>
</body>
</html>
