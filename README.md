# my-website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Items and Prices</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 20px;
    }
    h1 {
      text-align: center;
    }
    .container {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .item-card {
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 10px;
      width: 200px;
      padding: 15px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    .item-card h2 {
      font-size: 1.2em;
      margin: 0 0 10px;
    }
    .item-card p {
      font-size: 1em;
      color: #333;
    }
  </style>
</head>
<body>
  <h1>Product List</h1>
  <div class="container">
    <div class="item-card">
      <h2>Notebook</h2>
      <p>₹120</p>
    </div>
    <div class="item-card">
      <h2>Pen</h2>
      <p>₹25</p>
    </div>
    <div class="item-card">
      <h2>Backpack</h2>
      <p>₹999</p>
    </div>
    <div class="item-card">
      <h2>Mouse</h2>
      <p>₹499</p>
    </div>
    <div class="item-card">
      <h2>Keyboard</h2>
      <p>₹699</p>
    </div>
  </div>
</body>
</html>
