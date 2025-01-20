# -YourDreamStyle.com
YourDreamStyle is an innovative e-commerce platform where you can design and customize products like apparel and home decor. With AI-powered recommendations, eco-friendly materials, and a seamless design interface, it’s the ultimate destination for personalized shopping. Explore unique designs, create your own, and bring your dream style to life!
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YourDreamStyle - Customize Your World</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">YourDreamStyle</div>
        <nav>
            <a href="#products">Products</a>
            <a href="#features">Features</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="hero">
        <h1>Welcome to YourDreamStyle</h1>
        <p>Design and customize products that match your style.</p>
        <a href="#products" class="btn">Explore Now</a>
    </section>

    <section id="products">
        <h2>Our Products</h2>
        <div class="product-grid">
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Product 1">
                <h3>Custom T-Shirt</h3>
                <p>Personalize your own t-shirt design.</p>
                <button>Customize</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Product 2">
                <h3>Home Decor</h3>
                <p>Make your home uniquely yours.</p>
                <button>Customize</button>
            </div>
            <!-- Add more products as needed -->
        </div>
    </section>

    <section id="features">
        <h2>Why Choose Us?</h2>
        <div class="features-grid">
            <div class="feature">
                <h3>Customizable Products</h3>
                <p>Create designs that reflect your personality.</p>
            </div>
            <div class="feature">
                <h3>Eco-Friendly Materials</h3>
                <p>All products are made with sustainability in mind.</p>
            </div>
            <div class="feature">
                <h3>AI Recommendations</h3>
                <p>Let our AI suggest the perfect styles for you.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 YourDreamStyle. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
/* Basic Styles for YourDreamStyle */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

header {
    background: #333;
    color: #fff;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 2rem;
}

header nav a {
    color: #fff;
    margin: 0 1rem;
    text-decoration: none;
}

#hero {
    background: url('https://via.placeholder.com/1200x400') no-repeat center center/cover;
    color: #fff;
    text-align: center;
    padding: 5rem 2rem;
}

#hero .btn {
    display: inline-block;
    background: #ff5733;
    color: #fff;
    padding: 0.5rem 1rem;
    text-decoration: none;
    margin-top: 1rem;
}

section {
    padding: 2rem;
    text-align: center;
}

.product-grid, .features-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1rem;
}

.product img, .feature img {
    width: 100%;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
}
// Placeholder JavaScript for interactivity
document.querySelectorAll("button").forEach(button => {
    button.addEventListener("click", () => {
        alert("This feature will be available soon!");
    });
});
