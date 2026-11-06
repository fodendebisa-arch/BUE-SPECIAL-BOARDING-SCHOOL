<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BUE SPECIAL BOARDING SCHOOL</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  font-family: Arial, sans-serif;
  background: #f4f7fb;
  color: #222;
  line-height: 1.6;
}

header {
  background: #06366b;
  color: white;
  padding: 25px 15px;
  text-align: center;
}

header h1 {
  font-size: 27px;
}

header p {
  margin-top: 8px;
}

nav {
  background: #02264c;
  padding: 14px;
  text-align: center;
  position: sticky;
  top: 0;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 8px;
  font-weight: bold;
  display: inline-block;
}

nav a:hover {
  color: #ffc107;
}

.hero {
  background: linear-gradient(120deg, #06366b, #1686c9);
  color: white;
  text-align: center;
  padding: 85px 20px;
}

.hero h2 {
  font-size: 34px;
  margin-bottom: 15px;
}

.hero p {
  font-size: 18px;
  margin-bottom: 20px;
}

.button {
  display: inline-block;
  background: #ffc107;
  color: #172b45;
  padding: 12px 25px;
  border-radius: 6px;
  text-decoration: none;
  font-weight: bold;
}

section {
  padding: 50px 20px;
  max-width: 1050px;
  margin: auto;
}

section h2 {
  color: #06366b;
  text-align: center;
  margin-bottom: 25px;
  font-size: 27px;
}

.card-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}

.card {
  background: white;
  padding: 25px;
  border-radius: 10px;
  box-shadow: 0 3px 12px #00000012;
  text-align: center;
}

.card h3 {
  color: #07549b;
  margin-bottom: 12px;
}

.about {
  text-align: center;
}

footer {
  background: #02264c;
  color: white;
  text-align: center;
  padding: 25px;
  margin-top: 30px;
}

footer p {
  margin: 5px;
}

@media(max-width:600px) {
  header h1 {
    font-size: 22px;
  }

  .hero h2 {
    font-size: 27px;
  }

  nav a {
    font-size: 13px;
    margin: 5px;
  }
}
</style>
</head>

<body>

<header>
  <h1>BUE SPECIAL BOARDING SCHOOL</h1>
  <p>Education • Discipline • Excellence</p>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#about">About Us</a>
  <a href="#academics">Academics</a>
  <a href="#news">News</a>
  <a href="#achievements">Achievements</a>
  <a href="#contact">Contact</a>
</nav>

<div class="hero" id="home">
  <h2>Welcome to BUE SPECIAL BOARDING SCHOOL</h2>
  <p>Building Knowledge, Character and Future Leaders.</p>
  <a href="#about" class="button">Discover Our School</a>
</div>

<section id="about" class="about">
  <h2>About Our School</h2>
  <p>
    Welcome to BUE SPECIAL BOARDING SCHOOL.
    Our goal is to support quality education,
    student development, discipline and excellence.
    We believe education creates a brighter future.
  </p>
</section>

<section id="academics">
  <h2>Our Academics</h2>
  <div class="card-container">
    <div class="card">
      <h3>Quality Education</h3>
      <p>Supporting students to develop knowledge and skills.</p>
    </div>

    <div class="card">
      <h3>Student Development</h3>
      <p>Encouraging creativity, responsibility and leadership.</p>
    </div>

    <div class="card">
      <h3>Discipline</h3>
      <p>Promoting respect, teamwork and good character.</p>
    </div>
  </div>
</section>

<section id="news">
  <h2>News & Announcements</h2>
  <div class="card">
    <h3>School Announcements</h3>
    <p>New school announcements and updates will appear here.</p>
  </div>
</section>

<section id="achievements">
  <h2>Our Achievements</h2>
  <div class="card">
    <h3>Student Success</h3>
    <p>Celebrating learning, hard work and student achievements.</p>
  </div>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <div class="card">
    <h3>BUE SPECIAL BOARDING SCHOOL</h3>
    <p>Welcome to our school website.</p>
    <p>Official contact information will be added here.</p>
  </div>
</section>

<footer>
  <p>© 2026 BUE SPECIAL BOARDING SCHOOL</p>
  <p>All Rights Reserved.</p>
</footer>

</body>
</html>
