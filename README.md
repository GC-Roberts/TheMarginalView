# TheMarginalView
The Marginal View explores economic questions where theory meets data. It features empirical analysis, research notes, and quantitative perspectives designed to clarify complex economic issues and ground debate in measurable reality.
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The Marginal View | Applied Economics</title>
  <style>
    :root {
      --bg: #0f172a;
      --card: #111827;
      --text: #e5e7eb;
      --muted: #9ca3af;
      --accent: #38bdf8;
      --border: #1f2933;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      background: linear-gradient(180deg, #020617 0%, #0f172a 100%);
      color: var(--text);
      line-height: 1.7;
    }

    a {
      color: var(--accent);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .container {
      max-width: 1100px;
      margin: 0 auto;
      padding: 80px 24px;
    }

    header {
      padding: 100px 24px 60px;
      border-bottom: 1px solid var(--border);
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
      letter-spacing: -0.02em;
    }

    header p {
      max-width: 700px;
      font-size: 1.1rem;
      color: var(--muted);
    }

    nav {
      margin-top: 30px;
    }

    nav a {
      margin-right: 20px;
      font-weight: 600;
      color: var(--text);
    }

    section {
      margin-bottom: 80px;
    }

    h2 {
      font-size: 2rem;
      margin-bottom: 30px;
      letter-spacing: -0.01em;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 24px;
    }

    .card {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 14px;
      padding: 28px;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    .card:hover {
      transform: translateY(-4px);
      box-shadow: 0 10px 30px rgba(0,0,0,0.3);
    }

    .card h3 {
      margin-top: 0;
      margin-bottom: 10px;
    }

    .meta {
      font-size: 0.85rem;
      color: var(--muted);
      margin-bottom: 12px;
    }

    footer {
      border-top: 1px solid var(--border);
      padding: 40px 24px 80px;
      font-size: 0.9rem;
      color: var(--muted);
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2.3rem;
      }
    }
  </style>
</head>
<body>

<header>
  <div class="container">
    <h1>The Marginal View</h1>
    <p>
      Applied economics and evidence based analysis exploring markets, policy, and economic behaviour where theory meets data.
    </p>
    <nav>
      <a href="#research">Research</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </div>
</header>

<main class="container">

<section id="research">
  <h2>Research</h2>
  <div class="grid">

    <div class="card">
      <h3>Working Paper 01</h3>
      <div class="meta">Empirical Analysis • South Africa</div>
      <p>
        Applied econometric research examining a focused economic question using publicly available data. Emphasis on identification, robustness, and policy relevance.
      </p>
      <p>
        <a href="#">Download PDF</a> · <a href="#">Summary</a>
      </p>
    </div>

    <div class="card">
      <h3>Research Note 01</h3>
      <div class="meta">Short Form Analysis</div>
      <p>
        Concise research note addressing a narrowly defined economic mechanism. Designed for clarity, speed, and accessibility.
      </p>
      <p>
        <a href="#">Download PDF</a>
      </p>
    </div>

  </div>
</section>

<section id="about">
  <h2>About</h2>
  <p>
    The Marginal View is authored by Giovanni Roberts, an economics graduate with a background in econometrics and applied mathematical economics. The platform hosts independent research, working papers, and data driven economic commentary.
  </p>
  <p>
    The focus is on empirical methods, transparent assumptions, and real world relevance, with particular attention to South African and emerging market contexts.
  </p>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>
    Email: <a href="mailto:giovannicroberts2@gmail.com">giovannicroberts2@gmail.com</a><br />
    LinkedIn: <a href="#">Add your LinkedIn profile</a>
  </p>
</section>

</main>

<footer>
  <div class="container">
    <p>
      All views expressed are my own. This work represents independent research and has not undergone formal peer review.
    </p>
  </div>
</footer>

</body>
</html>
