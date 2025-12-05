* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Poppins",
    sans-serif;
  background: #f7f9fb;
  color: #123;
  line-height: 1.6;
}

a {
  text-decoration: none;
  color: inherit;
}

.container {
  max-width: 1100px;
  margin: 0 auto;
  padding: 0 16px;
}

/* Header / navbar */
header {
  background: #006e6b;
  color: #fff;
  position: sticky;
  top: 0;
  z-index: 100;
}

.nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 10px 0;
}

.logo {
  font-weight: 700;
  letter-spacing: 0.08em;
  font-size: 1.3rem;
}

.logo span {
  color: #ffe082;
}

.nav-links {
  display: flex;
  gap: 18px;
  font-size: 0.95rem;
}

.nav-links a {
  color: #eaf8f7;
  font-weight: 500;
}

.nav-links a:hover {
  text-decoration: underline;
}

/* Hero / sections */
.hero {
  background: linear-gradient(135deg, #00a0a0, #006e6b);
  color: #fff;
  padding: 50px 0 40px;
}

.hero-inner {
  display: grid;
  grid-template-columns: minmax(0, 1.4fr) minmax(0, 1fr);
  gap: 32px;
  align-items: center;
}

.hero h1 {
  font-size: 2.4rem;
  margin-bottom: 8px;
}

.tagline {
  font-size: 1.2rem;
  font-weight: 500;
  margin-bottom: 16px;
}

.hero p {
  font-size: 0.96rem;
  max-width: 520px;
  margin-bottom: 18px;
}

.badge {
  display: inline-block;
  padding: 4px 10px;
  border-radius: 999px;
  background: rgba(255, 255, 255, 0.16);
  font-size: 0.78rem;
  margin-bottom: 10px;
}

.hero-buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-bottom: 12px;
}

.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 9px 20px;
  border-radius: 999px;
  font-size: 0.95rem;
  font-weight: 600;
  border: none;
  cursor: pointer;
  transition: transform 0.15s ease, box-shadow 0.15s ease, background 0.15s ease;
}

.btn-primary {
  background: #ffe082;
  color: #004d40;
  box-shadow: 0 10px 18px rgba(0, 0, 0, 0.18);
}

.btn-primary:hover {
  transform: translateY(-1px);
  box-shadow: 0 14px 24px rgba(0, 0, 0, 0.22);
}

.btn-outline {
  background: transparent;
  border: 1px solid rgba(255, 255, 255, 0.8);
  color: #fff;
}

.btn-outline:hover {
  background: rgba(255, 255, 255, 0.12);
}

/* Generic sections */
section {
  padding: 40px 0;
}

.section-title {
  font-size: 1.6rem;
  text-align: center;
  color: #004d40;
  margin-bottom: 8px;
}

.section-subtitle {
  text-align: center;
  font-size: 0.95rem;
  color: #556;
  margin-bottom: 22px;
}

.features-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 18px;
}

.card {
  background: #fff;
  border-radius: 16px;
  padding: 18px;
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.06);
  font-size: 0.9rem;
}

.card h3 {
  margin-bottom: 6px;
  font-size: 1rem;
  color: #004d40;
}

.icon-circle {
  width: 34px;
  height: 34px;
  border-radius: 50%;
  background: #e0f2f1;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 6px;
}

/* Form */
.form-card {
  max-width: 520px;
  margin: 0 auto;
  background: #fff;
  padding: 22px 20px;
  border-radius: 18px;
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.08);
}

.form-row {
  margin-bottom: 12px;
}

label {
  display: block;
  font-size: 0.88rem;
  margin-bottom: 4px;
}

input[type="text"],
input[type="tel"],
textarea {
  width: 100%;
  padding: 8px 10px;
  border-radius: 8px;
  border: 1px solid #cfd8dc;
  font-size: 0.9rem;
}

textarea {
  min-height: 80px;
  resize: vertical;
}

/* Footer */
footer {
  text-align: center;
  padding: 16px 0 22px;
  font-size: 0.8rem;
  color: #778;
}

/* Responsive */
@media (max-width: 840px) {
  .hero-inner {
    grid-template-columns: 1fr;
  }

  .features-grid {
    grid-template-columns: 1fr;
  }

  .nav-links {
    display: none; /* simple mobile nav */
  }

  .hero {
    padding-top: 36px;
  }

  .hero h1 {
    font-size: 2rem;
  }
}# Medsondoor<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MedsOnDoor – Online Pharmacy Home Delivery in Bhopal</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <!-- HEADER -->
  <header>
    <div class="container nav">
      <div class="logo">Meds<span>On</span>Door</div>
      <nav class="nav-links">
        <a href="index.html">Home</a>
        <a href="order.html">Order Now</a>
        <a href="about.html">About</a>
        <a href="faq.html">FAQ</a>
      </nav>
    </div>
  </header>

  <!-- HERO -->
  <section class="hero">
    <div class="container hero-inner">
      <div>
        <div class="badge">Online Pharmacy • Bhopal</div>
        <h1>MedsOnDoor</h1>
        <div class="tagline">Bringing Better Health to Your Home</div>
        <p>
          Send your doctor prescription on WhatsApp and get your medicines,
          daily needs and OTC items delivered to your doorstep – fast, safe
          and affordable.
        </p>
        <div class="hero-buttons">
          <a class="btn btn-primary" href="order.html">Order Now</a>
          <a class="btn btn-outline" href="https://wa.me/917415369601" target="_blank">
            Chat on WhatsApp
          </a>
        </div>
        <p style="font-size:0.84rem;opacity:0.9;">
          Free home delivery on orders above ₹699 • Minimum 16–85% discount on medicines •
          Get medicines in ~2 hours* inside Bhopal.
        </p>
      </div>

      <div class="card">
        <div class="icon-circle">🚚</div>
        <h3>Fast home delivery</h3>
        <p>
          Service available all over Bhopal and nearby areas from
          Medicine Street, Bhopal 462001.
        </p>
      </div>
    </div>
  </section>

  <!-- FEATURES -->
  <section>
    <div class="container">
      <h2 class="section-title">Why Choose MedsOnDoor?</h2>
      <p class="section-subtitle">
        All the benefits of a trusted neighbourhood chemist – without leaving home.
      </p>

      <div class="features-grid">
        <div class="card">
          <div class="icon-circle">💊</div>
          <h3>Genuine Medicines</h3>
          <p>Supplied from licensed pharmacies with proper bills & expiry checks.</p>
        </div>

        <div class="card">
          <div class="icon-circle">💰</div>
          <h3>Big Savings</h3>
          <p>Minimum 16% and up to 85% discount on medicines (T&amp;C apply).</p>
        </div>

        <div class="card">
          <div class="icon-circle">🧾</div>
          <h3>WhatsApp Prescription</h3>
          <p>Send doctor prescription on WhatsApp and we prepare your order for you.</p>
        </div>

        <div class="card">
          <div class="icon-circle">🛒</div>
          <h3>Daily Needs & OTC</h3>
          <p>Hygiene, wellness, baby care and other OTC products also delivered.</p>
        </div>

        <div class="card">
          <div class="icon-circle">⏱️</div>
          <h3>2-Hour Delivery*</h3>
          <p>Get medicines in ~2 hours of order in most Bhopal locations.</p>
        </div>

        <div class="card">
          <div class="icon-circle">📍</div>
          <h3>Bhopal & Nearby</h3>
          <p>Service available all over Bhopal and selected nearby areas.</p>
        </div>
      </div>
    </div>
  </section>

  <footer>
    Address: Medicine Street, Bhopal 462001 • WhatsApp: +91 74153 69601<br />
    *Delivery time & offers depend on stock, prescription validity and exact location.<br />
    © <span id="year"></span> MedsOnDoor. All rights reserved.
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Order Medicines – MedsOnDoor</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="container nav">
      <div class="logo">Meds<span>On</span>Door</div>
      <nav class="nav-links">
        <a href="index.html">Home</a>
        <a href="order.html">Order Now</a>
        <a href="about.html">About</a>
        <a href="faq.html">FAQ</a>
      </nav>
    </div>
  </header>

  <section>
    <div class="container">
      <h2 class="section-title">Order Now</h2>
      <p class="section-subtitle">
        Fill this form and we’ll forward your details to WhatsApp.<br />
        <strong>Important:</strong> after the chat opens, please attach a clear photo of your
        doctor prescription before confirming the order.
      </p>

      <div class="form-card">
        <form id="orderForm">
          <div class="form-row">
            <label for="name">Full Name</label>
            <input id="name" type="text" required />
          </div>

          <div class="form-row">
            <label for="phone">Mobile Number</label>
            <input id="phone" type="tel" placeholder="10-digit number" required />
          </div>

          <div class="form-row">
            <label for="address">Full Delivery Address</label>
            <textarea id="address" required>Medicine Street, Bhopal 462001</textarea>
          </div>

          <div class="form-row">
            <label for="items">Medicines / Items Required</label>
            <textarea id="items" placeholder="Example: Tab XYZ 10mg – 1 strip, Paracetamol 650 – 2 strips" required></textarea>
          </div>

          <div class="form-row">
            <label for="notes">Extra Notes (optional)</label>
            <textarea id="notes" placeholder="Preferred time, landmark, payment mode, etc."></textarea>
          </div>

          <button type="submit" class="btn btn-primary" style="width:100%;">
            Send to WhatsApp
          </button>

          <p style="font-size:0.8rem;margin-top:8px;color:#555;">
            By clicking “Send to WhatsApp” your details will open in a WhatsApp chat
            with MedsOnDoor (+91 74153 69601). Please review and send manually.
          </p>
        </form>
      </div>
    </div>
  </section>

  <footer>
    © <span id="year"></span> MedsOnDoor. All rights reserved.
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();

    const form = document.getElementById("orderForm");
    form.addEventListener("submit", function (e) {
      e.preventDefault();

      const name = document.getElementById("name").value.trim();
      const phone = document.getElementById("phone").value.trim();
      const address = document.getElementById("address").value.trim();
      const items = document.getElementById("items").value.trim();
      const notes = document.getElementById("notes").value.trim();

      const targetNumber = "917415369601"; // your WhatsApp number with country code but no +
      let msg = "New MedsOnDoor Order%0A%0A";
      msg += "*Name:* " + encodeURIComponent(name) + "%0A";
      msg += "*Customer Mobile:* " + encodeURIComponent(phone) + "%0A%0A";
      msg += "*Delivery Address:*%0A" + encodeURIComponent(address) + "%0A%0A";
      msg += "*Medicines / Items:*%0A" + encodeURIComponent(items) + "%0A%0A";
      if (notes) {
        msg += "*Extra Notes:*%0A" + encodeURIComponent(notes) + "%0A%0A";
      }
      msg += "I will also send my doctor prescription photo.";

      const waUrl = "https://wa.me/" + targetNumber + "?text=" + msg;
      window.open(waUrl, "_blank");
    });
  </script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>About – MedsOnDoor</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="container nav">
      <div class="logo">Meds<span>On</span>Door</div>
      <nav class="nav-links">
        <a href="index.html">Home</a>
        <a href="order.html">Order Now</a>
        <a href="about.html">About</a>
        <a href="faq.html">FAQ</a>
      </nav>
    </div>
  </header>

  <section>
    <div class="container">
      <h2 class="section-title">About MedsOnDoor</h2>
      <p class="section-subtitle">
        Bringing better health to your home – one delivery at a time.
      </p>

      <div class="card">
        <h3>Who we are</h3>
        <p>
          MedsOnDoor is an online pharmacy home-delivery service based in
          Bhopal. We work with licensed pharmacies to deliver genuine
          medicines, daily essentials and OTC products directly to your home.
        </p>
        <br />
        <h3>Our mission</h3>
        <p>
          To make access to medicines simple, affordable and fast for every
          family in Bhopal and nearby areas – especially for senior citizens
          and patients who find it difficult to travel.
        </p>
        <br />
        <h3>What we believe</h3>
        <ul style="margin-left:18px;font-size:0.9rem;">
          <li>On-time delivery and clear communication.</li>
          <li>Only genuine, properly billed medicines.</li>
          <li>Transparent pricing and maximum discounts possible.</li>
        </ul>
      </div>
    </div>
  </section>

  <footer>
    © <span id="year"></span> MedsOnDoor. All rights reserved.
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>FAQ – MedsOnDoor</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="container nav">
      <div class="logo">Meds<span>On</span>Door</div>
      <nav class="nav-links">
        <a href="index.html">Home</a>
        <a href="order.html">Order Now</a>
        <a href="about.html">About</a>
        <a href="faq.html">FAQ</a>
      </nav>
    </div>
  </header>

  <section>
    <div class="container">
      <h2 class="section-title">Frequently Asked Questions</h2>

      <div class="card">
        <h3>Do I need a prescription?</h3>
        <p>
          Yes, a valid doctor prescription is required for all prescription
          medicines. For OTC products (vitamins, wellness, hygiene etc.) no
          prescription is needed.
        </p>
        <br />

        <h3>How do I share my prescription?</h3>
        <p>
          Simply click “Send to WhatsApp” from the Order page and then attach
          a clear photo of your prescription in the WhatsApp chat.
        </p>
        <br />

        <h3>How long will delivery take?</h3>
        <p>
          Most orders inside Bhopal are delivered within 2 hours of
          confirmation, depending on stock, distance and traffic.
        </p>
        <br />

        <h3>Which areas do you serve?</h3>
        <p>
          We serve all major areas of Bhopal city and nearby localities. You
          can send us your location on WhatsApp to confirm.
        </p>
        <br />

        <h3>What payment methods do you accept?</h3>
        <p>
          Cash on delivery and selected online payment options (UPI / wallet /
          bank transfer) – you can confirm with our team on WhatsApp.
        </p>
      </div>
    </div>
  </section>

  <footer>
    © <span id="year"></span> MedsOnDoor. All rights reserved.
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>
