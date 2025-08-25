<!DOCTYPE html>
<html lang="az">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>PEKAKA</title>
    <link rel="stylesheet" href="ders.css" />



</head>
<body>
  <!-- Header -->
  <header class="topbar">
    <div class="brand">
      <strong>Beginner</strong><span>HTML</span>
    </div>

    <nav class="nav">
      <a class="pill" href="#">home</a>
      <a class="pill" href="#">About</a>
      <a class="pill" href="#">example</a>
      <a class="pill" href="#">contact</a>
      <a class="pill pill--primary" href="#">Reach out</a>
    </nav>
  </header>

  <!-- Main -->
  <main class="container">
    <h1 class="html-kodum">We'd love your<br/>feedback!</h1>

    <section class="hero-grid">
      <!-- Left: Form card -->
      <article class="card Bloody">
        <form action="#" method="post" class="form">
          <label class="adsiz">
            <span>Full Name</span>
            <input type="text" placeholder="Enter your name" required>
          </label>

          <label class="adsiz">
            <span>Email Address</span>
            <input type="email" placeholder="ibrahim.email@gmail.com" required>
          </label>

          <label class="adsiz">
            <span>Share your thoughts</span>
            <textarea rows="4" placeholder="What did you learn?"></textarea>
          </label>

          <fieldset class="sallam">
            <legend>What topics interest you?</legend>

            <label class="check">
              <input type="checkbox" checked> HTML Basics
            </label>
            <label class="check">
              <input type="checkbox" checked> HTML Elements
            </label>
            <label class="check">
              <input type="checkbox" checked> HTML Forms
            </label>
            <label class="check">
              <input type="checkbox" checked> HTML Attributes
            </label>
            <label class="check">
              <input type="checkbox"> HTML Best
            </label>
            <label class="check">
              <input type="checkbox"> HTML Resources
            </label>
          </fieldset>

          <button class="btn" type="submit">Submit</button>
        </form>
      </article>

      <!-- Right: Image card -->
    <div class="card image-card">
        <img
          src="https://im.showtv.com.tr/5/6234/aras-bulut-iynemli-500x500.png?v=1588345422"
          />
    </div>
    </section>

    <!-- Footer blocks -->
    <section class="footer-grid">
      <article class="card info-card">
        <h2>HTML Learning</h2>
        <p class="muted">Your journey starts here</p>

        <ul class="link-list">
          <li><a href="#" class="dot">Home</a></li>
          <li><a href="#" class="dot">Structure</a></li>
          <li><a href="#" class="dot">Tips</a></li>
          <li><a href="#" class="dot">Concepts</a></li>
        </ul>
      </article>

      <article class="card newsletter-card">
        <h3>Join our newsletter for updates.</h3>
        <form action="#" method="post" class="newsletter">
          <input type="email" placeholder="Your email address" required>
          <button class="btn" type="submit">Subscribe</button>
        </form>
      </article>
    </section>
  </main>
</body>
</html>
