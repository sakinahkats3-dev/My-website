📂 File: index.html
Copy code
Html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Kalanzi Poultry Farm</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Kalanzi Poultry Farm</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About Us</a>
      <a href="products.html">Products</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Fresh Poultry & Eggs Direct From Our Farm</h2>
    <p>Supplying healthy chickens and farm-fresh eggs across Uganda.</p>
    <img src="images/farm.jpg" alt="Kalanzi Poultry Farm" width="80%">
  </section>

  <section class="intro">
    <h3>Why Choose Us?</h3>
    <ul>
      <li>🐓 Healthy and well-bred poultry</li>
      <li>🥚 Fresh, organic eggs daily</li>
      <li>🚚 Reliable delivery services</li>
      <li>✅ Affordable prices for every customer</li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2025 Kalanzi Poultry Farm | All Rights Reserved</p>
  </footer>
</body>
</html>
📂 File: about.html
Copy code
Html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>About Us - Kalanzi Poultry Farm</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Kalanzi Poultry Farm</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About Us</a>
      <a href="products.html">Products</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section>
    <h2>About Us</h2>
    <p>Kalanzi Poultry Farm is dedicated to producing quality poultry and eggs for our customers. 
    We focus on organic farming, ensuring that our chickens are healthy and free from harmful chemicals.</p>
    <img src="images/chickens.jpg" alt="Healthy Chickens" width="70%">
    <p>We started with just a few chickens, and today we supply restaurants, schools, and households across Uganda. 
    Our mission is to bring fresh, affordable, and nutritious poultry products to your table.</p>
  </section>

  <footer>
    <p>&copy; 2025 Kalanzi Poultry Farm</p>
  </footer>
</body>
</html>
📂 File: products.html
Copy code
Html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Our Products - Kalanzi Poultry Farm</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Kalanzi Poultry Farm</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About Us</a>
      <a href="products.html">Products</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section>
    <h2>Our Products</h2>

    <div class="product">
      <h3>Broiler Chickens</h3>
      <img src="images/broilers.jpg" alt="Broiler Chickens" width="60%">
      <p>Fast-growing broilers, perfect for meat production.</p>
    </div>

    <div class="product">
      <h3>Layers (Egg-Laying Hens)</h3>
      <img src="images/layers.jpg" alt="Layer Chickens" width="60%">
      <p>Healthy layers producing high-quality eggs daily.</p>
    </div>

    <div class="product">
      <h3>Fresh Eggs</h3>
      <img src="images/eggs.jpg" alt="Farm Fresh Eggs" width="60%">
      <p>Organic farm-fresh eggs, available in wholesale and retail.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Kalanzi Poultry Farm</p>
  </footer>
</body>
</html>
📂 File: contact.html
Copy code
Html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - Kalanzi Poultry Farm</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Kalanzi Poultry Farm</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About Us</a>
      <a href="products.html">Products</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section>
    <h2>Contact Us</h2>
    <p>We’d love to hear from you! Reach us through the following:</p>
    <ul>
      <li>📍 Location: Kampala, Uganda</li>
      <li>📞 Phone: +256 700 123456</li>
      <li>✉️ Email: info@kalanzipoultryfarm.com</li>
    </ul>

    <form>
      <label for="name">Your Name:</label><br>
      <input type="text" id="name" name="name" required><br><br>

      <label for="email">Your Email:</label><br>
      <input type="email" id="email" name="email" required><br><br>

      <label for="message">Your Message:</label><br>
      <textarea id="message" name="message" rows="5" required></textarea><br><br>

      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Kalanzi Poultry Farm</p>
  </footer>
</body>
</html>
📂 File: style.css (Optional styling)
Copy code
Css
body {
  font-family: Arial, sans-serif;
  margin: 0; padding: 0;
  background: #f9f9f9;
  color: #333;
  text-align: center;
}

header {
  background: #228B22;
  color: white;
  padding: 15px;
}

header h1 {
  margin: 0;
}

nav a {
  margin: 0 15px;
  color: white;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

.hero {
  background: #fff;
  padding: 20px;
}

section {
  padding: 20px;
}

.product {
  margin: 20px 0;
}

footer {
  background: #333;
  color: white;
  padding: 10px;
}
