# Quantum
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Quantum Co.</title>
  <style>
    body {
      margin: 0;
      overflow: hidden;
      font-family: 'Arial', sans-serif;
    }

    #background {
      position: fixed;
      width: 100%;
      height: 100%;
      z-index: -1;
      pointer-events: none;
    }

    #content {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
      color: white;
    }

    #social-button {
      display: inline-block;
      padding: 10px 20px;
      background-color: #3498db;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 20px;
    }

    #store {
      margin-top: 50px;
    }

    .product {
      display: inline-block;
      margin: 20px;
      padding: 20px;
      background-color: #2ecc71;
      border-radius: 10px;
      text-align: center;
    }

    #cart {
      margin-top: 20px;
    }
  </style>
</head>

<body>
  <div id="background"></div>
  <div id="content">
    <h1>Quantum Co.</h1>
    <a href="#" id="social-button">Follow us on social media</a>

    <div id="store">
      <div class="product">
        <h2>Logo Design Services</h2>
        <p>$10</p>
        <button onclick="addToCart('Logo Design Services', 10)">Add to Cart</button>
      </div>

      <div class="product">
        <h2>Video Editing Services</h2>
        <p>$13</p>
        <button onclick="addToCart('Video Editing Services', 13)">Add to Cart</button>
      </div>

      <div class="product">
        <h2>Poster Design Services</h2>
        <p>$15</p>
        <button onclick="addToCart('Poster Design Services', 15)">Add to Cart</button>
      </div>
    </div>

    <div id="cart">
      <h2>Shopping Cart</h2>
      <ul id="cart-items"></ul>
      <p>Total: $<span id="total">0</span></p>
      <button onclick="checkout()">Checkout with PayPal</button>
    </div>
  </div>

  <script>
    // Your animated background script goes here

    // Dummy functions for cart and checkout
    function addToCart(product, price) {
      // Implement adding to the cart
    }

    function checkout() {
      // Implement checkout with PayPal
    }
  </script>
</body>

</html>
