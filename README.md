<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>haki Gaming Accessories</title>
    <style>
        body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #1c1c1c;
    color: #ffffff;
}

header {
    background-color: #292929;
    color: #ffffff;
    padding: 1rem;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 1rem;
}

nav ul li a {
    color: #61dafb;
    text-decoration: none;
    font-weight: bold;
}

main {
    padding: 1rem;
}

section {
    background-color: #2e2e2e;
    padding: 1rem;
    margin: 1rem 0;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.product-list {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}

.product-item {
    background-color: #3a3a3a;
    border: 1px solid #444;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    margin: 1rem;
    padding: 1rem;
    text-align: center;
    width: calc(33% - 2rem);
}

.product-item img {
    max-width: 100%;
    border-radius: 8px;
}

.product-item h3 {
    margin: 1rem 0 0.5rem 0;
}

.product-item p {
    color: #aaa;
}

button {
    background-color: #61dafb;
    border: none;
    border-radius: 4px;
    color: #000;
    cursor: pointer;
    padding: 0.5rem 1rem;
    text-transform: uppercase;
}

button:hover {
    background-color: #4fa9d6;
}

#contactForm {
    display: flex;
    flex-direction: column;
}

#contactForm label {
    margin: 0.5rem 0 0.25rem 0;
}

#contactForm input, #contactForm textarea {
    border: 1px solid #444;
    border-radius: 4px;
    padding: 0.5rem;
    background-color: #3a3a3a;
    color: #fff;
    margin-bottom: 1rem;
}

#contactForm button {
    align-self: flex-start;
}
body {
    /* Default light mode styles */
    --text-color: #222;
    --bkg-color: #fff;
    --anchor-color: #0033cc;
  }
  
  body.dark-theme {
    /* Dark mode styles */
    --text-color: #eee;
    --bkg-color: #12121 }
    </style>
    <link rel="stylesheet" href="form.css">
</head>
<body>
    <header>
        <h1>HAKI Gaming Accessories</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
              
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h2>Welcome to the Best Gaming Accessories Store</h2>
            <p>Find the latest and greatest in gaming accessories here.</p>
        </section>
        <section id="products">
            <h2>Our Products(MORE AVAILABLE)</h2>
            <div class="product-list">
                <!-- Add product items here -->
                <div class="product-item">
                    <img src="images/headset.jpg" alt="Gaming Headset">
                    <h3>Gaming Headset</h3>
                    <p>High-quality sound for immersive gaming.</p>
                    <button>Buy Now</button>
                </div>
                <div class="product-item">
                    <img src="images/mouse.jpg" alt="Gaming Mouse">
                    <h3>Gaming Mouse</h3>
                    <p>Precision control for competitive gaming.</p>
                    <button>Buy Now</button>
                </div>
                <div class="product-item">
                    <img src="images/keyboard.jpg" alt="Gaming Keyboard">
                    <h3>Gaming Keyboard</h3>
                    <p>Mechanical keys for fast and responsive input.</p>
                    <button>Buy Now</button>
                </div>
                <div class="product-item">
                    <img src="images/controller.jpg" alt="Gaming Controller">
                    <h3>Gaming Controller</h3>
                    <p>Ergonomic design for comfortable gaming.</p>
                    <button>Buy Now</button>
                </div>
                <div class="product-item">
                    <img src="images/monitor.jpg" alt="Gaming Monitor">
                    <h3>Gaming Monitor</h3>
                    <p>High refresh rate for smooth gameplay.</p>
                    <button>Buy Now</button>
                </div>
                <div class="product-item">
                    <img src="images/chair.jpg" alt="Gaming Chair">
                    <h3>Gaming Chair</h3>
                    <p>Ultimate comfort for long gaming sessions.</p>
                    <button>Buy Now</button>
                </div>
                <div class="product-item">
                    <img src="images/ps5.jpg" alt="PlayStation 5">
                    <h3>PlayStation 5</h3>
                    <p>Next-gen gaming with ultra-high-speed SSD.</p>
                    <button>Buy Now</button>
                </div>
                <div class="product-item">
                    <img src="images/xbox.jpg" alt="Xbox Series X">
                    <h3>Xbox Series X</h3>
                    <p>Power your dreams with the fastest Xbox ever.</p>
                    <button>Buy Now</button>
                </div>
                <div class="product-item">
                    <img src="images/switch.jpg" alt="Nintendo Switch">
                    <h3>Nintendo Switch</h3>
                    <p>Versatile gaming console you can play at home or on the go.</p>
                    <button>Buy Now</button>
                </div>
                <div class="product-item">
                    <img src="images/ps5-controller.jpg" alt="PS5 Controller">
                    <h3>PS5 Controller</h3>
                    <p>DualSense wireless controller with immersive haptic feedback.</p>
                    <button>Buy Now</button>
                </div>
                <div class="product-item">
                    <img src="images/xbox-controller.jpg" alt="Xbox Controller">
                    <h3>Xbox Controller</h3>
                    <p>Xbox wireless controller with enhanced comfort and feel.</p>
                    <button>Buy Now</button>
                </div>
                <div class="product-item">
                    <img src="images/switch-controller.jpg" alt="Switch Pro Controller">
                    <h3>Switch Pro Controller</h3>
                    <p>Nintendo Switch Pro Controller for advanced gaming.</p>
                    <button>Buy Now</button>
                </div>
            </div>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <form id="contactForm">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                <button onclick="location.href='https://wa.me/8121373516';">submit</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Gaming Accessories</p>
    </footer>
    <script>
        document.getElementById('contactForm').addEventListener('submit', function(event) {
    event.preventDefault();
    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    const message = document.getElementById('message').value;

    fetch('/contact', {
        method: 'POST',
        headers: {
            'Content-Type': 'application/json'
        },
        body: JSON.stringify({ name, email, message })
    })
    .then(response => response.json())
    .then(data => {
        alert(data.message);
    })
    .catch(error => {
        console.error('Error:', error);
    });
});
    </script>
</body>
</html>
