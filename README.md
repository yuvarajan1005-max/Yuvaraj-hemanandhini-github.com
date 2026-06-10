<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hemanandhini ❤️ Yuvaraj Wedding Invitation</title>

<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;600&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:'Poppins',sans-serif;
background:#fff8f2;
color:#333;
overflow-x:hidden;
}

.hero{
height:100vh;
background:
linear-gradient(rgba(0,0,0,.45),rgba(0,0,0,.45)),
url('traditional-photo.jpg');
background-size:cover;
background-position:center;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
color:white;
padding:20px;
}

.hero-content h1{
font-size:4rem;
font-family:'Cinzel',serif;
}

.hero-content h2{
font-size:2rem;
margin:20px 0;
}

.hero-content p{
font-size:1.2rem;
}

.btn{
display:inline-block;
margin-top:25px;
padding:12px 30px;
background:#c49b38;
color:white;
text-decoration:none;
border-radius:30px;
}

.section{
padding:70px 20px;
text-align:center;
}

.section h2{
font-size:2.5rem;
color:#8b0000;
margin-bottom:20px;
font-family:'Cinzel',serif;
}

.countdown{
display:flex;
justify-content:center;
gap:20px;
flex-wrap:wrap;
margin-top:20px;
}

.box{
background:#8b0000;
color:white;
padding:20px;
border-radius:15px;
width:120px;
}

.box span{
font-size:2rem;
font-weight:bold;
display:block;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:20px;
padding:20px;
}

.gallery img{
width:100%;
border-radius:15px;
box-shadow:0 5px 20px rgba(0,0,0,.15);
}

.card{
max-width:700px;
margin:auto;
background:white;
padding:30px;
border-radius:20px;
box-shadow:0 5px 25px rgba(0,0,0,.1);
}

.footer{
background:#8b0000;
color:white;
padding:40px;
text-align:center;
}

.tamil{
font-size:1.1rem;
margin-top:10px;
}

.floral{
font-size:40px;
color:#c49b38;
margin-bottom:10px;
}

@media(max-width:768px){
.hero-content h1{
font-size:2.4rem;
}
.hero-content h2{
font-size:1.3rem;
}
}
</style>
</head>

<body>

<section class="hero">
<div class="hero-content">
<div class="floral">🌸🌺🌸</div>

<h1>Hemanandhini S</h1>
<h2>❤️</h2>
<h1>Yuvaraj V</h1>

<p>Two Hearts • One Journey • Forever Together</p>

<a href="#countdown" class="btn">View Invitation</a>
</div>
</section>

<section class="section" id="countdown">
<h2>Wedding Countdown</h2>

<div class="countdown">
<div class="box">
<span id="days">0</span>
Days
</div>

<div class="box">
<span id="hours">0</span>
Hours
</div>

<div class="box">
<span id="minutes">0</span>
Minutes
</div>

<div class="box">
<span id="seconds">0</span>
Seconds
</div>
</div>
</section>

<section class="section">
<h2>திருமண அழைப்பிதழ்</h2>

<div class="card">

<h3>Wedding Ceremony</h3>

<p><strong>Date:</strong> 25 June 2026</p>
<p><strong>Time:</strong> 7:00 AM – 9:30 AM</p>
<p><strong>Venue:</strong> Vadapalani Murugan Temple, Katupakkam</p>

<br>

<p class="tamil">
எங்கள் குடும்பத்தினரின் ஆசீர்வாதத்துடன்
எங்கள் திருமண விழாவில் கலந்து கொண்டு
எங்களை வாழ்த்துமாறு அன்புடன் அழைக்கிறோம்.
</p>

</div>
</section>

<section class="section">
<h2>Reception</h2>

<div class="card">

<p><strong>Date:</strong> 28 June 2026</p>
<p><strong>Time:</strong> 6:30 PM – 9:30 PM</p>
<p><strong>Venue:</strong> Saritha Mahal, Porur</p>

</div>
</section>

<section class="section">
<h2>Our Story</h2>

<div class="gallery">

<img src="beach-photo.jpg" alt="">
<img src="guitar-photo.jpg" alt="">
<img src="traditional-photo.jpg" alt="">

</div>
</section>

<section class="section">
<h2>Bless Us With Your Presence</h2>

<p>
Your presence will make our celebration
more joyful and memorable.
</p>

<br>

<p class="tamil">
தங்களின் வருகையே
எங்கள் மகிழ்ச்சியை முழுமையாக்கும்.
</p>

</section>

<footer class="footer">

<h2>Hemanandhini ❤️ Yuvaraj</h2>

<p>25 June 2026</p>

</footer>

<script>

const weddingDate =
new Date("June 25, 2026 07:00:00").getTime();

setInterval(() => {

const now = new Date().getTime();

const distance = weddingDate - now;

document.getElementById("days").innerHTML =
Math.floor(distance/(1000*60*60*24));

document.getElementById("hours").innerHTML =
Math.floor((distance%(1000*60*60*24))/(1000*60*60));

document.getElementById("minutes").innerHTML =
Math.floor((distance%(1000*60*60))/(1000*60));

document.getElementById("seconds").innerHTML =
Math.floor((distance%(1000*60))/1000);

},1000);

</script>

</body>
</html>
