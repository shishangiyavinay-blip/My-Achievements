# My-Achievements
Mechanical Design Engineer working across orthopedic implants &amp; surgical instruments, store/furniture design and aerodynamic parts — from concept through DFM, BOM &amp; GD&amp;T-ready drawings, with 2D tool design and hands-on wire-cut CNC programming and operation.
[portfolio.html](https://github.com/user-attachments/files/32717179/portfolio.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Vinay Shishangiya — Mechanical Design & Engineering Portfolio</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&family=Space+Grotesk:wght@500;600;700&display=swap" rel="stylesheet">
<style>
  :root {
    --primary: #0F3B66;       /* Corporate Deep Navy */
    --primary-light: #1E558A;
    --accent: #0284C7;        /* Engineering Cyan / Teal */
    --accent-subtle: #E0F2FE;
    --dark: #0F172A;
    --gray-bg: #F8FAFC;
    --card-bg: #FFFFFF;
    --border: #E2E8F0;
    --text-main: #1E293B;
    --text-muted: #64748B;
    --ok: #10B981;
    --radius: 4px;
    --sans: 'Plus Jakarta Sans', -apple-system, BlinkMacSystemFont, sans-serif;
    --head: 'Space Grotesk', -apple-system, BlinkMacSystemFont, sans-serif;
    --shadow-sm: 0 1px 3px rgba(15,23,42,0.06);
    --shadow-md: 0 8px 24px -6px rgba(15,23,42,0.08);
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }
  html { scroll-behavior: smooth; }
  body { background: var(--gray-bg); color: var(--text-main); font-family: var(--sans); font-size: 15px; line-height: 1.6; -webkit-font-smoothing: antialiased; }
  a { text-decoration: none; color: inherit; }
  button { font-family: inherit; cursor: pointer; }

  /* Top Navigation */
  .topnav {
    position: sticky; top: 0; z-index: 100;
    background: rgba(255, 255, 255, 0.95);
    backdrop-filter: blur(8px);
    border-bottom: 1px solid var(--border);
    display: flex; align-items: center; justify-content: space-between;
    padding: 14px 40px;
  }
  .brand-wrap { display: flex; align-items: center; gap: 10px; }
  .brand-logo { width: 36px; height: 36px; background: var(--primary); color: #fff; font-family: var(--head); font-weight: 800; display: flex; align-items: center; justify-content: center; border-radius: var(--radius); font-size: 1.1rem; }
  .brand-text b { font-family: var(--head); font-size: 1.05rem; color: var(--primary); display: block; line-height: 1.2; }
  .brand-text span { font-size: 0.72rem; letter-spacing: 0.08em; color: var(--text-muted); text-transform: uppercase; font-weight: 600; }
  
  .navlinks { display: flex; gap: 6px; }
  .navlinks button {
    background: none; border: none; color: var(--text-muted);
    font-size: 0.88rem; font-weight: 600; padding: 8px 16px; border-radius: var(--radius);
    transition: all .18s ease;
  }
  .navlinks button:hover { color: var(--primary); background: var(--gray-bg); }
  .navlinks button.active { color: var(--primary); background: var(--accent-subtle); }

  .badge-freelance {
    display: inline-flex; align-items: center; gap: 8px;
    font-size: 0.76rem; font-weight: 600; color: var(--primary);
    border: 1px solid var(--border); background: #fff; padding: 8px 14px;
    border-radius: 30px; cursor: pointer; box-shadow: var(--shadow-sm);
    transition: all .2s ease;
  }
  .badge-freelance:hover { border-color: var(--primary); transform: translateY(-1px); }
  .dot { width: 8px; height: 8px; border-radius: 50%; background: var(--ok); animation: pulse 2s infinite; }
  @keyframes pulse { 0% { box-shadow: 0 0 0 0 rgba(16,185,129,0.5); } 70% { box-shadow: 0 0 0 8px rgba(16,185,129,0); } 100% { box-shadow: 0 0 0 0 rgba(16,185,129,0); } }

  .view { display: block; scroll-margin-top: 84px; }
  .view + .view { border-top: 1px solid var(--border); }

  /* Hero Section */
  .hero-corporate {
    background: linear-gradient(135deg, #0F3B66 0%, #0A2540 100%);
    color: #fff; padding: 75px 40px; position: relative; overflow: hidden;
  }
  .hero-corporate::after {
    content: ""; position: absolute; right: -5%; top: -20%; width: 500px; height: 500px;
    background: radial-gradient(circle, rgba(2,132,199,0.2) 0%, transparent 70%); pointer-events: none;
  }
  .hero-content { max-width: 900px; position: relative; z-index: 2; }
  .hero-kicker { font-family: var(--head); font-size: 0.8rem; letter-spacing: 0.12em; color: #7DD3FC; font-weight: 700; text-transform: uppercase; margin-bottom: 12px; }
  .hero-title { font-family: var(--head); font-size: clamp(2.3rem, 5vw, 3.6rem); line-height: 1.12; font-weight: 800; margin-bottom: 16px; }
  .hero-title span { color: #38BDF8; }
  .hero-desc { font-size: 1.05rem; color: #CBD5E1; max-width: 740px; margin-bottom: 30px; font-weight: 400; }
  
  .btn-row { display: flex; gap: 12px; flex-wrap: wrap; margin-bottom: 40px; }
  .btn {
    padding: 11px 22px; font-size: 0.88rem; font-weight: 600; border-radius: var(--radius);
    display: inline-flex; align-items: center; gap: 8px; border: 1px solid transparent; transition: all .18s ease;
  }
  .btn-primary { background: #0284C7; color: #fff; }
  .btn-primary:hover { background: #0369A1; }
  .btn-outline { background: rgba(255,255,255,0.08); border-color: rgba(255,255,255,0.25); color: #fff; }
  .btn-outline:hover { background: rgba(255,255,255,0.18); border-color: #fff; }

  /* Spec Bar */
  .spec-banner {
    display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    background: rgba(255,255,255,0.06); border: 1px solid rgba(255,255,255,0.12);
    border-radius: var(--radius);
  }
  .spec-item { padding: 16px 20px; border-right: 1px solid rgba(255,255,255,0.12); }
  .spec-item:last-child { border-right: none; }
  .spec-label { display: block; font-size: 0.72rem; letter-spacing: 0.08em; color: #94A3B8; font-weight: 700; margin-bottom: 4px; }
  .spec-val { font-size: 0.95rem; font-weight: 600; color: #F8FAFC; }

  /* Layout Containers */
  .section-container { max-width: 1200px; margin: 0 auto; padding: 60px 40px; }
  .section-head { margin-bottom: 34px; }
  .section-kicker { font-family: var(--head); font-size: 0.78rem; font-weight: 700; color: var(--accent); letter-spacing: 0.1em; text-transform: uppercase; margin-bottom: 6px; display: block; }
  .section-title { font-family: var(--head); font-size: 2rem; font-weight: 700; color: var(--primary); }
  .section-sub { color: var(--text-muted); font-size: 1rem; max-width: 680px; margin-top: 6px; }

  /* Service Category Cards (Home Page) */
  .services-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 20px; }
  .service-card {
    background: var(--card-bg); border: 1px solid var(--border); padding: 26px;
    border-radius: var(--radius); box-shadow: var(--shadow-sm); transition: all .2s ease;
    border-top: 3px solid var(--border); cursor: pointer;
  }
  .service-card:hover { border-top-color: var(--accent); transform: translateY(-3px); box-shadow: var(--shadow-md); }
  .service-card h3 { font-family: var(--head); font-size: 1.15rem; color: var(--primary); margin-bottom: 8px; font-weight: 700; }
  .service-card p { font-size: 0.88rem; color: var(--text-muted); line-height: 1.5; margin-bottom: 16px; }
  .service-tags { display: flex; flex-wrap: wrap; gap: 6px; }
  .service-pill { background: var(--gray-bg); border: 1px solid var(--border); font-size: 0.74rem; font-weight: 600; color: var(--text-muted); padding: 3px 8px; border-radius: 4px; }

  /* Filter Tabs */
  .filter-tabs { display: flex; gap: 8px; flex-wrap: wrap; margin-bottom: 34px; }
  .tab-btn {
    padding: 8px 18px; font-size: 0.82rem; font-weight: 600; border-radius: 30px;
    border: 1px solid var(--border); background: var(--card-bg); color: var(--text-muted); transition: all .18s ease;
  }
  .tab-btn:hover, .tab-btn.active { background: var(--primary); color: #fff; border-color: var(--primary); }

  /* Category Blocks on Work Page */
  .category-section-block { margin-bottom: 46px; }
  .category-section-header {
    border-bottom: 2px solid var(--border);
    padding-bottom: 12px;
    margin-bottom: 22px;
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
  }
  .category-section-header h3 {
    font-family: var(--head);
    font-size: 1.35rem;
    color: var(--primary);
    font-weight: 700;
  }

  /* Projects Grid */
  .projects-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 20px; }
  .project-card {
    background: var(--card-bg); border: 1px solid var(--border); border-radius: var(--radius);
    padding: 24px; display: flex; flex-direction: column; justify-content: space-between;
    transition: all .2s ease; cursor: pointer; box-shadow: var(--shadow-sm);
  }
  .project-card:hover { border-color: var(--accent); transform: translateY(-3px); box-shadow: var(--shadow-md); }
  .project-card h4 { font-family: var(--head); font-size: 1.15rem; color: var(--primary); margin-bottom: 10px; font-weight: 700; }
  .project-card p { color: var(--text-muted); font-size: 0.88rem; margin-bottom: 18px; line-height: 1.5; flex-grow: 1; }
  .proj-link { font-family: var(--head); font-size: 0.84rem; font-weight: 700; color: var(--primary); display: inline-flex; align-items: center; gap: 6px; }

  /* Case Study Views */
  .case-container { background: #fff; border: 1px solid var(--border); border-radius: var(--radius); padding: 40px; margin-top: 20px; }
  .chips-row { display: flex; flex-wrap: wrap; gap: 8px; margin: 12px 0 20px; }
  .chip { background: var(--gray-bg); border: 1px solid var(--border); padding: 4px 10px; font-size: 0.8rem; font-weight: 600; border-radius: 4px; color: var(--text-main); }
  .case-body p { color: var(--text-main); font-size: 0.94rem; margin-bottom: 14px; max-width: 76ch; }
  
  .param-table { width: 100%; border-collapse: collapse; margin: 26px 0; }
  .param-table th { text-align: left; padding: 12px; background: var(--gray-bg); font-family: var(--head); font-size: 0.78rem; color: var(--primary); border-bottom: 2px solid var(--border); }
  .param-table td { padding: 12px; border-bottom: 1px solid var(--border); font-size: 0.88rem; }
  
  /* Google Drive Showcase Box */
  .drive-box {
    background: var(--gray-bg); border: 1px solid var(--border); padding: 24px;
    border-radius: var(--radius); display: flex; justify-content: space-between; align-items: center;
    flex-wrap: wrap; gap: 16px; margin: 24px 0;
  }
  .drive-info h4 { font-family: var(--head); font-size: 1.1rem; color: var(--primary); margin-bottom: 4px; }
  .drive-info p { font-size: 0.86rem; color: var(--text-muted); }

  /* Locked Vault Box */
  .locked-vault {
    background: #F8FAFC; border: 1px solid var(--border); border-left: 4px solid var(--accent);
    padding: 24px; border-radius: var(--radius); margin: 20px 0;
  }
  .vault-header { display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 12px; margin-bottom: 10px; }
  .vault-badge { background: #FEF3C7; color: #92400E; font-size: 0.74rem; font-weight: 700; padding: 3px 8px; border-radius: 4px; }
  .blur-preview { background: #0F172A; color: #64748B; font-family: monospace; font-size: 0.8rem; padding: 14px; border-radius: 4px; filter: blur(3px); user-select: none; margin-top: 10px; }

  /* Modals */
  .modal-overlay {
    display: none; position: fixed; inset: 0; background: rgba(15, 23, 42, 0.65);
    backdrop-filter: blur(4px); z-index: 999; align-items: center; justify-content: center; padding: 20px;
  }
  .modal-overlay.active { display: flex; }
  .modal-card {
    background: #fff; border-radius: var(--radius); width: 100%; max-width: 480px;
    padding: 28px; box-shadow: 0 20px 40px rgba(0,0,0,0.15);
  }
  .modal-head { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 16px; border-bottom: 1px solid var(--border); padding-bottom: 12px; }
  .modal-head h3 { font-family: var(--head); font-size: 1.2rem; color: var(--primary); }
  .modal-close { background: none; border: none; font-size: 1.6rem; color: var(--text-muted); cursor: pointer; }
  
  .form-group { margin-bottom: 14px; }
  .form-group label { display: block; font-size: 0.74rem; font-weight: 700; color: var(--primary); margin-bottom: 4px; text-transform: uppercase; }
  .form-group input, .form-group textarea {
    width: 100%; padding: 10px 12px; border: 1px solid var(--border); border-radius: var(--radius);
    font-family: var(--sans); font-size: 0.9rem; color: var(--text-main);
  }
  .form-group textarea { min-height: 80px; resize: vertical; }
  .form-group input:focus, .form-group textarea:focus { outline: 2px solid var(--accent); }

  /* Contact Channels */
  .contact-channel {
    display: flex; align-items: center; gap: 14px; padding: 14px; border: 1px solid var(--border);
    border-radius: var(--radius); margin-bottom: 10px; transition: all .18s ease;
  }
  .contact-channel:hover { border-color: var(--primary); background: var(--gray-bg); }
  .channel-icon { width: 38px; height: 38px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 1.1rem; flex-shrink: 0; }
  .channel-icon.wa { background: #DCFCE7; color: #15803D; }
  .channel-icon.call { background: var(--accent-subtle); color: var(--primary); }
  .channel-icon.mail { background: #F1F5F9; color: #475569; }

  /* Footer */
  .footer { background: var(--primary); color: #fff; padding: 60px 40px 30px; }
  .footer-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 30px; margin-bottom: 40px; }
  .footer-col h4 { font-family: var(--head); font-size: 0.86rem; color: #7DD3FC; margin-bottom: 14px; letter-spacing: 0.08em; text-transform: uppercase; }
  .footer-col p, .footer-col a { color: #CBD5E1; font-size: 0.88rem; line-height: 1.6; }
  .footer-bottom { border-top: 1px solid rgba(255,255,255,0.12); padding-top: 20px; display: flex; justify-content: space-between; font-size: 0.78rem; color: #94A3B8; }

  @media(max-width: 768px) {
    .topnav { padding: 12px 20px; flex-wrap: wrap; }
    .navlinks { order: 3; width: 100%; margin-top: 10px; overflow-x: auto; }
    .section-container, .hero-corporate { padding: 40px 20px; }
    .footer { padding: 40px 20px 20px; }
  }
</style>
</head>
<body>

  <!-- Top Navigation Bar -->
  <nav class="topnav">
    <div class="brand-wrap">
      <div class="brand-logo">VS</div>
      <div class="brand-text">
        <b>Vinay Shishangiya</b>
        <span>Mechanical Design Engineer</span>
      </div>
    </div>
    <div class="navlinks">
      <button data-view="home" class="active">Home</button>
      <button data-view="work">Services &amp; Projects</button>
      <button data-view="skills">Capabilities</button>
      <button data-view="resume">Resume</button>
      <button data-view="contact">Contact</button>
    </div>
    <!-- Freelance Connect Trigger -->
    <button class="badge-freelance" onclick="openFreelanceModal()">
      <span class="dot"></span> Available for freelance &rarr;
    </button>
  </nav>

  <!-- ===================== HOME VIEW ===================== -->
  <div class="view is-active" id="view-home">
    <header class="hero-corporate">
      <div class="hero-content">
        <span class="hero-kicker">ENGINEERING DESIGN · DFM &amp; CAD AUTOMATION</span>
        <h1 class="hero-title">Precision Mechanical Design &amp; <span>Manufacturing Engineering</span></h1>
        <p class="hero-desc">Delivering turnkey design engineering across orthopedic implants, retail store layouts, bulk material handling systems, and automated SolidWorks API programming.</p>
        
        <div class="btn-row">
          <button class="btn btn-primary" data-view="work">Explore All Projects &rarr;</button>
          <button class="btn btn-outline" data-view="resume">Request Resume (PDF)</button>
          <button class="btn btn-outline" onclick="openFreelanceModal()">Connect Channels ↗</button>
        </div>

        <div class="spec-banner">
          <div class="spec-item">
            <span class="spec-label">LOCATION</span>
            <span class="spec-val">Ahmedabad, Gujarat, India</span>
          </div>
          <div class="spec-item">
            <span class="spec-label">CAD / CAE SUITE</span>
            <span class="spec-val">SolidWorks · AutoCAD · Ansys</span>
          </div>
          <div class="spec-item">
            <span class="spec-label">MFG PROCESS</span>
            <span class="spec-val">Wire-Cut CNC (Program &amp; Run)</span>
          </div>
          <div class="spec-item">
            <span class="spec-label">STATUS</span>
            <span class="spec-val">Full-Time &amp; Freelance Open</span>
          </div>
        </div>
      </div>
    </header>

    <!-- 4 Official Categories Architecture (No Numbers) -->
    <section class="section-container">
      <div class="section-head">
        <span class="section-kicker">Core Practices</span>
        <h2 class="section-title">Specialized Engineering Domains</h2>
        <p class="section-sub">Standardized across DFM, ISO/ASTM compliance, and ASME Y14.5 GD&amp;T specifications.</p>
      </div>

      <div class="services-grid">
        <div class="service-card" onclick="switchView('work'); filterProjects('cat1');">
          <h3>Orthopedic and Surgical Designs and Development with Reverse Engineering</h3>
          <p>Reverse engineering, anatomical contouring, dynamic cervical plates, interbody spacers, and surgical instrumentation.</p>
          <div class="service-tags">
            <span class="service-pill">Biocompatible</span>
            <span class="service-pill">GD&amp;T</span>
            <span class="service-pill">Implants</span>
          </div>
        </div>

        <div class="service-card" onclick="switchView('work'); filterProjects('cat2');">
          <h3>Furniture Design and Store Layout</h3>
          <p>Coordinated retail interiors, heavy-duty shelving deflection analysis, weighted bases, and panel batch-cutting DFM.</p>
          <div class="service-tags">
            <span class="service-pill">Joinery BOM</span>
            <span class="service-pill">Deflection FEA</span>
            <span class="service-pill">DFM</span>
          </div>
        </div>

        <div class="service-card" onclick="switchView('work'); filterProjects('cat3');">
          <h3>Industrial and Product Design</h3>
          <p>Bulk material coal conveyor systems, chute wear liners, and dynamic bicycle frame structural load verification.</p>
          <div class="service-tags">
            <span class="service-pill">Bulk Systems</span>
            <span class="service-pill">Weld Fatigue</span>
            <span class="service-pill">Frame Geometry</span>
          </div>
        </div>

        <div class="service-card" onclick="switchView('work'); filterProjects('cat4');">
          <h3>CNC Tooling &amp; Automation</h3>
          <p>Wire-cut EDM 2D profile design, kerf compensation, machine setup, and custom SolidWorks VBA cabinet assembly macros.</p>
          <div class="service-tags">
            <span class="service-pill">Wire EDM</span>
            <span class="service-pill">VBA UserForms</span>
            <span class="service-pill">Assembly Macros</span>
          </div>
        </div>
      </div>
    </section>
  </div>

  <!-- ===================== WORK VIEW (STRUCTURED UNDER CATEGORIES WITHOUT COUNTING) ===================== -->
  <div class="view" id="view-work">
    <section class="section-container">
      <div class="section-head">
        <span class="section-kicker">Project Portfolio</span>
        <h2 class="section-title">Documented Engineering Case Studies</h2>
        <p class="section-sub">Projects structured directly under their specialized engineering disciplines.</p>
      </div>

      <!-- Filter Buttons without Counting -->
      <div class="filter-tabs">
        <button class="tab-btn active" data-filter="all">All Categories</button>
        <button class="tab-btn" data-filter="cat1">Orthopedic &amp; Surgical</button>
        <button class="tab-btn" data-filter="cat2">Furniture &amp; Store Layout</button>
        <button class="tab-btn" data-filter="cat3">Industrial &amp; Product Design</button>
        <button class="tab-btn" data-filter="cat4">CNC Tooling &amp; Automation</button>
      </div>

      <!-- Container where Category Sections are dynamically rendered -->
      <div id="projectsCategoryContainer"></div>
    </section>
  </div>

  <!-- ===================== CASE STUDY: VA LOCKING SCREW ===================== -->
  <div class="view" id="view-cs-1-1">
    <section class="section-container">
      <button class="btn btn-outline" style="color:var(--primary);border-color:var(--border);" data-view="work">&larr; Back to all projects</button>
      <div class="case-container">
        <span class="section-kicker">Orthopedic and Surgical Designs and Development with Reverse Engineering</span>
        <h2 style="font-family:var(--head);font-size:1.85rem;color:var(--primary);margin:6px 0 12px;">VA Locking Head Screw — Self-Tapping</h2>
        <div class="chips-row">
          <span class="chip">SolidWorks</span><span class="chip">GD&amp;T</span><span class="chip">Surgical Grade Materials</span>
        </div>
        <div class="case-body">
          <p>A variable-angle (VA) locking screw has to do two jobs at once: cut its own thread into bone on insertion, and then lock securely into the plate hole at whatever angle the surgeon chose — not just at one fixed angle.</p>
          <p>The design study covered the self-tapping tip and flute geometry for consistent bone-cutting without excessive insertion torque, and the head geometry that lets the screw engage the plate's locking thread across its full angular range while still seating flush. Tolerances on the locking-thread interface were treated as critical-to-function, since too loose a fit undermines the angular stability the whole VA system is built around, and material selection followed standard implant-grade requirements for strength and biocompatibility.</p>
        </div>
        <table class="param-table">
          <thead><tr><th>Parameter</th><th>Consideration</th></tr></thead>
          <tbody>
            <tr><td>Function</td><td>Self-tapping insertion + variable-angle locking</td></tr>
            <tr><td>Critical features</td><td>Head locking-thread interface, cutting flute geometry</td></tr>
            <tr><td>Material</td><td>Implant-grade metal (biocompatible, per standard requirements)</td></tr>
          </tbody>
        </table>
        <div class="drive-box">
          <div class="drive-info">
            <h4>Implant CAD Models &amp; Thread Details</h4>
            <p>Access 3D model files, cross-sectional views, and manufacturing drawings on Drive.</p>
          </div>
          <a href="https://drive.google.com/drive/folders/YOUR_VA_SCREW_DRIVE_LINK" target="_blank" class="btn btn-primary">See My Work (Google Drive) ↗</a>
        </div>
      </div>
    </section>
  </div>

  <!-- ===================== CASE STUDY: CERVICAL PLATE ===================== -->
  <div class="view" id="view-cs-1-2">
    <section class="section-container">
      <button class="btn btn-outline" style="color:var(--primary);border-color:var(--border);" data-view="work">&larr; Back to all projects</button>
      <div class="case-container">
        <span class="section-kicker">Orthopedic and Surgical Designs and Development with Reverse Engineering</span>
        <h2 style="font-family:var(--head);font-size:1.85rem;color:var(--primary);margin:6px 0 12px;">Cervical Plate</h2>
        <div class="chips-row">
          <span class="chip">SolidWorks</span><span class="chip">Anatomical Contouring</span><span class="chip">GD&amp;T</span>
        </div>
        <div class="case-body">
          <p>An anterior cervical plate sits directly against the front of the spine, so its shape has to follow the natural curve of the neck (cervical lordosis) rather than sit as a flat piece of metal — a poor contour match is both a fit problem and a soft-tissue irritation risk.</p>
          <p>The study focused on plate contouring to match typical cervical curvature, screw-hole spacing and angulation to line up with vertebral body anatomy across the levels the plate spans, and keeping the overall profile as low and smooth-edged as practical to minimise irritation to the esophagus and surrounding tissue. Screw holes carried a locking feature so screws couldn't back out once seated, consistent with standard anterior cervical plate designs.</p>
        </div>
        <table class="param-table">
          <thead><tr><th>Parameter</th><th>Consideration</th></tr></thead>
          <tbody>
            <tr><td>Geometry</td><td>Contour matched to cervical lordosis</td></tr>
            <tr><td>Screw holes</td><td>Spacing/angulation per vertebral anatomy, locking feature</td></tr>
            <tr><td>Profile</td><td>Low-profile, smooth edges to reduce soft-tissue irritation</td></tr>
          </tbody>
        </table>
        <div class="drive-box">
          <div class="drive-info">
            <h4>Anatomical Plate Drawing &amp; CAD Package</h4>
            <p>View contoured surface models, locking pocket GD&amp;T sheets, and STEP files on Drive.</p>
          </div>
          <a href="https://drive.google.com/drive/folders/YOUR_CERVICAL_PLATE_DRIVE_LINK" target="_blank" class="btn btn-primary">See My Work (Google Drive) ↗</a>
        </div>
      </div>
    </section>
  </div>

  <!-- ===================== CASE STUDY: SURGICAL INSTRUMENTS ===================== -->
  <div class="view" id="view-cs-1-3">
    <section class="section-container">
      <button class="btn btn-outline" style="color:var(--primary);border-color:var(--border);" data-view="work">&larr; Back to all projects</button>
      <div class="case-container">
        <span class="section-kicker">Orthopedic and Surgical Designs and Development with Reverse Engineering</span>
        <h2 style="font-family:var(--head);font-size:1.85rem;color:var(--primary);margin:6px 0 12px;">Surgical Instruments</h2>
        <div class="chips-row">
          <span class="chip">SolidWorks</span><span class="chip">Ergonomics</span><span class="chip">Sterilizable Materials</span>
        </div>
        <div class="case-body">
          <p>Instruments designed to accompany implant systems — drivers, holders and guides — where the design problem is less about strength and more about a reliable interface: the instrument has to engage the implant the same way, every time, under gloved hands and without a clear line of sight.</p>
          <p>The study covered grip ergonomics for one-handed and two-handed use under surgical gloves, the driver-to-screw and holder-to-implant interface tolerances needed for positive, unambiguous engagement, and material selection for repeated autoclave sterilization without corrosion or dimensional drift. Working surfaces were kept simple and low-snag by design, since anything that can trap tissue or resist cleaning is a functional defect in a surgical instrument, not just a cosmetic one.</p>
        </div>
        <table class="param-table">
          <thead><tr><th>Parameter</th><th>Consideration</th></tr></thead>
          <tbody>
            <tr><td>Interface</td><td>Driver/holder-to-implant engagement tolerances</td></tr>
            <tr><td>Ergonomics</td><td>Gloved-hand grip, one- and two-handed use</td></tr>
            <tr><td>Material</td><td>Autoclave-sterilizable, corrosion-resistant</td></tr>
          </tbody>
        </table>
        <div class="drive-box">
          <div class="drive-info">
            <h4>Instrument Assembly &amp; Handle Models</h4>
            <p>Access driver engagement tolerances and autoclavable passivated design drawings on Drive.</p>
          </div>
          <a href="https://drive.google.com/drive/folders/YOUR_INSTRUMENTS_DRIVE_LINK" target="_blank" class="btn btn-primary">See My Work (Google Drive) ↗</a>
        </div>
      </div>
    </section>
  </div>

  <!-- ===================== CASE STUDY: CERVICAL SPACER ===================== -->
  <div class="view" id="view-cs-1-4">
    <section class="section-container">
      <button class="btn btn-outline" style="color:var(--primary);border-color:var(--border);" data-view="work">&larr; Back to all projects</button>
      <div class="case-container">
        <span class="section-kicker">Orthopedic and Surgical Designs and Development with Reverse Engineering</span>
        <h2 style="font-family:var(--head);font-size:1.85rem;color:var(--primary);margin:6px 0 12px;">Cervical Spacer</h2>
        <div class="chips-row">
          <span class="chip">SolidWorks</span><span class="chip">Interbody Design</span><span class="chip">Material Trade-off Study</span>
        </div>
        <div class="case-body">
          <p>A cervical interbody spacer sits between two vertebrae after disc removal, holding the disc space open at the right height and angle while bone grows through it to fuse the segment — so it has to be mechanically stable immediately and biologically permeable over time.</p>
          <p>The study covered endplate contact geometry sized for stability against the vertebral endplates without subsiding into the bone, a graft window sized to allow enough bone-graft material through for fusion, and a comparison of lordotic-angle options to restore natural neck curvature at the treated level. Material choice weighed PEEK against titanium on stiffness match to bone, radiographic visibility, and the option of adding radiographic markers so the spacer's position is checkable on X-ray after surgery.</p>
        </div>
        <table class="param-table">
          <thead><tr><th>Parameter</th><th>Consideration</th></tr></thead>
          <tbody>
            <tr><td>Function</td><td>Disc-height restoration + bone fusion pathway</td></tr>
            <tr><td>Geometry</td><td>Endplate contact area, graft window, lordotic angle options</td></tr>
            <tr><td>Material</td><td>PEEK vs. titanium trade-off, radiographic markers</td></tr>
          </tbody>
        </table>
        <div class="drive-box">
          <div class="drive-info">
            <h4>Spacer Graft Window CAD &amp; Trade-off Docs</h4>
            <p>Download 3D interbody files and PEEK vs. Titanium FEA comparison studies from Drive.</p>
          </div>
          <a href="https://drive.google.com/drive/folders/YOUR_SPACER_DRIVE_LINK" target="_blank" class="btn btn-primary">See My Work (Google Drive) ↗</a>
        </div>
      </div>
    </section>
  </div>

  <!-- ===================== CASE STUDY: STORE INTERIOR ===================== -->
  <div class="view" id="view-cs-2-1">
    <section class="section-container">
      <button class="btn btn-outline" style="color:var(--primary);border-color:var(--border);" data-view="work">&larr; Back to all projects</button>
      <div class="case-container">
        <span class="section-kicker">Furniture Design and Store Layout</span>
        <h2 style="font-family:var(--head);font-size:1.85rem;color:var(--primary);margin:6px 0 12px;">Store Interior — Shelving, Display Unit &amp; Cabinet</h2>
        <div class="chips-row">
          <span class="chip">SolidWorks</span><span class="chip">DFM</span><span class="chip">Cost Estimation</span>
        </div>
        <div class="case-body">
          <p>A full store fit-out rather than a single piece: wall-mounted shelving, a central display unit and a storage cabinet, designed as one coordinated system rather than three unrelated pieces of furniture.</p>
          <p>The shelving study covered wall-anchor and bracket selection against expected product load, and shelf-span limits to keep deflection within an acceptable range for the panel material chosen. The display unit was designed around sightlines and reach — height and depth set so products stay visible and reachable from the aisle, with a base heavy enough to stay stable when loaded on one side.</p>
          <p>The cabinet went through a joinery and hardware study — comparing screw-and-dowel construction against systems hardware (soft-close hinges, drawer slides) for durability versus cost — and the whole set was reviewed for DFM so panels could be batch-cut and assembled on-site without custom fitting per unit, alongside a material and finish cost estimate.</p>
        </div>
        <table class="param-table">
          <thead><tr><th>Parameter</th><th>Consideration</th></tr></thead>
          <tbody>
            <tr><td>Elements</td><td>Wall shelving, display unit, storage cabinet</td></tr>
            <tr><td>Study areas</td><td>Wall load/anchoring, shelf-span deflection, sightlines &amp; reach</td></tr>
            <tr><td>Deliverables</td><td>DFM-reviewed drawings, hardware BOM, cost estimate</td></tr>
          </tbody>
        </table>
        <div class="drive-box">
          <div class="drive-info">
            <h4>Complete Drawing Package &amp; Blueprints</h4>
            <p>Access full layout plans, OSB detail sections, exploded BOM sheets, and hardware docs on Drive.</p>
          </div>
          <a href="https://drive.google.com/drive/folders/YOUR_STORE_FURNITURE_DRIVE_LINK" target="_blank" class="btn btn-primary">See My Work (Google Drive) ↗</a>
        </div>
      </div>
    </section>
  </div>

  <!-- ===================== CASE STUDY: COAL TRANSPORT ===================== -->
  <div class="view" id="view-cs-3-1">
    <section class="section-container">
      <button class="btn btn-outline" style="color:var(--primary);border-color:var(--border);" data-view="work">&larr; Back to all projects</button>
      <div class="case-container">
        <span class="section-kicker">Industrial and Product Design</span>
        <h2 style="font-family:var(--head);font-size:1.85rem;color:var(--primary);margin:6px 0 12px;">Coal Transportation Management System</h2>
        <div class="chips-row">
          <span class="chip">SolidWorks</span><span class="chip">System Layout</span><span class="chip">Bulk Material Handling</span>
        </div>
        <div class="case-body">
          <p>The brief was to design a system for moving coal reliably from stockpile to point of use, with the usual constraints of bulk material handling: abrasive wear on contact surfaces, dust generation, spillage at transfer points, and a layout that fits an existing plant footprint.</p>
          <p>The research phase looked at conveyor geometry and incline limits for the material's angle of repose, transfer-chute design to reduce spillage and impact wear, and where wear-resistant liner plates were worth the added cost versus a standard mild-steel chute. Structural sizing for supports and gantries followed from expected belt loading plus a margin for surge loads.</p>
          <p>The output was a full system layout modelled in SolidWorks, with supporting calculations for belt capacity, drive sizing and structural loading, documented for direct hand-off to fabrication.</p>
        </div>
        <table class="param-table">
          <thead><tr><th>Parameter</th><th>Consideration</th></tr></thead>
          <tbody>
            <tr><td>Material handled</td><td>Coal (bulk, abrasive)</td></tr>
            <tr><td>Key risks addressed</td><td>Spillage, dust, liner wear, surge loading</td></tr>
            <tr><td>Deliverables</td><td>System layout, structural calculations, fabrication drawings</td></tr>
          </tbody>
        </table>
        <div class="drive-box">
          <div class="drive-info">
            <h4>System Layout &amp; Fabrication Blueprints</h4>
            <p>Inspect conveyor sizing sheets, chute wear-plate details, and structural gantry drawings on Drive.</p>
          </div>
          <a href="https://drive.google.com/drive/folders/YOUR_COAL_PROJECT_DRIVE_LINK" target="_blank" class="btn btn-primary">See My Work (Google Drive) ↗</a>
        </div>
      </div>
    </section>
  </div>

  <!-- ===================== CASE STUDY: BICYCLE DESIGN ===================== -->
  <div class="view" id="view-cs-3-2">
    <section class="section-container">
      <button class="btn btn-outline" style="color:var(--primary);border-color:var(--border);" data-view="work">&larr; Back to all projects</button>
      <div class="case-container">
        <span class="section-kicker">Industrial and Product Design</span>
        <h2 style="font-family:var(--head);font-size:1.85rem;color:var(--primary);margin:6px 0 12px;">Bicycle Design</h2>
        <div class="chips-row">
          <span class="chip">SolidWorks</span><span class="chip">Frame Geometry</span><span class="chip">Load Analysis</span>
        </div>
        <div class="case-body">
          <p>Frame design sits at the intersection of ride feel and structural reliability — the same triangle of tubes has to feel right to ride and survive years of pedaling, braking and impact loads without failing at a weld joint.</p>
          <p>The study covered frame geometry — head-tube and seat-tube angles and their effect on handling and rider position — alongside a tube material and cross-section comparison (steel versus aluminium) for weight, stiffness and cost. Weld-joint locations were checked against expected load cases (pedaling, braking, and impact) with margin built in at the highest-stress junctions, and rider fit and ergonomics were checked against standard sizing ranges before finalising dimensions.</p>
        </div>
        <table class="param-table">
          <thead><tr><th>Parameter</th><th>Consideration</th></tr></thead>
          <tbody>
            <tr><td>Geometry</td><td>Head-tube/seat-tube angles, rider fit</td></tr>
            <tr><td>Material</td><td>Steel vs. aluminium trade-off</td></tr>
            <tr><td>Structural check</td><td>Pedaling, braking &amp; impact load cases at weld joints</td></tr>
          </tbody>
        </table>
        <div class="drive-box">
          <div class="drive-info">
            <h4>Bicycle Frame CAD &amp; Weld FEA</h4>
            <p>Access full tube profile CAD models, frame geometry sheets, and stress FEA reports on Drive.</p>
          </div>
          <a href="https://drive.google.com/drive/folders/YOUR_BIKE_DRIVE_LINK" target="_blank" class="btn btn-primary">See My Work (Google Drive) ↗</a>
        </div>
      </div>
    </section>
  </div>

  <!-- ===================== CASE STUDY: WIRE-CUT CNC TOOLING ===================== -->
  <div class="view" id="view-cs-4-1">
    <section class="section-container">
      <button class="btn btn-outline" style="color:var(--primary);border-color:var(--border);" data-view="work">&larr; Back to all projects</button>
      <div class="case-container">
        <span class="section-kicker">CNC Tooling &amp; Automation</span>
        <h2 style="font-family:var(--head);font-size:1.85rem;color:var(--primary);margin:6px 0 12px;">Tool Design &amp; Wire-Cut CNC Manufacturing</h2>
        <div class="chips-row">
          <span class="chip">AutoCAD 2D</span><span class="chip">CNC Programming</span><span class="chip">Wire-Cut EDM</span>
        </div>
        <div class="case-body">
          <p>End-to-end tooling work: the cutting tool's profile is designed in 2D AutoCAD first, then turned into a wire-cut EDM program, and the machine is set up and run in-house rather than handed off to a separate operator.</p>
          <p>The 2D design stage accounts for the things that only matter once the tool is actually cut — kerf compensation for wire diameter, achievable corner radii, and profile tolerances the tool needs to hold in service. From there the cutting path is planned: entry points, cutting sequence, and where a multi-pass strategy (rough pass plus a finish skim pass) is worth the extra time for a better surface finish or tighter tolerance.</p>
          <p>On the machine side, that includes wire tension and dielectric fluid setup, and monitoring the cut in progress rather than just starting the program and walking away — catching a drifting cut early is cheaper than scrapping a finished tool.</p>
        </div>
        <table class="param-table">
          <thead><tr><th>Parameter</th><th>Consideration</th></tr></thead>
          <tbody>
            <tr><td>Design stage</td><td>2D tool profile in AutoCAD, kerf compensation, corner radii</td></tr>
            <tr><td>Programming</td><td>Cutting sequence, multi-pass (rough + finish) strategy</td></tr>
            <tr><td>Operation</td><td>Machine setup, wire tension, in-process monitoring</td></tr>
          </tbody>
        </table>
        <div class="drive-box">
          <div class="drive-info">
            <h4>2D AutoCAD DXF &amp; G-Code Programs</h4>
            <p>Review 2D tool path layouts, kerf offset calculations, and wire-cut machine setup sheets on Drive.</p>
          </div>
          <a href="https://drive.google.com/drive/folders/YOUR_CNC_TOOLING_DRIVE_LINK" target="_blank" class="btn btn-primary">See My Work (Google Drive) ↗</a>
        </div>
      </div>
    </section>
  </div>

  <!-- ===================== CASE STUDY: SOLIDWORKS MACRO ===================== -->
  <div class="view" id="view-cs-4-2">
    <section class="section-container">
      <button class="btn btn-outline" style="color:var(--primary);border-color:var(--border);" data-view="work">&larr; Back to all projects</button>
      <div class="case-container">
        <span class="section-kicker">CNC Tooling &amp; Automation</span>
        <h2 style="font-family:var(--head);font-size:1.85rem;color:var(--primary);margin:6px 0 12px;">SolidWorks Macro Automation — Cabinet Assembly</h2>
        <div class="chips-row">
          <span class="chip">SolidWorks VBA</span><span class="chip">UserForm</span><span class="chip">Assembly Automation</span>
        </div>
        <div class="case-body">
          <p>Building a cabinet by hand in SolidWorks means repeating the same sketch-dimension-extrude steps for every panel, then assembling and mating them — tedious, and an easy place to introduce sizing mistakes. The goal here was to remove the repetition without removing control over the dimensions.</p>
          <p>The starting point was three separately recorded VBA macros, each generating one panel by sketching a rectangle on the Front Plane, setting its two dimensions, and extruding it. These were combined into a single master macro driven by a custom UserForm — with fields for height, width, thickness and name, plus a name and save-path field for each individual piece, and a checkbox to reuse one shared path for every piece instead of setting them one by one. Hardcoded values were kept only where they should be fixed by design: an 1/8" gap between paired doors and a 1/16" gap between panels and doors to leave clearance for the hinge.</p>
          <p>The macro generates the full panel set — top, bottom, sides, a shelf and the doors (door count taken from the form) — with each body saved out as its own part file, positioned correctly relative to one another. From there the macro drives SolidWorks to pull those saved parts into a proper assembly, rather than leaving everything as a single multibody part, so the cabinet ends up as a real, editable assembly straight out of one form submission.</p>
        </div>

        <!-- PROTECTED MACRO VBA SOURCE CODE -->
        <div class="locked-vault">
          <div class="vault-header">
            <div>
              <span class="vault-badge">🔒 CONFIDENTIAL SOURCE CODE</span>
              <h4 style="font-family:var(--head);font-size:1.15rem;color:var(--primary);margin-top:4px;">Master VBA Automation Script &amp; UserForm</h4>
            </div>
            <button class="btn btn-primary" onclick="openRequestModal('Macro VBA Source Code', 'Cabinet Assembly Automation Script (VBA)')">
              Request Code Access &rarr;
            </button>
          </div>
          <p style="font-size:0.86rem;color:var(--text-muted);">The master UserForm script and mating algorithms are proprietary. Request permission to review raw code.</p>
          <div class="blur-preview">
            Sub GenerateCabinet()<br>
            &nbsp;&nbsp;Dim swApp As SldWorks.SldWorks, swModel As SldWorks.ModelDoc2<br>
            &nbsp;&nbsp;' [PROTECTED]: UserForm dynamic bounding box &amp; automated assembly mating logic...<br>
            &nbsp;&nbsp;Set swApp = Application.SldWorks<br>
            End Sub
          </div>
        </div>

        <!-- PROTECTED MACRO FILE PACKAGE -->
        <div class="locked-vault" style="margin-top:16px;">
          <div class="vault-header">
            <div>
              <span class="vault-badge">🔒 PROTECTED PACKAGE DOWNLOAD</span>
              <h4 style="font-family:var(--head);font-size:1.15rem;color:var(--primary);margin-top:4px;">Macro Binary (.swp) &amp; SolidWorks UserForm</h4>
            </div>
            <button class="btn btn-primary" onclick="openRequestModal('Macro Executable Package', 'Cabinet Assembly Macro (.swp)')">
              Request Package Access &rarr;
            </button>
          </div>
          <p style="font-size:0.86rem;color:var(--text-muted);margin:0;">Request permission to download the executable macro package (.swp) for direct integration into SolidWorks.</p>
        </div>

        <table class="param-table" style="margin-top:24px;">
          <thead><tr><th>Parameter</th><th>Consideration</th></tr></thead>
          <tbody>
            <tr><td>Input method</td><td>Custom UserForm — height, width, thickness, name, per-piece path</td></tr>
            <tr><td>Generated parts</td><td>Top, bottom &amp; side panels, shelf, doors (quantity from form)</td></tr>
            <tr><td>Fixed clearances</td><td>1/8" gap between doors, 1/16" panel-to-door gap for hinge</td></tr>
            <tr><td>Output</td><td>Each panel saved as its own part file, combined into a SolidWorks assembly</td></tr>
          </tbody>
        </table>
      </div>
    </section>
  </div>

  <!-- ===================== CAPABILITIES (SKILLS) VIEW ===================== -->
  <div class="view" id="view-skills">
    <section class="section-container">
      <div class="section-head">
        <span class="section-kicker">Core Competencies</span>
        <h2 class="section-title">Technical Capabilities &amp; Software Suite</h2>
        <p class="section-sub">Demonstrated experience across full engineering design cycles, simulation, and shop-floor manufacturing.</p>
      </div>

      <div class="services-grid">
        <div class="service-card">
          <h3>3D CAD &amp; Surface Modeling</h3>
          <p>Parametric 3D solid and complex surface modeling using industry-standard engineering tools.</p>
          <div class="service-tags">
            <span class="service-pill">SolidWorks</span>
            <span class="service-pill">AutoCAD 2D/3D</span>
            <span class="service-pill">Sheet Metal</span>
            <span class="service-pill">Weldments</span>
          </div>
        </div>

        <div class="service-card">
          <h3>Simulation &amp; Structural CAE</h3>
          <p>Finite Element Analysis (FEA) evaluating stresses, dynamic deflection, and structural joint integrity.</p>
          <div class="service-tags">
            <span class="service-pill">Ansys FEA</span>
            <span class="service-pill">Stress Analysis</span>
            <span class="service-pill">Weld Fatigue</span>
            <span class="service-pill">Deflection Checks</span>
          </div>
        </div>

        <div class="service-card">
          <h3>Tooling &amp; CNC Manufacturing</h3>
          <p>Shop-floor tool design, wire EDM cutting paths, and precision ASME Y14.5 drafting standards.</p>
          <div class="service-tags">
            <span class="service-pill">Wire-Cut CNC</span>
            <span class="service-pill">ASME GD&amp;T</span>
            <span class="service-pill">DFM / DFA</span>
            <span class="service-pill">Kerf Offsets</span>
          </div>
        </div>

        <div class="service-card">
          <h3>Design Automation &amp; Code</h3>
          <p>Custom macros and API programs to eliminate repetitive drafting and build intelligent assemblies.</p>
          <div class="service-tags">
            <span class="service-pill">SolidWorks API</span>
            <span class="service-pill">VBA Automation</span>
            <span class="service-pill">Custom UserForms</span>
            <span class="service-pill">Excel BOM Sync</span>
          </div>
        </div>
      </div>
    </section>
  </div>

  <!-- ===================== RESUME VIEW ===================== -->
  <div class="view" id="view-resume">
    <section class="section-container">
      <div class="section-head">
        <span class="section-kicker">Professional Background</span>
        <h2 class="section-title">Curriculum Vitae &amp; Credentials</h2>
        <p class="section-sub">Direct download is protected. Submit an authorization request to receive the updated PDF resume via email.</p>
      </div>

      <div class="locked-vault" style="max-width:650px;">
        <div class="vault-header">
          <div>
            <span class="vault-badge">🔒 CONFIDENTIAL ASSET</span>
            <h4 style="font-family:var(--head);font-size:1.25rem;color:var(--primary);margin-top:4px;">Vinay Shishangiya — Resume (PDF)</h4>
          </div>
          <button class="btn btn-primary" onclick="openRequestModal('Resume / CV', 'Vinay Shishangiya - Mechanical Design Resume (PDF)')">
            Request Resume Access &rarr;
          </button>
        </div>
        <p style="font-size:0.9rem;color:var(--text-muted);margin:12px 0 18px;">
          Includes comprehensive industrial background across orthopedic implants, retail fixtures, industrial systems, and wire-cut tooling experience.
        </p>
        <div style="display:flex;flex-wrap:wrap;gap:8px;">
          <span class="chip">✔ Mechanical Design Engineer</span>
          <span class="chip">✔ SolidWorks / AutoCAD Specialist</span>
          <span class="chip">✔ CNC Wire-Cut Machining</span>
        </div>
      </div>
    </section>
  </div>

  <!-- ===================== CONTACT VIEW ===================== -->
  <div class="view" id="view-contact">
    <section class="section-container">
      <div class="section-head">
        <span class="section-kicker">Engagement</span>
        <h2 class="section-title">Start a Project Consultation</h2>
        <p class="section-sub">Open for freelance mechanical design engagements, 3D CAD modeling, and custom automation consulting.</p>
      </div>

      <div class="service-card" style="max-width:600px;">
        <h3 style="margin-bottom:14px;">Send Message Directly</h3>
        <form onsubmit="handleDirectContact(event)">
          <div class="form-group">
            <label>Full Name</label>
            <input type="text" id="directName" placeholder="e.g. John Doe" required>
          </div>
          <div class="form-group">
            <label>Business Email</label>
            <input type="email" id="directEmail" placeholder="e.g. john@company.com" required>
          </div>
          <div class="form-group">
            <label>Project Scope &amp; Timeline</label>
            <textarea id="directMsg" placeholder="Describe the CAD, FEA, or manufacturing requirements..." required></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Transmit Inquiry &rarr;</button>
        </form>
      </div>
    </section>
  </div>

  <!-- Footer -->
  <footer class="footer">
    <div class="footer-grid">
      <div class="footer-col">
        <h4>Practice</h4>
        <p>Mechanical Design Engineer specializing in medical implants, store layouts, industrial bulk systems, and CAD API automation.</p>
      </div>
      <div class="footer-col">
        <h4>Direct Channels</h4>
        <p><a href="mailto:shishangiyavinay@gmail.com">shishangiyavinay@gmail.com</a></p>
        <p><a href="tel:+919313436916">+91 9313436916</a></p>
      </div>
      <div class="footer-col">
        <h4>Location</h4>
        <p>Ahmedabad, Gujarat, India</p>
        <p>Available for on-site &amp; remote global contracting.</p>
      </div>
    </div>
    <div class="footer-bottom">
      <div>&copy; 2026 Vinay Shishangiya. All rights reserved.</div>
    </div>
  </footer>

  <!-- ===================== FREELANCE POPUP MODAL ===================== -->
  <div class="modal-overlay" id="freelanceModal">
    <div class="modal-card">
      <div class="modal-head">
        <div>
          <span class="vault-badge" style="background:#DCFCE7;color:#15803D;">🟢 AVAILABLE FOR ENGAGEMENT</span>
          <h3 style="margin-top:6px;">Connect with Vinay</h3>
        </div>
        <button class="modal-close" onclick="closeFreelanceModal()">&times;</button>
      </div>
      <p style="font-size:0.86rem;color:var(--text-muted);margin-bottom:16px;">Select your preferred communication channel to discuss design projects:</p>

      <!-- WhatsApp Button -->
      <a href="https://wa.me/919313436916?text=Hi%20Vinay%2C%20I%20reviewed%20your%20mechanical%20design%20portfolio%20and%20would%20like%20to%20discuss%20a%20project." target="_blank" class="contact-channel">
        <div class="channel-icon wa">💬</div>
        <div>
          <b style="color:var(--primary);font-size:0.92rem;display:block;">Chat on WhatsApp</b>
          <span style="font-size:0.8rem;color:var(--text-muted);">Direct message: +91 9313436916</span>
        </div>
      </a>

      <!-- Call Button -->
      <a href="tel:+919313436916" class="contact-channel">
        <div class="channel-icon call">📞</div>
        <div>
          <b style="color:var(--primary);font-size:0.92rem;display:block;">Direct Phone Call</b>
          <span style="font-size:0.8rem;color:var(--text-muted);">Dial: +91 9313436916</span>
        </div>
      </a>

      <!-- Mail Button -->
      <a href="mailto:shishangiyavinay@gmail.com?subject=Mechanical%20Design%20Consultation&body=Hi%20Vinay%2C%0A%0AI%20would%20like%20to%20discuss%20a%20design%20consultation%20with%20you.%0A%0AProject%20Scope%3A" class="contact-channel">
        <div class="channel-icon mail">✉️</div>
        <div>
          <b style="color:var(--primary);font-size:0.92rem;display:block;">Send Formal Email</b>
          <span style="font-size:0.8rem;color:var(--text-muted);">shishangiyavinay@gmail.com</span>
        </div>
      </a>
    </div>
  </div>

  <!-- ===================== REQUEST ACCESS MODAL ===================== -->
  <div class="modal-overlay" id="accessModal">
    <div class="modal-card">
      <div class="modal-head">
        <div>
          <span class="vault-badge">🔒 AUTHORIZATION REQUIRED</span>
          <h3 id="modalAssetTitle" style="margin-top:6px;">Request Resource</h3>
        </div>
        <button class="modal-close" onclick="closeRequestModal()">&times;</button>
      </div>

      <form onsubmit="handleMailRequest(event)">
        <div class="form-group">
          <label>Selected Resource</label>
          <input type="text" id="targetAsset" readonly>
        </div>
        <div class="form-group">
          <label>Your Full Name</label>
          <input type="text" id="reqName" placeholder="e.g. Rahul Sharma" required>
        </div>
        <div class="form-group">
          <label>Your Email</label>
          <input type="email" id="reqEmail" placeholder="e.g. rahul@company.com" required>
        </div>
        <div class="form-group">
          <label>Organization / Company</label>
          <input type="text" id="reqOrg" placeholder="e.g. L&T / Design Studio / VGEC" required>
        </div>
        <div class="form-group">
          <label>Evaluation Purpose</label>
          <textarea id="reqPurpose" placeholder="State your purpose (e.g. Candidate hiring, code evaluation, audit)..." required></textarea>
        </div>
        <div style="display:flex;justify-content:flex-end;gap:10px;">
          <button type="button" class="btn btn-outline" style="color:var(--text-main);border-color:var(--border);" onclick="closeRequestModal()">Cancel</button>
          <button type="submit" class="btn btn-primary">Transmit Request &rarr;</button>
        </div>
      </form>
    </div>
  </div>

  <!-- ===================== JAVASCRIPT LOGIC ===================== -->
  <script>
    const OWNER_EMAIL = "shishangiyavinay@gmail.com";

    // Categories Definition (Without numbers)
    const categories = [
      {
        key: "cat1",
        title: "Orthopedic and Surgical Designs and Development with Reverse Engineering"
      },
      {
        key: "cat2",
        title: "Furniture Design and Store Layout"
      },
      {
        key: "cat3",
        title: "Industrial and Product Design"
      },
      {
        key: "cat4",
        title: "CNC Tooling & Automation"
      }
    ];

    // All Case Studies (Without numbers in titles)
    const caseStudies = [
      // Orthopedic and Surgical
      {
        id: "va-screw",
        title: "VA Locking Head Screw — Self-Tapping",
        catKey: "cat1",
        desc: "Variable-angle locking screw design study: bone-cutting self-tapping tip, flute geometry, flush seating, and biocompatible material requirements.",
        viewId: "view-cs-1-1"
      },
      {
        id: "cervical-plate",
        title: "Cervical Plate",
        catKey: "cat1",
        desc: "Anterior cervical plate matched to lordosis curvature, anatomy-driven screw angulation, and low-profile smooth edges reducing soft-tissue irritation.",
        viewId: "view-cs-1-2"
      },
      {
        id: "surgical-instruments",
        title: "Surgical Instruments",
        catKey: "cat1",
        desc: "Drivers, holders, and guides engineered for unambiguous engagement under gloved hands, autoclave durability, and low-snag cleaning surfaces.",
        viewId: "view-cs-1-3"
      },
      {
        id: "cervical-spacer",
        title: "Cervical Spacer",
        catKey: "cat1",
        desc: "Cervical interbody spacer balancing immediate mechanical stability with bone fusion graft windows, plus PEEK vs. titanium radiographic studies.",
        viewId: "view-cs-1-4"
      },

      // Furniture Design and Store Layout
      {
        id: "store-interior",
        title: "Store Interior — Shelving, Display Unit & Cabinet",
        catKey: "cat2",
        desc: "Integrated store fit-out: wall-mounted shelving deflection analysis, weighted display sightline reach, and cabinet joinery DFM batch cutting.",
        viewId: "view-cs-2-1"
      },

      // Industrial and Product Design
      {
        id: "coal-transport",
        title: "Coal Transportation Management System",
        catKey: "cat3",
        desc: "Conveyor layout handling abrasive bulk coal, incline repose limits, transfer-chute wear plate optimization, and structural gantry sizing.",
        viewId: "view-cs-3-1"
      },
      {
        id: "bicycle-design",
        title: "Bicycle Design",
        catKey: "cat3",
        desc: "Tubular frame geometry, steel vs. aluminium trade-offs, and critical weld-joint load margin verification against pedaling, braking, and impact.",
        viewId: "view-cs-3-2"
      },

      // CNC Tooling & Automation
      {
        id: "cnc-tooling",
        title: "Tool Design & Wire-Cut CNC Manufacturing",
        catKey: "cat4",
        desc: "End-to-end tooling workflow: 2D AutoCAD profile detailing, kerf offsets, multi-pass EDM path programming, and live wire tension monitoring.",
        viewId: "view-cs-4-1"
      },
      {
        id: "cabinet-macro",
        title: "SolidWorks Macro Automation — Cabinet Assembly",
        catKey: "cat4",
        desc: "Master VBA automation macro with custom UserForm generating individual part files and assembling them automatically with precise clearance gaps.",
        viewId: "view-cs-4-2"
      }
    ];

    // Render Projects Grouped Under Each Category Block
    function renderProjectsGrouped(filter = 'all') {
      const container = document.getElementById('projectsCategoryContainer');
      if (!container) return;

      const catsToRender = filter === 'all' 
        ? categories 
        : categories.filter(c => c.key === filter);

      container.innerHTML = catsToRender.map(cat => {
        const catProjects = caseStudies.filter(p => p.catKey === cat.key);
        if (catProjects.length === 0) return '';

        return `
          <div class="category-section-block">
            <div class="category-section-header">
              <h3>${cat.title}</h3>
            </div>
            <div class="projects-grid">
              ${catProjects.map(cs => `
                <div class="project-card" onclick="switchView('${cs.viewId}')">
                  <div>
                    <h4>${cs.title}</h4>
                    <p>${cs.desc}</p>
                  </div>
                  <span class="proj-link">Read Case Study &rarr;</span>
                </div>
              `).join('')}
            </div>
          </div>
        `;
      }).join('');
    }

    function filterProjects(key) {
      document.querySelectorAll('.tab-btn').forEach(b => {
        b.classList.toggle('active', b.getAttribute('data-filter') === key);
      });
      renderProjectsGrouped(key);
    }

    // Single-Page Scroll Navigator (sections stay in the DOM; this just scrolls to them)
    function switchView(viewId) {
      const target = document.getElementById(viewId.startsWith('view-') ? viewId : 'view-' + viewId);
      if (target) target.scrollIntoView({ behavior: 'smooth', block: 'start' });

      const navKey = viewId.replace('view-', '').replace('cs-', '');
      document.querySelectorAll('.navlinks button').forEach(b => {
        b.classList.toggle('active', b.getAttribute('data-view') === navKey);
      });
    }

    // Attach Click Handlers
    document.querySelectorAll('[data-view]').forEach(btn => {
      btn.addEventListener('click', () => switchView(btn.getAttribute('data-view')));
    });

    document.querySelectorAll('.tab-btn').forEach(btn => {
      btn.addEventListener('click', () => {
        document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
        btn.classList.add('active');
        renderProjectsGrouped(btn.getAttribute('data-filter'));
      });
    });

    // Freelance Modal
    function openFreelanceModal() {
      document.getElementById('freelanceModal').classList.add('active');
    }
    function closeFreelanceModal() {
      document.getElementById('freelanceModal').classList.remove('active');
    }

    // Access Request Modal
    function openRequestModal(type, fullName) {
      const modal = document.getElementById('accessModal');
      document.getElementById('modalAssetTitle').innerText = 'Request Access: ' + type;
      document.getElementById('targetAsset').value = fullName;
      modal.classList.add('active');
    }
    function closeRequestModal() {
      document.getElementById('accessModal').classList.remove('active');
    }

    window.addEventListener('click', (e) => {
      if (e.target === document.getElementById('accessModal')) closeRequestModal();
      if (e.target === document.getElementById('freelanceModal')) closeFreelanceModal();
    });

    // Handle Mail Request
    function handleMailRequest(e) {
      e.preventDefault();
      const asset = document.getElementById('targetAsset').value;
      const name = document.getElementById('reqName').value.trim();
      const email = document.getElementById('reqEmail').value.trim();
      const org = document.getElementById('reqOrg').value.trim();
      const purpose = document.getElementById('reqPurpose').value.trim();

      const subject = encodeURIComponent(`[Access Request] ${asset} - ${name}`);
      const body = encodeURIComponent(
        `Hello Vinay,\n\nI would like to request authorized access to:\nResource: ${asset}\n\nRequester Details:\n- Name: ${name}\n- Email: ${email}\n- Organization / Client: ${org}\n- Purpose: ${purpose}\n\n(Vinay: just hit Reply on this email to send the file straight to ${email})\n\nBest regards,\n${name}`
      );

      window.location.href = `mailto:${OWNER_EMAIL}?subject=${subject}&body=${body}`;
      closeRequestModal();
    }

    // Handle Direct Contact
    function handleDirectContact(e) {
      e.preventDefault();
      const name = document.getElementById('directName').value.trim();
      const email = document.getElementById('directEmail').value.trim();
      const msg = document.getElementById('directMsg').value.trim();

      const subject = encodeURIComponent(`[Engineering Consultation] From ${name}`);
      const body = encodeURIComponent(
        `Hello Vinay,\n\nInquiry received from portfolio:\nName: ${name}\nEmail: ${email}\n\nScope:\n${msg}\n\nBest regards,\n${name}`
      );

      window.location.href = `mailto:${OWNER_EMAIL}?subject=${subject}&body=${body}`;
    }

    document.addEventListener('DOMContentLoaded', () => {
      renderProjectsGrouped('all');
    });
  </script>
</body>
</html>

