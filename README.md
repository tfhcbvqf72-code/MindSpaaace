# MindSpaaace
Creative MindSpace
```html
<!DOCTYPE html>
<html lang="sq">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>MindSpace</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f4f6fc;
    color:#1e2b4d;
}

/* HEADER */

header{
    background:#0f2d7a;
    color:white;
    padding:20px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:32px;
    font-weight:bold;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
    font-size:18px;
}

.btn{
    background:white;
    color:#0f2d7a;
    padding:12px 20px;
    border-radius:10px;
    text-decoration:none;
    font-weight:bold;
}

/* HERO */

.hero{
    width:90%;
    margin:40px auto;
    background:#e8edff;
    border-radius:25px;
    padding:60px;
    display:flex;
    justify-content:space-between;
    align-items:center;
    flex-wrap:wrap;
}

.hero-text{
    width:50%;
}

.hero-text h1{
    font-size:65px;
    margin-bottom:25px;
}

.hero-text span{
    color:#4d63ff;
}

.hero-text p{
    font-size:22px;
    line-height:1.7;
    margin-bottom:30px;
}

.buttons a{
    text-decoration:none;
    padding:15px 28px;
    border-radius:12px;
    margin-right:15px;
    font-size:18px;
}

.primary{
    background:#3559ff;
    color:white;
}

.secondary{
    border:2px solid #3559ff;
    color:#3559ff;
}

.hero-image{
    width:40%;
    text-align:center;
    font-size:180px;
}

/* SECTIONS */

.section{
    width:90%;
    margin:35px auto;
    background:#e8edff;
    border-radius:25px;
    padding:50px;
}

.section h2{
    text-align:center;
    color:#12337f;
    font-size:45px;
    margin-bottom:30px;
}

.section p{
    text-align:center;
    font-size:21px;
    line-height:1.8;
}

/* FEATURES */

.features{
    display:flex;
    justify-content:center;
    gap:25px;
    flex-wrap:wrap;
    margin-top:40px;
}

.feature-box{
    background:white;
    width:250px;
    padding:30px;
    border-radius:18px;
    text-align:center;
    box-shadow:0 0 10px rgba(0,0,0,0.08);
}

.feature-box h3{
    color:#2144a6;
    margin:15px 0;
}

/* STATS */

.stats{
    display:flex;
    justify-content:space-around;
    flex-wrap:wrap;
    text-align:center;
    margin-top:30px;
}

.stat h3{
    color:#3559ff;
    font-size:42px;
}

.stat p{
    font-size:18px;
}

/* FOOTER */

footer{
    background:#0f2d7a;
    color:white;
    text-align:center;
    padding:30px;
    margin-top:50px;
}

footer a{
    color:white;
    text-decoration:none;
}

/* RESPONSIVE */

@media(max-width:900px){

.hero{
    text-align:center;
}

.hero-text{
    width:100%;
}

.hero-image{
    width:100%;
    margin-top:30px;
}

.hero-text h1{
    font-size:45px;
}

}

</style>
</head>

<body>

<header>

<div class="logo">🧠 MindSpace</div>

<nav>
    <a href="#">Kreu</a>
    <a href="#">Rreth Nesh</a>
    <a href="#">Komuniteti</a>
    <a href="#">Sfida</a>
    <a href="#">Projekte</a>
    <a href="#">Kontakt</a>
</nav>

<a href="#" class="btn">Regjistrohu</a>

</header>

<!-- HERO -->

<section class="hero">

<div class="hero-text">

<h1>
Hapësira juaj <span>kreative</span>,
idetë bëhen realitet.
</h1>

<p>
MindSpace është komuniteti i të rinjve kreativë.
Ndaj ide, krijo projekte dhe frymëzo të tjerët.
</p>

<div class="buttons">
<a href="#" class="primary">Bëhu pjesë</a>
<a href="#" class="secondary">Shiko projektet</a>
</div>

</div>

<div class="hero-image">
💡
</div>

</section>

<!-- ABOUT -->

<section class="section">

<h2>Qëllimi i faqes</h2>

<p>
Qëllimi i faqes “MindSpace” është të krijojë një hapësirë online ku të rinjtë
mund të ndajnë ide kreative, të shprehin mendimet e tyre dhe të zhvillojnë
aftësitë në fusha si arti, teknologjia dhe komunikimi.
Faqja synon të nxisë kreativitetin dhe bashkëpunimin mes përdoruesve.
</p>

</section>

<!-- FEATURES -->

<section class="section">

<h2>Çfarë ofron MindSpace?</h2>

<div class="features">

<div class="feature-box">
<h3>👤 Profile personale</h3>
<p>Krijo profilin dhe prezanto talentin tënd.</p>
</div>

<div class="feature-box">
<h3>🎨 Projekte kreative</h3>
<p>Publiko ide, dizajne, foto dhe video.</p>
</div>

<div class="feature-box">
<h3>💬 Komunitet aktiv</h3>
<p>Komento dhe bashkëpuno me të tjerët.</p>
</div>

<div class="feature-box">
<h3>🏆 Sfida javore</h3>
<p>Merr pjesë në sfida kreative çdo javë.</p>
</div>

</div>

</section>

<!-- COMMUNITY -->

<section class="section">

<h2>Komuniteti ynë</h2>

<div class="stats">

<div class="stat">
<h3>1,250+</h3>
<p>Anëtarë aktivë</p>
</div>

<div class="stat">
<h3>3,400+</h3>
<p>Projekte kreative</p>
</div>

<div class="stat">
<h3>120+</h3>
<p>Sfida të realizuara</p>
</div>

<div class="stat">
<h3>850+</h3>
<p>Përdorues të vlerësuar</p>
</div>

</div>

</section>

<!-- PUBLISH -->

<section class="section">

<h2>Publikimi i faqes</h2>

<p>
Kjo faqe është publikuar përmes platformës GitHub Pages.
Kështu, përdoruesit mund të kenë akses të lehtë dhe të shpejtë online.
</p>

<br><br>

<p>
<b>https://www.mindspace-creative.com</b>
</p>

</section>

<footer>

<p>
©️ 2026 MindSpace | Të gjitha të drejtat e rezervuara
</p>

</footer>

</body>
</html>
```
