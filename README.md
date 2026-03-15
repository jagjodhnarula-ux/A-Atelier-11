```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>A'Atelier 11</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Montserrat:wght@300;400&display=swap" rel="stylesheet">

<style>

body{
margin:0;
font-family: 'Montserrat', sans-serif;
background:#0B1F3A;
color:white;
}

header{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 60px;
border-bottom:1px solid rgba(255,255,255,0.2);
}

.logo{
font-family:'Playfair Display', serif;
font-size:32px;
letter-spacing:2px;
}

nav a{
margin-left:30px;
text-decoration:none;
color:white;
font-size:14px;
letter-spacing:1px;
}

.hero{
height:80vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
}

.hero h1{
font-family:'Playfair Display', serif;
font-size:64px;
margin:0;
}

.hero p{
margin-top:15px;
font-size:18px;
opacity:0.8;
}

.btn{
margin-top:30px;
padding:12px 30px;
border:1px solid white;
color:white;
text-decoration:none;
transition:0.3s;
}

.btn:hover{
background:white;
color:#0B1F3A;
}

.collection{
padding:80px 10%;
text-align:center;
}

.collection h2{
font-family:'Playfair Display', serif;
font-size:36px;
margin-bottom:40px;
}

.products{
display:flex;
gap:30px;
justify-content:center;
flex-wrap:wrap;
}

.card{
background:white;
color:black;
padding:20px;
width:220px;
}

footer{
text-align:center;
padding:30px;
border-top:1px solid rgba(255,255,255,0.2);
margin-top:60px;
font-size:14px;
}

</style>
</head>

<body>

<header>
<div class="logo">A'Atelier 11</div>

<nav>
<a href="#">Home</a>
<a href="#">Collection</a>
<a href="#">About</a>
<a href="#">Contact</a>
</nav>
</header>

<section class="hero">
<h1>Luxury Fashion</h1>
<p>Elegance in Every Stitch</p>
<a href="#" class="btn">Shop Collection</a>
</section>

<section class="collection">
<h2>Featured Collection</h2>

<div class="products">

<div class="card">
<h3>Classic Tee</h3>
<p>$49</p>
</div>

<div class="card">
<h3>Luxury Hoodie</h3>
<p>$89</p>
</div>

<div class="card">
<h3>Premium Jacket</h3>
<p>$149</p>
</div>

</div>
</section>

<footer>
© 2026 A'Atelier 11 – All Rights Reserved
</footer>

</body>
</html>
```
