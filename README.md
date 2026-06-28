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

* border-radius:15px;
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
<section class="home" id="home">

<div class="home-text">

<h3>Hello, I'm</h3>

<h1>Lokesh Kumar</h1>

<h2>B.Tech - Electronics & Communication Engineering</h2>

<p>
Currently pursuing 3rd Year B.Tech in Electronics & Communication Engineering at
Madanapalle Institute of Technology and Science (MITS), Andhra Pradesh.
Interested in Embedded Systems, IoT, VLSI, Artificial Intelligence,
Python, HTML and Full Stack Development.
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

<img src="1000171937.png" alt="Lokesh Kumar">

</div>

<div class="about-text">

<p>
I am Lokesh Kumar, a third-year Electronics and Communication Engineering student at
Madanapalle Institute of Technology and Science (MITS), Andhra Pradesh.

I have knowledge of Python, HTML, GitHub, Embedded Systems, IoT and VLSI.
I am currently working on an Agricultural Drone project focused on crop disease detection
and crop yield estimation using Artificial Intelligence, Image Processing and IoT.

I have completed certifications in Technical Communication for Engineers,
Computer Architecture and Organization, and Understanding Incubation and Entrepreneurship.
I also hold an NCC 'B' Certificate.
</p>

</div>

</div>

</section>
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
