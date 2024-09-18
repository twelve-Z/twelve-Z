# HTML template for the requested webpage

html_content = """
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="AI Professional E-commerce platform for selling products with responsive design and SEO optimization">
    <meta name="keywords" content="AI, E-commerce, Products, Responsive Design, SEO, USTD payment">
    <meta name="author" content="Your Name">
    <title>AI Professional E-commerce</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f4f4f4;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 15px 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }
        .product-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product-item {
            background-color: white;
            border: 1px solid #ddd;
            padding: 15px;
            margin: 10px;
            width: 30%;
            text-align: center;
        }
        .product-item img {
            max-width: 100%;
            height: auto;
        }
        .product-item h3 {
            color: #333;
        }
        .product-item p {
            color: #666;
        }
        .price {
            color: green;
            font-size: 1.2em;
        }
        .contact-form, .live-chat {
            margin: 20px 0;
            padding: 20px;
            background-color: white;
            border: 1px solid #ddd;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .social-media {
            margin-top: 10px;
        }
        .social-media a {
            margin: 0 10px;
            color: white;
            text-decoration: none;
        }
        @media (max-width: 768px) {
            .product-item {
                width: 45%;
            }
        }
        @media (max-width: 480px) {
            .product-item {
                width: 100%;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to the AI Professional E-commerce Platform</h1>
</header>

<div class="container">
    <section class="product-grid">
        <div class="product-item">
            <img src="product1.jpg" alt="Product 1">
            <h3>Product 1</h3>
            <p>High-quality AI tool for professionals.</p>
            <p class="price">Price: 50 USTD</p>
        </div>
        <div class="product-item">
            <img src="product2.jpg" alt="Product 2">
            <h3>Product 2</h3>
            <p>AI-powered productivity solution.</p>
            <p class="price">Price: 100 USTD</p>
        </div>
        <div class="product-item">
            <img src="product3.jpg" alt="Product 3">
            <h3>Product 3</h3>
            <p>Advanced AI software for data analysis.</p>
            <p class="price">Price: 150 USTD</p>
        </div>
    </section>

    <section class="contact-form">
        <h2>Contact Us</h2>
        <form action="/submit-form" method="post">
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br><br>
            <label for="message">Message:</label><br>
            <textarea id="message" name="message" required></textarea><br><br>
            <input type="submit" value="Submit">
        </form>
    </section>

    <section class="live-chat">
        <h2>Live Chat</h2>
        <p>Chat with us live via <a href="https://wa.me/yourwhatsapplink" target="_blank">WhatsApp</a>!</p>
    </section>
</div>

<footer>
    <p>&copy; 2024 AI Professional E-commerce. All rights reserved.</p>
    <div class="social-media">
        <a href="https://wa.me/yourwhatsapplink" target="_blank">WhatsApp</a>
        <a href="#">Facebook</a>
        <a href="#">Instagram</a>
    </div>
</footer>

</body>
</html>
"""

# Saving the HTML content to a file
file_path = "/mnt/data/ai_professional_ecommerce.html"
with open(file_path, "w") as file:
    file.write(html_content)

file_path
