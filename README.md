<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Product Showcase</title>
  <style>
    body { font-family: Arial, sans-serif; background: #f2f2f2; margin: 0; padding: 20px; }
    h1 { text-align: center; }
    .products { display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; }
    .product {
      background: white;
      border-radius: 8px;
      padding: 15px;
      width: 260px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product img { width: 100%; border-radius: 6px; }
    .product h2 { font-size: 1.1em; margin: 10px 0; }
    .price { color: #e91e63; font-weight: bold; }
    .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 15px;
      background: #2196f3;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }
    .btn:hover { background: #0b7dda; }
  </style>
</head>
<body>
  <h1>Welcome to My Product Store</h1>
  <div class="products">
    <div class="product">
      <img src="https://via.placeholder.com/250x250?text=Bluetooth+Speaker" alt="Bluetooth Speaker">
      <h2>Bluetooth Speaker</h2>
      <p class="price">$29.99</p>
      <a class="btn" href="https://www.amazon.com/dp/B000123456" target="_blank">Buy Now</a>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x250?text=Fitness+Tracker" alt="Fitness Tracker">
      <h2>Fitness Tracker</h2>
      <p class="price">$49.99</p>
      <a class="btn" href="https://www.amazon.com/dp/B000654321" target="_blank">Buy Now</a>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x250?text=Reusable+Bottle" alt="Reusable Bottle">
      <h2>Reusable Water Bottle</h2>
      <p class="price">$15.99</p>
      <a class="btn" href="https://www.amazon.com/dp/B001234567" target="_blank">Buy Now</a>
    </div>
  </div>
</body>
</html>
