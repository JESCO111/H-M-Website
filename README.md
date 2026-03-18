<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>H & M Outdoor Design</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    color: #333;
}

header {
    background: url('https://images.unsplash.com/photo-1501004318641-b39e6451bec6') center/cover no-repeat;
    color: white;
    text-align: center;
    padding: 100px 20px;
}

header h1 {
    font-size: 3em;
}

nav {
    background: #2f5d34;
    padding: 15px;
    text-align: center;
}

nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
}

.section {
    padding: 60px 20px;
    text-align: center;
}

.services {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 25px;
}

.card {
    width: 300px;
    background: #f4f4f4;
    border-radius: 10px;
    overflow: hidden;
}

.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 10px;
}

.gallery img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.cta {
    background: #2f5d34;
    color: white;
    padding: 50px 20px;
}

button {
    padding: 15px 25px;
    font-size: 16px;
    border: none;
    background: white;
    color: #2f5d34;
    cursor: pointer;
}

footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 20px;
}
</style>
</head>

<body>

<header>
    <h1>H & M Outdoor Design</h1>
    <p>Landscaping & Masonry Experts</p>
    <p>Serving Central NJ Since 2018</p>
</header>

<nav>
    <a href="#services">Services</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
</nav>

<section id="services" class="section">
    <h2>Our Services</h2>

    <div class="services">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1622396636133-ba43f812bc35">
            <h3>Lawn Cutting</h3>
            <p>Clean, reliable mowing and lawn maintenance.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1598511727492-8c1c4c5c9b6d">
            <h3>Landscaping</h3>
            <p>Custom outdoor design and planting services.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1600566752355-35792bedcfea">
            <h3>Masonry</h3>
            <p>Patios, walkways, retaining walls & stone work.</p>
        </div>
    </div>
</section>

<section id="gallery" class="section">
    <h2>Our Work</h2>

    <div class="gallery">
        <img src="https://images.unsplash.com/photo-1600585152220-90363fe7e115">
        <img src="https://images.unsplash.com/photo-1597007030739-6d2e7f6b1b2b">
        <img src="https://images.unsplash.com/photo-1501594907352-04cda38ebc29">
        <img src="https://images.unsplash.com/photo-1600607687920-4e2a09cf159d">
        <img src="https://images.unsplash.com/photo-1600573472550-8090b5e0745e">
        <img src="https://images.unsplash.com/photo-1591825729269-caeb344f6df2">
    </div>
</section>

<section class="cta">
    <h2>Call or Text for a Free Estimate</h2>
    <button onclick="window.location.href='tel:9082943297'">📞 908-294-3297</button>
</section>

<section id="contact" class="section">
    <h2>Contact</h2>
    <p>Plainfield, NJ 07060</p>
    <p>Serving Middlesex, Somerset & Union County</p>
    <p>Call/Text: <strong>908-294-3297</strong></p>
</section>

<footer>
    <p>© 2025 H & M Outdoor Design</p>
</footer>

</body>
</html>
