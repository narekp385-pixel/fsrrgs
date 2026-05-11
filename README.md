
<html lang="hy">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=0.5">

<style>

body{
    margin:0;
    font-family:Arial;
    background:#f2f2f2;
}

nav{
    background:#1b5e20;
    padding:10px;
    text-align:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:8px;
    font-size:15px;
}

.section{
    background:white;
    margin:12px;
    padding:15px;
    border-radius:12px;
}

.section img{
    width:100%;
    border-radius:10px;
}

h2{
    color:#2e7d32;
}

p{
    font-size:16px;
    line-height:1.6;
}

.qr{
    text-align:center;
    background:white;
    margin:12px;
    padding:15px;
    border-radius:12px;
}

.qr img{
    width:160px;
}

footer{
    background:#2e7d32;
    color:white;
    text-align:center;
    padding:10px;
    margin-top:20px;
}

</style>
</head>

<body>

<nav>
<a href="#a">Անասնապահություն</a>
<a href="#d">Ձկնորսություն</a>
<a href="#dz">Ձկնաբուծություն</a>
<a href="#b">Բուսաբուծություն</a>
<a href="#t">Տրանսպորտ</a>
</nav>

<div class="section" id="a">
<img src="https://picsum.photos/600/300?1">

<h2>🐄 Անասնապահություն</h2>

<p>
Անասնապահությունը գյուղատնտեսության կարևոր ճյուղ է։ Այն զբաղվում է կենդանիների բուծմամբ և մարդկանց ապահովում է կաթով մսով և այլ մթերքներով։
</p>

</div>

<div class="section" id="d">

<img src="https://picsum.photos/600/300?2">

<h2>🎣 Ձկնորսություն</h2>

<p>
Ձկնորսությունը կատարվում է գետերում լճերում և ծովերում։ Այն կարևոր դեր ունի սննդի արտադրության մեջ։
</p>

</div>

<div class="section" id="dz">

<img src="https://picsum.photos/600/300?3">

<h2>🐟 Ձկնաբուծություն</h2>

<p>
Ձկնաբուծությունը ձկների աճեցումն է հատուկ ջրավազաններում։ Այն օգնում է ստանալ մեծ քանակությամբ ձուկ։
</p>

</div>

<div class="section" id="b">

<img src="https://picsum.photos/600/300?4">

<h2>🌱 Բուսաբուծություն</h2>

<p>
Բուսաբուծությունը զբաղվում է բույսերի աճեցմամբ։ Մարդիկ աճեցնում են ցորեն բանջարեղեն և մրգեր։
</p>

</div>

<div class="section" id="t">

<img src="https://picsum.photos/600/300?5">

<h2>🚗 Տրանսպորտ և կապ</h2>

<p>
Տրանսպորտը մարդկանց և բեռների տեղափոխումն է իսկ կապը ապահովում է հաղորդակցությունը։
</p>

</div>

<div class="qr">

<h2>🔳 QR Կոդ</h2>

<img src="https://api.qrserver.com/v1/create-qr-code/?size=160x160&data=https://narekp385-pixel.github.io/fsrrgs/">

</div>

<footer>
<p>© 2026</p>
</footer>

</body>
</html>    margin:15px;
    font-size:18px;
    transition:0.3s;
}

nav a:hover{
    color:#c8e6c9;
}

.section{
    display:flex;
    align-items:center;
    gap:30px;
    background:white;
    margin:25px;
    padding:25px;
    border-radius:20px;
    box-shadow:0 5px 15px rgba(0,0,0,0.15);
    animation:slide 1.2s;
    transition:0.3s;
}

.section:hover{
    transform:scale(1.02);
}

.section img{
    width:320px;
    border-radius:15px;
}

.text{
    flex:1;
}

h2{
    color:#2e7d32;
    font-size:32px;
}

p{
    font-size:19px;
    line-height:1.8;
}

footer{
    background:#2e7d32;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:30px;
}

.qr{
    text-align:center;
    background:white;
    margin:25px;
    padding:30px;
    border-radius:20px;
    box-shadow:0 5px 15px rgba(0,0,0,0.15);
}

.qr img{
    width:220px;
}

@keyframes fade{
    from{opacity:0;}
    to{opacity:1;}
}

@keyframes slide{
    from{
        opacity:0;
        transform:translateY(50px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

@media(max-width:900px){

.section{
    flex-direction:column;
}

.section img{
    width:100%;
}

}

</style>
</head>
