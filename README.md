<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Romandy Gijsbertha - RG</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #0044cc;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            text-align: center;
            margin: 1em 0;
        }
        nav a {
            margin: 0 1em;
            text-decoration: none;
            color: #0044cc;
            font-weight: bold;
        }
        section {
            padding: 2em;
            max-width: 800px;
            margin: 0 auto;
        }
        .section-title {
            color: #0044cc;
            border-bottom: 2px solid #0044cc;
            display: inline-block;
            margin-bottom: 1em;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
        }
        .contact-form label {
            margin-top: 1em;
        }
        .contact-form input, .contact-form textarea {
            padding: 0.5em;
            margin-top: 0.5em;
            border: 1px solid #ccc;
            border-radius: 4px;
            width: 100%;
        }
        .contact-form button {
            margin-top: 1em;
            padding: 0.7em;
            border: none;
            border-radius: 4px;
            background-color: #0044cc;
            color: white;
            font-size: 1em;
            cursor: pointer;
        }
        footer {
            text-align: center;
            padding: 1em 0;
            background-color: #0044cc;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Romandy Gijsbertha - RG</h1>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="about">
        <h2 class="section-title">About Me</h2>
        <p>Welcome! My name is Romandy Gijsbertha, and I am passionate about [your field or interest]. With a background in [your background], I have developed a keen interest in [related interest or skill]. I believe in [your philosophy or belief], and I am dedicated to [your goal or mission].</p>
    </section>
    <section id="portfolio">
        <h2 class="section-title">Portfolio</h2>
        <p>Here are some of my recent works and projects:</p>
        <ul>
            <li>Project 1: Description of project 1.</li>
            <li>Project 2: Description of project 2.</li>
            <li>Project 3: Description of project 3.</li>
        </ul>
    </section>
    <section id="blog">
        <h2 class="section-title">Blog</h2>
        <p>Welcome to my blog! Here, I share my thoughts, insights, and experiences on various topics. Stay tuned for updates.</p>
    </section>
    <section id="contact">
        <h2 class="section-title">Contact</h2>
        <form class="contact-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Romandy Gijsbertha. All rights reserved.</p>
    </footer>
</body>
</html>
