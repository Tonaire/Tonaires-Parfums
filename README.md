<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tonaires Perfumes - Luxury Scents</title>
  <style>
    /* CSS Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Arial', sans-serif;
    }

    /* Global Styles */
    body {
      background-color: #f9f5f0;
      color: #333;
      line-height: 1.6;
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 20px;
    }

    /* Header Styles */
    header {
      background-color: #2c3e50;
      color: white;
      padding: 20px 0;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    .header-content {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 28px;
      font-weight: bold;
      color: #e74c3c;
    }

    nav ul {
      display: flex;
      list-style: none;
    }

    nav ul li {
      margin-left: 20px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      transition: color 0.3s;
    }

    nav ul li a:hover {
      color: #e74c3c;
    }

    /* Hero Section */
    .hero {
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://media.discordapp.net/attachments/1352848905896722452/1358436878247788624/2f611e25-cb3d-417d-99f4-e91badbdcd18.jpg?ex=67f3d66e&is=67f284ee&hm=12254817f3e779ccdfc74da04dea86669caf3c6c79e216cd50dc0f82907e4dd0&=&format=webp');
      background-size: cover;
      background-position: center;
      height: 500px;
      display: flex;
      align-items: center;
      text-align: center;
      color: white;
    }

    .hero-content h1 {
      font-size: 48px;
      margin-bottom: 20px;
    }

    .hero-content p {
      font-size: 20px;
      margin-bottom: 30px;
    }

    .btn {
      display: inline-block;
      background-color: #e74c3c;
      color: white;
      padding: 12px 30px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      transition: background-color 0.3s;
    }

    .btn:hover {
      background-color: #c0392b;
    }

    /* Products Section */
    .products {
      padding: 80px 0;
    }

    .section-title {
      text-align: center;
      margin-bottom: 50px;
      font-size: 36px;
      color: #2c3e50;
    }

    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
      gap: 30px;
    }

    .product-card {
      background-color: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

    .product-card:hover {
      transform: translateY(-10px);
    }

    .product-image {
      height: 250px;
      background-color: #eee;
      background-size: cover;
      background-position: center;
    }

    .product-info {
      padding: 20px;
    }

    .product-name {
      font-size: 22px;
      margin-bottom: 10px;
      color: #2c3e50;
    }

    .product-desc {
      color: #7f8c8d;
      margin-bottom: 15px;
    }

    .product-price {
      display: flex;
      justify-content: space-between;
      margin-bottom: 15px;
    }

    .price-option {
      text-align: center;
      flex: 1;
    }

    .price-option:first-child {
      border-right: 1px solid #eee;
    }

    .size {
      font-size: 14px;
      color: #7f8c8d;
    }

    .price {
      font-weight: bold;
      color: #e74c3c;
      font-size: 18px;
    }

    .add-to-cart {
      width: 100%;
      padding: 10px;
      background-color: #2c3e50;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s;


    // Remove active class from all tabs
    document.querySelectorAll('.payment-tab').forEach(el => {
    el.classList.remove('active');
    });

    // Show selected payment form
    document.getElementById(method + '-payment').style.display = 'block';

    // Add active class to clicked tab
    event.currentTarget.classList.add('active');
    }

    function placeOrder() {
    alert('Thank you for your order! For real payments, integrate Stripe/PayPal.');
    // window.location.href = "success.html"; // Redirect to success page
    }
    </script>
    .add-to-cart:hover {
      background-color: #1a252f;
    }

    /* Footer */
    footer {
      background-color: #2c3e50;
      color: white;
      padding: 40px 0;
      text-align: center;
    }

    .footer-content {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
    }

    .footer-section {
      flex: 1;
      min-width: 250px;
      margin-bottom: 20px;
    }

    .footer-section h3 {
      margin-bottom: 20px;
      color: #e74c3c;
    }

    .footer-section p, .footer-section a {
      color: #bdc3c7;
      margin-bottom: 10px;
      display: block;
      text-decoration: none;
    }

    .footer-section a:hover {
      color: white;
    }

    .copyright {
      margin-top: 30px;
      padding-top: 20px;
      border-top: 1px solid #34495e;
    }

    /* Responsive */
    @media (max-width: 768px) {
      .header-content {
        flex-direction: column;
        text-align: center;
      }

      nav ul {
        margin-top: 20px;
        justify-content: center;
      }

      nav ul li {
        margin: 0 10px;
      }

      .hero-content h1 {
        font-size: 36px;
      }

      .hero-content p {
        font-size: 18px;
      }
    }
  </style>
</head>
<body>
<!-- Header -->
<header>
  <div class="container header-content">
    <div class="logo">TONAIRES PERFUMES</div>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#products">Products</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </div>
</header>

<!-- Hero Section -->
<section class="hero">
  <div class="container hero-content">
    <div>
      <h1>Luxury Scents for the Discerning</h1>
      <p>Premium fragrances crafted with passion and precision</p>
      <a href="#products" class="btn">Shop Now</a>
    </div>
  </div>
</section>

<!-- Products Section -->
<section class="products" id="products">
  <div class="container">
    <h2 class="section-title">Our Premium Collection</h2>
    <div class="product-grid">
      <!-- Stronger With You -->
      <div class="product-card">
        <div class="product-image" style="background-image: url('https://www.sephora.com.tr/on/demandware.static/-/Sites-masterCatalog_Sephora/default/dw098e53f9/images/hi-res/SKU/SKU_2003/541264_swatch.jpg');"></div>
        <div class="product-info">
          <h3 class="product-name">Stronger With You</h3>
          <p class="product-desc">An intense, seductive blend of amber, vanilla, and spices for bold confidence.</p>
          <div class="product-price">
            <div class="price-option">
              <div class="size">5ml</div>
              <div class="price">60DH</div>
            </div>
            <div class="price-option">
              <div class="size">10ml</div>
              <div class="price">120DH</div>
            </div>
          </div>
          <button class="add-to-cart">Add to Cart</button>
        </div>
      </div>

      <!-- Bleu de Chanel -->
      <div class="product-card">
        <div class="product-image" style="background-image: url('https://fimgs.net/mdimg/perfume/375x500.49912.jpg');"></div>
        <div class="product-info">
          <h3 class="product-name">Bleu de Chanel</h3>
          <p class="product-desc">A timeless blend of citrus, woods, and spices for effortless elegance.</p>
          <div class="product-price">
            <div class="price-option">
              <div class="size">5ml</div>
              <div class="price">60DH</div>
            </div>
            <div class="price-option">
              <div class="size">10ml</div>
              <div class="price">120DH</div>
            </div>
          </div>
          <button class="add-to-cart">Add to Cart</button>
        </div>
      </div>

      <!-- Jean Paul Gaultier -->
      <div class="product-card">
        <div class="product-image" style="background-image: url('https://www.elpalaciodehierro.com/dw/image/v2/BDKB_PRD/on/demandware.static/-/Sites-palacio-master-catalog/default/dw663d492f/images/40412732/large/40412732_x1.jpg?sw=960&sh=1152');"></div>
        <div class="product-info">
          <h3 class="product-name">Jean Paul Gaultier</h3>
          <p class="product-desc">Iconic Le Male: Lavender, vanilla, and mint for irresistible allure.</p>
          <div class="product-price">
            <div class="price-option">
              <div class="size">5ml</div>
              <div class="price">60DH</div>
            </div>
            <div class="price-option">
              <div class="size">10ml</div>
              <div class="price">120DH</div>
            </div>
          </div>
          <button class="add-to-cart">Add to Cart</button>
        </div>
      </div>
    </div>
  </div>
</section>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tonaires Perfumes - Luxury Scents</title>
  <style>
    /* Previous CSS remains the same */
    /* Add these new styles for payment section */

    .payment-section {
      padding: 60px 0;
      background-color: #f5f5f5;
    }

    .payment-methods {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-bottom: 30px;
    }

    .payment-tab {
      padding: 12px 25px;
      background: #e0e0e0;
      border-radius: 30px;
      cursor: pointer;
      transition: all 0.3s;
    }

    .payment-tab.active {
      background: #e74c3c;
      color: white;
    }

    .payment-form {
      max-width: 500px;
      margin: 0 auto;
      background: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      display: none;
    }

    .payment-form.active {
      display: block;
    }

    .form-group {
      margin-bottom: 20px;
    }

    .form-group label {
      display: block;
      margin-bottom: 8px;
      font-weight: bold;
    }

    .form-group input {
      width: 100%;
      padding: 12px;
      border: 1px solid #ddd;
      border-radius: 5px;
    }

    .whatsapp-float {
      position: fixed;
      bottom: 30px;
      right: 30px;
      background-color: #25D366;
      color: white;
      width: 60px;
      height: 60px;
      border-radius: 50%;
      text-align: center;
      font-size: 30px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
      z-index: 100;
      display: flex;
      align-items: center;
      justify-content: center;
      transition: all 0.3s;
    }

    .whatsapp-float:hover {
      transform: scale(1.1);
      background-color: #128C7E;
    }
  </style>
</head>
<body>
<!-- Previous HTML content remains the same until before footer -->

<!-- New Payment Section -->
<section class="payment-section" id="payment">
  <div class="container">
    <h2 class="section-title">Secure Payment</h2>

    <div class="payment-methods">
      <div class="payment-tab active" onclick="showPayment('cash')">Cash on Delivery</div>
      <div class="payment-tab" onclick="showPayment('card')">Credit Card</div>
      <div class="payment-tab" onclick="showPayment('whatsapp')">WhatsApp Order</div>
    </div>

    <!-- Cash on Delivery Form -->
    <div id="cash-payment" class="payment-form active">
      <h3>Cash on Delivery</h3>
      <p>Pay when you receive your order. Available for Kasba Tadla area.</p>
      <form id="cashForm">
        <div class="form-group">
          <label>Full Name</label>
          <input type="text" required>
        </div>
        <div class="form-group">
          <label>Address</label>
          <input type="text" required>
        </div>
        <div class="form-group">
          <label>Phone Number</label>
          <input type="tel" required>
        </div>
        <button type="button" class="btn" onclick="placeOrder()">Place Order</button>
      </form>
    </div>

    <!-- Credit Card Form -->
    <div id="card-payment" class="payment-form">
      <h3>Credit/Debit Card</h3>
      <p>Secure payment powered by our partners.</p>
      <form id="cardForm">
        <div class="form-group">
          <label>Card Number</label>
          <input type="text" placeholder="1234 5678 9012 3456" required>
        </div>
        <div class="form-group">
          <label>Expiry Date</label>
          <input type="text" placeholder="MM/YY" required>
        </div>
        <div class="form-group">
          <label>CVV</label>
          <input type="text" placeholder="123" required>
        </div>
        <div class="form-group">
          <label>Name on Card</label>
          <input type="text" required>
        </div>
        <button type="button" class="btn" onclick="placeOrder()">Pay Now</button>
      </form>
    </div>

    <!-- WhatsApp Order -->
    <div id="whatsapp-payment" class="payment-form">
      <h3>Order via WhatsApp</h3>
      <p>Send your order directly to our WhatsApp for personalized service.</p>
      <div style="text-align: center; margin-top: 30px;">
        <a href="https://wa.me/212720663991?text=Hello%20Tonaires%20Perfumes,%20I%20want%20to%20order:" class="btn" style="background-color: #25D366;">
          Chat on WhatsApp
        </a>
      </div>
    </div>
  </div>
</section>

<!-- WhatsApp Float Button -->
<a href="https://wa.me/212720663991" class="whatsapp-float" target="_blank">
  <i class="fab fa-whatsapp"></i>
</a>

<!-- Previous Footer remains the same -->

<!-- Add Font Awesome for WhatsApp icon -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">

<script>
  // Payment Method Tabs
  function showPayment(method) {
    // Hide all payment forms
    document.querySelectorAll('.payment-form').forEach(el => {
      el.classList.remove('active');
    });

    // Remove active class from all tabs
    document.querySelectorAll('.payment-tab').forEach(el => {
      el.classList.remove('active');
    });

    // Show selected payment form
    document.getElementById(method + '-payment').classList.add('active');

    // Add active class to clicked tab
    event.currentTarget.classList.add('active');
  }

  function placeOrder() {
    alert('Thank you for your order! We will contact you shortly.');
    // For WhatsApp orders, the link already handles this
  }
</script>
</body>
</html>

<!-- About Section -->
<section class="about" id="about" style="padding: 80px 0; background-color: #fff;">
  <div class="container">
    <h2 class="section-title">About Tonaires Perfumes</h2>
    <div style="max-width: 800px; margin: 0 auto; text-align: center;">
      <p style="margin-bottom: 20px; font-size: 18px;">
        At Tonaires Perfumes, we bring you the world’s most luxurious fragrances at accessible prices. Each scent is curated for unforgettable elegance.
      </p>
      <p style="font-size: 18px;">
        Choose between our 5ml travel size (60DH) or 10ml bottle (120DH) for a lasting impression.
      </p>
    </div>
  </div>
</section>

<!-- Footer -->
<footer id="contact">
  <div class="container">
    <div class="footer-content">
      <div class="footer-section">
        <h3>About Us</h3>
        <p>Tonaires Perfumes: Luxury scents from Kasba Tadla to the world.</p>
      </div>
      <div class="footer-section">
        <h3>Quick Links</h3>
        <a href="#">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
      </div>
      <div class="footer-section">
        <h3>Contact Us</h3>
        <p>Email: tonairetonaire20@gmail.com</p>
        <p>Phone: +212 720 663 991</p>
        <p>Address: Kasba Tadla, Morocco</p>
      </div>
    </div>
    <div class="copyright">
      <p>&copy; 2025 Tonaires Perfumes. All Rights Reserved.</p>
    </div>
  </div>
</footer>
</body>
</html>
