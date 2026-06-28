
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Lokesh Kumar | Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#081b29;
color:#fff;
}

header{
position:fixed;
top:0;
left:0;
width:100%;
background:#051129;
display:flex;
justify-content:space-between;
align-items:center;
padding:18px 8%;
z-index:1000;
}

.logo{
font-size:28px;
font-weight:700;
color:#00e5ff;
text-decoration:none;
}

nav a{
color:#fff;
text-decoration:none;
margin-left:25px;
transition:.3s;
}

nav a:hover{
color:#00e5ff;
}

section{
padding:100px 8%;
}

.home{
display:flex;
justify-content:space-between;
align-items:center;
min-height:100vh;
gap:60px;
}

.home-text h1{
font-size:55px;
color:#00e5ff;
margin:10px 0;
}

.home-text h2{
font-size:28px;
margin-bottom:20px;
}

.home-text p{
font-size:18px;
line-height:1.8;
}

.profile img{
width:340px;
height:340px;
border-radius:50%;
border:6px solid #00e5ff;
box-shadow:0 0 30px cyan;
object-fit:cover;
}

.title{
font-size:40px;
text-align:center;
color:#00e5ff;
margin-bottom:50px;
}

.about{
display:grid;
grid-template-columns:1fr 2fr;
gap:50px;
align-items:center;
}

.about img{
width:300px;
border-radius:20px;
box-shadow:0 0 25px cyan;
}

.about-text h3{
color:#00e5ff;
margin-top:20px;
margin-bottom:8px;
}

.about-text p,
.about-text li{
line-height:1.8;
}

.about-text ul{
margin-left:20px;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
}

.card{
background:#112e42;
padding:25px;
border-radius:15px;
transition:.4s;
}

.card:hover{
transform:translateY(-8px);
box-shadow:0 0 20px cyan;
}

.card h3{
color:#00e5ff;
margin-bottom:15px;
}

.contact{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:30px;
}

.contact-box{
background:#112e42;
padding:25px;
border-radius:15px;
}

.contact-box h3{
color:#00e5ff;
margin-bottom:15px;
}

footer{
background:#051129;
padding:20px;
text-align:center;
margin-top:40px;
}

@media(max-width:900px){

.home{
flex-direction:column-reverse;
text-align:center;
}

.about{
grid-template-columns:1fr;
text-align:center;
}

.about img{
margin:auto;
}

}

</style>
</head>

<body>

<header>

<a href="#" class="logo">Lokesh Kumar</a>

<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#education">Education</a>
<a href="#project">Project</a>
<a href="#contact">Contact</a>
</nav>

</header>

<section class="home" id="home">

<div class="home-text">

<h3>Hello, I'm</h3>

<h1>Lokesh Kumar</h1>

<h2>B.Tech - Electronics & Communication Engineering</h2>

<p>
Currently pursuing 3rd Year B.Tech at
Madanapalle Institute of Technology and Science (MITS),
Andhra Pradesh.
</p>

</div>

<div class="profile">

<img src="1000171937.png" alt="Lokesh Kumar">

</div>


</section>

<section id="about">

<h2 class="title">About Me</h2>

<div class="about">

<div>


<!-- PART 2 -->

<section id="skills">

<h2 class="title">Skills</h2>

<div class="cards">

<div class="card">
<h3>Python</h3>
<p>Basic programming, problem solving and scripting.</p>
</div>

<div class="card">
<h3>HTML</h3>
<p>beginner in web page development using HTML.</p>
</div>

</div>

</section>

<section id="project">

<h2 class="title">Project</h2>

<div class="cards">

<div class="card">

<h3>Agricultural Drone</h3>

<p>
Ongoing project developing an Agricultural Drone for crop disease detection and crop yield estimation.
</p>

</div>

</div>

</section>

<section id="certifications">

<h2 class="title">Certifications</h2>

<div class="cards">

<div class="card">
<h3>Technical Communication for Engineers(NPTEL)</h3>
</div>

<div class="card">
<h3>Computer Architecture and Organization(NPTEL)</h3>
</div>

<div class="card">
<h3>Understanding Incubation and Entrepreneurship(NPTEL)</h3>
</div>

</div>

</section>

<section id="languages">

<h2 class="title">Languages</h2>

<div class="cards">

<div class="card">
<h3>English</h3>
</div>

<div class="card">
<h3>Telugu</h3>
</div>

</div>

</section>

<section id="contact">

<h2 class="title">Contact</h2>

<div class="contact">

<div class="contact-box">

<h3>Email</h3>
<p>lokeshkumarchinnagurikani@gmail.com</p>

<h3>Phone</h3>
<p>+91 9392839803</p>

<h3>Location</h3>
<p>Anappali(v),Ramasamudram(mandal), annamayya (dist),Andhra Pradesh, India</p>

</div>

</div>

</section>

<footer>

<p>© 2026 Lokesh Kumar.</p>

</footer>

</body>
</html>




<img src="1000171937.png" alt="Lokesh Kumar">

</div>

<div class="about-text">

<h3>Name</h3>
<p>Lokesh Kumar</p>

<h3>Email</h3>
<p>lokeshkumarchinnagurikani@gmail.com</p>

<h3>Phone</h3>
<p>+91 9392839803</p>

<h3>Location</h3>
<p>Anapalli(v), ramasamudram (mandal), annamayya (dist), Andhra Pradesh, India</p>

<h3>Career Objective</h3>

<p>
Motivated Electronics and Communication Engineering student seeking internship opportunities to enhance technical skills  real-world projects.
</p>

<h3>Education</h3>

<ul>

<li>B.Tech (ECE) - Madanapalle Institute of Technology and Science (Currently Pursuing 3rd Year)</li>

<li>Intermediate - APRJC Gyarampalli (91.8%)</li>

</ul>

</div>

</div>

</section>
