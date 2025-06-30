<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <title>Neer Fashion House</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fefefe;
    }
    header {
      background-color: #8e44ad;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #eee;
      padding: 10px;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #444;
    }
    .hero {
      text-align: center;
      padding: 50px 20px;
      background-color: #f3e5f5;
    }
    .products {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 20px;
    }
    .product {
      border: 1px solid #ddd;
      margin: 10px;
      padding: 15px;
      width: 200px;
      text-align: center;
    }
    .product img {
      width: 100%;
      height: auto;
    }
    .contact {
      background: #eee;
      padding: 20px;
      text-align: center;
    }
    footer {
      background: #8e44ad;
      color: white;
      text-align: center;
      padding: 10px;
    }
    .order-btn {
      background: #27ae60;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
      display: inline-block;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Neer Fashion House</h1>
    <p>স্টাইল, ট্রেন্ড ও কমফোর্ট - সব একসাথে!</p>
  </header>

  <nav>
    <a href="#">হোম</a>
    <a href="#">কালেকশন</a>
    <a href="#">যোগাযোগ</a>
    <a href="https://facebook.com" target="_blank">Facebook</a>
  </nav>

  <div class="hero">
    <h2>নতুন কালেকশন এসে গেছে!</h2>
    <p>সবচেয়ে ট্রেন্ডি পোশাক এখন Neer Fashion-এ</p>
    <a class="order-btn" href="https://wa.me/8801XXXXXXXXX" target="_blank">অর্ডার করুন WhatsApp-এ</a>
  </div>

  <section class="products">
    <div class="product">
      <img src="https://via.placeholder.com/200x250" alt="Product 1">
      <h4>লেডিজ কুর্তি</h4>
      <p>৳ 850</p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200x250" alt="Product 2">
      <h4>জেন্টস শার্ট</h4>
      <p>৳ 750</p>
    </div>
    <!-- আরো প্রোডাক্ট যোগ করতে পারো -->
  </section>

  <div class="contact">
    <h3>যোগাযোগ</h3>
    <p>📞 01934648881</p>
    <p>📍 কুড়িগ্রাম সদর</p>
  </div>

  <footer>
    <p>&copy; 2025 Neer Fashion House. সর্বস্বত্ব সংরক্ষিত।</p>
  </footer>
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Neer Fashion House</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
    }
    header {
      background-color: #222;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    .bio {
      text-align: center;
      margin-top: 10px;
      color: #555;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }
    .product {
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 8px;
      margin: 10px;
      padding: 10px;
      width: 200px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .product img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .product h3 {
      margin: 10px 0 5px 0;
      font-size: 18px;
    }
    .product p {
      margin: 0;
      color: #333;
    }
    footer {
      background-color: #222;
      color: #fff;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Neer Fashion House</h1>
    <div class="bio">Buy only from here</div>
  </header>  <div class="products">
    <!-- 50 products will be inserted below --><!-- Example Product (repeat 50 times with random prices)-->
<!-- Use placeholders for now -->

  </div>  <footer>
    <p>Contact: 017XXXXXXXX</p>
    <p>Address: House #12, Road #7, Dhanmondi, Dhaka</p>
  </footer>  <script>
    const prices = [3500, 4000, 4500, 5000, 3800, 3000, 3700, 4900, 4200, 4600];
    const productsContainer = document.querySelector('.products');

    for (let i = 1; i <= 50; i++) {
      const price = prices[Math.floor(Math.random() * prices.length)];
      const product = document.createElement('div');
      product.className = 'product';
      product.innerHTML = `
        <img src="https://via.placeholder.com/200x200?text=Product+${i}" alt="Product ${i}" />
        <h3>Product ${i}</h3>
        <p>Price: ৳${price}</p>
      `;
      productsContainer.appendChild(product);
    }
  </script></body>
</html>
