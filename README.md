<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AyurvedaGlow - Premium Ayurvedic Hair Oil</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
        
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #fff5e1;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background: #8fbc8f;
            padding: 20px;
            font-size: 35px;
            color: #fff;
            font-weight: bold;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .logo-text {
            display: flex;
            align-items: center;
            gap: 15px;
        }
        .logo-text img {
            height: 60px;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #6fa76f;
            padding: 15px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
            font-weight: bold;
        }
        .container {
            padding: 40px 20px;
            text-align: center;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .product-card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
            text-align: left;
            transition: transform 0.3s ease-in-out;
        }
        .product-card:hover {
            transform: translateY(-5px);
        }
        .product-card img {
            width: 100%;
            border-radius: 10px;
            height: 250px;
            object-fit: cover;
        }
        .product-card h3, .product-card p {
            margin-left: 10px;
        }
        .buy-btn {
            display: block;
            width: max-content;
            padding: 10px 20px;
            background: #6fa76f;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin: 10px auto;
            font-weight: bold;
        }
        .about, .contact {
            text-align: center;
            padding: 40px;
            background: #8fbc8f;
            color: white;
        }
        .about h2, .contact h2 {
            font-size: 28px;
            margin-bottom: 15px;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo-text">
            <img src="https://i.postimg.cc/5tVhLJMJ/IMG-20250404-WA0013.jpg" alt="AyurvedaGlow Logo">
            <span>AyurvedaGlow</span>
        </div>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#collection">Collection</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="about" id="about">
        <h2>About Us</h2>
        <p>Experience the magic of nature with AyurvedaGlow – your premium Ayurvedic hair oil for healthy, shiny, and strong hair.</p>
    </div>
    <div class="container" id="collection">
        <h2>Our Ayurvedic Hair Oil Collection</h2>
        <div class="product-grid">
            <div class="product-card">
                <img src="https://i.postimg.cc/Cxy2b7sV/IMG-20250404-WA0010.jpg" alt="AyurvedaGlow Nourishing Oil">
                <h3>AyurvedaGlow Amla Nourishing Oil</h3>
                <p>A blend of herbs for deep nourishment and healthy growth.</p>
                <p>Price: ₹799</p>
                <a href="#" class="buy-btn">Buy Now</a>
            </div>
            <div class="product-card">
                <img src="https://i.postimg.cc/jdypgB5j/IMG-20250404-WA0012.jpg" alt="AyurvedaGlow Anti-Dandruff Oil">
                <h3>AyurvedaGlow Anti-Dandruff Oil</h3>
                <p>Say goodbye to dandruff with this herbal formula.</p>
                <p>Price: ₹899</p>
                <a href="#" class="buy-btn">Buy Now</a>
            </div>
            <div class="product-card">
                <img src="https://i.postimg.cc/FKwGQsCX/IMG-20250404-WA0011.jpg" alt="AyurvedaGlow Revitalizing Oil">
                <h3>AyurvedaGlow Revitalizing Oil</h3>
                <p>Revitalize your scalp and hair with this rejuvenating blend.</p>
                <p>Price: ₹999</p>
                <a href="#" class="buy-btn">Buy Now</a>
            </div>
        </div>
    </div>
    <div class="contact" id="contact">
        <h2>Contact Us</h2>
        <p>Email: ayurvedaglow@gmail.com</p>
        <p>Phone: 8798023091</p>
    </div>
</body>
</html>
