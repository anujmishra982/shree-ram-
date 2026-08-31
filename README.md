<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Shree Ram Traders | Stone Chips & Gitti</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#f4f4f4;
    color:#222;
}

/* HEADER */

header{
    background:#151515;
    color:white;
    padding:16px 7%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:sticky;
    top:0;
    z-index:999;
}

.logo{
    font-size:23px;
    font-weight:bold;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
}

nav a:hover{
    color:#f5b041;
}

/* HERO */

.hero{
    min-height:88vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
    padding:30px 20px;

    background:
    linear-gradient(#0009,#0009),
    url("https://images.unsplash.com/photo-1586864387967-d02ef85d93e8?auto=format&fit=crop&w=1600&q=80");

    background-size:cover;
    background-position:center;
}

.hero-content{
    max-width:800px;
}

.hero h1{
    font-size:55px;
    margin-bottom:15px;
}

.hero h1 span{
    color:#f5b041;
}

.hero p{
    font-size:20px;
    line-height:1.7;
}

.btn{
    display:inline-block;
    padding:14px 24px;
    margin:20px 5px 0;
    border-radius:8px;
    text-decoration:none;
    font-weight:bold;
}

.call{
    background:#f5b041;
    color:#111;
}

.whatsapp{
    background:#25d366;
    color:white;
}

/* COMMON */

section{
    padding:65px 7%;
}

.title{
    text-align:center;
    margin-bottom:35px;
}

.title h2{
    font-size:34px;
    margin-bottom:8px;
}

.title p{
    color:#666;
}

/* PRODUCTS */

.products{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:25px;
}

.card{
    background:white;
    padding:30px;
    border-radius:15px;
    text-align:center;
    box-shadow:0 5px 20px #0001;
    transition:.3s;
}

.card:hover{
    transform:translateY(-6px);
}

.icon{
    font-size:50px;
    margin-bottom:15px;
}

.card h3{
    margin-bottom:10px;
}

.card p{
    color:#666;
    line-height:1.6;
}

/* DELIVERY */

.delivery{
    background:#202020;
    color:white;
}

.delivery .title p{
    color:#ccc;
}

.delivery-box{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:20px;
}

.delivery-card{
    border:1px solid #555;
    padding:25px;
    border-radius:12px;
    text-align:center;
}

.delivery-card h3{
    color:#f5b041;
    margin-bottom:12px;
}

.delivery-card p{
    line-height:1.6;
}

/* ORDER */

.order{
    background:#f5b041;
    text-align:center;
}

.order h2{
    font-size:34px;
    margin-bottom:12px;
}

.order p{
    font-size:18px;
}

.order-btn{
    display:inline-block;
    margin-top:20px;
    padding:14px 25px;
    background:#171717;
    color:white;
    border-radius:8px;
    text-decoration:none;
    font-weight:bold;
}

/* CONTACT */

.contact{
    background:white;
}

.contact-box{
    max-width:700px;
    margin:auto;
    text-align:center;
    line-height:2;
}

.contact-box p{
    font-size:17px;
}

/* MAP */

.map{
    max-width:900px;
    margin:35px auto 0;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 5px 20px #0002;
}

.map iframe{
    width:100%;
    height:350px;
    border:0;
}

/* FOOTER */

footer{
    background:#111;
    color:#aaa;
    text-align:center;
    padding:25px;
}

/* MOBILE */

@media(max-width:800px){

    header{
        flex-direction:column;
        gap:12px;
    }

    nav a{
        margin:0 6px;
        font-size:14px;
    }

    .hero h1{
        font-size:40px;
    }

    .hero p{
        font-size:17px;
    }

    .products,
    .delivery-box{
        grid-template-columns:1fr;
    }

}
</style>
</head>

<body>

<!-- HEADER -->

<header>

<div class="logo">
🪨 Shree Ram Traders
</div>

<nav>
<a href="#home">Home</a>
<a href="#products">Products</a>
<a href="#delivery">Delivery</a>
<a href="#contact">Contact</a>
</nav>

</header>


<!-- HOME -->

<section class="hero" id="home">

<div class="hero-content">

<h1>
Shree Ram <span>Traders</span>
</h1>

<p>
Quality Stone Chips & Gitti Supplier
</p>

<p>
🚚 30–40 KM तक Delivery Available
</p>

<!-- APNA NUMBER YAHAN LAGAO -->

<a href="tel:+91XXXXXXXXXX" class="btn call">
📞 Call Now
</a>

<a href="https://wa.me/91XXXXXXXXXX"
class="btn whatsapp">
💬 WhatsApp
</a>

</div>

</section>


<!-- PRODUCTS -->

<section id="products">

<div class="title">

<h2>Our Products</h2>

<p>
Construction work ke liye quality material
</p>

</div>


<div class="products">

<div class="card">

<div class="icon">🪨</div>

<h3>Stone Chips</h3>

<p>
Quality stone chips construction projects
ke liye available.
</p>

</div>


<div class="card">

<div class="icon">🏗️</div>

<h3>Gitti</h3>

<p>
Different sizes ki gitti requirement
ke according available.
</p>

</div>


<div class="card">

<div class="icon">🚛</div>

<h3>Bulk Supply</h3>

<p>
Building aur construction projects
ke liye bulk supply available.
</p>

</div>

</div>

</section>


<!-- DELIVERY -->

<section class="delivery" id="delivery">

<div class="title">

<h2>Delivery Information</h2>

<p>
Delivery aur charges ki important information
</p>

</div>


<div class="delivery-box">

<div class="delivery-card">

<h3>📍 Delivery Area</h3>

<p>
Approx. 30–40 KM tak delivery
available.
</p>

</div>


<div class="delivery-card">

<h3>🚚 Transport Charge</h3>

<p>
Transport charge stone/material
charge se alag hoga.
</p>

</div>


<div class="delivery-card">

<h3>💰 Stone Charge</h3>

<p>
Stone/Gitti ka charge quantity
aur material ke according hoga.
</p>

</div>

</div>

</section>


<!-- ORDER -->

<section class="order">

<h2>
Gitti ya Stone Chips Chahiye?
</h2>

<p>
Quantity aur delivery location WhatsApp par bhejein.
</p>

<a href="https://wa.me/91XXXXXXXXXX"
class="order-btn">
💬 WhatsApp par Order Karein
</a>

</section>


<!-- CONTACT -->

<section class="contact" id="contact">

<div class="title">

<h2>Contact Us</h2>

<p>
Shree Ram Traders se contact karein
</p>

</div>


<div class="contact-box">

<p>
🏪 <b>Business:</b> Shree Ram Traders
</p>

<p>
📍 <b>Location:</b>
Near Hanuman Mandir, Narayanpur Anant,
Muzaffarpur, Bihar
</p>

<!-- NUMBER CHANGE KARO -->

<p>
📞 <b>Phone:</b>
+91-XXXXXXXXXX
</p>

<p>
💬 <b>WhatsApp:</b>
+91-XXXXXXXXXX
</p>


<a href="tel:+91XXXXXXXXXX"
class="btn call">
📞 Call Now
</a>

<a href="https://wa.me/91XXXXXXXXXX"
class="btn whatsapp">
💬 WhatsApp
</a>

</div>


<!-- GOOGLE MAP -->

<div class="map">

<iframe
src="https://www.google.com/maps?q=3CV5%2BJ63%2C%20Narayanpur%20Anant%2C%20Muzaffarpur%2C%20Bihar%20842005&output=embed"
loading="lazy"
allowfullscreen>
</iframe>

</div>

</section>


<!-- FOOTER -->

<footer>

© 2026 Shree Ram Traders
<br>
Stone Chips & Gitti Supplier
<br><br>
Near Hanuman Mandir, Narayanpur Anant, Muzaffarpur

</footer>

</body>
</html>
