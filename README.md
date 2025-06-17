<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Affiliate Marketing for Beginners</title>
  <meta name="description" content="Learn how to start affiliate marketing and earn daily income online. Perfect for beginners using only a smartphone!" />
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f9ff;
      color: #333;
    }

    header, footer {
      background-color: #003366;
      color: white;
      text-align: center;
      padding: 20px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 10px;
    }

    main {
      padding: 20px;
    }

    section {
      background: white;
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.08);
    }

    .btn {
      display: inline-block;
      background: #27ae60;
      color: white;
      padding: 10px 20px;
      border-radius: 6px;
      text-decoration: none;
      margin-top: 10px;
      transition: background 0.3s ease;
      cursor: pointer;
      border: none;
    }

    .btn:hover {
      background: #1e8449;
    }

    input, select {
      padding: 10px;
      margin: 10px 0;
      width: 100%;
      border-radius: 6px;
      border: 1px solid #ccc;
      box-sizing: border-box;
    }

    .floating-whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25D366;
      color: white;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      font-size: 30px;
      text-align: center;
      line-height: 60px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
      z-index: 1000;
    }

    .testimonial {
      margin-top: 15px;
      border-left: 5px solid #27ae60;
      padding-left: 15px;
      font-style: italic;
      color: #555;
    }

    .testimonial-name {
      margin-top: 5px;
      font-weight: bold;
      color: #333;
    }

    @media (max-width: 600px) {
      nav a {
        display: block;
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Affiliate Marketing for Beginners</h1>
    <nav>
      <a href="#pay">Pay</a>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#courses">Courses</a>
      <a href="#testimonials">Testimonials</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>

    <!-- Payment Section -->
    <section id="pay">
      <h2>Buy a Course</h2>
      <p>Enter your email and choose a course to pay with Paystack.</p>
      <input type="email" id="email" placeholder="Enter your email" required>
      <select id="course">
        <option value="" disabled selected>Select a course</option>
        <option value="12700">Video Editing Mastery – GHS 127</option>
        <option value="19000">Affiliate Marketing for Beginners – GHS 190</option>
        <option value="19000">Latest Video & Content Creation – GHS 190</option>
        <option value="16900">Ultimate Money Machine – GHS 169</option>
        <option value="13700">WhatsApp Instant Marketing – GHS 137</option>
        <option value="24300">Amazon KDP for All Devices – GHS 243</option>
        <option value="35900">Data Analytics (Excel & Power BI) – GHS 359</option>
        <option value="29600">Stellar Publishing Guide – GHS 296</option>
        <option value="24300">Passive Income Blueprint – GHS 243</option>
        <option value="6300">Contact Gain Blueprint – GHS 63</option>
        <option value="35900">Facebook Ads for Smartphone – GHS 359</option>
        <option value="59100">Forex Trading – GHS 591</option>
        <option value="24300">China Import Course – GHS 243</option>
        <option value="29600">Web Design – GHS 296</option>
        <option value="19000">Become a Computer Expert – GHS 190</option>
        <option value="25300">Facebook & Instagram Ad Sales – GHS 253</option>
        <option value="59100">Google Ads Mastery – GHS 591</option>
        <option value="25300">Sexual Weakness Remedy – GHS 253</option>
        <option value="19000">Height Loss in 30 Days – GHS 190</option>
      </select>
      <button class="btn" onclick="payWithPaystack()">💳 Pay Now</button>
    </section>

    <!-- Home Section -->
    <section id="home">
      <h2>Daily Income Program</h2>
      <p>Learn how to make 150K - 300K monthly using your smartphone, even if you're a complete beginner!</p>
      <a href="https://digitstem.com/t/ODNESE9YakZyVkVBcW01Vmk5OGdOZz09-MzE2NzU1" class="btn" target="_blank">👉 Join the Training Now</a>
    </section>

    <!-- What You Will Learn -->
    <section>
      <h2>What You Will Learn</h2>
      <ul>
        <li>Affiliate Marketing</li>
        <li>Facebook & WhatsApp Marketing</li>
        <li>Organic Traffic Method</li>
        <li>Sales Closing, Objection Handling</li>
        <li>Free Mentorship & Weekly Classes</li>
      </ul>
    </section>

    <!-- About Section -->
    <section id="about">
      <h2>About Coach Emmanuel</h2>
      <p>Hello! I'm Coach Emmanuel. I started affiliate marketing with no prior experience and was able to make $39 in just 3 sales. My mission is to help others like you start earning online from your smartphone using simple tools and step-by-step training.</p>
    </section>

    <!-- Courses Section -->
    <section id="courses">
      <h2>Course List (Prices in GHS)</h2>
      <ul>
        <li>Video Editing Mastery – GHS 127</li>
        <li>Affiliate Marketing for Beginners – GHS 190</li>
        <li>Latest Video & Content Creation – GHS 190</li>
        <li>Ultimate Money Machine – GHS 169</li>
        <li>WhatsApp Instant Marketing – GHS 137</li>
        <li>Amazon KDP for All Devices – GHS 243</li>
        <li>Data Analytics (Excel & Power BI) – GHS 359</li>
        <li>Stellar Publishing Guide – GHS 296</li>
        <li>Passive Income Blueprint – GHS 243</li>
        <li>Contact Gain Blueprint – GHS 63</li>
        <li>Facebook Ads for Smartphone – GHS 359</li>
        <li>Forex Trading – GHS 591</li>
        <li>China Import Without Agent – GHS 243</li>
        <li>Web Design – GHS 296</li>
        <li>Become a Computer Expert – GHS 190</li>
        <li>Facebook & Instagram Ad Sales – GHS 253</li>
        <li>Google Ads Mastery – GHS 591</li>
        <li>Sexual Weakness Remedy – GHS 253</li>
        <li>Height Loss in 30 Days – GHS 190</li>
      </ul>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials">
      <h2>What Students Are Saying</h2>

      <div class="testimonial">
        “I made my first online sale within 48 hours after Coach Emmanuel’s training. It felt so real and exciting!”
        <div class="testimonial-name">– Sarah A.</div>
      </div>

      <div class="testimonial">
        “The training was so beginner-friendly. I was scared to start but Coach made it simple and profitable.”
        <div class="testimonial-name">– Michael K.</div>
      </div>

      <div class="testimonial">
        “Joining Coach Emmanuel’s mentorship was the best decision. I now make GHS 300+ daily with just my phone!”
        <div class="testimonial-name">– Linda B.</div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
      <h2>Contact Me</h2>
      <p>If you have any questions or need assistance, feel free to reach out:</p>
      <ul>
        <li>Email: <a href="mailto:Kwabenaemma0554263293@gmail.com">Kwabenaemma0554263293@gmail.com</a></li>
        <li>Phone: <a href="tel:+233554263293">0554263293</a></li>
        <li>WhatsApp: <a href="https://wa.link/l10tsl" target="_blank">Chat with me on WhatsApp</a></li>
      </ul>
    </section>

  </main>

  <footer>
    <p>&copy; 2025 AffiliateStarter by Coach Emmanuel. All rights reserved.</p>
  </footer>

  <!-- Floating WhatsApp button -->
  <a href="https://wa.link/l10tsl" class="floating-whatsapp" target="_blank" title="Chat on WhatsApp">💬</a>

  <!-- Paystack Script -->
  <script src="https://js.paystack.co/v1/inline.js"></script>
  <script>
    function payWithPaystack() {
      var email = document.getElementById("email").value;
      var amount = document.getElementById("course").value;

      if (!email || !amount) {
        alert("Please enter your email and select a course.");
        return;
      }

      var handler = PaystackPop.setup({
        key: 'pk_live_ddbf47d168d6849ef29050ffc35c98a12e11e38b',
        email: email,
        amount: parseInt(amount),
        currency: 'GHS',
        ref: 'AFF' + Math.floor(Math.random() * 1000000000 + 1),
        callback: function(response) {
          alert('Payment successful! Reference: ' + response.reference);
        },
        onClose: function() {
          alert('Transaction cancelled.');
        }
      });
      handler.openIframe();
    }
  </script>

</body>
</html>
