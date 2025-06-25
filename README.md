<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Course Payment</title>
  <script src="https://js.paystack.co/v1/inline.js"></script>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      padding: 40px;
      text-align: center;
    }
    h2 {
      color: #222;
    }
    input, select, button {
      padding: 10px;
      margin: 10px;
      width: 250px;
      font-size: 16px;
    }
    button {
      background-color: #ff6600;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background-color: #e55a00;
    }
  </style>
</head>
<body>

  <h2>Buy a Course with Paystack</h2>

  <input type="email" id="email" placeholder="Enter your email" required><br>

  <select id="amount" required>
    <option value="">Select a course</option>
    <option value="5">Starter Course – $5</option>
    <option value="10">Intermediate Course – $10</option>
    <option value="20">Ultimate Money Machine – $20</option>
  </select><br>

  <button onclick="payWithPaystack()">Pay Now</button>

  <script>
    function payWithPaystack() {
      var email = document.getElementById("email").value;
      var amountUSD = document.getElementById("amount").value;

      if (!email || !amountUSD) {
        alert("Please enter your email and select a course.");
        return;
      }

      // Convert USD to GHS
      var exchangeRate = 11;
      var amountGHS = parseFloat(amountUSD) * exchangeRate;
      var amountPesewas = parseInt(amountGHS * 100); // Paystack uses pesewas

      var handler = PaystackPop.setup({
        key: 'pk_live_ddbf47d168d6849ef29050ffc35c98a12e11e38b', // Replace with your own key
        email: email,
        amount: amountPesewas,
        currency: 'GHS',
        ref: 'AFF' + Math.floor(Math.random() * 1000000000 + 1),
        callback: function(response) {
          alert('✅ Payment successful!\nReference: ' + response.reference);
        },
        onClose: function() {
          alert('❌ Transaction cancelled.');
        }
      });
      handler.openIframe();
    }
  </script>

</body>
</html>
