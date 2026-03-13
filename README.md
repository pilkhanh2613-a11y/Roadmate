<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>RoadMate | AI Traffic Sign Detection</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<script src="https://cdn.jsdelivr.net/npm/particles.js"></script>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:'Poppins',sans-serif;
background:#020617;
color:white;
line-height:1.6;
overflow-x:hidden;
}

/* PARTICLES BACKGROUND */

#particles-js{
position:fixed;
width:100%;
height:100%;
z-index:-1;
}

/* NAVBAR */

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
background:rgba(255,255,255,0.05);
backdrop-filter:blur(10px);
position:sticky;
top:0;
z-index:100;
}

.logo{
display:flex;
align-items:center;
gap:10px;
}

.logo-text h1{
font-size:26px;
}

.logo-text span:first-child{
color:#38bdf8;
}

.logo-text span:last-child{
color:#7bc043;
}

.logo-text p{
font-size:10px;
color:#cbd5f5;
}

nav ul{
display:flex;
gap:25px;
list-style:none;
}

nav a{
text-decoration:none;
color:white;
}

/* HERO */

.hero{
height:90vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
}

.hero h2{
font-size:48px;
margin-bottom:20px;
}

.hero p{
max-width:600px;
color:#cbd5f5;
}

.btn{
margin-top:25px;
background:#38bdf8;
padding:12px 28px;
border:none;
border-radius:30px;
cursor:pointer;
font-size:16px;
}

/* SECTION */

.section{
padding:80px 10%;
}

.section-title{
text-align:center;
font-size:32px;
margin-bottom:50px;
}

/* GRID */

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
}

/* CARD */

.card{
background:rgba(255,255,255,0.08);
padding:25px;
border-radius:15px;
transition:0.3s;
backdrop-filter:blur(8px);
}

.card:hover{
transform:translateY(-8px);
background:rgba(255,255,255,0.15);
}

/* HOW IT WORKS */

.steps{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:25px;
text-align:center;
}

.step{
background:rgba(255,255,255,0.08);
padding:30px;
border-radius:15px;
}

/* PRICING */

.price-box{
text-align:center;
background:rgba(255,255,255,0.08);
padding:40px;
border-radius:20px;
}

.price{
font-size:36px;
color:#38bdf8;
margin:20px 0;
}

/* DEMO */

.demo{
margin-top:50px;
border:2px dashed #38bdf8;
padding:40px;
border-radius:15px;
text-align:center;
}

.car{
font-size:80px;
transition:0.5s;
}

.car:hover{
transform:rotateY(180deg) scale(1.2);
}

/* CTA */

.cta{
text-align:center;
padding:80px 10%;
background:linear-gradient(135deg,#1e73be,#0b3d91);
}

/* FOOTER */

footer{
text-align:center;
padding:40px;
color:#94a3b8;
}

</style>

</head>

<body>

<div id="particles-js"></div>

<!-- NAVBAR -->

<nav>

<div class="logo">

<div class="logo-text">
<h1><span>Road</span><span>Mate</span></h1>
<p>Drive Smarter. Stress Less.</p>
</div>

</div>

<ul>
<li><a href="#">Home</a></li>
<li><a href="#features">Features</a></li>
<li><a href="#how">How it Works</a></li>
<li><a href="#pricing">Pricing</a></li>
</ul>

</nav>

<!-- HERO -->

<section class="hero">

<h2>AI Traffic Sign Recognition System</h2>

<p>
RoadMate is an intelligent driving assistant that detects traffic signs and provides real-time alerts to help drivers understand road regulations.
</p>

<button class="btn">Discover RoadMate</button>

</section>

<!-- PROBLEM -->

<section class="section">

<h2 class="section-title">Traffic Problems Drivers Face</h2>

<div class="grid">

<div class="card">
<h3>Complex Traffic Signs</h3>
<p>Drivers often struggle to interpret multiple road signs correctly.</p>
</div>

<div class="card">
<h3>Violation Risks</h3>
<p>Misunderstanding signs can lead to expensive traffic violations.</p>
</div>

<div class="card">
<h3>Information Overload</h3>
<p>Too many signs create confusion in busy urban environments.</p>
</div>

</div>

</section>

<!-- FEATURES -->

<section id="features" class="section">

<h2 class="section-title">Key AI Features</h2>

<div class="grid">

<div class="card">
<h3>AI Camera Detection</h3>
<p>Detects traffic signs using computer vision technology.</p>
</div>

<div class="card">
<h3>Vehicle-Specific Analysis</h3>
<p>Analyzes which rules apply based on vehicle type.</p>
</div>

<div class="card">
<h3>Real-Time Alerts</h3>
<p>Drivers receive instant visual and audio notifications.</p>
</div>

<div class="card">
<h3>Smart Filtering</h3>
<p>Displays only relevant signs for the specific vehicle.</p>
</div>

</div>

</section>

<!-- HOW IT WORKS -->

<section id="how" class="section">

<h2 class="section-title">How RoadMate Works</h2>

<div class="steps">

<div class="step">
<h3>1. Camera Capture</h3>
<p>The front camera scans traffic signs while driving.</p>
</div>

<div class="step">
<h3>2. AI Recognition</h3>
<p>AI identifies and classifies detected traffic signs.</p>
</div>

<div class="step">
<h3>3. Rule Interpretation</h3>
<p>The system determines which rules apply.</p>
</div>

<div class="step">
<h3>4. Driver Alert</h3>
<p>Drivers receive real-time warnings instantly.</p>
</div>

</div>

</section>

<!-- PRICING -->

<section id="pricing" class="section">

<h2 class="section-title">Pricing</h2>

<div class="price-box">

<h3>RoadMate Device</h3>

<div class="price">3 – 4 Million VND</div>

<p>Affordable AI driving assistant designed for professional drivers.</p>

<button class="btn">Contact Us</button>

</div>

</section>

<!-- DEMO -->

<section class="section">

<h2 class="section-title">Interactive AI Demo</h2>

<div class="demo">

<p>Hover over the car to simulate AI vehicle interaction</p>

<div class="car">🚗</div>

</div>

</section>

<!-- CTA -->

<section class="cta">

<h2>Drive Smarter. Drive Safer.</h2>

<p>Experience intelligent traffic sign detection with RoadMate.</p>

<button class="btn">Get Started</button>

</section>

<footer>

<p>© 2026 RoadMate AI Driving Assistance System</p>

</footer>

<script>

particlesJS("particles-js",{
particles:{
number:{value:80},
size:{value:3},
move:{speed:2},
line_linked:{enable:true},
color:{value:"#38bdf8"}
}
});

</script>

</body>
</html>
