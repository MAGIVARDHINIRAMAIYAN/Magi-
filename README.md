<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Web Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header {
            background-color: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav {
            background: #444;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        .hero {
            background: url('https://source.unsplash.com/1600x900/?nature') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
            font-size: 24px;
        }
        .container {
            padding: 20px;
        }
        .services {
            display: flex;
            justify-content: space-around;
            text-align: center;
            margin-top: 20px;
        }
        .service {
            padding: 20px;
            width: 30%;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .contact-form {
            max-width: 500px;
            margin: 20px auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Website</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="hero" id="home">
        <h2>Explore the Beauty of Nature</h2>
        <p>Your journey begins here</p>
    </section>

    <div class="container">
        <section id="about">
            <h2>About Us</h2>
            <p>We are a company dedicated to exploring and preserving the beauty of nature.</p>
        </section>

        <section class="services" id="services">
            <div class="service">
                <h3>Adventure Tours</h3>
                <p>Explore the world with our guided adventure tours.</p>
            </div>
            <div class="service">
                <h3>Wildlife Conservation</h3>
                <p>Join our efforts in protecting wildlife and natural habitats.</p>
            </div>
            <div class="service">
                <h3>Photography</h3>
                <p>Capture stunning moments with our professional photography services.</p>
            </div>
        </section>

        <section class="contact-form" id="contact">
            <h2>Contact Us</h2>
            <form>
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 My Website | All rights reserved.</p>
    </footer>

</body>
</html>
