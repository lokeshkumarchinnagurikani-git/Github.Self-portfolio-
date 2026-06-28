   <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Lokesh Kumar | Portfolio</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
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
color:white;
}

header{
position:fixed;
top:0;
left:0;
width:100%;
padding:20px 8%;
display:flex;
justify-content:space-between;
align-items:center;
background:#051129;
z-index:1000;
box-shadow:0 0 20px rgba(0,0,0,.4);
}

.logo{
font-size:30px;
font-weight:700;
color:#00eeff;
text-decoration:none;
}

nav a{
color:white;
text-decoration:none;
margin-left:30px;
font-size:17px;
transition:.4s;
}

nav a:hover{
color:#00eeff;
}

section{
padding:100px 8%;
}

.home{
display:flex;
justify-content:space-between;
align-items:center;
min-height:100vh;
gap:50px;
}

.home-text h3{
font-size:30px;
}

.home-text h1{
font-size:55px;
color:#00eeff;
margin:10px 0;
}

.home-text h2{
font-size:25px;
margin-bottom:20px;
}

.home-text p{
font-size:18px;
line-height:1.8;
margin-bottom:30px;
max-width:600px;
}

.btn{
display:inline-block;
padding:12px 30px;
background:#00eeff;
color:#081b29;
border-radius:30px;
text-decoration:none;
font-weight:600;
transition:.4s;
}

.btn:hover{
box-shadow:0 0 20px cyan;
transform:scale(1.05);
}

.profile{
width:380px;
height:380px;
border-radius:50%;
overflow:hidden;
border:8px solid #00eeff;
box-shadow:0 0 40px cyan;
}

.profile img{
width:100%;
height:100%;
object-fit:cover;
}

.title{
text-align:center;
font-size:40px;
color:#00eeff;
margin-bottom:50px;
}

.about{
display:grid;
grid-template-columns:1fr 1fr;
gap:60px;
align-items:center;
}

.about img{
width:100%;
border-radius:20px;
box-shadow:0 0 30px cyan;
}

.about-text p{
font-size:18px;
line-height:1.8;
}

.skills-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:25px;
}

.skill{
background:#112e42;
padding:25px;
border-radius:15px;
text-align:center;
transition:.5s;
}

.skill:hover{
transform:translateY(-10px);
box-shadow:0 0 25px cyan;
}

.skill h3{
color:#00eeff;
margin-bottom:10px;
}

.education{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:25px;
}

.edu-box{
background:#112e42;
padding:25px;
border-radius:15px;
transition:.5s;
}

.edu-box:hover{
box-shadow:0 0 25px cyan;
transform:translateY(-10px);
}

.edu-box h3{
color:#00eeff;
margin-bottom:10px;
}

.projects{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(350px,1fr));
gap:30px;
}

.project{
background:#112e42;
padding:25px;
border-radius:15px;
transition:.5s;
}

.project:hover{
box-shadow:0 0 25px cyan;
transform:scale(1.03);
}

.project h3{
color:#00eeff;
margin-bottom:15px;
}

.project p{
line-height:1.8;
}

.certificates{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.certificate{
background:#112e42;
padding:20px;
text-align:center;
border-radius:12px;
transition:.5s;
}

.certificate:hover{
box-shadow:0 0 20px cyan;
}

.contact{
display:grid;
grid-template-columns:1fr 1fr;
gap:40px;
}

.contact-box{
background:#112e42;
padding:30px;
border-radius:15px;
}

.contact-box h3{
margin-bottom:20px;
color:#00eeff;
}

.contact-box p{
margin:15px 0;
font-size:18px;
}

form input,
form textarea{
width:100%;
padding:15px;
margin-bottom:20px;
background:#081b29;
border:none;
outline:none;
border-radius:10px;
color:white;
}

form textarea{
height:180px;
resize:none;
}

footer{
text-align:center;
padding:30px;
background:#051129;
margin-top:60px;
}

@media(max-width:900px){

.home{
flex-direction:column-reverse;
text-align:center;
}

.about{
grid-template-columns:1fr;
}

.contact{
grid-template-columns:1fr;
}

.profile{
width:280px;
height:280px;
}

.home-text h1{
font-size:40px;
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
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</nav>

</header>

<section class="home" id="home">

<div class="home-text">

<h3>Hello, I'm</h3>

<h1>Lokesh Kumar</h1>

<h2>Electronics & Communication Engineering Student</h2>

<p>
Motivated Electronics and Communication Engineering student passionate about Embedded Systems, IoT, Artificial Intelligence, VLSI, Python, HTML, and Full Stack Development. Currently pursuing B.Tech and building innovative technology projects.
</p>

<a href="#contact" class="btn">Hire Me</a>

</div>

<div class="profile">

<img src="1000171937.png" alt="Lokesh Kumar">

</div>

</section>
