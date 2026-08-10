<!DOCTYPE html>
<html>
<head>
<title>Amrutha Restaurant</title>

<style>
body{
    margin:0;
    font-family:Arial, sans-serif;
    background:#fff8f0;
}

header{
    background:#8B0000;
    color:white;
    padding:20px;
    text-align:center;
}

nav{
    background:#333;
    padding:10px;
    text-align:center;
}

nav a{
    color:white;
    margin:15px;
    text-decoration:none;
}

.hero{
    background:url("restaurant.jpg");
    background-size:cover;
    height:350px;
    display:flex;
    justify-content:center;
    align-items:center;
    color:white;
    text-align:center;
    font-size:35px;
}

.section{
    padding:30px;
    text-align:center;
}

.menu{
    display:flex;
    justify-content:center;
    gap:20px;
    flex-wrap:wrap;
}

.card{
    background:white;
    width:220px;
    padding:20px;
    border-radius:10px;
    box-shadow:0 0 10px gray;
}

button{
    background:#8B0000;
    color:white;
    padding:12px 20px;
    border:none;
    border-radius:5px;
}

footer{
    background:#333;
    color:white;
    text-align:center;
    padding:15px;
}
</style>

</head>

<body>

<header>
<h1>🍽️ Amrutha Restaurant</h1>
<p>Delicious Food | Quality Service | Happy Customers</p>
</header>


<nav>
<a href="#home">Home</a>
<a href="#menu">Menu</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</nav>


<div class="hero" id="home">
<h2>Welcome to Amrutha Restaurant</h2>
</div>


<div class="section" id="about">

<h2>About Us</h2>

<p>
Amrutha Restaurant provides delicious traditional and modern cuisine
with fresh ingredients and excellent service.
Our goal is to provide every customer with a memorable dining experience.
</p>

</div>



<div class="section" id="menu">

<h2>Our Special Menu</h2>

<div class="menu">

<div class="card">
<h3>🍛 Veg Meals</h3>
<p>₹180</p>
</div>

<div class="card">
<h3>🍗 Chicken Biryani</h3>
<p>₹250</p>
</div>


<div class="card">
<h3>🥘 Paneer Special</h3>
<p>₹220</p>
</div>


<div class="card">
<h3>🍨 Desserts</h3>
<p>₹120</p>
</div>

</div>

</div>



<div class="section" id="contact">

<h2>Contact Us</h2>

<p>
📍 Chennai, Tamil Nadu
</p>

<p>
📞 +91 9876543210
</p>

<p>
Open: 11 AM - 11 PM
</p>


<a href="https://wa.me/919876543210">
<button>Order on WhatsApp</button>
</a>


</div>



<footer>

<p>© 2026 Amrutha Restaurant | All Rights Reserved</p>

</footer>


</body>
</html>