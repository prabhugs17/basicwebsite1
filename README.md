<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Basic Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background: #4CAF50;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            background: #333;
            padding: 0.5rem;
        }
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 1rem;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        main {
            padding: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 1rem;
        }
        .content-section {
            margin-bottom: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
        <p>A simple, basic website template</p>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <main>
        <section id="home" class="content-section">
            <h2>Home</h2>
            <p>Welcome to our website! This is the home section where you can introduce your site's purpose.</p>
        </section>

        <section id="about" class="content-section">
            <h2>About Us</h2>
            <p>This section contains information about your company or yourself.</p>
            <p>You can add more paragraphs, images, or other HTML elements as needed.</p>
        </section>

        <section id="services" class="content-section">
            <h2>Our Services</h2>
            <ul>
                <li>Service 1</li>
                <li>Service 2</li>
                <li>Service 3</li>
            </ul>
        </section>

        <section id="contact" class="content-section">
            <h2>Contact Us</h2>
            <p>Email: contact@example.com</p>
            <p>Phone: (123) 456-7890</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 My Basic Website. All rights reserved.</p>
    </footer>
</body>
</html>
