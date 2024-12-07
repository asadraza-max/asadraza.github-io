<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="about">
            <h2>About Us</h2>
            <p>This is a simple static website hosted on GitHub Pages.</p>
        </section>
        <section id="services">
            <h2>Our Services</h2>
            <ul>
                <li>Web Development</li>
                <li>Graphic Design</li>
                <li>Digital Marketing</li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <p>Email: example@example.com</p>
            <p>Phone: +1234567890</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

header {
    background: #333;
    color: #fff;
    padding: 1em 0;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 20px;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

footer p {
    margin: 0;
}
# My Static Website

A simple, static website created with HTML and CSS. Hosted on GitHub Pages.

## Features
- Minimalist design
- Fully responsive layout
- Easy to customize

## How to Access

You can view this website at: `https://<your-username>.github.io/<repository-name>/`.

## License
This project is licensed under the MIT License.
