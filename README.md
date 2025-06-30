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
</body>
</html>
