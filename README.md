<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Manaswi Yerande | Resume</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#f2f5fa;
display:flex;
justify-content:center;
align-items:center;
min-height:100vh;
padding:30px;
}

.resume{

width:1100px;
background:#fff;
display:grid;
grid-template-columns:340px 1fr;
border-radius:20px;
overflow:hidden;
box-shadow:0 20px 40px rgba(0,0,0,.15);

}

.left{

background:linear-gradient(180deg,#2563eb,#0f172a);
color:#fff;
padding:35px;

}

.profile{

width:170px;
height:170px;
border-radius:50%;
border:6px solid white;
display:block;
margin:auto;
object-fit:cover;

}

.name{

text-align:center;
font-size:30px;
margin-top:20px;

}

.role{

text-align:center;
color:#dbeafe;
margin-bottom:30px;

}

.section{

margin-top:30px;

}

.section h3{

margin-bottom:12px;
color:#fff;
border-bottom:2px solid rgba(255,255,255,.3);
padding-bottom:8px;

}

.contact p{

margin:10px 0;
font-size:14px;

}

.contact i{

width:25px;

}

.skill{

margin:15px 0;

}

.bar{

height:8px;
background:#fff;
border-radius:10px;
margin-top:5px;

}

.bar span{

display:block;
height:100%;
background:#38bdf8;
border-radius:10px;

}

.right{

padding:40px;

}

.title{

font-size:22px;
font-weight:600;
color:#2563eb;
margin-bottom:15px;

}

.about{

color:#555;
line-height:1.7;

}

.card{

margin-top:18px;
padding:15px;
background:#f7f9fc;
border-left:5px solid #2563eb;
border-radius:10px;

}

.card h4{

color:#111;

}

.card p{

color:#666;
margin-top:6px;
font-size:14px;

}

.projects{

display:grid;
grid-template-columns:repeat(2,1fr);
gap:15px;
margin-top:15px;

}

.project{

background:#f8fafc;
padding:15px;
border-radius:10px;
transition:.3s;

}

.project:hover{

transform:translateY(-5px);

}

.social{

margin-top:25px;
text-align:center;

}

.social a{

color:white;
font-size:22px;
margin:0 12px;
transition:.3s;

}

.social a:hover{

color:#38bdf8;

}

button{

margin-top:30px;
padding:15px 35px;
border:none;
background:#2563eb;
color:white;
border-radius:40px;
font-size:16px;
cursor:pointer;
transition:.3s;

}

button:hover{

background:#1d4ed8;

}

@media(max-width:900px){

.resume{

grid-template-columns:1fr;

}

.projects{

grid-template-columns:1fr;

}

}

</style>

</head>
<body>

<div class="resume">

<div class="left">

<img src="C:\Users\manas\Downloads\Manaswiprofile.jpeg" class="profile">

<h2 class="name">Manaswi Yerande</h2>

<p class="role">Computer Engineering Student</p>

<div class="section contact">

<h3>Contact</h3>

<p><i class="fa fa-phone"></i> +91 7517753030</p>

<p><i class="fa fa-envelope"></i> manaswiyerande22@gmail.com</p>

<p><i class="fa fa-location-dot"></i> Pune, India</p>

</div>

<div class="section">

<h3>Skills</h3>

<div class="skill">

HTML/CSS

<div class="bar"><span style="width:95%"></span></div>

</div>

<div class="skill">

JavaScript

<div class="bar"><span style="width:85%"></span></div>

</div>

<div class="skill">

Python

<div class="bar"><span style="width:90%"></span></div>

</div>

<div class="skill">

Java

<div class="bar"><span style="width:80%"></span></div>

</div>

<div class="skill">

AI & Machine Learning

<div class="bar"><span style="width:75%"></span></div>

</div>

</div>

<div class="social">

<a href="#"><i class="fab fa-github"></i></a>

<a href="#"><i class="fab fa-linkedin"></i></a>

<a href="#"><i class="fab fa-instagram"></i></a>

</div>

</div>

<div class="right">

<h2 class="title">Profile</h2>

<p class="about">

Passionate Computer Engineering student with strong knowledge of Web Development, Python, Java, AI, and Machine Learning. Seeking internship opportunities where I can apply my technical skills to build innovative real-world applications.

</p>

<h2 class="title" style="margin-top:30px;">Education</h2>

<div class="card">

<h4>B.E. Computer Engineering</h4>

<p>Keystone School of Engineering (SPPU)</p>

<p>2024 - Present</p>

</div>

<h2 class="title" style="margin-top:30px;">Projects</h2>

<div class="projects">

<div class="project">

<h4>🤖 AI Social Media Agent</h4>

<p>AI-powered social media automation platform.</p>

</div>

<div class="project">

<h4>🎟 Movie Ticket Booking</h4>

<p>Python & Data Structures project.</p>

</div>

<div class="project">

<h4>🏦 Bank Management</h4>

<p>Java desktop application.</p>

</div>

<div class="project">

<h4>🌐 Portfolio Website</h4>

<p>Responsive portfolio using HTML CSS JS.</p>

</div>

</div>

<h2 class="title" style="margin-top:30px;">Certificates</h2>

<div class="card">

Google AI Essentials • IBM SkillsBuild AI • Python Programming

</div>

<button onclick="window.print()">

<i class="fa fa-download"></i> Download Resume

</button>

</div>

</div>

</body>
</html>
