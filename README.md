<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Courier service website with tracking, services, and contact info.">
    <title>Courier Website</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }

        header nav ul {
            list-style: none;
            padding: 0;
        }

        header nav ul li {
            display: inline;
            margin-right: 20px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        #hero {
            background-color: #007BFF;
            color: white;
            padding: 50px 0;
            text-align: center;
        }

        #hero h2 {
            font-size: 3rem;
        }

        #hero .cta-btn {
            padding: 10px 20px;
            background-color: #28a745;
            color: white;
            text-decoration: none;
            font-size: 1.2rem;
            border-radius: 5px;
            margin-top: 20px;
            display: inline-block;
        }

        #services {
            padding: 40px 20px;
            text-align: center;
        }

        #services h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        .service-cards {
            display: flex;
            justify-content: space-around;
            gap: 20px;
        }

        .service-card {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 30%;
            text-align: center;
        }

        #tracking, #contact {
            padding: 40px 20px;
            background-color: #f9f9f9;
            text-align: center;
        }

        #tracking input, #contact input, #contact textarea {
            width: 80%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        #tracking button, #contact button {
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        footer p {
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">
            <h1>FastCourier</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#services">Services</a></li>
                <li><a href="#tracking">Track Your Package</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <h2>Reliable and Fast Courier Service</h2>
        <p>Get your parcels delivered swiftly and securely.</p>
        <a href="#services" class="cta-btn">Explore Our Services</a>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <div class="service-cards">
            <div class="service-card">
                <h3>Next-Day Delivery</h3>
                <p>Fast and reliable next-day delivery for your urgent parcels.</p>
            </div>
            <div class="service-card">
                <h3>International Shipping</h3>
                <p>Ship your packages to over 100 countries with our international shipping services.</p>
            </div>
            <div class="service-card">
                <h3>Parcel Tracking</h3>
                <p>Track your parcel in real-time from pickup to delivery.</p>
            </div>
        </div>
    </section>

    <section id="tracking">
        <h2>Track Your Package</h2>
        <form>
            <label for="trackingNumber">Enter Tracking Number:</label>
            <input type="text" id="trackingNumber" placeholder="Tracking Number">
            <button type="submit">Track</button>
        </form>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions, feel free to reach out!</p>
        <form>
            <label for="name">Your Name:</label>
            <input type="text" id="name" placeholder="Your Name" required>
            
            <label for="email">Your Email:</label>
            <input type="email" id="email" placeholder="Your Email" required>
            
            <label for="message">Your Message:</label>
            <textarea id="message" placeholder="Your Message" required></textarea>
            
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 FastCourier. All Rights Reserved.</p>
    </footer>
</body>
</html>
