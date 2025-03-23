# 🌟 E-Commerce Website

## 📌 Description
Welcome to the *E-Commerce Website* project! This project aims to create a user-friendly and visually appealing online store where customers can browse products, add them to their cart, and simulate a purchase process.

This project uses *HTML, **CSS*, and simple JavaScript to create an interactive shopping experience. It focuses on providing essential e-commerce features such as product listings, a shopping cart, and a checkout page.

The website is fully responsive, meaning it adapts to different screen sizes, making it usable on both desktop and mobile devices. The site includes multiple products with basic details like product images, descriptions, prices, and an "Add to Cart" button.

## 🎨 Demo Preview (HTML & CSS)
Here’s a sample of the code used to create the *Product Cards* for the e-commerce site:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Commerce Product Listing</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #3498db;
            color: white;
            text-align: center;
            padding: 20px;
        }

        header h1 {
            margin: 0;
        }

        .container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
            padding: 20px;
        }

        .product-card {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            width: 250px;
            padding: 15px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .product-card img {
            width: 100%;
            border-radius: 8px;
            height: 200px;
            object-fit: cover;
        }

        .product-card h3 {
            color: #333;
            font-size: 1.2rem;
            margin: 10px 0;
        }

        .product-card p {
            color: #777;
            font-size: 0.9rem;
            margin: 0 0 10px;
        }

        .product-card .price {
            color: #27ae60;
            font-size: 1.3rem;
            margin-top: 10px;
        }

        .product-card .btn {
            background-color: #3498db;
            color: white;
            padding: 12px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 1rem;
            margin-top: 15px;
            transition: background-color 0.3s;
        }

        .product-card .btn:hover {
            background-color: #2980b9;
        }

        .product-card:hover {
            transform: translateY(-5px);
        }

        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 15px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

    </style>
</head>
<body>

<header>
    <h1>Welcome to Our E-Commerce Store</h1>
    <p>Explore our wide range of products!</p>
</header>

<div class="container">
    <div class="product-card">
        <img src="https://via.placeholder.com/250x200" alt="Product Image">
        <h3>Product Name 1</h3>
        <p>High-quality product description.</p>
        <div class="price">$29.99</div>
        <button class="btn">Add to Cart</button>
    </div>

    <div class="product-card">
        <img src="https://via.placeholder.com/250x200" alt="Product Image">
        <h3>Product Name 2</h3>
        <p>Stylish and affordable for everyday use.</p>
        <div class="price">$19.99</div>
        <button class="btn">Add to Cart</button>
    </div>

    <div class="product-card">
        <img src="https://via.placeholder.com/250x200" alt="Product Image">
        <h3>Product Name 3</h3>
        <p>Durable and long-lasting quality.</p>
        <div class="price">$49.99</div>
        <button class="btn">Add to Cart</button>
    </div>

    <div class="product-card">
        <img src="https://via.placeholder.com/250x200" alt="Product Image">
        <h3>Product Name 4</h3>
        <p>Perfect for tech lovers and gadget enthusiasts.</p>
        <div class="price">$99.99</div>
        <button class="btn">Add to Cart</button>
    </div>
</div>

<footer>
    <p>&copy; 2025 E-Commerce Store | All rights reserved.</p>
</footer>

</body>
</html>
