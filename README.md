# african-imported-jewelries
#html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>African Imported Jewelries and More</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">How to Sell</a></li>
                <li><a href="#">FAQ</a></li>
                <li><a href="#">USA: 00011122233300000</a></li>
                <li><a href="#">Login</a></li>
            </ul>
        </nav>
    </header>
    
    <section class="welcome">
        <h1>Welcome to African Imported Jewelries and More</h1>
    </section>
    
    <section class="products">
        <h2>Our Products</h2>
        <div class="product">
            <img src="images/jewelry1.jpg" alt="Jewelry 1" onerror="this.onerror=null;this.src='images/placeholder.png';">
            <p>Beautiful handcrafted jewelry from Africa.</p>
        </div>
    </section>

    <footer>
        <div class="footer-content">
            <div class="footer-section">
                <h3>Customer Service</h3>
                <p>Phone: 00011122233300000</p>
                <p>Email: <a href="mailto:info@africanjewelries.com">info@africanjewelries.com</a></p>
            </div>
            <div class="footer-section">
                <h3>Company</h3>
                <ul>
                    <li><a href="#">Careers</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Press</a></li>
                    <li><a href="#">The CIRCA Journal</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h3>Policies</h3>
                <ul>
                    <li><a href="#">Privacy Policy</a></li>
                    <li><a href="#">Terms & Conditions</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h3>Sign up</h3>
                <form action="#">
                    <input type="email" placeholder="Email">
                    <button type="submit">Submit</button>
                </form>
                <div class="social-icons">
                    <a href="#"><img src="https://www.freeiconspng.com/uploads/logo-facebook-png-free-download-29.png" alt="Facebook" onerror="this.onerror=null;this.src='images/placeholder.png';"></a>
                    <a href="#"><img src="images/instagram-icon.png" alt="Instagram" onerror="this.onerror=null;this.src='images/placeholder.png';"></a>
                    <a href="#"><img src="images/linkedin-icon.png" alt="LinkedIn" onerror="this.onerror=null;this.src='images/placeholder.png';"></a>
                    <a href="#"><img src="images/pinterest-icon.png" alt="Pinterest" onerror="this.onerror=null;this.src='images/placeholder.png';"></a>
                </div>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2024 African Imported Jewelries and More. All Rights Reserved.</p>
        </div>
    </footer>
</body>
</html>


#June 24,2024
/**
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>African Imported Jewelries and More</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1em 0;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        .welcome {
            background: url('https://png.pngtree.com/background/20230612/original/pngtree-african-beautiful-woman-with-beaded-tribal-jewelry-picture-image_3176707.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 4em 0;
        }
        .products {
            padding: 2em;
            background-color: #fff;
            text-align: center;
        }
        .products h2 {
            margin-bottom: 1em;
        }
        .product {
            display: inline-block;
            margin: 1em;
        }
        .product img {
            width: 200px; /* Adjust the width to reduce the size by one-third */
            height: auto;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 2em 0;
        }
        .footer-content {
            display: flex;
            justify-content: space-around;
        }
        .footer-section h3 {
            margin-top: 0;
        }
        .footer-section ul {
            list-style: none;
            padding: 0;
        }
        .footer-section ul li {
            margin: 0.5em 0;
        }
        .footer-section ul li a {
            color: white;
            text-decoration: none;
        }
        .footer-bottom {
            text-align: center;
            margin-top: 1em;
        }
        .social-icons img {
            width: 30px;
            height: 30px;
            margin: 0 5px;
        }
        .login-form {
            text-align: center;
            margin: 2em 0;
        }
        .login-form input[type="text"], .login-form input[type="password"] {
            padding: 10px;
            margin: 10px;
            width: 200px;
        }
        .login-form button {
            padding: 10px 20px;
            background-color: #333;
            color: white;
            border: none;
        }
        .search-bar {
            text-align: center;
            margin: 2em 0;
        }
        .search-bar input[type="text"] {
            padding: 10px;
            width: 300px;
        }
        .search-bar button {
            padding: 10px 20px;
            background-color: #333;
            color: white;
            border: none;
        }
        .cart {
            text-align: center;
            margin: 2em 0;
        }
        .cart table {
            margin: 0 auto;
            width: 80%;
            border-collapse: collapse;
        }
        .cart table, .cart th, .cart td {
            border: 1px solid #ddd;
            padding: 10px;
        }
        .cart th {
            background-color: #333;
            color: white;
        }
        .cart td img {
            width: 50px;
            height: 50px;
        }
        .payment-methods {
            text-align: center;
            margin: 2em 0;
        }
        .payment-methods img {
            width: 50px;
            height: 30px;
            margin: 0 10px;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">How to Sell</a></li>
                <li><a href="#">FAQ</a></li>
                <li><a href="#">USA: 00011122233300000</a></li>
                <li><a href="#">Login</a></li>
            </ul>
        </nav>
    </header>
    
    <section class="welcome">
        <h1>Welcome to African Imported Jewelries and More</h1>
    </section>
    
    <div class="login-form">
        <h2>Login</h2>
        <form action="#">
            <input type="text" placeholder="Username" required>
            <input type="password" placeholder="Password" required>
            <button type="submit">Login</button>
        </form>
    </div>
    
    <div class="search-bar">
        <h2>Search Products</h2>
        <form action="#">
            <input type="text" placeholder="Search for jewelry">
            <button type="submit">Search</button>
        </form>
    </div>
    
    <section class="products">
        <h2>Our Products</h2>
        <div class="product">
            <img src="https://png.pngtree.com/background/20230612/original/pngtree-african-beautiful-woman-with-beaded-tribal-jewelry-picture-image_3176707.jpg" alt="Jewelry 1" onerror="this.onerror=null;this.src='images/placeholder.png';">
            <p>Beautiful handcrafted jewelry from Africa.</p>
        </div>
        <div class="product">
            <img src="https://africduka-cdn.s3.amazonaws.com/media/afric_duka/images/products-images/488672839496921934872532.png" alt="Jewelry 2" onerror="this.onerror=null;this.src='images/placeholder.png';">
            <p>Elegant African bead necklaces.</p>
        </div>
        <div class="product">
            <img src="https://png.pngtree.com/thumb_back/fw800/background/20240606/pngtree-colorful-african-bracelets-necklaces-and-jewelry-cape-town-image_15741582.jpg" alt="Jewelry 3" onerror="this.onerror=null;this.src='images/placeholder.png';">
            <p>Traditional African bracelets.</p>
        </div>
    </section>
    
    <div class="cart">
        <h2>Shopping Cart</h2>
        <table>
            <tr>
                <th>Product</th>
                <th>Name</th>
                <th>Quantity</th>
                <th>Price</th>
                <th>Total</th>
            </tr>
            <tr>
                <td><img src="https://png.pngtree.com/background/20230612/original/pngtree-african-beautiful-woman-with-beaded-tribal-jewelry-picture-image_3176707.jpg" alt="Jewelry 1"></td>
                <td>Jewelry 1</td>
                <td>1</td>
                <td>$50</td>
                <td>$50</td>
            </tr>
            <tr>
                <td><img src="https://africduka-cdn.s3.amazonaws.com/media/afric_duka/images/products-images/488672839496921934872532.png" alt="Jewelry 2"></td>
                <td>Jewelry 2</td>
                <td>2</td>
                <td>$30</td>
                <td>$60</td>
            </tr>
        </table>
    </div>
    
    <div class="payment-methods">
        <h2>Payment Methods</h2>
        <p>We accept the following payment methods:</p>
        <img src="https://www.freeiconspng.com/thumbs/credit-card-icon-png/credit-cards-icon-25.png" alt="Credit Card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d1/Visa_Debit_SVG_logo.svg/2560px-Visa_Debit_SVG_logo.svg.png" alt="Debit Card">
        <img src="https://freepnglogo.com/images/all_img/1707675116zelle-logo-png.png" alt="Zelle">
    </div>
    
    <footer>
        <div class="footer-content">
            <div class="footer-section">
                <h3>Customer Service</h3>
                <p>Phone: 00011122233300000</p>
                <p>Email: <a href="mailto:info@africanjewelries.com">info@africanjewelries.com</a></p>
            </div>
            <div class="footer-section">
                <h3>Company</h3>
                <ul>
                    <li><a href="#">Careers</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Press</a></li>
                    <li><a href="#">The CIRCA Journal</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h3>Policies</h3>
                <ul>
                    <li><a href="#">Privacy Policy</a></li>
                    <li><a href="#">Terms & Conditions</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h3>Sign up</h3>
                <form action="#">
                    <input type="email" placeholder="Email">
                    <button type="submit">Submit</button>
                </form>
                <div class="social-icons">
                    <a href="#"><img src="https://www.freeiconspng.com/uploads/logo-facebook-png-free-download-29.png" alt="Facebook" onerror="this.onerror=null;this.src='images/placeholder.png';"></a>
                    <a href="https://commons.wikimedia.org/wiki/File:Instagram_icon.png"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a5/Instagram_icon.png/2048px-Instagram_icon.png" alt="Instagram" onerror="this.onerror=null;this.src='images/placeholder.png';"></a>
                    <a href="https://commons.wikimedia.org/wiki/File:LinkedIn_logo_initials.png"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/480px-LinkedIn_logo_initials.png" alt="LinkedIn" onerror="this.onerror=null;this.src='images/placeholder.png';"></a>
                    <a href="https://commons.wikimedia.org/wiki/File:Pinterest-logo.png"><img src="https://upload.wikimedia.org/wikipedia/commons/0/08/Pinterest-logo.png" alt="Pinterest" onerror="this.onerror=null;this.src='images/placeholder.png';"></a>
                </div>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2024 African Imported Jewelries and More. All Rights Reserved.</p>
        </div>
    </footer>
</body>
</html>
**\
