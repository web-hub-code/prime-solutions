<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Professional Business Demo</title>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:Arial}
body{background:#f4f6f9;color:#333}

/* Navbar */
header{
position:sticky;top:0;z-index:1000;
background:#0d6efd;color:#fff;
padding:15px 40px;display:flex;
justify-content:space-between;align-items:center}
header a{color:#fff;text-decoration:none;margin:0 12px;font-weight:bold}

/* Hero */
.hero{
background:linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.6)),
url('https://images.unsplash.com/photo-1522202176988-66273c2fd55f');
background-size:cover;background-position:center;
color:#fff;text-align:center;padding:100px 20px}
.hero h1{font-size:42px;margin-bottom:15px}
.hero p{font-size:18px;margin-bottom:25px}
.hero button{
background:#0d6efd;border:none;color:#fff;
padding:12px 30px;border-radius:30px;font-size:16px;cursor:pointer}

/* Sections */
section{padding:60px 40px}
.section-title{text-align:center;margin-bottom:40px}

/* Services */
.services{
display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px}
.card{
background:#fff;padding:30px;border-radius:15px;
box-shadow:0 10px 20px rgba(0,0,0,.1);
text-align:center}
.card i{font-size:40px;color:#0d6efd;margin-bottom:15px}

/* Stats */
.stats{
background:#0d6efd;color:#fff;
display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
text-align:center}
.stats div{padding:30px}

/* Contact */
.contact form{
max-width:500px;margin:auto;background:#fff;
padding:30px;border-radius:15px;
box-shadow:0 10px 20px rgba(0,0,0,.1)}
.contact input,.contact textarea{
width:100%;padding:12px;margin-bottom:15px;border-radius:8px;border:1px solid #ccc}
.contact button{
width:100%;padding:12px;background:#0d6efd;color:#fff;
border:none;border-radius:25px;font-size:16px}

/* Footer */
footer{background:#111;color:#fff;text-align:center;padding:20px}

/* WhatsApp */
.whatsapp{
position:fixed;bottom:20px;right:20px;
background:#25d366;color:#fff;
padding:15px;border-radius:50%;
font-size:22px;text-decoration:none}
</style>
</head>

<body>

<header>
<h2>BusinessPro</h2>
<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#services">Services</a>
<a href="#contact">Contact</a>
</nav>
</header>

<div class="hero" id="home">
<h1>Professional WordPress Website</h1>
<p>Grow your business with a modern & responsive website</p>
<button>Get Free Consultation</button>
</div>

<section id="about">
<h2 class="section-title">About Us</h2>
<p style="max-width:800px;margin:auto;text-align:center">
We create modern, fast and SEO-friendly websites for businesses and startups.
</p>
</section>

<section class="stats">
<div><h2>150+</h2><p>Happy Clients</p></div>
<div><h2>300+</h2><p>Projects Done</p></div>
<div><h2>5+</h2><p>Years Experience</p></div>
</section>

<section id="services">
<h2 class="section-title">Our Services</h2>
<div class="services">
<div class="card"><i class="fa-solid fa-code"></i><h3>Web Development</h3></div>
<div class="card"><i class="fa-brands fa-wordpress"></i><h3>WordPress</h3></div>
<div class="card"><i class="fa-solid fa-chart-line"></i><h3>SEO Marketing</h3></div>
<div class="card"><i class="fa-solid fa-mobile"></i><h3>Responsive Design</h3></div>
</div>
</section>

<section class="contact" id="contact">
<h2 class="section-title">Contact Us</h2>
<form>
<input type="text" placeholder="Your Name">
<input type="email" placeholder="Email Address">
<textarea rows="4" placeholder="Your Message"></textarea>
<button>Send Message</button>
</form>
</section>

<footer>
© 2026 BusinessPro — All Rights Reserved
</footer>

<a class="whatsapp" href="#">💬</a>

</body>
</html>
