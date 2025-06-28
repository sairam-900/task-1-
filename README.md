<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Fresh Milk Store</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5fdf6;
    }

    header {
      background-color: #2a9d8f;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background-color: #264653;
      text-align: center;
      padding: 10px;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    .container {
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }

    .product {
      display: flex;
      align-items: center;
      gap: 20px;
      margin-bottom: 20px;
      background: #ffffff;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
    }

    .product img {
      width: 150px;
      height: auto;
      border-radius: 8px;
    }

    .product-details {
      flex: 1;
    }

    .product-details h3 {
      margin: 0;
      color: #333;
    }

    .product-details p {
      margin: 8px 0;
      color: #555;
    }

    .alert-btn {
      display: block;
      margin: 40px auto;
      padding: 12px 24px;
      background-color: #e76f51;
      color: white;
      border: none;
      border-radius: 8px;
      font-size: 16px;
      cursor: pointer;
    }

    footer {
      background-color: #2a9d8f;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to Fresh Milk Store 🥛</h1>
    <p>Pure. Fresh. Affordable Milk at your doorstep.</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">Products</a>
    <a href="#">Contact</a>
  </nav>

  <div class="container">
    <h2>Our Products</h2>

    <div class="product">
      <img src="https://via.placeholder.com/150?text=1L+Milk" alt="1 litre milk" />
      <div class="product-details">
        <h3>1 Litre Fresh Milk</h3>
        <p>Price: ₹60/-</p>
        <p>Ideal for families and regular use.</p>
      </div>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/150?text=500ml+Milk" alt="500ml milk" />
      <div class="product-details">
        <h3>500ml Fresh Milk</h3>
        <p>Price: ₹30/-</p>
        <p>Perfect for quick needs and small households.</p>
      </div>
    </div>

    <button class="alert-btn" onclick="showAlert()">Order Now</button>
  </div>

  <footer>
    &copy; 2025 Fresh Milk Store 
  </footer>

  <script>
    function showAlert() {
      alert("Thank you for choosing Fresh Milk Store! Your order will be processed soon.");
    }
  </script>
</body>
</html>
 
