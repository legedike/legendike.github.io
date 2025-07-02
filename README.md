# legendike.github.io

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Legend Trading</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Orbitron', sans-serif;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #fff;
      overflow-x: hidden;
    }

    header {
      background-color: rgba(255, 255, 255, 0.05);
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
      backdrop-filter: blur(8px);
    }

    header h1 {
      font-size: 2rem;
      color: #00f9ff;
      text-shadow: 0 0 10px #00f9ff;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #00f9ff;
    }

    .hero {
      padding: 80px 40px;
      text-align: center;
      perspective: 1000px;
    }

    .hero-content {
      background: rgba(255,255,255,0.1);
      padding: 60px;
      border-radius: 15px;
      backdrop-filter: blur(10px);
      transform: rotateY(5deg);
      box-shadow: 0 15px 30px rgba(0,0,0,0.3);
      transition: transform 0.5s;
    }

    .hero-content:hover {
      transform: rotateY(0deg) scale(1.02);
    }

    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 1.1rem;
      line-height: 1.6;
    }

    section {
      padding: 60px 40px;
    }

    .section-title {
      font-size: 2rem;
      color: #00f9ff;
      text-align: center;
      margin-bottom: 40px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
    }

    .card {
      background: rgba(255,255,255,0.08);
      padding: 25px;
      border-radius: 12px;
      text-align: center;
      backdrop-filter: blur(5px);
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .card:hover {
      transform: scale(1.05);
      box-shadow: 0 10px 30px rgba(0,0,0,0.4);
    }

    footer {
      background: rgba(0,0,0,0.3);
      text-align: center;
      padding: 30px;
      font-size: 1rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Legend Trading</h1>
    <nav>
      <a href="#crypto">Crypto</a>
      <a href="#forex">Forex</a>
      <a href="#academy">Academy</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h2>Welcome to Legend Trading</h2>
      <p>Empowering your financial journey with expert insights into cryptocurrencies, foreign exchange markets, and trading education. We are Legend.</p>
    </div>
  </section>

  <section id="crypto">
    <h3 class="section-title">Cryptocurrency Trading</h3>
    <div class="grid">
      <div class="card">Live Signals</div>
      <div class="card">Portfolio Management</div>
      <div class="card">Secure Wallet Integration</div>
    </div>
  </section>

  <section id="forex">
    <h3 class="section-title">Foreign Exchange Services</h3>
    <div class="grid">
      <div class="card">Real-time Forex Rates</div>
      <div class="card">Expert Analysis</div>
      <div class="card">Risk Management</div>
    </div>
  </section>

  <section id="academy">
    <h3 class="section-title">Legend Academy</h3>
    <div class="grid">
      <div class="card">Courses on Crypto & Forex</div>
      <div class="card">Webinars & Live Coaching</div>
      <div class="card">Trading Strategy Building</div>
    </div>
  </section>

  <section id="contact">
    <h3 class="section-title">Contact Us</h3>
    <div style="text-align:center">
      <p>Email: <a href="mailto:legendike321@gmail.com" style="color: #00f9ff;">legendike321@gmail.com</a></p>
      <p>Phone: <a href="tel:0537193310" style="color: #00f9ff;">0537193310</a></p>
    </div>
  </section>

  <footer>
    &copy; 2025 Legend Trading. All Rights Reserved.
  </footer>

</body>
</html>
