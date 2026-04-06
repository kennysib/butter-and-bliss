<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Butter & Bliss | Home-baked with a Mother's Love</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            margin: 0;
            padding: 0;
            color: #5d4037;
            background-color: #fffcf9;
        }

        /* Header & Branding */
        header {
            background-color: #f8f1e7;
            color: #8d6e63;
            padding: 40px 20px;
            text-align: center;
            border-bottom: 3px double #d7ccc8;
        }

        .logo-font {
            font-size: 3rem;
            margin: 0;
            font-style: italic;
        }

        .tagline {
            font-size: 1.2rem;
            letter-spacing: 1px;
            color: #a1887f;
        }

        /* Navigation */
        nav {
            background: white;
            padding: 15px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }

        nav a {
            text-decoration: none;
            color: #8d6e63;
            margin: 0 20px;
            font-weight: bold;
            text-transform: uppercase;
            font-size: 0.9rem;
        }

        .container {
            max-width: 1100px;
            margin: auto;
            padding: 20px;
        }

        /* Hero Image */
        .hero-banner {
            width: 100%;
            height: 450px;
            object-fit: cover;
            border-radius: 15px;
            margin-bottom: 40px;
        }

        h2.section-title {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 30px;
            color: #795548;
        }

        /* Gallery Grid */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
        }

        .card {
            background: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 6px 15px rgba(0,0,0,0.05);
            text-align: center;
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-8px);
        }

        .card img {
            width: 100%;
            height: 300px;
            object-fit: cover;
        }

        .card-info {
            padding: 20px;
        }

        .card-info h3 {
            margin: 10px 0;
            color: #5d4037;
        }

        /* Contact Section */
        .contact-box {
            background: #fdf5e6;
            padding: 40px;
            border-radius: 15px;
            margin-top: 60px;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            align-items: center;
            border: 1px solid #eee;
        }

        .contact-details {
            max-width: 400px;
        }

        .cta-button {
            background-color: #8d6e63;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 30px;
            display: inline-block;
            margin-top: 10px;
            font-weight: bold;
        }

        footer {
            text-align: center;
            padding: 30px;
            background: #8d6e63;
            color: white;
            margin-top: 50px;
        }
    </style>
</head>
<body>

    <header>
        <h1 class="logo-font">Butter & Bliss</h1>
        <p class="tagline">"Home-baked with a Mother's Love"</p>
        <p>Making life sweeter, one delicious layer at a time.</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#cakes">Cakes</a>
        <a href="#cookies">Cookies</a>
        <a href="#order">Order Now</a>
    </nav>

    <div class="container">
        <img src="main page top.jpeg" class="hero-banner" alt="Butter and Bliss Signature Cake" id="home">

        <h2 class="section-title" id="cakes">Our Signature Creations</h2>
        <div class="gallery">
            <div class="card">
                <img src="Birthdays and events.jpeg" alt="Birthday Cake">
                <div class="card-info">
                    <h3>Birthdays & Events</h3>
                    <p>Customized celebration cakes designed for your special moments.</p>
                </div>
            </div>

            <div class="card">
                <img src="rich plum cakes.jpeg" alt="Rich Plum Cake">
                <div class="card-info">
                    <h3>Festive Rich Plum Cakes</h3>
                    <p>Traditional fruit-soaked cakes for the holiday season.</p>
                </div>
            </div>

            <div class="card">
                <img src="rich fruits and nuts cakes.jpeg" alt="Fruit and Nut Cake">
                <div class="card-info">
                    <h3>Fruits & Nuts Cakes</h3>
                    <p>Loaded with premium dry fruits and crunchy nuts.</p>
                </div>
            </div>
        </div>

        <h2 class="section-title" id="cookies" style="margin-top: 60px;">Handcrafted Cookies & Treats</h2>
        <div class="gallery">
            <div class="card">
                <img src="christmas bliss.jpeg" alt="Christmas Treats">
                <div class="card-info">
                    <h3>Gourmet Cookies</h3>
                    <p>Almond, Pista, Dry Fruit, and Rich Chocolate varieties.</p>
                </div>
            </div>
            <div class="card">
                <div style="height:300px; background:#f9f9f9; display:flex; align-items:center; justify-content:center;">
                    <p>Wedding & Fondant Designs</p>
                </div>
                <div class="card-info">
                    <h3>Specialty Designs</h3>
                    <p>Elegant wedding cakes and intricate fondant craftsmanship.</p>
                </div>
            </div>
        </div>

        <section class="contact-box" id="order">
            <div class="contact-details">
                <h2>Place Your Order</h2>
                <p>Ready to make your occasion special? Reach out to us directly!</p>
                <p><strong>Call/Text:</strong> +91 70126 49062</p>
                <p><strong>Email:</strong> butterandbliss.in@gmail.com</p>
                <a href="https://wa.me/917012649062" class="cta-button">Chat on WhatsApp</a>
            </div>
            <div>
                <img src="WhatsApp Image 2026-04-06 at 12.00.22 (1).jpeg" style="max-width: 300px; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);" alt="Order Details">
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2026 Butter & Bliss | Home-made with Love</p>
    </footer>

</body>
</html>
