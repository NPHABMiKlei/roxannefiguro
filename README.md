# roxannefiguro
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Roxanne B. Figuro | Personal Website</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Poppins',sans-serif;
    background:
    radial-gradient(#ffd6e7 2px, transparent 2px),
    radial-gradient(#fff3a6 2px, transparent 2px),
    #f7f3e9;
    background-size:40px 40px;
    background-position:0 0,20px 20px;
    color:#5b4a42;
}

header{
    background:linear-gradient(135deg,#f7d8e7,#d8f0d2);
    text-align:center;
    padding:60px 20px;
    border-bottom:5px dashed #ffc0cb;
}

header h1{
    font-family:'Playfair Display',serif;
    font-size:3rem;
    color:#c75c8c;
}

header p{
    margin-top:10px;
    font-size:1.1rem;
}

nav{
    background:#fff8fc;
    padding:15px;
    text-align:center;
    position:sticky;
    top:0;
    z-index:100;
    box-shadow:0 2px 10px rgba(0,0,0,.1);
}

nav a{
    text-decoration:none;
    color:#c75c8c;
    margin:0 15px;
    font-weight:600;
}

nav a:hover{
    color:#8db58c;
}

.container{
    width:90%;
    max-width:1100px;
    margin:auto;
    padding:40px 0;
}

.section{
    background:white;
    padding:30px;
    margin-bottom:30px;
    border-radius:25px;
    box-shadow:0 8px 20px rgba(0,0,0,.08);
    border:3px solid #ffe4ef;
}

.section h2{
    color:#c75c8c;
    margin-bottom:15px;
    font-family:'Playfair Display',serif;
}

.profile-card{
    text-align:center;
}

.profile-card img{
    width:180px;
    height:180px;
    border-radius:50%;
    object-fit:cover;
    border:6px solid #ffd4e5;
    margin-bottom:20px;
}

.info{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:15px;
    margin-top:20px;
}

.box{
    background:#fff8fc;
    padding:15px;
    border-radius:15px;
    border:2px dashed #ffd4e5;
}

.education-item{
    margin-bottom:20px;
    padding:15px;
    background:#fdf9f2;
    border-left:5px solid #cfe9c9;
    border-radius:10px;
}

.family-list li,
.collection-list li{
    margin:10px 0;
}

footer{
    text-align:center;
    padding:25px;
    background:#fff8fc;
    color:#c75c8c;
    font-weight:500;
}

.bow{
    position:fixed;
    font-size:25px;
    animation:float 8s infinite linear;
    opacity:.4;
}

.bow:nth-child(1){
    left:10%;
    animation-duration:10s;
}

.bow:nth-child(2){
    left:50%;
    animation-duration:12s;
}

.bow:nth-child(3){
    left:80%;
    animation-duration:9s;
}

@keyframes float{
    from{
        top:100%;
    }
    to{
        top:-10%;
    }
}

.collection-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:15px;
    margin-top:15px;
}

.collection-card{
    background:#fff8fc;
    padding:20px;
    border-radius:15px;
    text-align:center;
    border:2px dashed #ffd4e5;
}

.collection-card:hover{
    transform:translateY(-5px);
    transition:.3s;
}

@media(max-width:768px){
header h1{
font-size:2.2rem;
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
<p>Personal Website</p>
</header>

<nav>
<a href="#about">About Me</a>
<a href="#education">Education</a>
<a href="#family">Family</a>
<a href="#collection">Collections</a>
</nav>

<div class="container">

<section id="about" class="section">
<div class="profile-card">

<!-- Replace profile.jpg with your image -->
<img src="att._tPH1nf4hrcZz_uwAIZO3CXXGj148E3thXRTp4pZJUM.jpeg" alt="Roxanne">

<h2>Welcome Message</h2>

<p>
Hi! Welcome to my personal website.
This website is created to share my personal life, education,
family, friends, interests, achievements, and my advocacy for social change.
Through this, you will know more about me as a student, daughter,
friend, and as a person with dreams and goals in life.
</p>

<div class="info">

<div class="box">
<strong>Name:</strong><br>
Roxanne B. Figuro
</div>

<div class="box">
<strong>Age:</strong><br>
19 Years Old
</div>

<div class="box">
<strong>Birthdate:</strong><br>
September 01, 2006
</div>

<div class="box">
<strong>Favorite Colors:</strong><br>
Pink & Yellow 💖💛
</div>

</div>

</div>
</section>

<section id="education" class="section">
<h2>🎓 Educational Background</h2>

<div class="education-item">
<h3>GS (Elementary)</h3>
<p>
I completed my elementary education at Sumnanga Elementary School.
This is where I learned the basic foundations of reading, writing,
and mathematics. My elementary years helped me build discipline,
confidence, and the habit of learning every day.
</p>
</div>

<div class="education-item">
<h3>HS (High School)</h3>
<p>
I studied high school at Sabtang National School of Fisheries.
</p>
</div>

<div class="education-item">
<h3>SHS (Senior High School)</h3>
<p>
I completed my senior high school at Our Lady of Perpetual Succor College.
</p>
</div>

<div class="education-item">
<h3>College</h3>
<p>
I am currently a 1st Year College Student at
Lyceum of the Philippines University – Manila.
</p>
</div>

</section>

<section id="family" class="section">
<h2>👨‍👩‍👧‍👦 Family Menu</h2>

<ul class="family-list">
<li><strong>Father:</strong> Teodoro A. Figuro</li>
<li><strong>Mother:</strong> Basilisa B. Figuro</li>
<li><strong>Siblings:</strong> Rizza B. Figuro, Rachel B. Figuro, Rosevail B. Figuro, Richmond B. Figuro, Rich Joshua B. Figuro, Reiven B. Figuro</li>
<li><strong>Grand Parent:</strong> Irene B. Beronque</li>
</ul>

</section>

<section id="collection" class="section">
<h2>💖 Collection Menu</h2>

<div class="collection-grid">

<div class="collection-card">
👗
<h3>Fashion & Styling</h3>
<p>Expressing creativity through outfits and personal style.</p>
</div>

<div class="collection-card">
✈️
<h3>Travel</h3>
<p>Exploring new places and creating unforgettable memories.</p>
</div>

<div class="collection-card">
🧴
<h3>Skincare & Self-Care</h3>
<p>Maintaining wellness, confidence, and healthy habits.</p>
</div>

<div class="collection-card">
📸
<h3>Aesthetic Photography</h3>
<p>Capturing beautiful moments and artistic scenery.</p>
</div>

<div class="collection-card">
🖤💗
<h3>BLACKPINK</h3>
<p>Enjoying music, performances, and inspiration from BLACKPINK.</p>
</div>

<div class="collection-card">
🎤
<h3>Sabrina Carpenter</h3>
<p>Listening to music and following her creative journey.</p>
</div>

</div>

</section>

</div>

<footer>
🎀 Made with Love by Roxanne B. Figuro | Strawberry Matcha Coquette Theme 🎀
</footer>

<script>
document.querySelectorAll('nav a').forEach(anchor=>{
anchor.addEventListener('click',function(e){
e.preventDefault();
document.querySelector(this.getAttribute('href'))
.scrollIntoView({
behavior:'smooth'
});
});
});
</script>

</body>
</html>
