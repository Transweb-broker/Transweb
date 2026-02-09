<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>TRANSWEB d.o.o. | Independent Shipbroker</title>
<style>
body {
  margin: 0;
  font-family: -apple-system, BlinkMacSystemFont, "SF Pro Display", "Helvetica Neue", Arial, sans-serif;
  background-color: #fafafa;
  color: #0f0f0f;
  -webkit-font-smoothing: antialiased;
}
header {
  padding: 80px 20px 40px;
  text-align: center;
}
header h1 {
  margin: 0;
  font-size: 24px;
  font-weight: 600;
  letter-spacing: 0.5px;
}
header p {
  margin: 14px 0 0;
  font-size: 14px;
  color: #8a8a8a;
  letter-spacing: 2.5px;
  text-transform: uppercase;
  font-weight: 500;
}
section {
  padding: 140px 20px;
  max-width: 900px;
  margin: auto;
}
.hero {
  text-align: center;
  min-height: 85vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.hero h2 {
  line-height: 1.15;
  font-size: 56px;
  font-weight: 700;
  margin: 0 auto 45px;
  letter-spacing: -0.5px;
  text-align: center;
}
.hero p {
  color: #555;
  font-size: 22px;
  line-height: 1.8;
  max-width: 720px;
  margin: 0 auto 40px;
  font-weight: 400;
}

.hero p:last-of-type {
  font-weight: 600;
  color: #111;
}

.cta-button {
  display: inline-block;
  padding: 18px 40px;
  background: #0f0f0f;
  color: #fff;
  text-decoration: none;
  font-size: 16px;
  font-weight: 700;
  border-radius: 12px;
  transition: all 0.3s ease;
  box-shadow: 0 12px 40px rgba(0,0,0,0.06);
}

.cta-button:hover {
  opacity: 0.85;
  transform: translateY(-2px);
}

.cta-subtext {
  margin-top: 18px;
  font-size: 14px;
  color: #777;
  letter-spacing: 1px;
  font-weight: 500;
}
.services {
  display: flex;
  flex-wrap: wrap;
  gap: 80px;
  justify-content: center;
  text-align: center;
}
.service-box {
  flex: 1 1 220px;
  max-width: 240px;
}
.service-box h3 {
  font-size: 18px;
  font-weight: 600;
  margin-bottom: 16px;
}
.service-box p {
  font-size: 15px;
  color: #777;
  line-height: 1.8;
}
.contact {
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.contact h2 {
  font-weight: 500;
  margin-bottom: 30px;
  text-align: center;
}
.contact p {
  margin: 6px 0;
  font-size: 14px;
  color: #555;
}
form input, form textarea {
  border: none;
  border-bottom: 1px solid #e0e0e0;
  border-radius: 0;
  background: transparent;
  padding: 18px 8px;
  font-size: 15px;
  transition: border-color 0.3s ease;
}

form input:focus, form textarea:focus {
  outline: none;
  border-bottom: 1px solid #0f0f0f;
}
form button {
  background: #0f0f0f;
  color: #ffffff;
  border: none;
  padding: 18px;
  font-size: 15px;
  font-weight: 600;
  border-radius: 12px;
  margin-top: 30px;
  transition: all 0.3s ease;
  box-shadow: 0 10px 30px rgba(0,0,0,0.05);
}
form button:hover {
  opacity: 0.85;
}
footer {
  text-align: center;
  padding: 120px 15px 80px;
  font-size: 13px;
  color: #aaa;
  border-top: 1px solid #ececec;
}

/* Fade-in animation */
.fade-in {
  opacity: 0;
  transform: translateY(30px);
  transition: opacity 0.9s ease, transform 0.9s ease;
}

.fade-in.visible {
  opacity: 1;
  transform: translateY(0);
}
@media (max-width: 768px) {
  .services {
    flex-direction: column;
    align-items: center;
  }
  .hero h2 {
    font-size: 32px;
  }
}
</style>
</head>
<body>

<header>
  <div style="text-align:center;">
    <img src="logo.png" alt="TRANSWEB Logo" style="max-width:180px; margin-bottom:15px;">
    <h1>TRANSWEB d.o.o. | Konstantin – Independent Shipbroker</h1>
    <p>Connecting Cargo & Tonnage Worldwide</p>
  </div>
</header>

<section class="hero fade-in">
  <h2>
    Serious Cargo.<br>
    Reliable Tonnage.<br>
    Decisive Execution.
  </h2>
  <p>
    We secure competitive freight with speed and precision. Direct access to vetted shipowners,
    disciplined negotiation, and strict post-fixture control ensure your cargo moves on schedule
    and on firmly agreed terms. No noise. No delays. Just performance.
  </p>
  <a href="#" class="cta-button" onclick="document.querySelector('form').scrollIntoView({behavior: 'smooth'}); return false;">
    Discuss Your Shipment
  </a>
  <div class="cta-subtext">
    Fast response. Clear terms.
  </div>
</section>

<section class="fade-in" style="padding:60px 20px; border-top:1px solid #ececec; border-bottom:1px solid #ececec;">
  <div style="text-align:center; font-size:14px; letter-spacing:2px; text-transform:uppercase; color:#8a8a8a; font-weight:500;">
    Dry Bulk &nbsp; | &nbsp; Coal &nbsp; | &nbsp; Grain &nbsp; | &nbsp; Steel &nbsp; | &nbsp; Black Sea &nbsp; | &nbsp; Med &nbsp; | &nbsp; Far East
  </div>
</section>

<section class="fade-in">
  <div class="services">
    <div class="service-box">
      <h3>Vessel Chartering</h3>
      <p>Handy, Supramax and Panamax chartering for coal, grain, steel and bulk commodities.</p>
    </div>
    <div class="service-box">
      <h3>Post-Fixture Support</h3>
      <p>Operational follow-up, laycan monitoring, documentation coordination and voyage execution support.</p>
    </div>
    <div class="service-box">
      <h3>Market Advisory</h3>
      <p>Freight market insights, rate evaluation and strategic positioning for cargo owners and operators.</p>
    </div>
  </div>
</section>

<section class="contact fade-in">
  <h2>Contact</h2>
  <p>Email: K.INFOLOGIC@MAIL.COM</p>
  <p>Telegram: +381 61 1049972 (UTC +3)</p>
  <p>Telegram / WhatsApp / Mobile: +7 960 4848248 (UTC +3)</p>
  <p>TRANSWEB d.o.o.</p>
  <p>Zheleznicka 20, 21101 Novi Sad, Srbija</p>
</section>

<section class="fade-in">
  <h2 style="text-align:center; margin-bottom:40px; font-weight:600;">Discuss Your Shipment</h2>
  <p style="text-align:center; color:#777; max-width:520px; margin:0 auto 60px; font-size:16px;">
    Provide brief shipment details below. Further specifications can be aligned directly and efficiently.
  </p>
  <form action="mailto:K.INFOLOGIC@MAIL.COM" method="post" enctype="text/plain" style="max-width:520px; margin:0 auto; display:flex; flex-direction:column; gap:25px;">
    <input type="text" name="Company" placeholder="Company" required>
    <input type="email" name="Email" placeholder="Business Email" required>
    <input type="text" name="Cargo" placeholder="Cargo & Approx. Quantity" required>
    <input type="text" name="Route" placeholder="Loading – Discharge" required>
    <textarea name="Details" placeholder="Laycan / Vessel Preference (optional)" rows="3"></textarea>
    <button type="submit">
      Send Details
    </button>
  </form>
</section>

<footer>
  <div style="margin-bottom:20px; font-size:12px; letter-spacing:1.5px; text-transform:uppercase; color:#888;">
    Independent Marine Brokerage | Dry Bulk Focus | Black Sea & Mediterranean
  </div>
  © 2026 TRANSWEB d.o.o. | Novi Sad, Serbia. All rights reserved.
</footer>

<script>
const observer = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      entry.target.classList.add('visible');
    }
  });
}, { threshold: 0.15 });

document.querySelectorAll('.fade-in').forEach(el => {
  observer.observe(el);
});
</script>

</body>
</html>
