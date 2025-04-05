<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tiny Toons Music</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header, nav, main, footer {
            padding: 20px;
        }
        header {
            background-color: #ffcc00;
            text-align: center;
        }
        nav {
            background-color: #ff9900;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            color: #fff;
            text-decoration: none;
        }
        main {
            background-color: #fff;
        }
        footer {
            background-color: #ffcc00;
            text-align: center;
        }
        .video {
            text-align: center;
            margin: 20px 0;
        }
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            margin-bottom: 10px;
            padding: 10px;
        }
        .contact-form button {
            background-color: #ff9900;
            color: #fff;
            border: none;
            padding: 10px 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Tiny Toons Music!</h1>
    <p>Join us on a musical adventure filled with fun, learning, and endless smiles!</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#videos">Videos</a>
    <a href="#contact">Contact</a>
</nav>

<main id="home">
    <section class="video">
        <h2>Featured Video</h2>
        <!-- Replace VIDEO_ID with your actual YouTube video ID -->
        <iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
    </section>
</main>

<section id="about">
    <h2>About Us</h2>
    <p>Tiny Toons Music is dedicated to creating catchy, educational songs that bring joy and learning to children everywhere.</p>
</section>

<section id="videos">
    <h2>Our Videos</h2>
    <!-- Repeat this block for each video -->
    <div class="video">
        <h3>Video Title</h3>
        <!-- Replace VIDEO_ID with your actual YouTube video ID -->
        <iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
    </div>
    <!-- End of video block -->
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <div class="contact-form">
        <form action="mailto:your-email@example.com" method="post" enctype="text/plain">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </div>
</section>

<footer>
    <p>&copy; 2025 Tiny Toons Music. All rights reserved.</p>
</footer>

</body>
</html>
