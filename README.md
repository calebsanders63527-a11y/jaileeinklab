<!DOCTYPE html>
<html lang="en">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Jailee Ink Lab</title>

<link rel="stylesheet" href="style.css">

<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@500;700&family=Poppins:wght@300;400;500&family=Great+Vibes&display=swap" rel="stylesheet">

</head>

<body>

<header class="hero">

<div class="overlay">

<h1 class="logo">
Jailee
</h1>

<h2 class="subtitle">
INK LAB
</h2>

<p class="tagline">
Custom Tattoos • Booking Only
</p>

<a href="#booking">
<button class="heroButton">
Book Now
</button>
</a>

</div>

</header>


<section id="booking" class="card">

<h2>Book Your Tattoo</h2>

<form
action="PASTE_YOUR_FORMSPREE_URL_HERE"
method="POST"
enctype="multipart/form-data">

<input
name="name"
placeholder="Full Name"
required>

<input
name="contact"
placeholder="Phone or Instagram"
required>

<input
name="tattoo_idea"
placeholder="Tattoo Idea"
required>

<textarea
name="placement"
placeholder="Placement"></textarea>

<textarea
name="extra_notes"
placeholder="Size, Style, Color"></textarea>

<label>
Upload Reference Image(s)
</label>

<input
type="file"
name="reference_image"
accept="image/*"
multiple>

<label>
Payment Method
</label>

<select name="payment_method">

<option>Cash App</option>

<option>Venmo</option>

<option>Cash (Pay in Person)</option>

</select>

<button type="submit">
Submit Booking Request
</button>

</form>

</section>


<section class="card">

<h2>Deposit</h2>

<p>$25 Deposit Required</p>

<p>

<a href="https://cash.app/$JaileeMcDowell" target="_blank">

Cash App:
$JaileeMcDowell

</a>

</p>

<p>

<a href="https://venmo.com/jaileem" target="_blank">

Venmo:
@jaileem

</a>

</p>

</section>


<section class="card">

<h2>Socials</h2>

<p>

<a href="https://instagram.com/jaileeinklab" target="_blank">

Instagram

</a>

</p>

<p>

<a href="https://www.snapchat.com/add/jailee_babym" target="_blank">

Snapchat

</a>

</p>

</section>


<footer>

© 2026 Jailee Ink Lab

</footer>

<script src="script.js"></script>

</body>
</html>

/* ---------------- GENERAL ---------------- */

*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
}

body{

font-family:'Poppins',sans-serif;

background:
linear-gradient(rgba(15,0,30,.82),rgba(15,0,30,.9)),
url("https://images.unsplash.com/photo-1522383225653-ed111181a951?auto=format&fit=crop&w=1800&q=80");

background-size:cover;
background-position:center;
background-attachment:fixed;

color:white;

}


/* ---------------- HERO ---------------- */

.hero{

height:100vh;

display:flex;

justify-content:center;

align-items:center;

text-align:center;

position:relative;

overflow:hidden;

}

.hero::before{

content:"";

position:absolute;

width:100%;

height:100%;

background:

radial-gradient(circle,#a64dff33 0%,transparent 60%),

linear-gradient(to top,#120016,#00000044);

backdrop-filter:blur(2px);

}


.overlay{

position:relative;

z-index:2;

}


.logo{

font-family:'Great Vibes',cursive;

font-size:110px;

color:#d4a8ff;

text-shadow:

0 0 20px #a020f0,

0 0 45px #7d1fff;

}


.subtitle{

letter-spacing:8px;

font-family:'Cinzel',serif;

margin-top:-20px;

font-size:30px;

}


.tagline{

margin-top:20px;

font-size:20px;

opacity:.9;

}


/* ---------------- BUTTON ---------------- */

.heroButton{

margin-top:40px;

padding:18px 45px;

font-size:18px;

border:none;

border-radius:50px;

cursor:pointer;

background:linear-gradient(90deg,#8f2fff,#cb6cff);

color:white;

font-weight:bold;

transition:.35s;

box-shadow:0 0 20px #9b30ff;

}

.heroButton:hover{

transform:translateY(-5px) scale(1.05);

box-shadow:

0 0 25px #c266ff,

0 0 50px #b100ff;

}


/* ---------------- CARDS ---------------- */

.card{

width:min(900px,92%);

margin:50px auto;

padding:35px;

border-radius:25px;

background:rgba(255,255,255,.08);

backdrop-filter:blur(18px);

border:1px solid rgba(255,255,255,.15);

box-shadow:

0 0 30px rgba(155,48,255,.3);

transition:.3s;

}

.card:hover{

transform:translateY(-8px);

box-shadow:

0 0 40px rgba(155,48,255,.55);

}

.card h2{

font-family:'Cinzel',serif;

margin-bottom:25px;

text-align:center;

font-size:34px;

color:#e7c6ff;

}


/* ---------------- FORM ---------------- */

input,
textarea,
select{

width:100%;

padding:15px;

margin:12px 0;

border:none;

outline:none;

border-radius:12px;

background:rgba(255,255,255,.1);

color:white;

font-size:16px;

}

textarea{

height:120px;

resize:vertical;

}

input::placeholder,
textarea::placeholder{

color:#ddd;

}


button[type=submit]{

width:100%;

padding:18px;

margin-top:20px;

border:none;

border-radius:14px;

background:linear-gradient(90deg,#822dff,#d257ff);

color:white;

font-size:18px;

font-weight:600;

cursor:pointer;

transition:.3s;

}

button[type=submit]:hover{

transform:scale(1.03);

box-shadow:0 0 25px #bb5cff;

}


/* ---------------- LINKS ---------------- */

a{

color:#e6b7ff;

text-decoration:none;

transition:.25s;

}

a:hover{

color:white;

}


/* ---------------- FOOTER ---------------- */

footer{

padding:50px;

text-align:center;

opacity:.7;

}


/* ---------------- MOBILE ---------------- */

@media(max-width:768px){

.logo{

font-size:75px;

}

.subtitle{

font-size:20px;

letter-spacing:4px;

}

.tagline{

font-size:17px;

}

.card{

padding:25px;

}

} <header class="hero">

    <div class="moon"></div>

    <div class="mist"></div>

    <div class="pagoda"></div>

    <div class="overlay">

        <h1 class="logo">
            Jailee
        </h1>

        <h2 class="subtitle">
            INK LAB
        </h2>

        <p class="tagline">
            Custom Tattoos • Fine Line • Black & Grey • Booking Only
        </p>

        <a href="#booking">
            <button class="heroButton">
                Book Your Tattoo
            </button>
        </a>

    </div>

</header>

/* ---------------- MOON ---------------- */

.moon{

width:320px;
height:320px;

border-radius:50%;

background:radial-gradient(circle,#d9b3ff,#8d3cff);

position:absolute;

top:80px;
right:8%;

opacity:.85;

filter:blur(.5px);

box-shadow:
0 0 80px #b24dff,
0 0 150px #7f2cff;

z-index:1;

}

/* ---------------- PAGODA ---------------- */

.pagoda{

position:absolute;

bottom:0;

left:50%;

transform:translateX(-50%);

width:330px;

height:520px;

background-image:url("https://upload.wikimedia.org/wikipedia/commons/8/84/Pagoda_silhouette.svg");

background-repeat:no-repeat;

background-position:center;

background-size:contain;

opacity:.18;

z-index:1;

}

/* ---------------- MIST ---------------- */

.mist{

position:absolute;

bottom:0;

left:0;

width:100%;

height:240px;

background:

linear-gradient(

to top,

rgba(255,255,255,.22),

transparent

);

filter:blur(18px);

animation:fog 10s ease-in-out infinite alternate;

}

@keyframes fog{

from{

transform:translateX(-40px);

}

to{

transform:translateX(40px);

}

}

/* ---------------- LOGO GLOW ---------------- */

.logo{

animation:glow 4s ease-in-out infinite;

}

@keyframes glow{

0%{

text-shadow:

0 0 20px #8d3cff,

0 0 40px #8d3cff;

}

50%{

text-shadow:

0 0 35px #d97fff,

0 0 70px #c95dff,

0 0 120px #9f4dff;

}

100%{

text-shadow:

0 0 20px #8d3cff,

0 0 40px #8d3cff;

}

} <div class="petals">

<span>🌸</span>
<span>🌸</span>
<span>🌸</span>
<span>🌸</span>
<span>🌸</span>
<span>🌸</span>
<span>🌸</span>
<span>🌸</span>

</div>

/* ==========================
      FALLING PETALS
========================== */

.petals{

position:fixed;

top:0;
left:0;

width:100%;
height:100%;

pointer-events:none;

overflow:hidden;

z-index:999;

}

.petals span{

position:absolute;

top:-10%;

font-size:30px;

animation:fall linear infinite;

opacity:.7;

}

/* Different speeds */

.petals span:nth-child(1){

left:5%;

animation-duration:10s;

}

.petals span:nth-child(2){

left:20%;

animation-duration:13s;

}

.petals span:nth-child(3){

left:35%;

animation-duration:9s;

}

.petals span:nth-child(4){

left:50%;

animation-duration:14s;

}

.petals span:nth-child(5){

left:65%;

animation-duration:12s;

}

.petals span:nth-child(6){

left:78%;

animation-duration:11s;

}

.petals span:nth-child(7){

left:90%;

animation-duration:15s;

}

.petals span:nth-child(8){

left:96%;

animation-duration:10s;

}

@keyframes fall{

0%{

transform:
translateY(-120px)
rotate(0deg);

}

100%{

transform:
translateY(120vh)
rotate(360deg);

}

} body::before{

content:"🌸";

position:fixed;

top:20px;

left:20px;

font-size:140px;

opacity:.18;

pointer-events:none;

transform:rotate(-15deg);

}

body::after{

content:"🌸";

position:fixed;

bottom:20px;

right:20px;

font-size:140px;

opacity:.12;

pointer-events:none;

transform:rotate(15deg);

} .card{

opacity:0;

transform:translateY(80px);

animation:fadeUp .8s forwards;

}

.card:nth-of-type(1){

animation-delay:.2s;

}

.card:nth-of-type(2){

animation-delay:.5s;

}

.card:nth-of-type(3){

animation-delay:.8s;

}

@keyframes fadeUp{

to{

opacity:1;

transform:translateY(0);

}

} button{

transition:.35s;

position:relative;

overflow:hidden;

}

button::before{

content:"";

position:absolute;

left:-100%;

top:0;

width:100%;

height:100%;

background:linear-gradient(

90deg,

transparent,

rgba(255,255,255,.45),

transparent

);

transition:.6s;

}

button:hover::before{

left:100%;

}

button:hover{

transform:translateY(-4px);

box-shadow:

0 0 20px #bb66ff,

0 0 40px #a044ff,

0 0 80px #7e1dff;

} <nav>

<div class="navLogo">

Jailee Ink Lab

</div>

<ul>

<li><a href="#">Home</a></li>

<li><a href="#gallery">Gallery</a></li>

<li><a href="#booking">Book</a></li>

<li><a href="#reviews">Reviews</a></li>

<li><a href="#contact">Contact</a></li>

</ul>

</nav>

/* ---------------- NAVBAR ---------------- */

nav{

position:fixed;

top:0;

left:0;

width:100%;

padding:18px 50px;

display:flex;

justify-content:space-between;

align-items:center;

background:rgba(18,0,30,.75);

backdrop-filter:blur(18px);

z-index:10000;

}

.navLogo{

font-family:'Great Vibes',cursive;

font-size:42px;

color:#d8b0ff;

}

nav ul{

display:flex;

gap:35px;

list-style:none;

}

nav a{

color:white;

text-decoration:none;

font-weight:500;

transition:.3s;

}

nav a:hover{

color:#d79cff;

} <section id="gallery" class="card">

<h2>Recent Work</h2>

<div class="gallery">

<img src="images/tattoo1.jpg">

<img src="images/tattoo2.jpg">

<img src="images/tattoo3.jpg">

<img src="images/tattoo4.jpg">

<img src="images/tattoo5.jpg">

<img src="images/tattoo6.jpg">

</div>

</section>

.gallery{

display:grid;

grid-template-columns:repeat(auto-fit,minmax(250px,1fr));

gap:20px;

}

.gallery img{

width:100%;

height:300px;

object-fit:cover;

border-radius:18px;

transition:.4s;

cursor:pointer;

box-shadow:0 0 20px rgba(0,0,0,.4);

}

.gallery img:hover{

transform:scale(1.05);

box-shadow:

0 0 25px #b84cff,

0 0 50px #9f33ff;

} <section id="reviews" class="card">

<h2>Client Reviews</h2>

<div class="review">

★★★★★

<p>

"Jailee absolutely killed my tattoo.
Super clean shop and amazing work."

</p>

<b>- Sarah</b>

</div>

<div class="review">

★★★★★

<p>

"Best tattoo experience I've ever had."

</p>

<b>- Marcus</b>

</div>

<div class="review">

★★★★★

<p>

"I'll definitely be coming back."

</p>

<b>- Emily</b>

</div>

</section> .review{

margin:25px 0;

padding:25px;

border-radius:18px;

background:rgba(255,255,255,.05);

border-left:5px solid #b84cff;

}

.review b{

color:#e3b9ff;

} <section id="contact" class="card">

<h2>Contact</h2>

<p>Instagram: @jaileeinklab</p>

<p>Snapchat: @jailee_babym</p>

<p>Email: your@email.com</p>

</section>

<header class="hero">
    <div class="overlay">

        <img src="logo.png" class="logo">

        <h1>Jailee Ink Lab</h1>
        <p>Custom Tattoos • Booking Only</p>

    </div>
</header>

/* LOGO */
.logo {
    width: 140px;
    border-radius: 50%;
    margin-bottom: 15px;
    box-shadow: 0 0 25px rgba(180, 0, 255, 0.7);
    animation: fadeIn 1.5s ease-in-out;
}

/* FADE IN ANIMATION */
@keyframes fadeIn {
    from {
        opacity: 0;
        transform: translateY(-20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

// Button glow
const btn = document.querySelector("button");

btn.addEventListener("mouseenter", () => {
    btn.style.boxShadow = "0 0 25px #b400ff";
});

btn.addEventListener("mouseleave", () => {
    btn.style.boxShadow = "none";
});

// Fade cards in
const cards = document.querySelectorAll(".card");

cards.forEach((card, i) => {
    card.style.opacity = "0";
    card.style.transform = "translateY(30px)";

    setTimeout(() => {
        card.style.transition = "0.6s ease";
        card.style.opacity = "1";
        card.style.transform = "translateY(0)";
    }, i * 200);
});

<form action="https://formspree.io/f/YOUR_ID" method="POST">
<input type="hidden" name="_next" value="thank-you.html">

<label>Preferred Date</label>
<input type="date" name="date">

<label>Preferred Time</label>
<select name="time">
<option>Morning</option>
<option>Afternoon</option>
<option>Evening</option>
</select>

<label>
<input type="checkbox" required>
 I understand a $25 deposit is required before booking is confirmed
</label>

<div class="card">
<h2>Recent Work</h2>

<div class="gallery">
<img src="https://via.placeholder.com/150">
<img src="https://via.placeholder.com/150">
<img src="https://via.placeholder.com/150">
</div>

</div>

.gallery {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
}

.gallery img {
    width: 30%;
    border-radius: 12px;
    transition: 0.3s;
}

.gallery img:hover {
    transform: scale(1.05);
}

<!DOCTYPE html>
<html>
<body style="font-family:Poppins;background:#120016;color:white;text-align:center;padding:100px">

<h1>You're Booked 🔥</h1>
<p>Your request has been sent. We’ll contact you soon.</p>

<a href="index.html" style="color:#dba6ff">Back to Home</a>

</body>
</html>

<div class="app">

</div>

<nav class="bottom-nav">
    <a href="#book">Book</a>
    <a href="#gallery">Work</a>
    <a href="#deposit">Deposit</a>
    <a href="#socials">Socials</a>
</nav>

<div class="card" id="book">

<div class="card" id="gallery">

<div class="card" id="deposit">

<div class="card" id="socials">

/* APP WRAPPER */
.app {
    padding-bottom: 80px;
}

/* BOTTOM NAV */
.bottom-nav {
    position: fixed;
    bottom: 0;
    width: 100%;
    background: rgba(20,0,30,0.95);
    display: flex;
    justify-content: space-around;
    padding: 12px 0;
    backdrop-filter: blur(10px);
    border-top: 1px solid rgba(255,255,255,0.1);
}

.bottom-nav a {
    color: #dba6ff;
    text-decoration: none;
    font-size: 14px;
}

.bottom-nav a:active {
    transform: scale(0.9);
}

html {
    scroll-behavior: smooth;
}

<a class="pay-btn" href="https://cash.app/$JaileeMcDowell" target="_blank">Pay with Cash App</a>
<a class="pay-btn" href="https://venmo.com/jaileem" target="_blank">Pay with Venmo</a>

.pay-btn {
    display: block;
    margin: 10px 0;
    padding: 14px;
    text-align: center;
    border-radius: 12px;
    background: linear-gradient(90deg,#8a2be2,#b400ff);
    color: white;
    font-weight: bold;
}
