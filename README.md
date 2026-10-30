# ShanTel-Church.

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport"
content="width=device-width, initial-scale=1.0">
<title>GladTidings Church</title>

<style>
:root {
  --green: #245343;
  --cream: #f8f5ed;
  --gold: #c49b52;
}

* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  color: #26372e;
  background: white;
  line-height: 1.6;
}

header {
  background: white;
  padding: 18px 6%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 12px;
  border-bottom: 1px solid #eee;
}

.logo {
  font-size: 21px;
  font-weight: bold;
  color: var(--green);
}

.logo span {
  color: var(--gold);
}

nav {
  display: flex;
  gap: 15px;
  flex-wrap: wrap;
}

nav a {
  text-decoration: none;
  color: var(--green);
  font-size: 13px;
  font-weight: bold;
}

.hero {
  background: var(--cream);
  padding: 65px 7%;
  display: flex;
  align-items: center;
  gap: 35px;
  flex-wrap: wrap;
}

.hero-text {
  flex: 1 1 260px;
}

.tag {
  color: #946d30;
  font-weight: bold;
  font-size: 13px;
  letter-spacing: 1px;
}

h1 {
  font-size: clamp(34px, 7vw, 54px);
  line-height: 1.15;
  margin: 18px 0;
  color: var(--green);
}

.hero p {
  max-width: 460px;
}

.hero-photo {
  flex: 1 1 260px;
}

.hero-photo img {
  width: 100%;
  height: 310px;
  object-fit: cover;
  border-radius: 12px;
}

.btn {
  display: inline-block;
  padding: 12px 24px;
  background: var(--green);
  color: white;
  border-radius: 6px;
  text-decoration: none;
  margin-top: 15px;
}

section {
  padding: 60px 7%;
}

h2 {
  color: var(--green);
  font-size: 29px;
  margin: 0 0 15px;
}

.section-intro {
  max-width: 650px;
  margin-bottom: 30px;
}

.about {
  text-align: center;
}

.about p {
  max-width: 680px;
  margin: auto;
}

.services {
  background: var(--cream);
}

.service-table {
  width: 100%;
  border-collapse: collapse;
  background: white;
  border-radius: 10px;
  overflow: hidden;
}

.service-table th,
.service-table td {
  padding: 16px 12px;
  text-align: left;
  border-bottom: 1px solid #e8e8e8;
  font-size: 14px;
}

.service-table th {
  background: var(--green);
  color: white;
}

.cards {
  display: grid;
  grid-template-columns:
    repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}

.card {
  background: white;
  border: 1px solid #e6e6e6;
  border-radius: 10px;
  padding: 24px;
}

.card h3 {
  color: var(--green);
}

.events {
  background: var(--cream);
}

.contact {
  text-align: center;
}

footer {
  background: var(--green);
  color: white;
  text-align: center;
  padding: 30px 15px;
}

footer p {
  margin: 5px;
}

@media (max-width: 600px) {
  header {
    justify-content: center;
    text-align: center;
  }

  nav {
    justify-content: center;
  }

  .hero {
    padding-top: 45px;
  }

  .hero-photo img {
    height: 240px;
  }

  section {
    padding: 45px 6%;
  }

  .service-table th,
  .service-table td {
    padding: 10px 6px;
    font-size: 12px;
  }
}
</style>
</head>

<body>

<header>
  <div class="logo">
    Glad<span>Tidings</span> Church
  </div>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#ministries">Ministries</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>

<div class="hero" id="home">
  <div class="hero-text">
    <div class="tag">
      WELCOME TO GLADTIDINGS CHURCH
    </div>

    <h1>Faith. Family.<br>Fellowship.</h1>

    <p>
      A community where everyone is
      welcome to worship, grow in faith,
      and experience God's love together.
    </p>

    <a class="btn" href="#services">
      Plan Your Visit
    </a>
  </div>

  <div class="hero-photo">
    <img
      src="https://images.unsplash.com/photo-1438232992991-995b7058bbb3?w=900"
      alt="Church worship gathering"
    >
  </div>
</div>

<section class="about" id="about">
  <h2>Welcome to Our Church</h2>
  <p>
    GladTidings Church is a welcoming
    Christian community dedicated to
    worship, prayer, fellowship and
    spiritual growth.

    We believe in building strong
    relationships, encouraging one
    another and sharing God's love.
  </p>
</section>

<section class="services" id="services">
  <h2>Our Weekly Services</h2>
  <p class="section-intro">
    Join us throughout the week for
    worship, prayer and fellowship.
  </p>

  <table class="service-table">
    <thead>
      <tr>
        <th>Service</th>
        <th>Day</th>
        <th>Time</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Sunday Worship</td>
        <td>Sunday</td>
        <td>09:00</td>
      </tr>
      <tr>
        <td>Bible Study</td>
        <td>Wednesday</td>
        <td>17:00</td>
      </tr>
      <tr>
        <td>Prayer Meeting</td>
        <td>Friday</td>
        <td>17:00</td>
      </tr>
      <tr>
        <td>Youth Fellowship</td>
        <td>Saturday</td>
        <td>14:00</td>
      </tr>
    </tbody>
  </table>
</section>

<section id="ministries">
  <h2>Our Ministries</h2>
  <p class="section-intro">
    There's a place for everyone
    to connect and serve.
  </p>

  <div class="cards">
    <div class="card">
      <h3>Youth Ministry</h3>
      <p>
        Helping young people grow
        spiritually and build
        meaningful friendships.
      </p>
    </div>

    <div class="card">
      <h3>Women's Ministry</h3>
      <p>
        Encouraging women through
        prayer, fellowship and
        spiritual development.
      </p>
    </div>

    <div class="card">
      <h3>Men's Ministry</h3>
      <p>
        Bringing men together
        for fellowship, support
        and spiritual growth.
      </p>
    </div>

    <div class="card">
      <h3>Children's Ministry</h3>
      <p>
        Providing a welcoming
        environment where children
        can learn about faith.
      </p>
    </div>
  </div>
</section>

<section class="events" id="events">
  <h2>Church Announcements</h2>
  <p class="section-intro">
    Stay updated with our church
    programmes and activities.
  </p>

  <div class="cards">
    <div class="card">
      <h3>Sunday Fellowship</h3>
      <p>
        Join us for worship and
        fellowship every Sunday.
      </p>
    </div>

    <div class="card">
      <h3>Youth Programmes</h3>
      <p>
        Discover opportunities for
        young people to connect,
        learn and serve.
      </p>
    </div>
  </div>
</section>


<section class="contact" id="contact">
  <h2>Visit or Contact Us</h2>

  <p>
    We would love to welcome you
    to our church family.
  </p>

  <p>
    <strong>Our Address:</strong><br>
    Lusaka West, Road A15<br>
    Lusaka, Zambia
  </p>

  <p>
    <strong>Email Address:</strong><br>
    churchofficegladtidings@gmail.com
  </p>

  <p>
    <em>Sample contact details for
    website demonstration.</em>
  </p>

  <a class="btn"
     href="mailto:churchofficegladtidings@gmail.com">
    Email Our Church
  </a>
</section>

  <h2>Visit or Contact Us</h2>
  <p>
    We would love to welcome you
    to our church family.
  </p>

  <p><strong>Location:</strong>
    Lusaka, Zambia
  </p>

  <p>
    Contact details will be
    provided by the church.
  </p>

  <a class="btn" href="mailto:">
    Send Us an Email
  </a>
</>
  
<section class="location" id="location">
  <h2>Find Our Church</h2>

  <p>
    Sample Location: Lusaka West,
    Road A15, Lusaka, Zambia.
  </p>

  <div class="map-container">
    <iframe
      title="Map of Lusaka West"
      src="https://www.google.com/maps?q=Lusaka%20West%2C%20Lusaka%2C%20Zambia&output=embed"
      width="100%"
      height="300"
      style="border:0;"
      loading="lazy"
      referrerpolicy="no-referrer-when-downgrade">
    </iframe>
  </div>

  <p>
    <small>
      Map shows the general Lusaka West
      area, not an exact church location.
    </small>
  </p>
</section>

</main>

<footer>
  <h3>GladTidings Church</h3>
  <p>Faith • Family • Fellowship</p>
  <p>© 2026 GladTidings Church</p>
  <p>Website Design Prototype</p>
</footer>

</body>
</html>
 