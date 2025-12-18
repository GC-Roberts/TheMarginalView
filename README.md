<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>The Marginal View — Research & Analysis</title>
  <meta name="description" content="The Marginal View explores economic questions where theory meets data. Empirical analysis, research notes, and quantitative perspectives." />
  <meta name="author" content="GC-Roberts" />
  <link rel="icon" href="data:;base64,iVBORw0KGgo="> 
  <style>
    :root{
      --bg:#0f1724; --card:#0b1220; --muted:#94a3b8; --accent:#7c3aed; --glass: rgba(255,255,255,0.04);
      --max-width:1100px; --radius:12px; --gap:18px; color-scheme: dark;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;background:linear-gradient(180deg,#071029 0%, #07101a 60%);color:#e6eef8}
    .container{max-width:var(--max-width);margin:32px auto;padding:28px;}

    header{display:flex;align-items:center;justify-content:space-between;gap:12px}
    .brand{display:flex;gap:14px;align-items:center}
    .logo{width:56px;height:56px;border-radius:10px;background:linear-gradient(135deg,var(--accent),#2dd4bf);display:flex;align-items:center;justify-content:center;font-weight:700;color:#041024}
    .site-title{font-size:1.125rem;font-weight:700}
    .site-desc{color:var(--muted);font-size:0.95rem}

    nav{display:flex;gap:12px;align-items:center}
    .btn{background:transparent;border:1px solid rgba(255,255,255,0.06);padding:8px 12px;border-radius:10px;color:inherit;text-decoration:none;font-weight:600}
    .btn.secondary{background:var(--glass)}

    .grid{display:grid;grid-template-columns:1fr 360px;gap:var(--gap);margin-top:28px}
    main{min-width:0}
    .hero{background:linear-gradient(180deg, rgba(124,58,237,0.12), rgba(13,26,48,0.1));padding:28px;border-radius:var(--radius);backdrop-filter: blur(6px);border:1px solid rgba(255,255,255,0.03)}
    .hero h1{margin:0;font-size:1.8rem}
    .hero p{margin:10px 0 0;color:var(--muted)}

    .cards{display:grid;grid-template-columns:repeat(auto-fill,minmax(260px,1fr));gap:16px;margin-top:18px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:16px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}
    .card h3{margin:0 0 6px;font-size:1rem}
    .card p{margin:0;color:var(--muted);font-size:0.95rem}
    .meta{margin-top:10px;color:var(--muted);font-size:0.85rem}

    aside .panel{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:16px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}
    .about h4{margin:0 0 8px}
    .tags{display:flex;flex-wrap:wrap;gap:8px;margin-top:12px}
    .tag{background:rgba(255,255,255,0.03);padding:6px 10px;border-radius:999px;font-size:0.85rem;color:var(--muted)}

    footer{margin-top:32px;color:var(--muted);font-size:0.9rem;text-align:center}

    /* responsive */
    @media (max-width:980px){.grid{grid-template-columns:1fr}.container{padding:18px}.logo{width:48px;height:48px}}

    /* light mode (prefers-color-scheme) */
    @media (prefers-color-scheme:light){:root{--bg:#f7fbff;--card:#ffffff;--muted:#475569;color-scheme:light}body{background:linear-gradient(180deg,#f8fafc,#f1f5f9)}.logo{color:#fff}}

    /* small utilities */
    .muted{color:var(--muted)}
    .read-more{display:inline-block;margin-top:12px;color:var(--accent);font-weight:700;text-decoration:none}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo" aria-hidden="true">MV</div>
        <div>
          <div class="site-title">The Marginal View</div>
          <div class="site-desc">Where economic theory meets data — empirical analysis, research notes, and quantitative perspective.</div>
        </div>
      </div>
      <nav>
        <a class="btn" href="#research">Research</a>
        <a class="btn" href="#notes">Notes</a>
        <a class="btn secondary" href="#about">About</a>
      </nav>
    </header>

    <div class="grid">
      <main>
        <section class="hero" aria-labelledby="hero-heading">
          <h1 id="hero-heading">Evidence-based perspectives on important economic questions</h1>
          <p>Empirical analysis, reproducible code, and concise notes that translate complex economic ideas into measurable conclusions.</p>
        </section>

        <section id="research" style="margin-top:22px">
          <h2 style="margin:0 0 12px">Recent research</h2>
          <div class="cards" role="list">
            <article class="card" role="listitem">
              <h3>Labor market dynamics after policy changes</h3>
              <p class="muted">A short note examining labor supply responses and empirical identification using event-study methods.</p>
              <div class="meta">Dec 2025 · 8 min read · <span class="muted">Empirical</span></div>
              <a class="read-more" href="#">Read →</a>
            </article>

            <article class="card" role="listitem">
              <h3>Price pass-through in concentrated markets</h3>
              <p class="muted">Quantifying how input cost shocks transmit to consumer prices across industries with differing competitive structure.</p>
              <div class="meta">Oct 2025 · 12 min read · <span class="muted">Applied</span></div>
              <a class="read-more" href="#">Read →</a>
            </article>

            <article class="card" role="listitem">
              <h3>Notes on causal inference: best practices</h3>
              <p class="muted">Practical checklist and code snippets for transparent causal analysis and robustness checks.</p>
              <div class="meta">Aug 2025 · 6 min read · <span class="muted">Notes</span></div>
              <a class="read-more" href="#notes">Read →</a>
            </article>
          </div>
        </section>

        <section id="notes" style="margin-top:28px">
          <h2 style="margin:0 0 12px">Research notes & tools</h2>
          <div class="card" style="padding:18px">
            <h3>Reproducible workflows</h3>
            <p class="muted">Short practical tips for organizing analysis, versioning data, and sharing code to make results easy to verify.</p>
            <div class="meta">Short notes · Code examples included</div>
          </div>
        </section>

        <footer>
          <p>Looking to collaborate or cite a post? Email <a href="mailto:gc-roberts@example.com">gc-roberts@example.com</a> · <span class="muted">© The Marginal View</span></p>
        </footer>
      </main>

      <aside>
        <div class="panel about">
          <h4>About</h4>
          <p class="muted">The Marginal View explores economic questions where theory meets data. Short, focused pieces designed to clarify debate with empirical evidence.</p>
          <div class="tags" style="margin-top:12px">
            <span class="tag">Macroeconomics</span>
            <span class="tag">Labor</span>
            <span class="tag">Industrial Organization</span>
            <span class="tag">Causal Inference</span>
          </div>
        </div>

        <div class="panel" style="margin-top:12px">
          <h4>Featured datasets</h4>
          <ul style="margin:8px 0 0;padding-left:18px;color:var(--muted)">
            <li>Public microdata (CPS, ACS)</li>
            <li>Administrative datasets (replicated)</li>
            <li>Open code for analyses</li>
          </ul>
        </div>

        <div class="panel" style="margin-top:12px">
          <h4>Connect</h4>
          <p class="muted">Follow on <a class="read-more" href="#">Twitter/X</a> · <a class="read-more" href="#">GitHub</a></p>
        </div>
      </aside>
    </div>
  </div>

  <script>
    // Small accessibility enhancement: focus outline for keyboard users only
    (function(){
      let usingMouse = false;
      window.addEventListener('mousedown',()=>usingMouse=true);
      window.addEventListener('keydown',()=>usingMouse=false);
      document.addEventListener('focusin', e => {
        if(!usingMouse) e.target.classList.add('focused');
      });
      document.addEventListener('focusout', e => e.target.classList.remove('focused'));
    })();
  </script>
</body>
</html>
