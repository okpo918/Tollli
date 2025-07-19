<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>SkillNest - Freelance Marketplace</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; background: #f9f9f9; }
    header, footer { background: #1e1e2f; color: white; padding: 20px; text-align: center; }
    nav a { color: white; margin: 0 15px; text-decoration: none; }
    .container { max-width: 1000px; margin: auto; padding: 20px; }
    .gig { background: white; padding: 20px; margin-bottom: 20px; border-radius: 8px; box-shadow: 0 0 10px #ccc; }
    .button { background: #28a745; color: white; padding: 10px 20px; text-decoration: none; border-radius: 4px; }
    .escrow-box { background: #fff3cd; padding: 15px; border: 1px solid #ffeeba; margin-top: 10px; }
  </style>
</head>
<body>

  <header>
    <h1>SkillNest</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Gigs</a>
      <a href="#">Post a Job</a>
      <a href="#">Login</a>
    </nav>
  </header>

  <div class="container">
    <h2>Featured Gigs</h2>

    <div class="gig">
      <h3>I will design a modern website</h3>
      <p>By <strong>JaneDesigns</strong> | ⭐ 4.9 (233)</p>
      <p>Price: <strong>$100</strong></p>
      <a href="#escrow" class="button">Order with Escrow</a>
    </div>

    <div class="gig">
      <h3>I will write SEO blog posts</h3>
      <p>By <strong>WriterPro</strong> | ⭐ 5.0 (98)</p>
      <p>Price: <strong>$60</strong></p>
      <a href="#escrow" class="button">Order with Escrow</a>
    </div>

    <!-- Simulated Escrow Section -->
    <div id="escrow" class="escrow-box">
      <h4>Escrow Process (Simulated)</h4>
      <ol>
        <li>Client pays $100 — funds held in escrow.</li>
        <li>Freelancer delivers the work.</li>
        <li>Client approves — funds released to freelancer.</li>
        <li><em>Dispute? Admin can intervene.</em></li>
      </ol>
      <p><strong>⚠️ Escrow requires backend + payment processor like Stripe.</strong></p>
    </div>
  </div>

  <footer>
    <p>&copy; 2025 SkillNest. All rights reserved.</p>
    <p><a href="#" style="color: #ccc;">Privacy Policy</a> | <a href="#" style="color: #ccc;">Terms</a></p>
  </footer>

</body>
</html>
