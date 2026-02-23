# DaveArchkt.github.io
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>David Reyes — Architecture Portfolio</title>
  <meta name="description" content="Architecture portfolio of David Reyes — design, visualization, and master planning." />
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header class="header">
    <nav class="nav">
      <a class="brand" href="#top">DR</a>
      <div class="links">
        <a href="#work">Work</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>

    <div class="hero" id="top">
      <p class="kicker">Architecture · Visualization · Master Planning</p>
      <h1>David Reyes</h1>
      <p class="sub">
        I help clients communicate design clearly through high-quality 2D/3D visualizations and concept packages.
      </p>
      <div class="cta">
        <a class="btn" href="#work">View selected work</a>
        <a class="btn ghost" href="#contact">Request a quote</a>
      </div>
    </div>
  </header>

  <main class="main">
    <section class="section" id="work">
      <div class="section-head">
        <h2>Selected Work</h2>
        <p>Swap the images and titles with your projects. Each card can link to a PDF or a case study page.</p>
      </div>

      <div class="grid">
        <article class="card">
          <a class="thumb" href="#" aria-label="Project 1">
            <img src="assets/project-01.jpg" alt="Project 1 preview" loading="lazy" />
          </a>
          <div class="card-body">
            <h3>Project Title 01</h3>
            <p class="meta">Location · Year · Type</p>
            <p class="desc">1–2 lines describing the intent, constraints, and your role.</p>
            <div class="tags">
              <span>Master plan</span><span>3D</span><span>Site analysis</span>
            </div>
          </div>
        </article>

        <article class="card">
          <a class="thumb" href="#" aria-label="Project 2">
            <img src="assets/project-02.jpg" alt="Project 2 preview" loading="lazy" />
          </a>
          <div class="card-body">
            <h3>Project Title 02</h3>
            <p class="meta">Location · Year · Type</p>
            <p class="desc">Short, objective description of the deliverables and outcome.</p>
            <div class="tags">
              <span>Concept</span><span>Render</span><span>Diagram</span>
            </div>
          </div>
        </article>

        <article class="card">
          <a class="thumb" href="#" aria-label="Project 3">
            <img src="assets/project-03.jpg" alt="Project 3 preview" loading="lazy" />
          </a>
          <div class="card-body">
            <h3>Project Title 03</h3>
            <p class="meta">Location · Year · Type</p>
            <p class="desc">Keep it brief — the image should do the heavy lifting.</p>
            <div class="tags">
              <span>Residential</span><span>Plans</span><span>Visualization</span>
            </div>
          </div>
        </article>

        <article class="card">
          <a class="thumb" href="#" aria-label="Project 4">
            <img src="assets/project-04.jpg" alt="Project 4 preview" loading="lazy" />
          </a>
          <div class="card-body">
            <h3>Project Title 04</h3>
            <p class="meta">Location · Year · Type</p>
            <p class="desc">Add links to PDFs, drawings, or a Behance/Drive folder if needed.</p>
            <div class="tags">
              <span>Urban</span><span>Mapping</span><span>Research</span>
            </div>
          </div>
        </article>
      </div>
    </section>

    <section class="section" id="about">
      <div class="two-col">
        <div>
          <h2>About</h2>
          <p>
            I’m an architect focused on design communication: site analysis, conceptual design,
            and high-quality visualizations for clients worldwide.
          </p>
          <p class="small">
            Tools: Rhino · Revit · AutoCAD · Adobe Suite · (add your stack)
          </p>
          <div class="row">
            <a class="btn smallbtn" href="assets/David-Reyes-CV.pdf" target="_blank" rel="noreferrer">Download CV</a>
            <a class="btn smallbtn ghost" href="#contact">Contact</a>
          </div>
        </div>
        <div class="about-card">
          <h3>What I’m good at</h3>
          <ul>
            <li>Clear, structured site analysis and mapping</li>
            <li>Concept packages for early-stage design</li>
            <li>2D/3D visualization that sells the idea</li>
            <li>Fast iteration with clean deliverables</li>
          </ul>
        </div>
      </div>
    </section>

    <section class="section" id="services">
      <div class="section-head">
        <h2>Services</h2>
        <p>Simple, client-friendly list. You can tailor this to Fiverr/website leads.</p>
      </div>
      <div class="grid services">
        <div class="service">
          <h3>Site Analysis</h3>
          <p>Maps, SWOT, Kevin Lynch, climate, mobility, land use, and opportunities.</p>
        </div>
        <div class="service">
          <h3>Concept Design</h3>
          <p>Layout options, diagrams, narrative, and early feasibility visuals.</p>
        </div>
        <div class="service">
          <h3>3D Visualization</h3>
          <p>Exterior/interior renders, axons, massing, and presentation boards.</p>
        </div>
      </div>
    </section>

    <section class="section" id="contact">
      <div class="two-col">
        <div>
          <h2>Contact</h2>
          <p>If you want, I can also wire this to a form provider (Formspree) so it emails you.</p>

          <div class="contact-box">
            <p><strong>Email:</strong> <a href="mailto:you@email.com">you@email.com</a></p>
            <p><strong>Location:</strong> Mexico · Remote</p>
            <p><strong>Links:</strong>
              <a href="#" target="_blank" rel="noreferrer">Fiverr</a> ·
              <a href="#" target="_blank" rel="noreferrer">LinkedIn</a> ·
              <a href="#" target="_blank" rel="noreferrer">Instagram</a>
            </p>
          </div>
        </div>

        <form class="form" action="#" method="post" onsubmit="return false;">
          <label>
            Name
            <input type="text" placeholder="Your name" />
          </label>
          <label>
            Email
            <input type="email" placeholder="you@company.com" />
          </label>
          <label>
            Message
            <textarea rows="5" placeholder="Tell me about the project..."></textarea>
          </label>
          <button class="btn" type="submit" onclick="fakeSubmit()">Send message</button>
          <p class="small" id="formNote"></p>
        </form>
      </div>
    </section>

    <footer class="footer">
      <p>© <span id="year"></span> David Reyes · Built with HTML/CSS</p>
    </footer>
  </main>

  <script src="script.js"></script>
</body>
</html>
