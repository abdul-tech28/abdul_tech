<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NASTRA</title>

    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
        rel="stylesheet">

    <!-- My CSS -->
    <link rel="stylesheet" href="style.css">

    <!-- font awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.3.1/css/all.css"
        integrity="sha512-x9WwyMYBnlXMNQ6kQ/Lyzu1NqIhLQKL5Oq6xByfXuRj7s9CskyCbLv/1IjqzJmXwFXWr0ov6jBV7Qbc0hh9nHg=="
        crossorigin="anonymous" referrerpolicy="no-referrer">

</head>
<body>
    <!-- Navbar -->
    <nav class="navbar">
        <h1>NASTRA</h1>
        <div class="nav-links">
            <p class="nav-link"><a href="index.html">Home</a></p>
            <p class="nav-link"><a href="collection.html">Collections</a></p>
            <p class="nav-link"><a href="contact.html">Contact</a></p>
        </div>
        <div class="nav-icons" onclick="openNav()">
            <i class="fa-solid fa-bars"></i>
        </div>
    </nav>

    <!-- Side navbar -->
    <div class="side-navbar">
        <p style="text-align: right;" onclick="closeNav()">
            <i class="fa-solid fa-xmark"></i>
        </p>
        <div class="side-links">
            <p class="side-link"><a href="index.html">Home</a></p>
            <p class="side-link"><a href="collection.html">Collections</a></p>
            <p class="side-link"><a href="contact.html">Contact</a></p>
        </div>
    </div>
    <!-- products -->
    <div class="product-section">
        <form class="product-search">
            <input type="text" id="search" placeholder="Search">
            <i class="fa-solid fa-magnifying-glass"></i>
        </form>

        <div class="products" id="products">
            <div class="product-box">
                <img src="https://images.unsplash.com/photo-1596755389378-c31d21fd1273?w=200" width="200" height="200"
                    alt="Casual Shirt">
                <p>Casual Shirt</p>
            </div>
            <div class="product-box">
                <img src="https://images.unsplash.com/photo-1602810318383-e386cc2a3ccf?w=200" width="200" height="200"
                    alt="Formal Shirt">
                <p>Formal Shirt</p>
            </div>
            <div class="product-box">
                <img src="https://images.unsplash.com/photo-1603252109303-2751441dd157?w=200" width="200" height="200"
                    alt="White Shirt">
                <p>White Shirt</p>
            </div>
            <div class="product-box">
                <img src="https://images.unsplash.com/photo-1620012253295-c15cc3e65df4?w=200" width="200" height="200"
                    alt="Printed Shirt">
                <p>Printed Shirt</p>
            </div>
            <div class="product-box">
                <img src="https://images.unsplash.com/photo-1598032895397-b9472444bf93?w=200" width="200" height="200"
                    alt="Cotton Shirt">
                <p>Cotton Shirt</p>
            </div>
            <div class="product-box">
                <img src="https://images.unsplash.com/photo-1542272604-787c3835535d?w=200" width="200" height="200"
                    alt="Blue Jeans">
                <p>Blue Jeans</p>
            </div>
            <div class="product-box">
                <img src="https://images.unsplash.com/photo-1541099649105-f69ad21f3246?w=200" width="200" height="200"
                    alt="Denim Jeans">
                <p>Denim Jeans</p>
            </div>
            <div class="product-box">
                <img src="https://images.unsplash.com/photo-1624378439575-d8705ad7ae80?w=200" width="200" height="200"
                    alt="Black Pants">
                <p>Black Pants</p>
            </div>
            <div class="product-box">
                <img src="https://images.unsplash.com/photo-1473966968600-fa801b869a1a?w=200" width="200" height="200"
                    alt="Casual Pants">
                <p>Casual Pants</p>
            </div>
            <div class="product-box">
                <img src="https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?w=200" width="200" height="200"
                    alt="Fashion Pants">
                <p>Fashion Pants</p>
            </div>
            <div class="product-box">
                <img src="https://images.unsplash.com/photo-1602810318383-e386cc2a3ccf?w=600" alt="Shirt" width="200"
                    height="200">
                <p>Navy Blue Pants</p>
            </div>
            <div class="product-box">
                <img src="https://images.unsplash.com/photo-1473966968600-fa801b869a1a?w=200" width="200" height="200"
                    alt="Gray Pants">
                <p>Gray Pants</p>
            </div>
        </div>
    </div>

    <!-- FOOTER -->
    <div class="footer">
        <div class="footer-box">
            <h2 class="heading-txt">Contact Us</h2>
            <p>if you have any questions, feel free to contact us! and we'll get back to you as soon
                as possible. and any problems you encounter, please let us know.</p>
            <div class="footer-icon-box">
                <i class="fa-brands fa-instagram" style="color: #ffffff;"></i>
                <i class="fa-brands fa-facebook" style="color: #ffffff;"></i>
                <i class="fa-brands fa-twitter" style="color: #ffffff;"></i>
            </div>
        </div>
        <p>@ 2023 Your Company. All rights reserved.</p>
    </div>

    <script src="collection.js"></script>
</body>

</html>            
