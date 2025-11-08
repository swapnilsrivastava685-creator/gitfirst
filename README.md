[food.html](https://github.com/user-attachments/files/23433698/food.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TasteBite – Grand Opening!</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Poppins', sans-serif;
      color: #333;
      background-color: #fff;
    }
    header {
      background: url('https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=1350&q=80') center/cover no-repeat;
      height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
      padding: 0 20px;
    }
    header h1 {
      font-size: 3em;
      text-shadow: 2px 2px 10px rgba(0,0,0,0.6);
    }
    header p {
      font-size: 1.3em;
      margin: 20px 0;
    }
    .cta-btn {
      background-color: #e63946;
      color: white;
      padding: 15px 35px;
      font-size: 1.1em;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      transition: 0.3s;
    }
    .cta-btn:hover {
      background-color: #ff5252;
    }
    section {
      padding: 60px 20px;
      text-align: center;
    }
    section h2 {
      font-size: 2em;
      color: #e63946;
      margin-bottom: 20px;
    }
    section p {
      max-width: 700px;
      margin: 0 auto;
      font-size: 1.1em;
      line-height: 1.6;
    }
    footer {
      background: #111;
      color: #ccc;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }
    input[type="email"] {
      padding: 10px;
      width: 250px;
      border: 1px solid #ccc;
      border-radius: 5px;
      margin-top: 10px;
    }
    .subscribe-btn {
      background: #e63946;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
      margin-left: 5px;
      transition: 0.3s;
    }
    .subscribe-btn:hover {
      background: #ff5252;
    }
  </style>
</head>
<body>

  <header>
    <h1>🍕 TasteBite is Opening Soon!</h1>
    <p>Join us for the grand opening and get <strong>20% off your first meal!</strong></p>
    <button class="cta-btn">Get Early Access</button>
  </header>

  <section>
    <h2>About TasteBite</h2>
    <p>
      We’re bringing fresh, local ingredients and bold flavors to your neighborhood.
      From sizzling pizzas to handcrafted desserts — every bite tells a story.
      Be the first to experience our menu at the grand opening!
    </p>

    <div style="margin-top: 30px;">
      <h3>Get Notified When We Open 🎉</h3>
      <input type="email" placeholder="Enter your email" />
      <button class="subscribe-btn">Notify Me</button>
    </div>
  </section>

  <footer>
    © 2025 TasteBite | Follow us on Instagram @TasteBiteEats
  </footer>

</body>
</html>
