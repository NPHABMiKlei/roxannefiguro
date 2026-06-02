<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Roxanne B. Figuro | Personal Website</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
}

body{
font-family:'Poppins',sans-serif;
background:#f5dce5;
background-image:
radial-gradient(#3b1f1f 4px, transparent 4px);
background-size:38px 38px;
color:#5c4b51;
}

/* Floating Bows */

.bow{
position:fixed;
font-size:25px;
opacity:.3;
animation:float 12s linear infinite;
z-index:-1;
}

.bow:nth-child(1){left:10%;}
.bow:nth-child(2){left:50%;animation-duration:15s;}
.bow:nth-child(3){left:80%;animation-duration:18s;}

@keyframes float{
from{
top:100%;
}
to{
top:-10%;
}
}
  
header{
background:linear-gradient(135deg,#ffd6e7,#d8f0d2);
padding:80px 20px;
text-align:center;
border-bottom:6px dotted #c98aaa;
}

header h1{
font-family:'Playfair Display',serif;
font-size:3rem;
color:#b05d84;
}

header p{
margin-top:10px;
font-size:1.1rem;
}

nav{
position:sticky;
top:0;
background:white;
padding:15px;
text-align:center;
box-shadow:0 3px 10px rgba(0,0,0,.1);
z-index:1000;
}

nav a{
text-decoration:none;
margin:0 15px;
font-weight:600;
color:#b05d84;
}

nav a:hover{
color:#7ba87f;
}

.container{
width:90%;
max-width:1200px;
margin:auto;
padding:40px 0;
}

.section{
background:rgba(255,255,255,.95);
padding:30px;
margin-bottom:30px;
border-radius:25px;
box-shadow:0 8px 20px rgba(0,0,0,.08);
border:3px solid #ffdbe8;
}

.section h2{
color:#b05d84;
margin-bottom:20px;
font-family:'Playfair Display',serif;
}

.profile{
text-align:center;
}

.profile img{
width:200px;
height:200px;
border-radius:50%;
object-fit:cover;
border:6px solid #ffd4e5;
margin-bottom:20px;
}

.info-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:15px;
margin-top:25px;
}

.card{
background:#fff7fb;
padding:15px;
border-radius:15px;
border:2px dashed #ffc6dc;
}

.education{
margin-bottom:20px;
background:#fff7fb;
padding:15px;
border-left:5px solid #cde8c7;
border-radius:12px;
}

.family-list li{
margin:12px 0;
}

.collection-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
}

.collection-card{
background:#fff7fb;
padding:20px;
border-radius:20px;
text-align:center;
border:2px dashed #ffc6dc;
transition:.3s;
}

.collection-card:hover{
transform:translateY(-8px);
}

.collection-card span{
font-size:2rem;
display:block;
margin-bottom:10px;
}

/* Gallery */

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.gallery img{
width:100%;
height:280px;
object-fit:cover;
border-radius:20px;
border:5px solid white;
box-shadow:0 5px 15px rgba(0,0,0,.15);
transition:.4s;
cursor:pointer;
}

.gallery img:hover{
transform:scale(1.05);
}

footer{
background:white;
padding:20px;
text-align:center;
font-weight:600;
color:#b05d84;
}

/* Responsive */

@media(max-width:768px){

header h1{
font-size:2.2rem;
}

nav a{
display:inline-block;
margin:8px;
}

}

</style>
</head>

<body>

<div class="bow">🎀</div>
<div class="bow">🎀</div>
<div class="bow">🎀</div>

<header>
<h1>🎀 Roxanne B. Figuro 🎀</h1>
<p>My Personal Website</p>
</header>

<nav>
<a href="#about">About</a>
<a href="#education">Education</a>
<a href="#family">Family</a>
<a href="#collection">Collections</a>
<a href="#gallery">Gallery</a>
<a href="#advocacy">Advocacy</a>
</nav>

<div class="container">

<!-- ABOUT -->

<section class="section" id="about">

<div class="profile">

<!-- CHANGE THIS TO YOUR PHOTO -->
<img src="att._tPH1nf4hrcZz_uwAIZO3CXXGj148E3thXRTp4pZJUM.jpeg" alt="Profile Photo">

<h2></h2>

<p>
Hi! Welcome to my personal website.
This website is created to share my personal life, education, family, friends, interests, achievements, and my advocacy for social change.
Through this, you will know more about me as a student, daughter, friend, and as a person with dreams and goals in life.
</p>

<div class="info-grid">

<div class="card">
<strong>Name</strong><br>
Roxanne B. Figuro
</div>

<div class="card">
<strong>Age</strong><br>
19 Years Old
</div>

<div class="card">
<strong>Birthdate</strong><br>
September 01, 2006
</div>

<div class="card">
<strong>Favorite Colors</strong><br>
Pink 💗 & Yellow 💛
</div>

</div>

</div>

</section>

<!-- EDUCATION -->

<section class="section" id="education">

<h2>🎓 Educational Background</h2>

<div class="education">
<h3>GS (Elementary)</h3>
<p>
I completed my elementary education at Sumnanga Elementary School.
This is where I learned the basic foundations of reading, writing, and mathematics.
My elementary years helped me build discipline, confidence, and the habit of learning every day.
</p>
</div>

<div class="education">
<h3>HS (High School)</h3>
<p>
I studied high school at Sabtang National School of Fisheries.
</p>
</div>

<div class="education">
<h3>SHS (Senior High School)</h3>
<p>
I completed my senior high school at Our Lady of Perpetual Succor College.
</p>
</div>

<div class="education">
<h3>College</h3>
<p>
I am currently a 1st Year College Student at Lyceum of the Philippines University – Manila.
</p>
</div>

</section>

<!-- FAMILY -->

<section class="section" id="family">

<h2>👨‍👩‍👧‍👦 Family Menu</h2>

<ul class="family-list">
<li><strong>Father:</strong> Teodoro A. Figuro</li>
<li><strong>Mother:</strong> Basilisa B. Figuro</li>
<li><strong>Siblings:</strong> Rizza B. Figuro, Rachel B. Figuro, Rosevail B. Figuro, Richmond B. Figuro, Rich Joshua B. Figuro, Reiven B. Figuro</li>
<li><strong>Grand Parent:</strong> Irene B. Beronque</li>
</ul>

</section>

<!-- COLLECTIONS -->

<section class="section" id="collection">

<h2>💖 Collections & Interests</h2>

<div class="collection-grid">

<div class="collection-card">
<span>👗</span>
<h3>Fashion & Styling</h3>
</div>

<div class="collection-card">
<span>✈️</span>
<h3>Travel to New Places</h3>
</div>

<div class="collection-card">
<span>🧴</span>
<h3>Skincare & Self-Care</h3>
</div>

<div class="collection-card">
<span>📸</span>
<h3>Aesthetic Photography</h3>
</div>

<div class="collection-card">
<span>🖤💗</span>
<h3>BLACKPINK</h3>
</div>

<div class="collection-card">
<span>🎤</span>
<h3>Sabrina Carpenter</h3>
</div>

</div>

</section>

<!-- GALLERY -->


<h2>📸 My Gallery</h2>

<div class="gallery">

<!-- Replace with your photos -->

<img src="att.Xs29Upv91wY1g_WfoqRoUZbaj00G8rwP_mD9vAP9ExA.jpeg" alt="">
<img src="att.s6L3GUiSKHO3_6B6rpdylLX8WM_PVH7kqyN8vwYl2p8.jpeg" alt="">
<img src="att.HwpwiVKIFM0w1qGpImPJ049Ev3tFhenZAWlSaPML-iM.jpeg" alt="">
<img src="att.tfq95l97-SHYqIn3on4MhEQsKxnA96QO9jwyyOAYCug.jpeg" alt="">
<img src="att.yU5sd2U6nFkEWippVgGJ2NdvNSA5ke1IHfa94nbZ5mU.jpeg" alt="">
<img src="att.-n7EC73UwyL-oHKDlfFri2blUXJMIYCREyd3K0nMFlw.jpeg" alt="">
</div>

</div>

</section>

<!-- ADVOCACY -->


<section class="section" id="advocacy">

<h2> Sustainable Developmental Goals </h2>

I believe that everyone can contribute to making the world a better place. 
The Sustainable Development Goals (SDGs) inspire me to be more responsible, caring, and mindful of my actions. By supporting quality education, protecting the environment, promoting equality, and helping those in need, we can create positive change in our communities. Through awareness and collective effort, we can work toward a more sustainable, inclusive, and prosperous future for everyone.
May earth and trees
</div> 

</div>

</section>

</div>

<footer>
🎀 Made with Love by Roxanne B. Figuro 🎀
</footer>

<script>

const galleryImages=document.querySelectorAll('.gallery img');

galleryImages.forEach(img=>{

img.addEventListener('click',()=>{

window.open(img.src,'_blank');

});

});

</script>
