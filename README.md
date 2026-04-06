<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sweet Delights | Custom Cakes</title>
    <style>
        /* Basic Styling */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            color: #4a4a4a;
            background-color: #fffaf0;
        }

        header {
            background-color: #ffb7c5; /* Pastel Pink */
            color: white;
            padding: 2rem;
            text-align: center;
        }

        nav {
            background: #fff;
            padding: 10px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .container {
            max-width: 1000px;
            margin: auto;
            padding: 20px;
        }

        /* Hero Section */
        .hero {
            text-align: center;
            padding: 50px 0;
        }

        /* Cake Gallery */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .cake-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }

        .cake-card:hover {
            transform: translateY(-5px);
        }

        .cake-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            background-color: #eee; /* Placeholder */
        }

        .cake-info {
            padding: 15px;
            text-align: center;
        }

        /* Contact Form */
        .order-form {
            background: #ffe4e1;
            padding: 30px;
            border-radius: 10px;
            margin-top: 50px;
        }

        input, textarea, button {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            box-sizing: border-box;
        }

        button {
            background-color: #ffb7c5;
            color: white;
            border: none;
            font-weight: bold;
            cursor: pointer;
        }

        footer {
            text-align: center;
            padding: 20px;
            font-size: 0.9rem;
            background: #4a4a4a;
            color: white;
        }
    </style>
</head>
<body>

    <header>
        <h1>Sweet Delights Bakery</h1>
        <p>Baking memories, one slice at a time.</p>
    </header>

    <nav>
        <strong>Home | Menu | Order Now | About</strong>
    </nav>

    <div class="container">
        <section class="hero">
            <h2>Handcrafted Cakes for Every Occasion</h2>
            <p>From weddings to birthdays, we make your celebrations sweeter.</p>
        </section>

        <section class="gallery">
            <div class="cake-card">
                <img src="https://via.placeholder.com/300x200?text=Chocolate+Lava" alt="Chocolate Cake">
                <div class="cake-info">
                    <h3>Signature Chocolate</h3>
                    <p>Rich dark chocolate with ganache filling.</p>
                </div>
            </div>
            <div class="cake-card">
                <img src="https://via.placeholder.com/300x200?text=Strawberry+Bliss" alt="Strawberry Cake">
                <div class="cake-info">
                    <h3>Strawberry Bliss</h3>
                    <p>Fresh berries and light vanilla sponge.</p>
                </div>
            </div>
            <div class="cake-card">
                <img src="https://via.placeholder.com/300x200?text=Red+Velvet" alt="Red Velvet">
                <div class="cake-info">
                    <h3>Classic Red Velvet</h3>
                    <p>Velvety texture with cream cheese frosting.</p>
                </div>
            </div>
        </section>

        <section class="order-form">
            <h2 style="text-align:center;">Place an Inquiry</h2>
            <form>
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <input type="text" placeholder="Cake Type (e.g. Birthday, Wedding)">
                <textarea rows="4" placeholder="Tell us about your dream cake..."></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </div>

    <footer>
        &copy; 2026 Sweet Delights Bakery | Follow us on Instagram
    </footer>

</body>
</html># kennysib.github.io
