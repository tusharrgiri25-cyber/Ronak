[rooo.html](https://github.com/user-attachments/files/32689421/rooo.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Zen Z Clothing</title>
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #111;
      color: #eee;
    }
    header {
      background: #000;
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid #444;
    }
    header h1 {
      font-size: 2.5em;
      color: #fff;
      letter-spacing: 2px;
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      color: #eee;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ff4d4d;
    }
    .hero {
      background: url('your-hoodie-image.jpg') no-repeat center center/cover;
      height: 70vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
      text-shadow: 2px 2px 5px #000;
    }
    .hero h2 {
      font-size: 3em;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 40px;
      gap: 20px;
    }
    .product {
      background: #222;
      padding: 20px;
      border-radius: 8px;
      width: 250px;
      text-align: center;
      transition: transform 0.3s;
    }
    .product:hover {
      transform: scale(1.05);
    }
    .product img {
      width: 100%;
      border-radius: 8px;
    }
    footer {
      background: #000;
      color: #aaa;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
      border-top: 2px solid #444;
    }
  </style>
</head>
<body>
  <header>
    <h1>Zen Z Clothing</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Shop</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Streetwear. Redefined.</h2>
  </section>

  <section class="products">
    <div class="product">
      <img src="hoodie.jpg" alt="Zen Z Hoodie">
      <h3>Zen Z Hoodie</h3>
      <p>₹1999</p>
    </div>
    <div class="product">
      <img src="baggy-pants.jpg" alt="Baggy Pants">
      <h3>Baggy Pants</h3>
      <p>₹1499</p>
    </div>
    <div class="product">
      <img src="new-drop.jpg" alt="New Drop">
      <h3>Latest Drop</h3>
      <p>₹2499</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2026 Zen Z Clothing | Follow us on Instagram @ZenZClothing</p>
  </footer>
</body>
</html>
