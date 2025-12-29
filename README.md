<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>GreenBasket | Fresh Vegetables</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background-color: #f6fff6;
      color: #2f4f2f;
    }
    header {
      background: #2ecc71;
      padding: 20px;
      text-align: center;
      color: white;
    }
    nav {
      background: #27ae60;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      padding: 40px 20px;
      text-align: center;
      background: #eaffea;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      padding: 40px;
    }
    .card {
      background: white;
      border-radius: 12px;
      padding: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    .card img {
      width: 100px;
      height: 100px;
      object-fit: cover;
      border-radius: 50%;
    }
    .card button {
      margin-top: 10px;
      padding: 10px 15px;
      background: #2ecc71;
      border: none;
      border-radius: 8px;
      color: white;
      cursor: pointer;
    }
    footer {
      background: #27ae60;
      color: white;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>
<body>

  <header>
    <img src="https://via.placeholder.com/120?text=Owner" alt="Owner Image" style="width:120px;height:120px;border-radius:50%;object-fit:cover;margin-bottom:10px;" />
    <h1>🥕 GreenBasket</h1>
    <p>Fresh • Organic • Daily</p>
    <p style="font-size:14px; margin-top:8px;">Owned by <strong>Saurabh Pandey</strong></p>
    <p style="font-size:14px;">📞 <a href="tel:7355623160" style="color:white; text-decoration:none;">7355623160</a></p>
    <p style="font-size:14px;">📍 IET Campus, Ayodhya</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#products">Vegetables</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>

  <section class="hero">
    <h2>Farm Fresh Vegetables Delivered</h2>
    <p>Healthy food for a healthy life</p>
  </section>

  <section class="products" id="products">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1567306226416-28f0efdc88ce" alt="Tomato">
      <h3>Tomato</h3>
      <p>₹40 / kg</p>
      <button>Add to Cart</button>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1582515073490-dc0c7b1b3b7d" alt="Potato">
      <h3>Potato</h3>
      <p>₹30 / kg</p>
      <button>Add to Cart</button>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1584270354949-1f79c6f0a3f5" alt="Carrot">
      <h3>Carrot</h3>
      <p>₹50 / kg</p>
      <button>Add to Cart</button>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1540420773420-3366772f4999" alt="Spinach">
      <h3>Spinach</h3>
      <p>₹25 / bunch</p>
      <button>Add to Cart</button>
    </div>
  </section>

  <footer>
    <p>© 2025 GreenBasket | Owned by Saurabh Pandey | Contact: 7355623160 | Location: IET Campus, Ayodhya</p>
  </footer>

</body>
</html>
