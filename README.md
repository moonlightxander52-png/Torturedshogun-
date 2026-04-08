<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tortured Shogun</title>

<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Inter', sans-serif;
    background: #0b0b0b;
    color: white;
}

/* NAV */
nav {
    display: flex;
    justify-content: space-between;
    padding: 20px 10%;
    background: rgba(0,0,0,0.9);
    border-bottom: 1px solid #222;
}

nav h1 {
    font-family: 'Orbitron';
    letter-spacing: 2px;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
}

/* HERO */
.hero {
    height: 90vh;
    background: linear-gradient(to bottom, rgba(0,0,0,0.7), #0b0b0b),
    url('https://images.unsplash.com/photo-1549887534-3ec93abae9f8');
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    padding: 0 10%;
}

.hero-text h2 {
    font-size: 3rem;
    font-family: 'Orbitron';
}

.hero-text p {
    margin: 15px 0;
    color: #ccc;
}

.btn {
    padding: 12px 25px;
    background: crimson;
    border: none;
    color: white;
    cursor: pointer;
    transition: 0.3s;
}

.btn:hover {
    background: darkred;
}

/* PRODUCTS */
.products {
    padding: 60px 10%;
}

.products h2 {
    text-align: center;
    margin-bottom: 40px;
    font-family: 'Orbitron';
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
}

.card {
    background: #111;
    padding: 20px;
    border: 1px solid #222;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-5px);
    border-color: crimson;
}

.card img {
    width: 100%;
}

.card h3 {
    margin: 10px 0;
}

.price {
    color: crimson;
}

/* ABOUT */
.about {
    padding: 60px 10%;
    background: #111;
    text-align: center;
}

.about h2 {
    font-family: 'Orbitron';
    margin-bottom: 20px;
}

/* FOOTER */
footer {
    padding: 20px;
    text-align: center;
    border-top: 1px solid #222;
    color: #aaa;
}
</style>
</head>

<body>

<!-- NAV -->
<nav>
    <h1>TORTURED SHOGUN</h1>
    <div>
        <a href="#">Shop</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </div>
</nav>

<!-- HERO -->
<section class="hero">
    <div class="hero-text">
        <h2>VOL. 1 DROP — SILENT WAR</h2>
        <p>Beauty born from suffering.</p>
        <button class="btn">Shop Now</button>
    </div>
</section>

<!-- PRODUCTS -->
<section class="products">
    <h2>FEATURED DROP</h2>

    <div class="grid">
        <div class="card">
            <img src="https://via.placeholder.com/400x500" alt="">
            <h3>Silent Shogun Hoodie</h3>
            <p class="price">$80</p>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/400x500" alt="">
            <h3>Blossom Pain Hoodie</h3>
            <p class="price">$85</p>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/400x500" alt="">
            <h3>No Mercy Code Hoodie</h3>
            <p class="price">$90</p>
        </div>
    </div>
</section>

<!-- ABOUT -->
<section class="about">
    <h2>THE BRAND</h2>
    <p>
        Tortured Shogun represents discipline, pain, and transformation.
        Every piece tells a story — forged through struggle and built for those
        who move in silence but strike with purpose.
    </p>
</section>

<!-- FOOTER -->
<footer>
    <p>© 2026 Tortured Shogun. Limited Drop.</p>
</footer>

</body>
</html># Torturedshogun-
