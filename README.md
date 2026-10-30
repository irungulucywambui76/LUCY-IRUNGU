
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>PIM MEAT GO | Meat Suppliers Nairobi Kenya</title>

<meta name="description" content="PIM MEAT GO supplies beef, goat meat, chicken, lamb, pork and fish to hotels, restaurants and supermarkets in Nairobi, Kenya.">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
}

header {
    background: #173d29;
    color: white;
    padding: 18px 7%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}

.logo {
    color: #f2bd55;
    font-size: 27px;
    font-weight: bold;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 10px;
    font-weight: bold;
}

nav a:hover {
    color: #f2bd55;
}

.hero {
    min-height: 500px;
    background:
    linear-gradient(#0009, #0009),
    url('https://images.unsplash.com/photo-1607623814075-e51df1bdc82f?auto=format&fit=crop&w=1600&q=80');
    background-size: cover;
    background-position: center;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 30px;
}

.hero h1 {
    font-size: 50px;
    margin-bottom: 15px;
}

.hero p {
    font-size: 21px;
    margin-bottom: 25px;
}

.btn {
    display: inline-block;
    background: #d69a32;
    color: #173d29;
    padding: 13px 25px;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
    margin: 5px;
}

.btn:hover {
    background: #f2bd55;
}

section {
    padding: 65px 8%;
    text-align: center;
}

h2 {
    color: #173d29;
    font-size: 32px;
    margin-bottom: 20px;
}

.about {
    background: #f2f5ef;
}

.products {
    display: grid;
    grid-template-columns:
    repeat(auto-fit, minmax(220px, 1fr));
    gap: 25px;
    margin-top: 35px;
}

.product {
    background: #f7f7f2;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 3px 10px #0001;
    padding-bottom: 20px;
}

.product img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.product h3 {
    color: #173d29;
    margin: 15px;
}

.services {
    background: #173d29;
    color: white;
}

.services h2 {
    color: #f2bd55;
}

.service-list {
    display: grid;
    grid-template-columns:
    repeat(auto-fit, minmax(200px, 1fr));
    gap: 25px;
    margin-top: 30px;
}

.service {
    background: #28533b;
    padding: 30px 20px;
    border-radius: 10px;
}

.contact {
    background: #f2f5ef;
}

.contact-details {
    margin: 25px auto;
    line-height: 2;
}

footer {
    background: #102b1d;
    color: white;
    text-align: center;
    padding: 25px;
}

@media(max-width: 600px) {
    header {
        justify-content: center;
        gap: 15px;
    }

    nav {
        text-align: center;
    }

    nav a {
        display: inline-block;
        margin: 5px;
    }

    .hero h1 {
        font-size: 35px;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">PIM MEAT GO</div>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#products">Products</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<div class="hero" id="home">

    <h1>PIM MEAT GO</h1>

    <p>Quality Meat. Reliable Supply. Every Time.</p>

    <p>Your Trusted Meat Supply Partner in Nairobi, Kenya.</p>

    <a href="#products" class="btn">
        Explore Our Products
    </a>

    <a href="#contact" class="btn">
        Contact Us
    </a>

</div>

<section class="about" id="about">

    <h2>About PIM MEAT GO</h2>

    <p>
    PIM MEAT GO is a meat supply business based in
    Nairobi, Kenya.

    We specialize in supplying quality meat products
    to hotels, restaurants and supermarkets.

    Our commitment is to provide dependable supply,
    excellent customer service and convenient delivery
    within Nairobi.
    </p>

</section>

<section id="products">

    <h2>Our Products</h2>

    <p>
    We supply a variety of meat products to meet
    the needs of our business customers.
    </p>

    <div class="products">

        <div class="product">
            <img src="https://images.unsplash.com/photo-1607623814075-e51df1bdc82f?w=600"
            alt="Beef meat">
            <h3>Beef</h3>
            <p>Quality beef products for businesses.</p>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1602470520998-f4a52199a3d6?w=600"
            alt="Goat meat">
            <h3>Goat Meat</h3>
            <p>Goat meat supply for our customers.</p>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1604503468506-a8da13d82791?w=600"
            alt="Chicken">
            <h3>Chicken</h3>
            <p>Chicken products for hotels and restaurants.</p>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1608039829572-78524f79c4c7?w=600"
            alt="Lamb meat">
            <h3>Lamb</h3>
            <p>Quality lamb meat products.</p>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1529193591184-b1d58069ecdd?w=600"
            alt="Pork">
            <h3>Pork</h3>
            <p>Pork products for business customers.</p>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1510130387422-82bed34b37e9?w=600"
            alt="Fish">
            <h3>Fish</h3>
            <p>Fish supply for our customers.</p>
        </div>

    </div>

</section>

<section class="services" id="services">

    <h2>Who We Supply</h2>

    <div class="service-list">

        <div class="service">
            <h3>Hotels</h3>
            <p>
            Dependable meat supply for hotel kitchens
            and hospitality businesses.
            </p>
        </div>

        <div class="service">
            <h3>Restaurants</h3>
            <p>
            Quality meat products for restaurants
            and food service businesses.
            </p>
        </div>

        <div class="service">
            <h3>Supermarkets</h3>
            <p>
            Meat supply solutions for supermarket
            businesses.
            </p>
        </div>

        <div class="service">
            <h3>Nairobi Delivery</h3>
            <p>
            Delivery arrangements for customers
            within Nairobi.
            </p>
        </div>

    </div>

</section>

<section class="contact" id="contact">

    <h2>Contact PIM MEAT GO</h2>

    <p>
    Looking for a reliable meat supply partner
    in Nairobi? Contact us today.
    </p>

    <div class="contact-details">

        <p><strong>Business:</strong> PIM MEAT GO</p>

        <p><strong>Location:</strong> Nairobi, Kenya</p>

        <p><strong>Phone:</strong> 0140843017</p>

        <p><strong>Email:</strong>
        pimmeatgokenya.ac.ke</p>

        <p><strong>Delivery:</strong> Within Nairobi</p>

    </div>

    <a href="tel:0140843017" class="btn">
        Call Us
    </a>

    <a href="https://wa.me/254140843017"
       class="btn">
        WhatsApp Us
    </a>

    <a href="mailto:pimmeatgokenya.ac.ke"
       class="btn">
        Email Us
    </a>

</section>

<footer>

    <h3>PIM MEAT GO</h3>

    <p>Quality Meat. Reliable Supply. Every Time.</p>

    <p>Nairobi, Kenya</p>

    <p>
    &copy; 2026 PIM MEAT GO.
    All Rights Reserved.
    </p>

</footer>

</body>
</html>
