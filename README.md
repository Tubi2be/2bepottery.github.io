<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2bepottery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0e5d8; /* Sand color */
            color: #2b3e40; /* Dark blue-green color */
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4a9c8c; /* Blue-green color */
            color: #fff;
            text-align: center;
            padding: 1em 0;
        }
        nav {
            background-color: #3d7d75; /* Darker blue-green color */
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #f0e5d8; /* Sand color for hover effect */
            color: #2b3e40; /* Dark blue-green for text on hover */
        }
        section {
            padding: 20px;
        }
        .container {
            max-width: 1000px;
            margin: auto;
            overflow: hidden;
        }
        footer {
            background-color: #4a9c8c; /* Blue-green color */
            color: #fff;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .portfolio img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 10px auto;
        }
        .sales-options {
            list-style: none;
            padding: 0;
        }
        .sales-options li {
            background-color: #4a9c8c; /* Blue-green color */
            color: #fff;
            margin: 5px 0;
            padding: 10px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>2bepottery</h1>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#sales">Sales Options</a>
    </nav>
    <section id="about" class="container">
        <h2>About Me</h2>
        <p>Welcome to 2bepottery! I am passionate about creating beautiful, handcrafted pottery pieces that bring joy and functionality to your home. Each piece is made with care and attention to detail, reflecting my love for earthy colors and natural textures.</p>
    </section>
    <section id="portfolio" class="container">
        <h2>Portfolio</h2>
        <div class="portfolio">
            <img src="pottery1.jpg" alt="Pottery Piece 1">
            <img src="pottery2.jpg" alt="Pottery Piece 2">
            <img src="pottery3.jpg" alt="Pottery Piece 3">
        </div>
    </section>
    <section id="sales" class="container">
        <h2>Sales Options</h2>
        <ul class="sales-options">
            <li>Custom Orders</li>
            <li>Online Store</li>
            <li>Local Market Events</li>
        </ul>
    </section>
    <footer>
        <p>&copy; 2024 2bepottery</p>
    </footer>
</body>
</html>
