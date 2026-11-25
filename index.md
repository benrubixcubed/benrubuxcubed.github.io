<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Benjamin Ruby — Independent Researcher &amp; Commercial Operations</title>
  <meta
    name="description"
    content="Benjamin Ruby is an independent researcher in computational cognitive science, philosophy of mind, and analytic epistemology, and a commercial operations manager in Columbus, Ohio."
  />
  <style>
    :root {
      --bg: #f7f8fa;
      --surface: #ffffff;
      --text: #18202a;
      --muted: #526071;
      --border: #dfe5ec;
      --accent: #1f4e78;
      --accent-soft: #eef4fa;
      --radius: 12px;
      --max-w: 880px;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    a {
      color: var(--accent);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .container {
      max-width: var(--max-w);
      margin: 0 auto;
      padding: 28px 20px 64px;
    }

    header.hero {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: var(--radius);
      padding: 28px;
      margin-bottom: 24px;
    }

    .eyebrow {
      font-size: 0.85rem;
      font-weight: 600;
      color: var(--accent);
      text-transform: uppercase;
      letter-spacing: 0.04em;
      margin-bottom: 8px;
    }

    h1 {
      margin: 0 0 8px;
      font-size: clamp(1.8rem, 4vw, 2.4rem);
      line-height: 1.2;
    }

    .subtitle {
      margin: 0 0 14px;
      color: var(--muted);
      font-size: 1rem;
    }

    .bio {
      margin: 0 0 18px;
      font-size: 0.98rem;
    }

    nav.quick-links {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    nav.quick-links a {
      background: var(--accent-soft);
      color: var(--accent);
      padding: 6px 12px;
      border-radius: 999px;
      font-size: 0.88rem;
      font-weight: 600;
    }

    nav.quick-links a:hover {
      text-decoration: none;
      filter: brightness(0.97);
    }

    section.card-section {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: var(--radius);
      padding: 24px 28px;
      margin-bottom: 24px;
    }

    h2 {
      margin: 0 0 14px;
      font-size: 1.3rem;
      line-height: 1.3;
    }

    p {
      margin: 0 0 12px;
    }

    p:last-child {
      margin-bottom: 0;
    }

    .focus-grid,
    .ventures-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 14px;
      margin-top: 12px;
    }

    .mini-box {
      border: 1px solid var(--border);
      border-radius: 10px;
      padding: 16px;
      background: #fcfcfd;
    }

    .mini-box h3 {
      margin: 0 0 6px;
      font-size: 1rem;
    }

    .mini-box p {
      margin: 0;
      font-size: 0.92rem;
      color: var(--muted);
    }

    .works-header {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: space-between;
      gap: 12px;
      margin-bottom: 14px;
    }

    .works-header h2 {
      margin: 0;
    }

    .filters {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
    }

    .filter-btn {
      border: 1px solid var(--border);
      background: var(--surface);
      color: var(--text);
      padding: 6px 12px;
      border-radius: 999px;
      font-size: 0.86rem;
      font-weight: 600;
      cursor: pointer;
    }

    .filter-btn.active {
      background: var(--accent);
      border-color: var(--accent);
      color: #ffffff;
    }

    .works-list {
      display: flex;
      flex-direction: column;
      gap: 12px;
    }

    .work-item {
      border: 1px solid var(--border);
      border-radius: 10px;
      padding: 14px 16px;
      background: #fcfcfd;
    }

    .work-item.hidden {
      display: none;
    }

    .work-meta {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      gap: 8px;
      margin-bottom: 6px;
      font-size: 0.82rem;
      color: var(--muted);
    }

    .badge {
      display: inline-block;
      padding: 2px 8px;
      border-radius: 999px;
      font-weight: 600;
      font-size: 0.76rem;
      background: var(--accent-soft);
      color: var(--accent);
    }

    .work-title {
      margin: 0 0 6px;
      font-size: 1rem;
      font-weight: 700;
      line-height: 1.35;
    }

    .work-link {
      font-size: 0.9rem;
      font-weight: 600;
    }

    .profile-links {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 8px;
    }

    .profile-pill {
      display: inline-block;
      border: 1px solid var(--border);
      border-radius: 8px;
      padding: 8px 14px;
      font-size: 0.9rem;
      font-weight: 600;
      background: #fcfcfd;
    }

    footer {
      text-align: center;
      color: var(--muted);
      font-size: 0.85rem;
      margin-top: 28px;
    }

    @media (max-width: 600px) {
      header.hero,
      section.card-section {
        padding: 20px;
      }
    }
  </style>

  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Benjamin Ruby",
    "url": "https://benjaminruby.com",
    "address": {
      "@type": "PostalAddress",
      "addressLocality": "Columbus",
      "addressRegion": "OH",
      "addressCountry": "US"
    },
    "jobTitle": "Independent Researcher & Entrepreneur",
    "description": "Benjamin Ruby is an independent computational cognitive science researcher and business owner based in Columbus, Ohio.",
    "knowsAbout": [
      "Computational Neuroscience",
      "Active Inference",
      "Predictive Processing",
      "Thermodynamic State-Space Model",
      "Analytic Epistemology"
    ],
    "hasOccupation": [
      {
        "@type": "Occupation",
        "name": "Computational Cognitive Science Researcher"
      },
      {
        "@type": "Occupation",
        "name": "Commercial Operations Manager"
      }
    ],
    "sameAs": [
      "https://benjaminruby.com",
      "https://github.com/benrubixcubed/benrubuxcubed.github.io",
      "https://philpeople.org/profiles/ben-ruby",
      "https://zenodo.org/me/uploads?q=&f=shared_with_me%3Afalse&l=list&p=1&s=10&sort=newest",
      "https://www.linkedin.com/in/benjamin-ruby-4344b090?utm_source=share_via&utm_content=profile&utm_medium=member_android",
      "https://www.facebook.com/share/19iNzXD33q/"
    ]
  }
  </script>
</head>
<body>
  <div class="container">
    <header class="hero">
      <div class="eyebrow">Columbus, Ohio</div>
      <h1>Benjamin Ruby</h1>
      <p class="subtitle">
        Independent Researcher (Computational Cognitive Science, Philosophy of Mind, &amp; Analytic Epistemology) &middot; Commercial Operations Manager
      </p>
      <p class="bio">
        Combining localized commercial management with theoretical computational neuroscience and epistemology to build cross-disciplinary frameworks spanning cognitive architectures, doxastic states, and practical operations.
      </p>
      <nav class="quick-links" aria-label="Page sections">
        <a href="#research">Research</a>
        <a href="#works">Public Works (11)</a>
        <a href="#ventures">Business Ventures</a>
        <a href="#profiles">Profiles</a>
      </nav>
    </header>

    <section id="research" class="card-section">
      <h2>Research &amp; Theoretical Focus</h2>
      <p>
        My independent research investigates belief configurations, predictive processing, and neuro-computational modeling across philosophy and cognitive science.
      </p>
      <div class="focus-grid">
        <div class="mini-box">
          <h3>Active Inference &amp; FEP</h3>
          <p>Using computational frameworks to examine how biological neural systems minimize uncertainty and regulate commitment.</p>
        </div>
        <div class="mini-box">
          <h3>Prefrontal Metabolic States &amp; TSSM</h3>
          <p>Modeling energetic reserves, phase transitions, and metabolic trade-offs in doxastic configurations, decision fatigue, and online discourse.</p>
        </div>
      </div>
    </section>

    <section id="works" class="card-section">
      <div class="works-header">
        <h2>Public Works &amp; Zenodo Archive</h2>
        <div class="filters" role="group" aria-label="Filter works by type">
          <button type="button" class="filter-btn active" data-filter="all">All (11)</button>
          <button type="button" class="filter-btn" data-filter="preprint">Preprints (9)</button>
          <button type="button" class="filter-btn" data-filter="software">Software (2)</button>
        </div>
      </div>

      <div class="works-list">
        <article class="work-item" data-type="preprint">
          <div class="work-meta">
            <span class="badge">Preprint</span>
            <span>Nov 25, 2026</span>
            <span>v1.0.0</span>
          </div>
          <h3 class="work-title">Metabolic Phase Collapse in High-Stakes Sequential Judgment: Reconciling Decision Fatigue, Bottleneck Diagnostics, and Circuit Breakers via the Thermodynamic State-Space Model (TSSM)</h3>
          <a class="work-link" href="#">View on Zenodo &rarr;</a>
        </article>

        <article class="work-item" data-type="preprint">
          <div class="work-meta">
            <span class="badge">Preprint</span>
            <span>Nov 25, 2026</span>
            <span>v1.0.0</span>
          </div>
          <h3 class="work-title">The Agnostic's Burden... What It Actually Takes to Refuse a Side on Facebook...: A Philosophical, Socio-Epistemic, and Neuroepistemological Taxonomy of Agnosticism, Implicit Atheism, and Explicit Atheism</h3>
          <a class="work-link" href="#">View on Zenodo &rarr;</a>
        </article>

        <article class="work-item" data-type="preprint">
          <div class="work-meta">
            <span class="badge">Preprint</span>
            <span>Nov 22, 2026</span>
            <span>v12</span>
          </div>
          <h3 class="work-title">A Hierarchical Thermodynamic Taxonomy of Doxastic States: An Active Inference Model, Neuro-Computational Opportunity Cost Architecture, and EEG-fMRI Fusion Paradigm</h3>
          <a class="work-link" href="#">View on Zenodo &rarr;</a>
        </article>

        <article class="work-item" data-type="software">
          <div class="work-meta">
            <span class="badge">Software</span>
            <span>Nov 22, 2026</span>
            <span>v1.1.6</span>
          </div>
          <h3 class="work-title">TSSM-FCABP: Forced-Choice Asymmetric Betting Paradigm and Thermodynamic State-Space Model</h3>
          <a class="work-link" href="#">View on Zenodo &rarr;</a>
        </article>

        <article class="work-item" data-type="preprint">
          <div class="work-meta">
            <span class="badge">Preprint</span>
            <span>Nov 22, 2026</span>
            <span>v3</span>
          </div>
          <h3 class="work-title">The Cost of Equanimity: Why Consciousness Cannot Outrun the Physics of the Brain</h3>
          <a class="work-link" href="#">View on Zenodo &rarr;</a>
        </article>

        <article class="work-item" data-type="preprint">
          <div class="work-meta">
            <span class="badge">Preprint</span>
            <span>Nov 21, 2026</span>
            <span>v1.0.0</span>
          </div>
          <h3 class="work-title">Thermodynamic Unification of Propositional Belief Evaluation: Subsuming Content-Independence...</h3>
          <a class="work-link" href="#">View on Zenodo &rarr;</a>
        </article>

        <article class="work-item" data-type="software">
          <div class="work-meta">
            <span class="badge">Software</span>
            <span>Nov 21, 2026</span>
            <span>0.2.0</span>
          </div>
          <h3 class="work-title">TSSM Core (v0.2.0): Digital Polarization and Dynamic Reserve Bifurcation Solver</h3>
          <a class="work-link" href="#">View on Zenodo &rarr;</a>
        </article>

        <article class="work-item" data-type="preprint">
          <div class="work-meta">
            <span class="badge">Preprint</span>
            <span>Nov 21, 2026</span>
            <span>1.0</span>
          </div>
          <h3 class="work-title">Metabolic Bottlenecks in the Digital Public Square: A Thermodynamic Model of Online...</h3>
          <a class="work-link" href="#">View on Zenodo &rarr;</a>
        </article>

        <article class="work-item" data-type="preprint">
          <div class="work-meta">
            <span class="badge">Preprint</span>
            <span>Nov 18, 2026</span>
            <span>1.0.0</span>
          </div>
          <h3 class="work-title">Thermodynamic Boundaries of Metaphysics: Resolving Epicurean Theology and Simulation...</h3>
          <a class="work-link" href="#">View on Zenodo &rarr;</a>
        </article>

        <article class="work-item" data-type="preprint">
          <div class="work-meta">
            <span class="badge">Preprint</span>
            <span>Nov 14, 2026</span>
            <span>1.0</span>
          </div>
          <h3 class="work-title">All Toads Are Frogs: The Metabolic Architecture of Belief and the Erasure of...</h3>
          <a class="work-link" href="#">View on Zenodo &rarr;</a>
        </article>

        <article class="work-item" data-type="preprint">
          <div class="work-meta">
            <span class="badge">Preprint</span>
            <span>Oct 28, 2026</span>
            <span>1</span>
          </div>
          <h3 class="work-title">The Doxastic Divide: Why the "Agnostic Atheist" Is a Modern Epistemological Myth</h3>
          <a class="work-link" href="#">View on Zenodo &rarr;</a>
        </article>
      </div>
    </section>

    <section id="ventures" class="card-section">
      <h2>Business Ventures &amp; Local Operations</h2>
      <p>
        Alongside academic modeling and writing, I own and operate local commercial enterprises in Columbus, Ohio.
      </p>
      <div class="ventures-grid">
        <div class="mini-box">
          <h3>Ruby Home and Hauling Services, Inc.</h3>
          <p>Founded in 2012, providing localized home management, logistical organization, and hauling solutions.</p>
        </div>
        <div class="mini-box">
          <h3>Ben and Bri's Black RAVE Boutique LLC</h3>
          <p>Specialized local boutique and apparel retail establishment in Columbus, Ohio.</p>
        </div>
      </div>
    </section>

    <section id="profiles" class="card-section">
      <h2>Verified Professional Profiles</h2>
      <div class="profile-links">
        <a class="profile-pill" href="https://benjaminruby.com">Personal Website</a>
        <a class="profile-pill" href="https://philpeople.org/profiles/ben-ruby">PhilPeople</a>
        <a class="profile-pill" href="https://zenodo.org/me/uploads">Zenodo Uploads</a>
        <a class="profile-pill" href="https://www.linkedin.com/in/benjamin-ruby-4344b090">LinkedIn</a>
        <a class="profile-pill" href="https://www.facebook.com/share/19iNzXD33q/">Facebook</a>
      </div>
    </section>

    <footer>
      Benjamin Ruby &middot; Columbus, Ohio
    </footer>
  </div>

  <script>
    const buttons = document.querySelectorAll(".filter-btn");
    const items = document.querySelectorAll(".work-item");

    buttons.forEach((btn) => {
      btn.addEventListener("click", () => {
        const filter = btn.dataset.filter;
        buttons.forEach((b) => b.classList.remove("active"));
        btn.classList.add("active");

        items.forEach((item) => {
          const matches = filter === "all" || item.dataset.type === filter;
          item.classList.toggle("hidden", !matches);
        });
      });
    });
  </script>
</body>
</html>
