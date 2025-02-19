<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Essential Service Finder</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f9;
    }
    header {
      background-color: #2c3e50;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    main {
      padding: 1rem;
    }
    .service-card {
      background-color: white;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      margin-bottom: 1rem;
      padding: 1rem;
    }
    .service-card h3 {
      margin-top: 0;
    }
    footer {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 1rem;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
    button {
      background-color: #3498db;
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 4px;
      cursor: pointer;
    }
    button:hover {
      background-color: #2980b9;
    }
    .cta-section {
      background-color: #e74c3c;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
      margin-top: 1rem;
      border-radius: 8px;
    }
    .cta-section h2 {
      margin-bottom: 1rem;
    }
    .cta-button {
      background-color: #c0392b;
      padding: 1rem 2rem;
      font-size: 1rem;
      border-radius: 4px;
      transition: background-color 0.3s ease;
    }
    .cta-button:hover {
      background-color: #a52f23;
    }
  </style>
</head>
<body>
  <header>
    <h1>Essential Service Finder</h1>
    <p>Connecting you to high-demand, low-supply services in your area.</p>
  </header>
  <main>
    <div class="service-card">
      <h3>Medical Supplies</h3>
      <p>Find essential medical supplies like masks, gloves, and sanitizers.</p>
      <button onclick="alert('Redirecting to Medical Supplies...')">Find Now</button>
    </div>
    <div class="service-card">
      <h3>Grocery Delivery</h3>
      <p>Order groceries online and get them delivered to your doorstep.</p>
      <button onclick="alert('Redirecting to Grocery Delivery...')">Order Now</button>
    </div>
    <div class="service-card">
      <h3>Home Repair Services</h3>
      <p>Connect with trusted professionals for plumbing, electrical, and more.</p>
      <button onclick="alert('Redirecting to Home Repair Services...')">Book Now</button>
    </div>
    <div class="service-card">
      <h3>Online Education</h3>
      <p>Access high-quality online courses for skill development.</p>
      <button onclick="alert('Redirecting to Online Education...')">Learn Now</button>
    </div>

    <!-- Call to Action Section -->
    <div class="cta-section">
      <h2>Need Immediate Assistance?</h2>
      <p>Our team is here to help you find the services you need quickly and efficiently.</p>
      <button class="cta-button" onclick="alert('Contacting support team...')">Get Help Now</button>
    </div>
  </main>
  <footer>
    <p>&copy; 2023 Essential Service Finder. All rights reserved.</p>
  </footer>
</body>
</html>
