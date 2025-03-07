<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sneaker Store</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f4f4f4;
            background: url('shoe.jpg') no-repeat center center/cover;
        }
        header {
            background: #333;
            color: white;
            padding: 15px 0;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 15px;
        }
        .nav-button {
            background: #ff6600;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
        }
        .nav-button:hover {
            background: #cc5500;
            opacity: 1s;
        }
        .banner {
            color: black;
            padding: 50px 20px;
        }
        .sneaker-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 20px;
        }
        .sneaker {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(0,0,0,0.2);
        }
        footer {
            background: #333;
            color: white;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .button{
            width: 60px;
            border-radius: 5px;
            border: 2px;
            background-color: #333;
            cursor: pointer;
            color: white;
        }
        .button:hover{
            box-shadow: #333;
            opacity: 2s;
            background: grey;
        }
    </style>
</head>
<body>
    <header>
        <h1> Welcome to Shoe palace</h1>
        <nav>
            <a href="index.html" target="_blank" class="nav-button">Home</a>
            <a href="products.html" target="_blank" class="nav-button">Products</a>
            <a href="pricing.html" target="_blank" class="nav-button">Pricing</a>
            <a href="reviews.html" target="_blank" class="nav-button">Reviews</a>
            <a href="contact.html" target="_blank" class="nav-button">Contact</a>
        </nav>
    </header>
    
    <section class="banner">
        <h2>Step Into Comfort & Style</h2>
        <p>Discover the latest collection of high-performance sneakers.</p>
        <button onclick="showAlert()" class="button">Shop Now</button>
    </section>
    
    <section class="featured">
        <h2>Featured Sneakers</h2>
        <div class="sneaker-container">
            <div class="sneaker">
                <h3>New Balance</h3>
                <p>Perfect for running and casual wear.</p>
                <button onclick="showDetails('New Balance', 'Perfect for running and casual wear.')">View Details</button>
            </div>
            <div class="sneaker">
                <h3>Air max</h3>
                <p>Bold design with premium materials.</p>
                <button onclick="showDetails('Air max', 'Bold design with premium materials.')">View Details</button>
            </div>
        </div>
    </section>
    
    <footer>
        <p>&copy; 2025 Shoe palace. All Rights Reserved.</p>
    </footer>

    <script>
        function showAlert() {
            alert('Welcome to Shoe Palace! Explore our latest collection.');
        }

        function showDetails(name, description) {
            alert(`${name}: ${description}`);
        }
    </script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HOME page</title>
    <style>
        .sneakerimage{
            width: 150px;
        }
        .sneakerimage2{
            width: 250px;
            height: 150px;
        }
        .banner {
            color: black;
            padding: 50px 20px;
        }
        .sneaker {
            background: #cc5500;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(0,0,0,0.2);
        }
        .sneaker-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 20px;
             
        }
        header{
            padding: 15px 0;
        }
        .shop{
            background-color: #ff6600;
            border-radius: 10px;
            border: none;
            color: white;
            cursor: pointer;
            padding: 15px 10px;
            display: block;
            margin: auto;
            margin-top: 20px;
        }
        .shop:hover{
            background: #cc5500;
        }
        .paragraph{
            font-family: Arial, Helvetica, sans-serif;
            font-weight: bold;
            font-size: 45px;
            text-align: center;

        }
        body{
            background: url('shoe3.jpg');
        }
    </style>
</head>
<body>
    <header>
         <h1><marquee behavior="scroll" direction="left">karibu shoe palace welcome to shoe palace</marquee></h1>
         <p class="paragraph">we are shoe palace we offer the best shoes and prices </p>
    </header>
   
    <section class="featured">
        <h2 class="paragraph">Featured Sneakers</h2>
        <div class="sneaker-container">
            <div class="sneaker">
                <img src="sneaker1.jpg" alt="Sneaker 1" class="sneakerimage">
                <h3>New Balance</h3>
                <p>Perfect for running and casual wear.</p>
                <button onclick="showDetails('New Balance', 'Perfect for running and casual wear.')">View Details</button>
            </div>
            <div class="sneaker">
                <img src="sneaker2.jpg" alt="Sneaker 2" class="sneakerimage2">
                <h3>Air max</h3>
                <p>Bold design with premium materials.</p>
                <button onclick="showDetails('Air max', 'Bold design with premium materials.')">View Details</button>
            </div>
        </div>
    </section>
    <a href="products.html" target="_blank"><button class="shop">shop now</button></a>
    <script>

        function showDetails(name, description) {
            alert(`${name}: ${description}`);
        }
    </script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>products</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        h1 {
            background-color: #333;
            color: white;
            padding: 15px;
            margin: 0;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 20px;
        }
        .product {
            background: white;
            border-radius: 10px;
            padding: 15px;
            margin: 15px;
            width: 250px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .price {
            font-size: 18px;
            color: #333;
            margin: 10px 0;
        }
        .buttons {
            display: flex;
            justify-content: space-between;
        }
        .btn {
            background-color: #ff6600;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
            width: 48%;
        }
        .btn:hover {
            background-color: #e65c00;
        }
    </style>
</head>
<body>

    <h1>shoe palace's products</h1>

    <div class="container">
        <!-- Shoe 1 -->
        <div class="product">
            <img src="images/image1.webp" alt="Nike Air Max">
            <h3>Nike Air Max</h3>
            <p class="price">ksh3500/=</p>
            <div class="buttons">
                <a href="pricing.html" target="_blank" class="btn">Buy Now</a>
            </div>
        </div>

        <!-- Shoe 2 -->
        <div class="product">
            <img src="images/image2.avif" alt="Adidas Ultraboost">
            <h3>Adidas Ultraboost</h3>
            <p class="price">ksh4500/=</p>
            <div class="buttons">
                <a href="pricing.html" target="_blank" class="btn">Buy Now</a>
            </div>
        </div>

        <!-- Shoe 3 -->
        <div class="product">
            <img src="images/image3.jpeg" alt="Puma RS-X">
            <h3>Puma RS-X</h3>
            <p class="price">ksh3000/=</p>
            <div class="buttons">
                <a href="pricing.html" target="_blank" class="btn">Buy Now</a>
            </div>
        </div>

        <!-- Shoe 4 -->
        <div class="product">
            <img src="images/image4.jpg" alt="Reebok Classic">
            <h3>Reebok Classic</h3>
            <p class="price">ksh2250/=</p>
            <div class="buttons">
                <a href="pricing.html" target="_blank" class="btn">Buy Now</a>
            </div>
        </div>

        <!-- Shoe 5 -->
        <div class="product">
            <img src="images/image5.jpg" alt="New Balance 574">
            <h3>New Balance 574</h3>
            <p class="price">ksh2500/=</p>
            <div class="buttons">
                <a href="pricing.html" target="_blank" class="btn">Buy Now</a>
            </div>
        </div>

        <!-- Shoe 6 -->
        <div class="product">
            <img src="images/image6.jpg" alt="Vans Old Skool">
            <h3>Vans Old Skool</h3>
            <p class="price">ksh1200/=</p>
            <div class="buttons">
                <a href="pricing.html" target="_blank" class="btn">Buy Now</a>
            </div>
        </div>

        <!-- Shoe 7 -->
        <div class="product">
            <img src="images/A03770C.png" alt="Converse Chuck Taylor">
            <h3>Converse Chuck Taylor</h3>
            <p class="price">ksh950/=</p>
            <div class="buttons">
                <a href="pricing.html" target="_blank" class="btn">Buy Now</a>
            </div>
        </div>
    </div>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>pricing</title>
    <style>
        table {
            width: 50%;
            border-collapse: collapse;
            margin: 20px auto;
            font-family: Arial, sans-serif;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #f4f4f4;
        }
        
        body {
            font-family: Arial, sans-serif;
            background-color: lightblue;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            width: 400px;
            text-align: center;
        }
        h2 {
            margin-bottom: 20px;
        }
        label {
            display: block;
            text-align: left;
            margin: 10px 0 5px;
            font-weight: bold;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .btn {
            background-color: #ff6600;
            color: white;
            border: none;
            padding: 10px;
            width: 100%;
            border-radius: 5px;
            cursor: pointer;
        }
        .btn:hover {
            background-color: #e65c00;
        }
    </style>
</head>
<body>
    <h2 style="text-align: center;">Shoe Price List</h2>

    <table>
        <tr>
            <th>Product</th>
            <th>Price</th>
        </tr>
        <tr>
            <td>Nike Air Max</td>
            <td>ksh3500/=</td>
        </tr>
        <tr>
            <td>Adidas Ultraboost</td>
            <td>ksh4500/=</td>
        </tr>
        <tr>
            <td>Puma RS-X</td>
            <td>ksh3000/=</td>
        </tr>
        <tr>
            <td>Reebok Classic</td>
            <td>ksh2250/=</td>
        </tr>
        <tr>
            <td>New Balance 574</td>
            <td>ksh2500/=</td>
        </tr>
        <tr>
            <td>Vans Old Skool</td>
            <td>ksh1200/=</td>
        </tr>
        <tr>
            <td>Converse Chuck Taylor</td>
            <td>ksh950/=</td>
        </tr>
    </table>
    <div class="container">
        <h2>Enter Delivery Details</h2>
        <form action="order-confirmation.html" method="POST">
            <label for="name">Full Name</label>
            <input type="text" id="name" name="name" required>

            <label for="address">Address</label>
            <textarea id="address" name="address" rows="3" required></textarea>

            <label for="phone">Phone Number</label>
            <input type="tel" id="phone" name="phone" required>

            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>

            <button type="submit" class="btn" onclick="showDetails('your order has been placed succesfully')">Submit Order</button>
        </form>
    </div>
<script>
    function showDetails(description){
        alert(`${description}`);
    }
</script>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Customer Reviews</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f8f8;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            width: 400px;
            text-align: center;
        }
        h2 {
            margin-bottom: 20px;
        }
        label {
            display: block;
            text-align: left;
            margin: 10px 0 5px;
            font-weight: bold;
        }
        input, textarea, select {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .btn {
            background-color: #ff6600;
            color: white;
            border: none;
            padding: 10px;
            width: 100%;
            border-radius: 5px;
            cursor: pointer;
        }
        .btn:hover {
            background-color: #e65c00;
        }
        .reviews-container {
            margin-top: 20px;
            text-align: left;
        }
        .review {
            background: #fff;
            padding: 10px;
            margin-top: 10px;
            border-radius: 5px;
            box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>Leave a Review</h2>
        <form id="reviewForm">
            <label for="name">Your Name</label>
            <input type="text" id="name" required>

            <label for="rating">Rating</label>
            <select id="rating" required>
                <option value="5">⭐⭐⭐⭐⭐ - Excellent</option>
                <option value="4">⭐⭐⭐⭐ - Good</option>
                <option value="3">⭐⭐⭐ - Average</option>
                <option value="2">⭐⭐ - Poor</option>
                <option value="1">⭐ - Terrible</option>
            </select>

            <label for="review">Your Review</label>
            <textarea id="review" rows="3" required></textarea>

            <button type="submit" class="btn"  onclick="showDetails('we appreciate your review')">Submit Review</button>
        </form>

        <div class="reviews-container" id="reviews">
            <h3>Customer Reviews</h3>
            <!-- Reviews will be displayed here -->
        </div>
    </div>

    <script>
        function showDetails(description){
            alert(`${description}`);
        }
        document.getElementById('reviewForm').addEventListener('submit', function(event) {
            event.preventDefault(); // Prevent form submission

            
            const name = document.getElementById('name').value;
            const rating = document.getElementById('rating').value;
            const reviewText = document.getElementById('review').value;

            
            const reviewContainer = document.getElementById('reviews');
            const reviewElement = document.createElement('div');
            reviewElement.classList.add('review');
            reviewElement.innerHTML = `<strong>${name}</strong> - ⭐${'⭐'.repeat(rating)}<br><p>${reviewText}</p>`;

            
            reviewContainer.appendChild(reviewElement);

            
            document.getElementById('reviewForm').reset();
        });
    </script>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f8f8;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            width: 400px;
            margin: 30px auto;
        }
        h2 {
            margin-bottom: 10px;
        }
        .info {
            text-align: left;
            margin-bottom: 20px;
        }
        .info p {
            margin: 5px 0;
        }
        label {
            display: block;
            text-align: left;
            margin: 10px 0 5px;
            font-weight: bold;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .btn {
            background-color: #ff6600;
            color: white;
            border: none;
            padding: 10px;
            width: 100%;
            border-radius: 5px;
            cursor: pointer;
        }
        .btn:hover {
            background-color: #e65c00;
        }
        .map {
            margin: 20px auto;
            width: 90%;
            max-width: 600px;
        }
    </style>
</head>
<body>

    <h2>Contact Us</h2>

    <div class="container">
        <div class="info">
            <p><strong>📍 Address:</strong> 123 Shoe palace, Nairobi, 0100</p>
            <p><strong>📞 Phone:</strong> +254 748318190</p>
            <p><strong>📧 Email:</strong> Theeshoepalace@gmail.com</p>
        </div>

        <h3>Send us a message</h3>
        <form action="mailto:contact@shoestore.com" method="post" enctype="text/plain">
            <label for="name">Your Name</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Your Email</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Your Message</label>
            <textarea id="message" name="message" rows="3" required></textarea>

            <button type="submit" class="btn" onclick="showDetails('we have recieved your message thankyou')">Send Message</button>
        </form>
    </div>
<script>
        function showDetails(description){
            alert(`${description}`);
    }
</script>
</body>
</html>
