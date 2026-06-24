[index.html](https://github.com/user-attachments/files/29280716/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="DecodeLabs Frontend Project 1 — Static Webpage Design built with semantic HTML and clean CSS." />
  <title>DecodeLabs — Frontend Project 1</title>
  <link rel="stylesheet" href="css/style.css" />
</head>
<body>
  <!-- HEADER -->
  <header class="site-header">
    <div class="container header__inner">
      <a href="index.html" class="logo">Decode<span>Labs</span></a>
      <nav class="main-nav" aria-label="Primary">
        <ul>
          <li><a href="index.html" class="active">Home</a></li>
          <li><a href="about.html">About</a></li>
          <li><a href="services.html">Services</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main>
    <!-- HERO -->
    <section class="hero">
      <div class="container hero__inner">
        <p class="eyebrow">Industrial Training Kit · Batch 2026</p>
        <h1>Build the Visual Architecture of the Web.</h1>
        <p class="hero__lead">
          Project 1 — Static Webpage Design. Master semantic HTML, clean CSS
          and pixel-perfect layout before touching dynamic logic.
        </p>
        <div class="hero__cta">
          <a href="services.html" class="btn btn--primary">Explore the Track</a>
          <a href="about.html" class="btn btn--ghost">Learn More</a>
        </div>
      </div>
    </section>

    <!-- CONTENT GRID -->
    <section class="features">
      <div class="container">
        <h2 class="section-title">The Engineering Mindset</h2>
        <p class="section-sub">Input → Process → Output. Debug by isolating the stage.</p>

        <div class="grid">
          <article class="card">
            <h3>Semantic HTML</h3>
            <p>Use <code>&lt;header&gt;</code>, <code>&lt;main&gt;</code>, <code>&lt;article&gt;</code> and <code>&lt;footer&gt;</code> — give content explicit meaning.</p>
          </article>
          <article class="card">
            <h3>Clean CSS</h3>
            <p>External stylesheets only. Follow DRY and BEM. No inline styles, no IDs for styling.</p>
          </article>
          <article class="card">
            <h3>Layout Systems</h3>
            <p>CSS Grid for macro page structure. Flexbox for micro component alignment.</p>
          </article>
          <article class="card">
            <h3>Accessibility</h3>
            <p>Alt text on every image. Contrast ratio above 4.5:1. Labels on every input.</p>
          </article>
          <article class="card">
            <h3>Asset Discipline</h3>
            <p>Modern formats (AVIF / WebP) with explicit width &amp; height to prevent layout shift.</p>
          </article>
          <article class="card">
            <h3>Quality Gate</h3>
            <p>W3C validation, semantic audit and Lighthouse pass before code ships to production.</p>
          </article>
        </div>
      </div>
    </section>

    <!-- QUOTE -->
    <section class="quote">
      <div class="container">
        <blockquote>
          “Build it well, for the frontend is the only part of the system
          the world will ever see.”
        </blockquote>
        <cite>— The Architect’s Mandate</cite>
      </div>
    </section>
  </main>

  <!-- FOOTER -->
  <footer class="site-footer">
    <div class="container footer__inner">
      <div>
        <h4>DecodeLabs</h4>
        <p>Engineering Foundations · Frontend Track</p>
      </div>
      <div>
        <h4>Contact</h4>
        <p>📞 +91 89330 06408</p>
        <p>✉ decodelabs.tech@gmail.com</p>
      </div>
      <div>
        <h4>Location</h4>
        <p>🌎 www.decodelabs.tech</p>
        <p>📍 Greater Lucknow, India</p>
      </div>
    </div>
    <p class="copyright">© 2026 DecodeLabs. All rights reserved.</p>
  </footer>
</body>
</html>
