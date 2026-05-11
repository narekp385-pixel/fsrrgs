
<html lang="hy">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Գյուղատնտեսություն և Տրանսպորտ</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family: Arial, sans-serif;
    background: linear-gradient(to right,#dcedc8,#ffffff);
    color:#222;
}

/* HEADER */

header{
    background: linear-gradient(45deg,#2e7d32,#66bb6a);
    color:white;
    text-align:center;
    padding:50px 20px;
    animation: fade 2s;
}

header h1{
    font-size:42px;
}

header p{
    margin-top:10px;
    font-size:20px;
}

/* MENU */

nav{
    background:#1b5e20;
    padding:15px;
    text-align:center;
    position:sticky;
    top:0;
}

nav a{
    color:white;
    text-decoration:none;
    margin:15px;
    font-size:18px;
    transition:0.3s;
}

nav a:hover{
    color:#a5d6a7;
}

/* SECTION */

.section{
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:30px;

    background:white;
    margin:30px;
    padding:30px;

    border-radius:20px;

    box-shadow:0 5px 15px rgba(0,0,0,0.15);

    animation: slide 1s;
    transition:0.3s;
}

.section:hover{
    transform:scale(1.02);
}

.text{
    width:60%;
}

.text h2{
    font-size:35px;
    margin-bottom:20px;
    color:#2e7d32;
}

.text p{
    font-size:20px;
    line-height:1.8;
}

/* IMAGE */

.image{
    width:35%;
}

.image img{
    width:100%;
    border-radius:20px;
    height:300px;
    object-fit:cover;
}

/* FOOTER */

footer{
    background:#2e7d32;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:30px;
}

/* ANIMATIONS */

@keyframes fade{
    from{
        opacity:0;
    }
    to{
        opacity:1;
    }
}

@keyframes slide{
    from{
        transform:translateY(50px);
        opacity:0;
    }
    to{
        transform:translateY(0);
        opacity:1;
    }
}

/* MOBILE */

@media(max-width:900px){

.section{
    flex-direction:column;
}

.text{
    width:100%;
}

.image{
    width:100%;
}

}

</style>

</head>

<body>

<header>
<h1>🌿 Գյուղատնտեսություն, Տրանսպորտ և Կապ</h1>
<p>Ժամանակակից ուսումնական կայք</p>
</header>

<nav>
<a href="#animals">Անասնապահություն</a>
<a href="#fishing">Ձկնորսություն</a>
<a href="#fishfarm">Ձկնաբուծություն</a>
<a href="#plants">Բուսաբուծություն</a>
<a href="#transport">Տրանսպորտ և կապ</a>
</nav>

<!-- ANASNAPAHUTYUN -->

<section class="section" id="animals">

<div class="text">

<h2>🐄 Անասնապահություն</h2>

<p>

Անասնապահությունը գյուղատնտեսության ամենակարևոր ճյուղերից մեկն է։ 
Այն զբաղվում է ընտանի կենդանիների բուծմամբ և խնամքով։ 
Մարդիկ անասնապահությամբ զբաղվել են հազարավոր տարիներ։ 
Այս ոլորտը մարդկանց ապահովում է կաթով, մսով, բրդով և այլ կարևոր մթերքներով։ 

Հայաստանում տարածված են կովաբուծությունը, ոչխարաբուծությունը և թռչնաբուծությունը։ 
Կենդանիների ճիշտ խնամքը օգնում է ստանալ բարձրորակ արտադրանք։ 
Ժամանակակից անասնապահության մեջ օգտագործվում են նոր տեխնոլոգիաներ և հատուկ սարքավորումներ։

</p>

</div>

<div class="image">

<img src="https://images.unsplash.com/photo-1516467508483-a7212febe31a?q=80&w=1200&auto=format&fit=crop">

</div>

</section>

<!-- DZKNORSUTYUN -->

<section class="section" id="fishing">

<div class="text">

<h2>🎣 Ձկնորսություն</h2>

<p>

Ձկնորսությունը մարդկանց հնագույն զբաղմունքներից մեկն է։ 
Այն իրենից ներկայացնում է ձկների որս բնական ջրերում՝ գետերում, լճերում և ծովերում։ 
Ձուկը համարվում է առողջարար սնունդ, քանի որ հարուստ է վիտամիններով և օգտակար նյութերով։ 

Շատ երկրներում ձկնորսությունը կարևոր տնտեսական ճյուղ է։ 
Այն ապահովում է աշխատատեղեր և զարգացնում տնտեսությունը։ 
Ժամանակակից ձկնորսության մեջ օգտագործվում են նավեր, ցանցեր և տարբեր տեխնոլոգիաներ։ 
Կարևոր է պահպանել բնությունը և չվնասել ջրային կենդանական աշխարհը։

</p>

</div>

<div class="image">

<img src="https://images.unsplash.com/photo-1504893524553-b855bce32c67?q=80&w=1200&auto=format&fit=crop">

</div>

</section>

<!-- DZKNABUTYUN -->

<section class="section" id="fishfarm">

<div class="text">

<h2>🐟 Ձկնաբուծություն</h2>

<p>

Ձկնաբուծությունը ձկների արհեստական աճեցումն է հատուկ պայմաններում։ 
Այն իրականացվում է լճակներում, ջրավազաններում և հատուկ տնտեսություններում։ 
Այս ոլորտը շատ կարևոր է, քանի որ օգնում է մարդկանց ապահովել սննդով և պահպանել բնական ռեսուրսները։ 

Հայաստանում զարգացած է իշխանի և այլ ձկների բուծումը։ 
Ժամանակակից ձկնաբուծարաններում օգտագործվում են մաքուր ջուր և հատուկ կերեր։ 
Ձկնաբուծությունը համարվում է գյուղատնտեսության ժամանակակից և կարևոր ուղղություն։

</p>

</div>

<div class="image">

<img src="https://images.unsplash.com/photo-1524704654690-b56c05c78a00?q=80&w=1200&auto=format&fit=crop">

</div>

</section>

<!-- BUSABUTYUN -->

<section class="section" id="plants">

<div class="text">

<h2>🌱 Բուսաբուծություն</h2>

<p>

Բուսաբուծությունը զբաղվում է տարբեր բույսերի և մշակաբույսերի աճեցմամբ։ 
Մարդիկ բուսաբուծությամբ ստանում են հացահատիկ, բանջարեղեն, մրգեր և այլ սննդամթերքներ։ 

Բույսերի աճի համար անհրաժեշտ են բերրի հող, ջուր, արևի լույս և լավ խնամք։ 
Հայաստանում տարածված է ցորենի, կարտոֆիլի, խաղողի և տարբեր մրգերի մշակումը։ 
Ժամանակակից տեխնոլոգիաները օգնում են ստանալ ավելի մեծ և որակյալ բերք։

</p>

</div>

<div class="image">

<img src="https://images.unsplash.com/photo-1464226184884-fa280b87c399?q=80&w=1200&auto=format&fit=crop">

</div>

</section>

<!-- TRANSPORT -->

<section class="section" id="transport">

<div class="text">

<h2>🚗 Տրանսպորտ և կապ</h2>

<p>

Տրանսպորտը մարդկանց և բեռների տեղափոխման միջոց է։ 
Գոյություն ունեն ավտոմոբիլային, երկաթուղային, օդային և ջրային տրանսպորտներ։ 
Տրանսպորտը կարևոր դեր ունի տնտեսության զարգացման և մարդկանց առօրյայի մեջ։ 

Կապը ապահովում է մարդկանց միջև հաղորդակցությունը։ 
Ժամանակակից աշխարհում մարդիկ օգտվում են հեռախոսներից, ինտերնետից և տարբեր կապի միջոցներից։ 
Կապն ու տրանսպորտը օգնում են արագ տեղեկություն փոխանցել և կապել աշխարհի տարբեր երկրներ։

</p>

</div>

<div class="image">

<img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70?q=80&w=1200&auto=format&fit=crop">

</div>

</section>

<footer>

<h2>🔳 QR Կոդ</h2>

<p>Սկանավորիր կայքը բացելու համար</p>

<img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=https://narekp385-pixel.github.io/fsrrgs/" alt="QR">

<br><br>

<p>© 2026 Ուսումնական կայք</p>

</footer>

</body>
</html>
