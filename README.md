[index.html](https://github.com/user-attachments/files/28808083/index.html)

<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Portfolio</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:Poppins,sans-serif}
html{scroll-behavior:smooth}
body{background:#000;color:#fff;overflow-x:hidden}
#bubbles{position:fixed;inset:0;z-index:0;pointer-events:none;overflow:hidden}
.bubble{position:absolute;border-radius:50%;background:rgba(255,255,255,.08);border:2px solid rgba(255,255,255,.22);box-shadow:0 0 20px rgba(255,255,255,.18),inset 0 0 18px rgba(255,255,255,.08);animation:up linear infinite}
@keyframes up{from{transform:translateY(120vh);opacity:.85}to{transform:translateY(-160vh);opacity:.05}}
.main{position:relative;z-index:2}
nav{position:fixed;top:0;left:0;right:0;padding:18px 6%;display:flex;justify-content:space-between;background:rgba(0,0,0,.35);backdrop-filter:blur(10px)}
nav a{color:#fff;text-decoration:none;margin-left:20px}
.hero{min-height:100vh;display:flex;align-items:center;justify-content:center;text-align:center;padding:120px 20px}
.hero h1{font-size:64px;max-width:900px}
.hero p{max-width:820px;color:#ddd;line-height:1.8;margin:22px auto}
.btn{display:inline-block;padding:15px 32px;margin:8px;border-radius:999px;border:1px solid rgba(255,255,255,.25);background:rgba(255,255,255,.05);color:#fff;text-decoration:none;transition:.35s}
.btn:hover{background:#fff;color:#000;transform:translateY(-5px) scale(1.05);box-shadow:0 0 25px rgba(255,255,255,.35)}
section{padding:95px 8%}
h2{text-align:center;font-size:42px;margin-bottom:35px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:24px}
.card{background:rgba(255,255,255,.05);border:1px solid rgba(255,255,255,.14);backdrop-filter:blur(8px);padding:24px;border-radius:18px;transition:.3s}
.card:hover{transform:translateY(-8px)}
.card p,li{color:#ddd;line-height:1.7}
.mock{height:210px;border-radius:16px;background:linear-gradient(135deg,#111,#222,#111);border:1px solid rgba(255,255,255,.14);display:flex;align-items:center;justify-content:center;font-size:28px;font-weight:700;margin-bottom:15px}
.stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:20px}
.stat{background:rgba(255,255,255,.05);border:1px solid rgba(255,255,255,.14);border-radius:16px;padding:22px;text-align:center}
.stat b{display:block;font-size:40px}
footer{text-align:center;padding:40px;color:#aaa}
</style>
</head>
<body>
<div id="bubbles"></div>
<div class="main">
<nav><b>Portfolio</b><div><a href="#sites">Sites</a><a href="#competences">Compétences</a><a href="#contact">Contact</a></div></nav>

<div class="hero">
<div>
<h1>Créer une image qui donne confiance.</h1>
<p>Nous sommes deux jeunes développeurs passionnés. Notre objectif est de créer des sites modernes, rapides et élégants à un prix accessible. Nous échangeons avec chaque client et proposons toujours deux idées avant le développement.</p>
<a class="btn" href="#sites">Découvrir nos réalisations</a>
<a class="btn" href="#contact">Travailler avec nous</a>
</div>
</div>

<section>
<h2>Pourquoi nous choisir ?</h2>
<div class="stats">
<div class="stat"><b>100€+</b>À partir de</div>
<div class="stat"><b>2</b>Propositions</div>
<div class="stat"><b>100%</b>Motivation</div>
<div class="stat"><b>7j/7</b>Disponibles</div>
</div>
</section>

<section id="sites">
<h2>Quelques réalisations</h2>
<div class="grid">
<div class="card">
<div class="mock">BLACK COFFEE</div>
<h3>Black Coffee</h3>
<p>Site vitrine moderne pour un café avec réservation, menu interactif, galerie et page événements. Design minimaliste noir et blanc et optimisation mobile.</p>
</div>
<div class="card">
<div class="mock">DRIVE AUTO</div>
<h3>Drive Auto</h3>
<p>Création d'un site pour un garage avec prise de rendez-vous, catalogue de véhicules, présentation des services et formulaire de devis.</p>
</div>
<div class="card">
<div class="mock">MAISON DESIGN</div>
<h3>Maison & Design</h3>
<p>Site élégant pour une entreprise de rénovation avec portfolio, avant/après, témoignages et demande de devis en ligne.</p>
</div>
</div>
</section>

<section id="competences">
<h2>Nos compétences</h2>
<div class="grid">
<div class="card">
<h3>Anis Marzouk</h3>
<ul>
<li>HTML / CSS</li>
<li>JavaScript</li>
<li>Animations modernes</li>
<li>Responsive Design</li>
<li>UI / UX</li>
</ul>
</div>
<div class="card">
<h3>Mathis Gaudar Saint‑Paul</h3>
<ul>
<li>JavaScript</li>
<li>PHP</li>
<li>Bases de données</li>
<li>Optimisation</li>
<li>Architecture de projet</li>
</ul>
</div>
<div class="card">
<h3>Ce que nous faisons ensemble</h3>
<ul>
<li>Création de sites vitrines</li>
<li>Refonte de sites existants</li>
<li>Design moderne et rapide</li>
<li>Accompagnement client</li>
<li>Deux propositions de maquette</li>
<li>Suivi après livraison</li>
</ul>
</div>
</div>
</section>

<section>
<h2>Notre méthode</h2>
<div class="grid">
<div class="card"><h3>1. Échange</h3><p>Nous discutons de votre activité et de vos objectifs.</p></div>
<div class="card"><h3>2. Proposition</h3><p>Nous réalisons deux idées de design pour vous laisser le choix.</p></div>
<div class="card"><h3>3. Développement</h3><p>Nous créons un site rapide, moderne et adapté à tous les écrans.</p></div>
</div>
</section>

<section id="contact">
<h2>Contact</h2>
<div class="grid">
<div class="card"><h3>Anis Marzouk</h3><p>marzoukanis847@gmail.com<br>06 35 55 55 68</p></div>
<div class="card"><h3>Mathis Gaudar Saint‑Paul</h3><p>mathis.gaudard.sp@gmail.com<br>07 69 17 52 00</p></div>
</div>
</section>

<footer>Jeunes • Motivés • Créatifs • Prêts à réaliser votre projet</footer>
</div>
<script>
const c=document.getElementById("bubbles");
for(let i=0;i<45;i++){
 let b=document.createElement("div");
 b.className="bubble";
 let s=30+Math.random()*120;
 b.style.width=s+"px";b.style.height=s+"px";
 b.style.left=Math.random()*100+"vw";
 b.style.top=Math.random()*100+"vh";
 b.style.animationDuration=(18+Math.random()*18)+"s";
 b.style.animationDelay=(-Math.random()*30)+"s";
 c.appendChild(b);
}
</script>
</body>
</html>
