<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Cloth Portal</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to Online Cloth Portal</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#">Products</a>
            <a href="#">About Us</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <section id="products">
        <h2>Our Products</h2>
        <div class="product-list">
            <div class="product-item">
                <img src="shirt.jpg" alt="Shirt">
                <h3>Casual Shirt</h3>
                <p>$20</p>
                <button onclick="addToCart('Casual Shirt', 20)">Add to Cart</button>
            </div>
            <div class="product-item">
                <img src="jeans.jpg" alt="Jeans">
                <h3>Denim Jeans</h3>
                <p>$30</p>
                <button onclick="addToCart('Denim Jeans', 30)">Add to Cart</button>
            </div>
        </div>
    </section>

    <section id="cart">
        <h2>Your Cart</h2>
        <ul id="cart-items"></ul>
        <button onclick="checkout()">Checkout</button>
    </section>

    <script src="script.js"></script>
</body>
</html>

