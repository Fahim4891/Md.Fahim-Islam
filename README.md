<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Md Fahim Islam | Digital Creator</title>

<meta name="description" content="Official Portfolio of Md Fahim Islam - Digital Creator, Digital Marketing Expert, AI Expert, Social Media Strategist and Content Creator.">

<meta name="keywords" content="Md Fahim Islam, Digital Creator, AI Expert, Digital Marketing, Social Media Marketing, Portfolio">

<meta name="author" content="Md Fahim Islam">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

<link rel="stylesheet"
href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
font-family:'Poppins',sans-serif;
}

:root{
--primary:#6c63ff;
--secondary:#00c6ff;
--dark:#0f172a;
--light:#ffffff;
--gray:#94a3b8;
--card:#111827;
}

body{
background:var(--dark);
color:white;
overflow-x:hidden;
}

a{
text-decoration:none;
color:white;
}

ul{
list-style:none;
}

.container{
width:90%;
max-width:1200px;
margin:auto;
}

section{
padding:100px 0;
}

.section-title{
text-align:center;
margin-bottom:60px;
}

.section-title h2{
font-size:40px;
margin-bottom:10px;
}

.section-title p{
color:var(--gray);
}

/* NAVBAR */

header{
position:fixed;
top:0;
left:0;
width:100%;
z-index:999;
background:rgba(15,23,42,.95);
backdrop-filter:blur(10px);
}

.navbar{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 0;
}

.logo{
font-size:28px;
font-weight:700;
color:var(--secondary);
}

.nav-links{
display:flex;
gap:25px;
}

.nav-links a{
transition:.3s;
}

.nav-links a:hover{
color:var(--secondary);
}

.menu-btn{
display:none;
font-size:25px;
cursor:pointer;
}

/* HERO SECTION */

.hero{
min-height:100vh;
display:flex;
align-items:center;
background:
linear-gradient(
135deg,
#0f172a 0%,
#111827 50%,
#1e293b 100%);
}

.hero-content{
display:grid;
grid-template-columns:1fr 1fr;
gap:50px;
align-items:center;
}

.hero-text h4{
font-size:22px;
color:var(--secondary);
margin-bottom:10px;
}

.hero-text h1{
font-size:65px;
line-height:1.2;
margin-bottom:20px;
}

.hero-text h1 span{
color:var(--primary);
}

.hero-text p{
color:#cbd5e1;
font-size:18px;
line-height:1.8;
margin-bottom:30px;
}

.hero-btns{
display:flex;
gap:15px;
flex-wrap:wrap;
}

.btn{
padding:14px 30px;
border-radius:50px;
display:inline-block;
font-weight:600;
transition:.4s;
}

.btn-primary{
background:var(--primary);
}

.btn-primary:hover{
transform:translateY(-5px);
}

.btn-outline{
border:2px solid var(--secondary);
}

.btn-outline:hover{
background:var(--secondary);
color:black;
}

.hero-image{
display:flex;
justify-content:center;
}

.profile-card{
width:380px;
height:380px;
border-radius:30px;
background:
linear-gradient(
135deg,
#6c63ff,
#00c6ff);
padding:6px;
}

.profile-inner{
width:100%;
height:100%;
background:#111827;
border-radius:25px;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
}

.profile-inner i{
font-size:120px;
color:white;
margin-bottom:15px;
}

.profile-inner h3{
font-size:28px;
}

.profile-inner p{
color:#cbd5e1;
}

/* SOCIAL */

.social-icons{
display:flex;
gap:15px;
margin-top:25px;
}

.social-icons a{
width:45px;
height:45px;
display:flex;
align-items:center;
justify-content:center;
background:#1e293b;
border-radius:50%;
transition:.4s;
}

.social-icons a:hover{
transform:translateY(-5px);
background:var(--primary);
}
