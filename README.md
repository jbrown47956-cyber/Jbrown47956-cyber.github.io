<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Venu — Know Before You Go</title>

  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet" />
  <script src="https://cdn.tailwindcss.com"></script>

  <style>
    :root {
      --bg: #0D0F14;
      --surface: #131720;
      --card: #181D2A;
      --border: #232B3E;
      --violet: #7B61FF;
      --violet2: #9B84FF;
      --cyan: #22D3EE;
      --green: #10B981;
      --amber: #F59E0B;
      --red: #EF4444;
      --text: #F8F9FA;
      --muted: #8B95A8;
      --subtle: #3D4A60;
    }

    * { box-sizing: border-box; }
    body {
      margin: 0;
      background: var(--bg);
      color: var(--text);
      font-family: 'Inter', sans-serif;
      -webkit-font-smoothing: antialiased;
      overflow-x: hidden;
    }

    .font-display { font-family: 'Plus Jakarta Sans', sans-serif; }

    .email-input {
      flex: 1;
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 14px 18px;
      color: var(--text);
      font-size: 15px;
      outline: none;
      min-width: 0;
    }

    .btn-primary {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      padding: 14px 28px;
      background: linear-gradient(135deg, var(--violet), #9B84FF);
      color: white;
      font-weight: 700;
      border-radius: 12px;
      border: none;
      cursor: pointer;
      text-decoration: none;
    }
  </style>
</head>

<body>

<nav style="padding:16px 24px;display:flex;justify-content:space-between;align-items:center;">
  <span class="font-display" style="font-size:22px;font-weight:800;">Venu</span>
  <a href="#waitlist" class="btn-primary" style="padding:10px 18px;font-size:14px;">Join Waitlist</a>
</nav>

<section style="padding:120px 24px;text-align:center;">
  <h1 class="font-display" style="font-size:64px;font-weight:800;">Know Before You Go.</h1>
  <p style="color:var(--muted);max-width:600px;margin:20px auto;">
    See real-time crowd levels at bars and restaurants in Philadelphia before you leave.
  </p>

  <a href="#waitlist" class="btn-primary">Join Waitlist</a>
</section>

<section id="waitlist" style="padding:100px 24px;text-align:center;">
  <div style="max-width:600px;margin:0 auto;background:var(--card);padding:40px;border-radius:20px;border:1px solid var(--border);">

    <h2 class="font-display" style="font-size:32px;margin-bottom:10px;">Be First In</h2>
    <p style="color:var(--muted);margin-bottom:30px;">
      Venu launches first in Philadelphia. Get early access.
    </p>

    <!-- REAL WORKING FORM -->
    <form action="https://formsubmit.co/jbrown47956@gmail.com" method="POST" style="display:flex;gap:10px;flex-wrap:wrap;justify-content:center;">

      <input 
        type="email"
        name="email"
        required
        placeholder="your@email.com"
        class="email-input"
        style="flex:1;min-width:220px;"
      />

      <button type="submit" class="btn-primary">
        Join Waitlist
      </button>

      <!-- CONFIG -->
      <input type="hidden" name="_subject" value="New Venu Waitlist Signup">
      <input type="hidden" name="_template" value="table">
      <input type="hidden" name="_captcha" value="false">
      <input type="hidden" name="_autoresponse" value="You're on the Venu waitlist. We'll notify you when early access launches in Philadelphia.">
      <input type="hidden" name="_next" value="https://jbrown47956-cyber.github.io/#waitlist">

    </form>

  </div>
</section>

</body>
</html>
