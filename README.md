
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Little Star Academic Daycare</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<link href="https://fonts.googleapis.com/css2?family=Baloo+2:wght@400;600;800&family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background: linear-gradient(180deg, #cceeff, #ffffff);
  color: #333;
}

/* HEADER */
header {
  background: linear-gradient(135deg, #ffcc00, #ff9900);
  text-align: center;
  padding: 60px 20px;
  color: #1a1a1a;
}
header h1 {
  font-family: 'Baloo 2', cursive;
  font-size: 3rem;
  margin-bottom: 10px;
}
header p {
  font-size: 1.2rem;
}

/* SECTION */
section {
  padding: 60px 20px;
  max-width: 1100px;
  margin: auto;
}
h2 {
  text-align: center;
  font-family: 'Baloo 2', cursive;
  color: #ff6600;
  font-size: 2.2rem;
}

/* CARDS */
.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 25px;
  margin-top: 40px;
}
.card {
  background: white;
  border-radius: 20px;
  padding: 30px;
  text-align: center;
  box-shadow: 0 10px 25px rgba(0,0,0,0.1);
  transition: transform 0.3s;
}
.card:hover {
  transform: translateY(-8px);
}
.card span {
  font-size: 2.5rem;
}

/* CTA */
.cta {
  background: linear-gradient(135deg, #66ccff, #3399ff);
  color: white;
  text-align: center;
  padding: 70px 20px;
}
.cta h2 {
  color: white;
}
.cta a {
  display: inline-block;
  margin-top: 20px;
  background: #ffcc00;
  color: #000;
  padding: 15px 35px;
  border-radius: 40px;
  font-weight: bold;
  text-decoration: none;
  font-size: 1.1rem;
}

/* CONTACT */
.contact {
  background: #fff5cc;
  border-radius: 25px;
  padding: 40px;
  text-align: center;
  margin-top: 40px;
}
.contact p {
  font-size: 1.1rem;
}

/* FOOTER */
footer {
  background: #333;
  color: white;
  text-align: center;
  padding: 25px;
  font-size: 14px;
}
</style>
</head>

<body>

<header>
  <h1>🌟 Little Star Academic Daycare 🌟</h1>
  <p>Where Learning Begins & Little Stars Shine Bright</p>
</header>

<section>
  <h2>About Us</h2>
  <p style="text-align:center; font-size:1.1rem;">
    At Little Star Academic Daycare, we provide a loving, safe, and stimulating
    environment where children learn through play, creativity, and structure.
    Our goal is to help every child grow with confidence and joy.
  </p>
</section>

<section>
  <h2>Our Programs</h2>
  <div class="cards">
    <div class="card"><span>👶</span><br><strong>Infant Care</strong><br>Safe, warm, and nurturing care</div>
    <div class="card"><span>🧒</span><br><strong>Toddlers</strong><br>Learning through play</div>
    <div class="card"><span>📚</span><br><strong>Preschool</strong><br>Early academic foundation</div>
    <div class="card"><span>⭐</span><br><strong>Pre-K</strong><br>School readiness & confidence</div>
  </div>
</section>

<section>
  <h2>Why Choose Little Star?</h2>
  <div class="cards">
    <div class="card">✔ Licensed & Caring Staff</div>
    <div class="card">✔ Safe & Clean Environment</div>
    <div class="card">✔ Fun Learning Activities</div>
    <div class="card">✔ Focus on Child Development</div>
  </div>
</section>

<div class="cta">
  <h2>Enroll Your Little Star Today!</h2>
  <p>Call or email us to schedule a tour</p>
  <a href="mailto:TheLittleStaracademic@gmail.com">Email Us</a>
</div>

<section>
  <div class="contact">
    <h2>Contact Information</h2>
    <p>📧 <strong>Email:</strong> TheLittleStaracademic@gmail.com</p>
    <p>📞 <strong>Phone:</strong> 971-397-3102</p>
  </div>
</section>

<footer>
  © 2025 Little Star Academic Daycare | All Rights Reserved
</footer>

</body>
</html>
