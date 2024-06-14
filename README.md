<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coffee Bliss</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #b5651d;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #333;
            color: white;
        }

        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 20px;
            margin: 20px auto;
            max-width: 800px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Coffee Bliss</h1>
        <p>Your daily dose of bliss in every cup</p>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About Us</a></li>
            <li><a href="#menu">Menu</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="about">
        <h2>About Us</h2>
        <p>Coffee Bliss is a cozy coffee shop located in the heart of the city. We serve a variety of coffee blends sourced from around the world, along with delicious pastries and snacks.</p>
    </section>
    <section id="menu">
        <h2>Our Menu</h2>
        <ul>
            <li>Espresso</li>
            <li>Latte</li>
            <li>Cappuccino</li>
            <li>Mocha</li>
            <li>Cold Brew</li>
            <li>Pastries</li>
        </ul>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: info@coffeebliss.com</p>
        <p>Phone: (123) 456-7890</p>
    </section>
    <footer>
        <p>&copy; 2024 Coffee Bliss. All rights reserved.</p>
    </footer>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            alert("Welcome to Coffee Bliss!");
        });
    </script>
</body>
</html>
