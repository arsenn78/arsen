<!DOCTYPE html>
<html lang="kk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Шерхан Мұртаза — Қазақ әдебиетінің шежіресі</title>
<style>
:root{
  --black:#0b0b0b;
  --gold:#d4af37;
  --bg-dark:#121212;
  --bg-light:#1a1a1a;
  --text:#f3f3f3;
  --muted:#cfcfcf;
  --maxw:1000px;
}
*{box-sizing:border-box;}
body{
  margin:0;
  font-family: system-ui, -apple-system, 'Segoe UI', Roboto, Arial, sans-serif;
  background: linear-gradient(180deg,var(--bg-dark),#0f0f10);
  color: var(--text);
}
header{
  background: var(--black);
  padding: 20px;
  text-align: center;
  border-bottom: 4px solid var(--gold);
}
header h1{
  margin:0;
  font-size: 32px;
  color: var(--gold);
}
main{
  max-width: var(--maxw);
  margin: 30px auto;
  padding: 0 15px;
  display: grid;
  gap: 20px;
}
section{
  background: var(--bg-light);
  padding: 25px;
  border-radius: 12px;
  box-shadow: 0 6px 20px rgba(0,0,0,0.6);
  transition: transform 0.3s;
}
section:hover{
  transform: translateY(-4px);
}
section h2{
  color: var(--gold);
  margin-top:0;
  font-size:24px;
}
section p, section li{
  color: var(--muted);
  font-size:16px;
}
a.button{
  display:inline-block;
  margin-top:12px;
  padding:10px 18px;
  border-radius:10px;
  background: linear-gradient(90deg,var(--gold),#b58f2a);
  color: var(--black);
  font-weight:600;
  text-decoration:none;
  cursor:pointer;
  transition: transform 0.2s;
}
a.button:hover{
  transform: scale(1.05);
}
footer{
  text-align:center;
  padding:20px;
  background: var(--black);
  border-top: 2px solid rgba(212,175,55,0.2);
  font-size:14px;
  color: var(--muted);
}
ul{padding-left:20px;}
.hidden{display:none;}
</style>
</head>
<body>

<header>
  <h1>Шерхан Мұртаза</h1>
  <p style="color:var(--muted);margin:5px 0;">Қазақ әдебиетінің шежіресі</p>
</header>

<!-- Негізгі бөлімдер -->
<main id="main-content">
  <section>
    <h2>Өмірбаяны</h2>
    <p>Шерхан Мұртаза — XX ғасырдың екінші жартысы мен XXI ғасыр басындағы көрнекті қазақ жазушысы, қоғам қайраткері және аудармашы. Ол қазақ халқының рухани дүниесін, ел тағдырын, әділет пен ар-ождан мәселелерін өз шығармаларында терең суреттеді.</p>
  </section>

  <section>
    <h2>Шығармалары</h2>
    <p>Жазушының шығармаларының ішінде "Қызыл жебе", "Бесеудің хаты", "Ай мен Айша" сияқты туындылары кеңінен танылған. Оның еңбектері қазақ әдебиетінде жаңа ой мен қоғамдық сана қалыптастырды.</p>
  </section>

  <section>
    <h2>«Қызыл жебе» — талдау</h2>
    <p>«Қызыл жебе» шығармасы — Шерхан Мұртазаның ең танымал туындысы. Онда халық тағдыры, әділет пен ерлік, туған жерге деген сүйіспеншілік терең бейнеленеді.</p>
    <a class="button" onclick="showDetail()">Толығырақ оқу</a>
  </section>

  <section>
    <h2>Марапаттары</h2>
    <p>Шерхан Мұртаза Қазақстанның Халық жазушысы атағына ие болып, көптеген әдеби және мемлекеттік сыйлықтармен марапатталған.</p>
  </section>

  <section>
    <h2>Дереккөздер</h2>
    <p>Материалдар ашық әдеби және ғылыми дереккөздер негізінде дайындалды.</p>
  </section>

  <section>
    <h2>Байланыс</h2>
    <p>Егер сұрақтарыңыз болса немесе қосымша ақпарат қажет болса, төмендегі байланыс арқылы хабарласа аласыз:</p>
    <ul>
      <li>Аты-жөні: <strong>Тимирбеков Арсен</strong></li>
      <li>Email: <strong>arsentwmirbekov@gmail.com</strong></li>
      <li>Оқу орны: <strong>ALT University</strong></li>
    </ul>
  </section>
</main>

<!-- Толығырақ оқу бөлімдері -->
<main id="detail-content" class="hidden">
  <section>
    <h2>«Қызыл жебе» — Толық талдау</h2>
    <p>Бұл шығармада Тұрар Рысқұлов бейнесі арқылы ел тағдыры мен әділет жолындағы күрес суреттеледі. Автор жеке адамның тағдыры арқылы тұтас халықтың өмірін бейнелейді.</p>
  </section>
  <section>
    <h2>Негізгі тақырыптар</h2>
    <ul>
      <li>Ерлік пен батырлық</li>
      <li>Әділет пен адалдық</li>
      <li>Махаббат пен намыс</li>
      <li>Халық тағдыры және ел бірлігі</li>
    </ul>
  </section>
  <section>
    <h2>Қорытынды</h2>
    <p>«Қызыл жебе» — тек әдеби шығарма ғана емес, ұлт рухының айнасы. Ол оқырманға адамгершілік, батылдық және елге қызмет етудің мәнін ұқтырады.</p>
    <a class="button" onclick="showMain()">Басты бетке қайту</a>
  </section>
</main>

<footer>
  © 2025. «Шерхан Мұртаза — Қазақ әдебиетінің шежіресі». Барлық құқықтар қорғалған.
</footer>

<script>
function showDetail() {
  document.getElementById('main-content').classList.add('hidden');
  document.getElementById('detail-content').classList.remove('hidden');
  window.scrollTo(0,0);
}
function showMain() {
  document.getElementById('detail-content').classList.add('hidden');
  document.getElementById('main-content').classList.remove('hidden');
  window.scrollTo(0,0);
}
</script>

</body>
</html>
