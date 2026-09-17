# My-Achievements
Mechanical Design Engineer working across orthopedic implants &amp; surgical instruments, store/furniture design and aerodynamic parts — from concept through DFM, BOM &amp; GD&amp;T-ready drawings, with 2D tool design and hands-on wire-cut CNC programming and operation.
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Vinay Shishangiya — Mechanical Design Engineer</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&family=IBM+Plex+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --paper:#EDEFF2; --paper-2:#E1E5EA; --ink:#14181F; --ink-soft:#4A5260;
    --blueprint:#2F5D8A; --blueprint-light:#7FA8C9; --accent:#D4551C;
    --dark:#171B22; --dark-2:#1F2530;
    --line:rgba(47,93,138,0.28); --line-soft:rgba(47,93,138,0.14);
    --ok:#3E8E5C;
    --radius:2px;
    --sans:'IBM Plex Sans', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
    --head:'Space Grotesk', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
  }
  @media (prefers-color-scheme: dark){
    :root:not([data-theme="light"]){
      --paper:#12151B; --paper-2:#181C24; --ink:#E7E9ED; --ink-soft:#A7AFBC;
      --blueprint:#7FA8C9; --blueprint-light:#4A6E93; --accent:#E36A32;
      --dark:#0B0D11; --dark-2:#0F131A; --line:rgba(127,168,201,0.28); --line-soft:rgba(127,168,201,0.12);
    }
  }
  :root[data-theme="dark"]{
    --paper:#12151B; --paper-2:#181C24; --ink:#E7E9ED; --ink-soft:#A7AFBC;
    --blueprint:#7FA8C9; --blueprint-light:#4A6E93; --accent:#E36A32;
    --dark:#0B0D11; --dark-2:#0F131A; --line:rgba(127,168,201,0.28); --line-soft:rgba(127,168,201,0.12);
  }
  *{box-sizing:border-box;}
  html{scroll-behavior:smooth;}
  body{margin:0;background:var(--paper);color:var(--ink);font-family:var(--sans);font-size:16px;line-height:1.6;-webkit-font-smoothing:antialiased;}
  a{color:var(--blueprint);}
  button{font-family:inherit;cursor:pointer;}
  @media (prefers-reduced-motion: reduce){
    *{animation-duration:.001ms !important; transition-duration:.001ms !important;}
  }
  .frame{max-width:1180px;margin:0 auto;border-left:1px solid var(--line);border-right:1px solid var(--line);position:relative;min-height:100vh;}
  .topnav{position:sticky;top:0;z-index:30;display:flex;align-items:center;justify-content:space-between;gap:16px;padding:14px 28px;background:rgba(237,239,242,0.86);backdrop-filter:blur(10px);border-bottom:1px solid var(--line);}
  @media (prefers-color-scheme:dark){ .topnav{background:rgba(18,21,27,0.86);} }
  :root[data-theme="dark"] .topnav{background:rgba(18,21,27,0.86);}
  .brand{font-family:var(--head);font-weight:700;font-size:1.15rem;letter-spacing:.02em;color:var(--ink);flex:0 0 auto;}
  .brand span{color:var(--accent);}
  .navlinks{display:flex;gap:4px;flex-wrap:wrap;}
  .navlinks button{background:none;border:none;color:var(--ink-soft);font-size:.86rem;font-family:var(--head);letter-spacing:.02em;padding:8px 12px;border-radius:var(--radius);position:relative;transition:color .18s ease;}
  .navlinks button:hover{color:var(--ink);}
  .navlinks button.active{color:var(--blueprint);}
  .navlinks button.active::after{content:"";position:absolute;left:12px;right:12px;bottom:2px;height:2px;background:var(--accent);}
  .badge-freelance{flex:0 0 auto;display:inline-flex;align-items:center;gap:7px;font-family:var(--head);font-size:.72rem;letter-spacing:.06em;color:var(--ok);border:1px solid var(--line);padding:6px 11px;border-radius:20px;white-space:nowrap;}
  .badge-freelance .dot{width:7px;height:7px;border-radius:50%;background:var(--ok);box-shadow:0 0 0 0 rgba(62,142,92,.5);animation:pulse 2.2s infinite;}
  @keyframes pulse{0%{box-shadow:0 0 0 0 rgba(62,142,92,.45);}70%{box-shadow:0 0 0 7px rgba(62,142,92,0);}100%{box-shadow:0 0 0 0 rgba(62,142,92,0);}}
  .view{display:none;}
  .view.is-active{display:block;animation:viewIn .5s ease both;}
  @keyframes viewIn{from{opacity:0;transform:translateY(14px);}to{opacity:1;transform:translateY(0);}}
  .reveal{opacity:0;transform:translateY(18px);transition:opacity .6s ease, transform .6s ease;}
  .reveal.in{opacity:1;transform:translateY(0);}
  .hero{position:relative;background:linear-gradient(var(--line-soft) 1px, transparent 1px) 0 0/40px 40px, linear-gradient(90deg, var(--line-soft) 1px, transparent 1px) 0 0/40px 40px, var(--dark);color:#EDEFF2;padding:76px 40px 40px;overflow:hidden;}
  .hero::before{content:"";position:absolute;inset:0;background:radial-gradient(ellipse 60% 55% at 78% 20%, rgba(212,85,28,0.16), transparent 70%);pointer-events:none;}
  .hero-kicker{font-family:var(--head);font-size:13px;letter-spacing:.08em;color:var(--blueprint-light);margin:0 0 18px;opacity:0;animation:fadeUp .6s ease .05s forwards;}
  .hero-name{font-family:var(--head);font-weight:700;font-size:clamp(2.4rem,6.6vw,4.8rem);line-height:.98;margin:0 0 6px;letter-spacing:-0.01em;opacity:0;animation:fadeUp .7s ease .18s forwards;}
  .hero-role{font-size:clamp(1.05rem,2.2vw,1.4rem);color:#C7CDD6;max-width:680px;margin:0 0 34px;font-weight:400;opacity:0;animation:fadeUp .7s ease .32s forwards;}
  @keyframes fadeUp{from{opacity:0;transform:translateY(16px);}to{opacity:1;transform:translateY(0);}}
  .titleblock{border:1px solid var(--line);background:rgba(237,239,242,0.03);display:grid;grid-template-columns:repeat(4,1fr);max-width:760px;opacity:0;animation:fadeUp .7s ease .46s forwards;}
  .titleblock .cell{padding:12px 16px;border-right:1px solid var(--line);border-top:1px solid var(--line);}
  .titleblock .cell:nth-child(4n){border-right:none;}
  .titleblock .cell:nth-child(-n+4){border-top:none;}
  .titleblock .label{display:block;font-family:var(--head);font-size:10.5px;letter-spacing:.09em;color:var(--blueprint-light);margin-bottom:4px;}
  .titleblock .val{font-size:13px;color:#EDEFF2;}
  .hero-ctas{margin-top:28px;display:flex;gap:12px;flex-wrap:wrap;opacity:0;animation:fadeUp .7s ease .58s forwards;}
  .btn{font-family:var(--head);font-size:.85rem;letter-spacing:.03em;padding:11px 20px;border-radius:var(--radius);border:1px solid var(--line);background:transparent;color:inherit;display:inline-flex;align-items:center;gap:8px;transition:transform .18s ease, border-color .18s ease, background .18s ease;}
  .btn:hover{transform:translateY(-2px);border-color:var(--accent);}
  .btn-solid{background:var(--accent);border-color:var(--accent);color:#fff;}
  .btn-solid:hover{background:#B84A19;}
  .sheet{display:flex;border-bottom:1px solid var(--line);background:var(--paper);}
  .sheet.alt{background:var(--paper-2);}
  .sheet-tab{flex:0 0 90px;padding:34px 0 34px 22px;border-right:1px solid var(--line);}
  .sheet-tab .code{writing-mode:vertical-rl;text-orientation:mixed;font-family:var(--head);font-size:12px;letter-spacing:.14em;color:var(--blueprint);font-weight:600;}
  .sheet-body{flex:1;padding:36px 40px 44px;min-width:0;}
  .sheet-title{font-family:var(--head);font-weight:600;font-size:1.8rem;margin:0 0 16px;color:var(--ink);}
  .sheet-lede{max-width:66ch;color:var(--ink-soft);font-size:1rem;margin:0 0 8px;}
  .work-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:16px;margin-top:22px;}
  .work-card{border:1px solid var(--line);background:var(--paper);padding:22px;text-align:left;transition:transform .22s ease, box-shadow .22s ease, border-color .22s ease;position:relative;overflow:hidden;}
  .work-card::before{content:"";position:absolute;left:0;top:0;bottom:0;width:3px;background:var(--accent);transform:scaleY(0);transform-origin:top;transition:transform .25s ease;}
  .work-card:hover{transform:translateY(-4px);box-shadow:0 14px 28px -18px rgba(20,24,31,.35);border-color:var(--blueprint-light);}
  .work-card:hover::before{transform:scaleY(1);}
  .work-card .tag{font-family:var(--head);font-size:10px;letter-spacing:.09em;color:var(--blueprint);display:block;margin-bottom:10px;}
  .work-card h3{font-family:var(--head);font-size:1.1rem;margin:0 0 8px;}
  .work-card p{color:var(--ink-soft);font-size:.88rem;margin:0 0 14px;}
  .work-card .go{font-family:var(--head);font-size:.8rem;color:var(--accent);display:inline-flex;align-items:center;gap:6px;}
  .work-card .go .arrow{transition:transform .2s ease;}
  .work-card:hover .go .arrow{transform:translateX(4px);}
  .strip{display:grid;grid-template-columns:repeat(auto-fit,minmax(190px,1fr));border-top:1px solid var(--line);border-left:1px solid var(--line);margin-top:8px;}
  .strip-cell{border-right:1px solid var(--line);border-bottom:1px solid var(--line);padding:20px;}
  .strip-cell .n{font-family:var(--head);font-size:11px;color:var(--blueprint);letter-spacing:.08em;display:block;margin-bottom:8px;}
  .strip-cell b{display:block;font-size:.95rem;margin-bottom:4px;}
  .strip-cell span.d{font-size:.83rem;color:var(--ink-soft);}
  .spec-grid{display:grid;grid-template-columns:repeat(2,1fr);border-top:1px solid var(--line);border-left:1px solid var(--line);margin-top:8px;}
  .spec-cell{border-right:1px solid var(--line);border-bottom:1px solid var(--line);padding:18px 20px;}
  .spec-cell .param{font-family:var(--head);font-size:10.5px;letter-spacing:.09em;color:var(--blueprint);display:block;margin-bottom:8px;}
  .chip-row{display:flex;flex-wrap:wrap;gap:8px;}
  .chip{border:1px solid var(--line);padding:4px 10px;font-size:.82rem;border-radius:var(--radius);color:var(--ink);background:var(--paper);}
  .back-link{display:inline-flex;align-items:center;gap:6px;font-family:var(--head);font-size:.82rem;color:var(--blueprint);margin-bottom:18px;background:none;border:none;padding:0;}
  .back-link:hover{color:var(--accent);}
  .proj-meta-row{display:flex;gap:8px;flex-wrap:wrap;margin:14px 0 22px;}
  .research p{max-width:70ch;color:var(--ink);font-size:.97rem;margin:0 0 14px;}
  .param-table{width:100%;border-collapse:collapse;margin:18px 0 6px;}
  .param-table th{text-align:left;font-family:var(--head);font-size:10.5px;letter-spacing:.08em;color:var(--blueprint);padding:0 14px 8px 0;border-bottom:1px solid var(--line);}
  .param-table td{padding:12px 14px 12px 0;border-bottom:1px solid var(--line-soft);font-size:.9rem;vertical-align:top;}
  .photo-section-title{font-family:var(--head);font-size:.85rem;letter-spacing:.06em;color:var(--blueprint);margin:30px 0 12px;}
  .photo-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:12px;}
  .photo-slot{border:1.5px dashed var(--line);background:var(--line-soft);min-height:150px;display:flex;align-items:center;justify-content:center;text-align:center;padding:14px;color:var(--blueprint);font-family:var(--head);font-size:11px;letter-spacing:.05em;}
  .resume-box{border:1px solid var(--line);padding:30px;max-width:560px;margin-top:20px;background:var(--paper);}
  .resume-box h3{font-family:var(--head);margin:0 0 8px;font-size:1.2rem;}
  .resume-box p{color:var(--ink-soft);font-size:.92rem;margin:0 0 20px;}
  .resume-includes{list-style:none;padding:0;margin:0 0 22px;}
  .resume-includes li{font-size:.86rem;padding:7px 0;border-bottom:1px solid var(--line-soft);color:var(--ink);}
  #resumeStatus{margin-top:12px;font-size:.82rem;color:var(--ink-soft);min-height:18px;}
  .footer{background:var(--dark);color:#EDEFF2;padding:52px 40px 34px;}
  .footer-title{font-family:var(--head);font-weight:700;font-size:clamp(1.7rem,3.6vw,2.4rem);margin:0 0 10px;}
  .footer-sub{color:#A7AFBC;max-width:56ch;margin:0 0 30px;}
  .contact-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(190px,1fr));gap:1px;background:var(--line);border:1px solid var(--line);margin-bottom:36px;}
  .contact-cell{background:var(--dark);padding:18px 20px;}
  .contact-cell .label{display:block;font-family:var(--head);font-size:10px;letter-spacing:.09em;color:var(--blueprint-light);margin-bottom:8px;}
  .contact-cell a,.contact-cell span.val{color:#EDEFF2;text-decoration:none;font-size:.94rem;}
  .contact-cell a:hover{color:var(--accent);}
  .footer-meta{margin-top:36px;padding-top:16px;border-top:1px solid var(--line);display:flex;justify-content:space-between;font-size:.76rem;color:#6B7280;flex-wrap:wrap;gap:8px;}
  .inquiry-box{border:1px solid var(--line);background:rgba(237,239,242,0.03);padding:28px;max-width:640px;}
  .inquiry-box h3{font-family:var(--head);margin:0 0 6px;font-size:1.15rem;color:#EDEFF2;}
  .inquiry-box p.note{color:#A7AFBC;font-size:.84rem;margin:0 0 20px;}
  .field{margin-bottom:14px;}
  .field label{display:block;font-family:var(--head);font-size:10.5px;letter-spacing:.07em;color:var(--blueprint-light);margin-bottom:6px;}
  .field input, .field textarea{width:100%;background:rgba(255,255,255,0.04);border:1px solid var(--line);color:#EDEFF2;padding:10px 12px;font-family:var(--sans);font-size:.92rem;border-radius:var(--radius);}
  .field textarea{min-height:90px;resize:vertical;}
  .field input:focus, .field textarea:focus{outline:2px solid var(--accent);outline-offset:1px;}
  @media (max-width:760px){
    .topnav{padding:12px 16px;flex-wrap:wrap;}
    .navlinks{order:3;width:100%;justify-content:flex-start;}
    .sheet{flex-direction:column;}
    .sheet-tab{flex-direction:row;width:100%;padding:14px 22px;border-right:none;border-bottom:1px solid var(--line);}
    .sheet-tab .code{writing-mode:horizontal-tb;}
    .sheet-body{padding:24px 20px 32px;}
    .spec-grid{grid-template-columns:1fr;}
    .titleblock{grid-template-columns:repeat(2,1fr);}
    .titleblock .cell:nth-child(2n){border-right:none;}
    .titleblock .cell:nth-child(n+3){border-top:1px solid var(--line);}
    .hero{padding:56px 20px 28px;}
    .footer{padding:36px 20px 24px;}
  }
</style>
</head>
<body>
<div class="frame">

  <nav class="topnav">
    <div class="brand">VS<span>.</span></div>
    <div class="navlinks">
      <button data-view="home" class="active">Home</button>
      <button data-view="work">Work</button>
      <button data-view="skills">Skills</button>
      <button data-view="resume">Resume</button>
      <button data-view="contact">Contact</button>
    </div>
    <div class="badge-freelance"><span class="dot"></span>Available for freelance</div>
  </nav>

  <!-- ===================== HOME ===================== -->
  <section class="view is-active" id="view-home">
    <div class="hero">
      <p class="hero-kicker">MECHANICAL DESIGN &nbsp;·&nbsp; MEDICAL DEVICES &nbsp;·&nbsp; FREELANCE OPEN</p>
      <h1 class="hero-name">Vinay<br>Shishangiya</h1>
      <p class="hero-role">Mechanical Design Engineer working across orthopedic implants &amp; surgical instruments, store/furniture design and aerodynamic parts — from concept through DFM, BOM &amp; GD&amp;T-ready drawings, with 2D tool design and hands-on wire-cut CNC programming and operation.</p>
      <div class="titleblock">
        <div class="cell"><span class="label">BASED IN</span><span class="val">Ahmedabad, India</span></div>
        <div class="cell"><span class="label">CAD / CAE</span><span class="val">SolidWorks · AutoCAD · Ansys</span></div>
        <div class="cell"><span class="label">MFG</span><span class="val">Wire-Cut CNC — Design, Program &amp; Operate</span></div>
        <div class="cell"><span class="label">STATUS</span><span class="val">Full-time + Freelance</span></div>
      </div>
      <div class="hero-ctas">
        <button class="btn btn-solid" data-view="work">See selected work</button>
        <button class="btn" data-view="resume">Download resume</button>
        <button class="btn" data-view="contact">Get in touch</button>
      </div>
    </div>

    <section class="sheet">
      <div class="sheet-tab"><span class="code">WHAT I DO</span></div>
      <div class="sheet-body">
        <h2 class="sheet-title reveal">Design, documented and manufacturing-ready</h2>
        <p class="sheet-lede reveal">A mix of design engineering and teaching means the work is careful on both ends — the model and the drawing, and the explanation behind each decision.</p>
        <div class="strip reveal">
          <div class="strip-cell"><span class="n">01</span><b>Orthopedic &amp; Surgical Design</b><span class="d">Implants and surgical instruments</span></div>
          <div class="strip-cell"><span class="n">02</span><b>Store &amp; Furniture Design</b><span class="d">Shelving, display units, cabinetry</span></div>
          <div class="strip-cell"><span class="n">03</span><b>Technical Documentation</b><span class="d">DFM, BOM, GD&amp;T-compliant drawings</span></div>
          <div class="strip-cell"><span class="n">04</span><b>CNC Tool Design &amp; Operation</b><span class="d">2D AutoCAD tool design, wire-cut programming &amp; machine operation</span></div>
        </div>
      </div>
    </section>

    <section class="sheet alt">
      <div class="sheet-tab"><span class="code">SELECTED WORK</span></div>
      <div class="sheet-body">
        <h2 class="sheet-title reveal">Case studies</h2>
        <p class="sheet-lede reveal">Each project below has the research behind the design and a section for renders &amp; photos.</p>
        <div class="work-grid reveal" id="homeWorkGrid"></div>
      </div>
    </section>
  </section>

  <!-- ===================== WORK (list) ===================== -->
  <section class="view" id="view-work">
    <section class="sheet">
      <div class="sheet-tab"><span class="code">SHEET D — WORK</span></div>
      <div class="sheet-body">
        <h2 class="sheet-title">Selected Work</h2>
        <p class="sheet-lede">Mechanical design case studies — from research and calculations through to manufacturing-ready documentation.</p>
        <div class="work-grid" id="workGrid"></div>
      </div>
    </section>
  </section>

  <!-- ===================== PROJECT: COAL ===================== -->
  <section class="view" id="view-proj-coal"><section class="sheet"><div class="sheet-body" style="padding-top:34px;">
    <button class="back-link" data-view="work">&larr; Back to work</button>
    <span class="tag" style="font-family:var(--head);font-size:10px;letter-spacing:.09em;color:var(--blueprint);">MECHANICAL SYSTEM DESIGN · 2025</span>
    <h2 class="sheet-title" style="margin-top:10px;">Coal Transportation Management System</h2>
    <div class="proj-meta-row"><span class="chip">SolidWorks</span><span class="chip">System Layout</span><span class="chip">Bulk Material Handling</span></div>
    <div class="research">
      <p>The brief was to design a system for moving coal reliably from stockpile to point of use, with the usual constraints of bulk material handling: abrasive wear on contact surfaces, dust generation, spillage at transfer points, and a layout that fits an existing plant footprint.</p>
      <p>The research phase looked at conveyor geometry and incline limits for the material's angle of repose, transfer-chute design to reduce spillage and impact wear, and where wear-resistant liner plates were worth the added cost versus a standard mild-steel chute. Structural sizing for supports and gantries followed from expected belt loading plus a margin for surge loads.</p>
      <p>The output was a full system layout modelled in SolidWorks, with supporting calculations for belt capacity, drive sizing and structural loading, documented for direct hand-off to fabrication.</p>
    </div>
    <table class="param-table"><thead><tr><th>Parameter</th><th>Consideration</th></tr></thead><tbody>
      <tr><td>Material handled</td><td>Coal (bulk, abrasive)</td></tr>
      <tr><td>Key risks addressed</td><td>Spillage, dust, liner wear, surge loading</td></tr>
      <tr><td>Deliverables</td><td>System layout, structural calculations, fabrication drawings</td></tr>
    </tbody></table>
    <p class="photo-section-title">PHOTOS &amp; RENDERS</p>
    <div class="photo-grid">
      <div class="photo-slot">SYSTEM LAYOUT<br>— add render —</div>
      <div class="photo-slot">CAD MODEL<br>— add screenshot —</div>
      <div class="photo-slot">SITE / SETUP PHOTO<br>— add photo —</div>
      <div class="photo-slot">DETAIL / DRAWING<br>— add image —</div>
    </div>
  </div></section></section>

  <!-- ===================== PROJECT: STORE / FURNITURE ===================== -->
  <section class="view" id="view-proj-store"><section class="sheet"><div class="sheet-body" style="padding-top:34px;">
    <button class="back-link" data-view="work">&larr; Back to work</button>
    <span class="tag" style="font-family:var(--head);font-size:10px;letter-spacing:.09em;color:var(--blueprint);">STORE &amp; FURNITURE DESIGN</span>
    <h2 class="sheet-title" style="margin-top:10px;">Store Interior — Shelving, Display Unit &amp; Cabinet</h2>
    <div class="proj-meta-row"><span class="chip">SolidWorks</span><span class="chip">DFM</span><span class="chip">Cost Estimation</span></div>
    <div class="research">
      <p>A full store fit-out rather than a single piece: wall-mounted shelving, a central display unit and a storage cabinet, designed as one coordinated system rather than three unrelated pieces of furniture.</p>
      <p>The shelving study covered wall-anchor and bracket selection against expected product load, and shelf-span limits to keep deflection within an acceptable range for the panel material chosen. The display unit was designed around sightlines and reach — height and depth set so products stay visible and reachable from the aisle, with a base heavy enough to stay stable when loaded on one side.</p>
      <p>The cabinet went through a joinery and hardware study — comparing screw-and-dowel construction against systems hardware (soft-close hinges, drawer slides) for durability versus cost — and the whole set was reviewed for DFM so panels could be batch-cut and assembled on-site without custom fitting per unit, alongside a material and finish cost estimate.</p>
    </div>
    <table class="param-table"><thead><tr><th>Parameter</th><th>Consideration</th></tr></thead><tbody>
      <tr><td>Elements</td><td>Wall shelving, display unit, storage cabinet</td></tr>
      <tr><td>Study areas</td><td>Wall load/anchoring, shelf-span deflection, sightlines &amp; reach</td></tr>
      <tr><td>Deliverables</td><td>DFM-reviewed drawings, hardware BOM, cost estimate</td></tr>
    </tbody></table>
    <p class="photo-section-title">PHOTOS &amp; RENDERS</p>
    <div class="photo-grid">
      <div class="photo-slot">STORE LAYOUT<br>— add render —</div>
      <div class="photo-slot">SHELVING CAD<br>— add screenshot —</div>
      <div class="photo-slot">DISPLAY UNIT<br>— add photo —</div>
      <div class="photo-slot">CABINET DETAIL<br>— add photo —</div>
    </div>
  </div></section></section>

  <!-- ===================== PROJECT: CNC TOOLING ===================== -->
  <section class="view" id="view-proj-cnc"><section class="sheet"><div class="sheet-body" style="padding-top:34px;">
    <button class="back-link" data-view="work">&larr; Back to work</button>
    <span class="tag" style="font-family:var(--head);font-size:10px;letter-spacing:.09em;color:var(--blueprint);">TOOL DESIGN &amp; WIRE-CUT CNC</span>
    <h2 class="sheet-title" style="margin-top:10px;">Tool Design &amp; Wire-Cut CNC Manufacturing</h2>
    <div class="proj-meta-row"><span class="chip">AutoCAD 2D</span><span class="chip">CNC Programming</span><span class="chip">Wire-Cut EDM</span></div>
    <div class="research">
      <p>End-to-end tooling work: the cutting tool's profile is designed in 2D AutoCAD first, then turned into a wire-cut EDM program, and the machine is set up and run in-house rather than handed off to a separate operator.</p>
      <p>The 2D design stage accounts for the things that only matter once the tool is actually cut — kerf compensation for wire diameter, achievable corner radii, and profile tolerances the tool needs to hold in service. From there the cutting path is planned: entry points, cutting sequence, and where a multi-pass strategy (rough pass plus a finish skim pass) is worth the extra time for a better surface finish or tighter tolerance.</p>
      <p>On the machine side, that includes wire tension and dielectric fluid setup, and monitoring the cut in progress rather than just starting the program and walking away — catching a drifting cut early is cheaper than scrapping a finished tool.</p>
    </div>
    <table class="param-table"><thead><tr><th>Parameter</th><th>Consideration</th></tr></thead><tbody>
      <tr><td>Design stage</td><td>2D tool profile in AutoCAD, kerf compensation, corner radii</td></tr>
      <tr><td>Programming</td><td>Cutting sequence, multi-pass (rough + finish) strategy</td></tr>
      <tr><td>Operation</td><td>Machine setup, wire tension, in-process monitoring</td></tr>
    </tbody></table>
    <p class="photo-section-title">PHOTOS &amp; RENDERS</p>
    <div class="photo-grid">
      <div class="photo-slot">2D TOOL DRAWING<br>— add drawing —</div>
      <div class="photo-slot">MACHINE SETUP<br>— add photo —</div>
      <div class="photo-slot">FINISHED TOOL<br>— add photo —</div>
      <div class="photo-slot">CNC PROGRAM<br>— add screenshot —</div>
    </div>
  </div></section></section>

  <!-- ===================== PROJECT: VA LOCKING HEAD SCREW ===================== -->
  <section class="view" id="view-proj-screw"><section class="sheet"><div class="sheet-body" style="padding-top:34px;">
    <button class="back-link" data-view="work">&larr; Back to work</button>
    <span class="tag" style="font-family:var(--head);font-size:10px;letter-spacing:.09em;color:var(--blueprint);">ORTHOPEDIC IMPLANT</span>
    <h2 class="sheet-title" style="margin-top:10px;">VA Locking Head Screw — Self-Tapping</h2>
    <div class="proj-meta-row"><span class="chip">SolidWorks</span><span class="chip">GD&amp;T</span><span class="chip">Surgical Grade Materials</span></div>
    <div class="research">
      <p>A variable-angle (VA) locking screw has to do two jobs at once: cut its own thread into bone on insertion, and then lock securely into the plate hole at whatever angle the surgeon chose — not just at one fixed angle.</p>
      <p>The design study covered the self-tapping tip and flute geometry for consistent bone-cutting without excessive insertion torque, and the head geometry that lets the screw engage the plate's locking thread across its full angular range while still seating flush. Tolerances on the locking-thread interface were treated as critical-to-function, since too loose a fit undermines the angular stability the whole VA system is built around, and material selection followed standard implant-grade requirements for strength and biocompatibility.</p>
    </div>
    <table class="param-table"><thead><tr><th>Parameter</th><th>Consideration</th></tr></thead><tbody>
      <tr><td>Function</td><td>Self-tapping insertion + variable-angle locking</td></tr>
      <tr><td>Critical features</td><td>Head locking-thread interface, cutting flute geometry</td></tr>
      <tr><td>Material</td><td>Implant-grade metal (biocompatible, per standard requirements)</td></tr>
    </tbody></table>
    <p class="photo-section-title">PHOTOS &amp; RENDERS</p>
    <div class="photo-grid">
      <div class="photo-slot">CAD MODEL<br>— add render —</div>
      <div class="photo-slot">DRAWING / GD&amp;T<br>— add image —</div>
      <div class="photo-slot">MANUFACTURED PART<br>— add photo —</div>
    </div>
  </div></section></section>

  <!-- ===================== PROJECT: CERVICAL PLATE ===================== -->
  <section class="view" id="view-proj-plate"><section class="sheet"><div class="sheet-body" style="padding-top:34px;">
    <button class="back-link" data-view="work">&larr; Back to work</button>
    <span class="tag" style="font-family:var(--head);font-size:10px;letter-spacing:.09em;color:var(--blueprint);">ORTHOPEDIC IMPLANT</span>
    <h2 class="sheet-title" style="margin-top:10px;">Cervical Plate</h2>
    <div class="proj-meta-row"><span class="chip">SolidWorks</span><span class="chip">Anatomical Contouring</span><span class="chip">GD&amp;T</span></div>
    <div class="research">
      <p>An anterior cervical plate sits directly against the front of the spine, so its shape has to follow the natural curve of the neck (cervical lordosis) rather than sit as a flat piece of metal — a poor contour match is both a fit problem and a soft-tissue irritation risk.</p>
      <p>The study focused on plate contouring to match typical cervical curvature, screw-hole spacing and angulation to line up with vertebral body anatomy across the levels the plate spans, and keeping the overall profile as low and smooth-edged as practical to minimise irritation to the esophagus and surrounding tissue. Screw holes carried a locking feature so screws couldn't back out once seated, consistent with standard anterior cervical plate designs.</p>
    </div>
    <table class="param-table"><thead><tr><th>Parameter</th><th>Consideration</th></tr></thead><tbody>
      <tr><td>Geometry</td><td>Contour matched to cervical lordosis</td></tr>
      <tr><td>Screw holes</td><td>Spacing/angulation per vertebral anatomy, locking feature</td></tr>
      <tr><td>Profile</td><td>Low-profile, smooth edges to reduce soft-tissue irritation</td></tr>
    </tbody></table>
    <p class="photo-section-title">PHOTOS &amp; RENDERS</p>
    <div class="photo-grid">
      <div class="photo-slot">CAD MODEL<br>— add render —</div>
      <div class="photo-slot">DRAWING<br>— add image —</div>
      <div class="photo-slot">MANUFACTURED PART<br>— add photo —</div>
    </div>
  </div></section></section>

  <!-- ===================== PROJECT: SURGICAL INSTRUMENTS ===================== -->
  <section class="view" id="view-proj-instruments"><section class="sheet"><div class="sheet-body" style="padding-top:34px;">
    <button class="back-link" data-view="work">&larr; Back to work</button>
    <span class="tag" style="font-family:var(--head);font-size:10px;letter-spacing:.09em;color:var(--blueprint);">ORTHOPEDIC IMPLANT</span>
    <h2 class="sheet-title" style="margin-top:10px;">Surgical Instruments</h2>
    <div class="proj-meta-row"><span class="chip">SolidWorks</span><span class="chip">Ergonomics</span><span class="chip">Sterilizable Materials</span></div>
    <div class="research">
      <p>Instruments designed to accompany implant systems — drivers, holders and guides — where the design problem is less about strength and more about a reliable interface: the instrument has to engage the implant the same way, every time, under gloved hands and without a clear line of sight.</p>
      <p>The study covered grip ergonomics for one-handed and two-handed use under surgical gloves, the driver-to-screw and holder-to-implant interface tolerances needed for positive, unambiguous engagement, and material selection for repeated autoclave sterilization without corrosion or dimensional drift. Working surfaces were kept simple and low-snag by design, since anything that can trap tissue or resist cleaning is a functional defect in a surgical instrument, not just a cosmetic one.</p>
    </div>
    <table class="param-table"><thead><tr><th>Parameter</th><th>Consideration</th></tr></thead><tbody>
      <tr><td>Interface</td><td>Driver/holder-to-implant engagement tolerances</td></tr>
      <tr><td>Ergonomics</td><td>Gloved-hand grip, one- and two-handed use</td></tr>
      <tr><td>Material</td><td>Autoclave-sterilizable, corrosion-resistant</td></tr>
    </tbody></table>
    <p class="photo-section-title">PHOTOS &amp; RENDERS</p>
    <div class="photo-grid">
      <div class="photo-slot">CAD MODEL<br>— add render —</div>
      <div class="photo-slot">DRAWING<br>— add image —</div>
      <div class="photo-slot">MANUFACTURED SET<br>— add photo —</div>
    </div>
  </div></section></section>

  <!-- ===================== PROJECT: CERVICAL SPACER ===================== -->
  <section class="view" id="view-proj-spacer"><section class="sheet"><div class="sheet-body" style="padding-top:34px;">
    <button class="back-link" data-view="work">&larr; Back to work</button>
    <span class="tag" style="font-family:var(--head);font-size:10px;letter-spacing:.09em;color:var(--blueprint);">ORTHOPEDIC IMPLANT</span>
    <h2 class="sheet-title" style="margin-top:10px;">Cervical Spacer</h2>
    <div class="proj-meta-row"><span class="chip">SolidWorks</span><span class="chip">Interbody Design</span><span class="chip">Material Trade-off Study</span></div>
    <div class="research">
      <p>A cervical interbody spacer sits between two vertebrae after disc removal, holding the disc space open at the right height and angle while bone grows through it to fuse the segment — so it has to be mechanically stable immediately and biologically permeable over time.</p>
      <p>The study covered endplate contact geometry sized for stability against the vertebral endplates without subsiding into the bone, a graft window sized to allow enough bone-graft material through for fusion, and a comparison of lordotic-angle options to restore natural neck curvature at the treated level. Material choice weighed PEEK against titanium on stiffness match to bone, radiographic visibility, and the option of adding radiographic markers so the spacer's position is checkable on X-ray after surgery.</p>
    </div>
    <table class="param-table"><thead><tr><th>Parameter</th><th>Consideration</th></tr></thead><tbody>
      <tr><td>Function</td><td>Disc-height restoration + bone fusion pathway</td></tr>
      <tr><td>Geometry</td><td>Endplate contact area, graft window, lordotic angle options</td></tr>
      <tr><td>Material</td><td>PEEK vs. titanium trade-off, radiographic markers</td></tr>
    </tbody></table>
    <p class="photo-section-title">PHOTOS &amp; RENDERS</p>
    <div class="photo-grid">
      <div class="photo-slot">CAD MODEL<br>— add render —</div>
      <div class="photo-slot">DRAWING<br>— add image —</div>
      <div class="photo-slot">MANUFACTURED PART<br>— add photo —</div>
    </div>
  </div></section></section>

  <!-- ===================== PROJECT: BICYCLE ===================== -->
  <section class="view" id="view-proj-bicycle"><section class="sheet"><div class="sheet-body" style="padding-top:34px;">
    <button class="back-link" data-view="work">&larr; Back to work</button>
    <span class="tag" style="font-family:var(--head);font-size:10px;letter-spacing:.09em;color:var(--blueprint);">PRODUCT DESIGN</span>
    <h2 class="sheet-title" style="margin-top:10px;">Bicycle Design</h2>
    <div class="proj-meta-row"><span class="chip">SolidWorks</span><span class="chip">Frame Geometry</span><span class="chip">Load Analysis</span></div>
    <div class="research">
      <p>Frame design sits at the intersection of ride feel and structural reliability — the same triangle of tubes has to feel right to ride and survive years of pedaling, braking and impact loads without failing at a weld joint.</p>
      <p>The study covered frame geometry — head-tube and seat-tube angles and their effect on handling and rider position — alongside a tube material and cross-section comparison (steel versus aluminium) for weight, stiffness and cost. Weld-joint locations were checked against expected load cases (pedaling, braking, and impact) with margin built in at the highest-stress junctions, and rider fit and ergonomics were checked against standard sizing ranges before finalising dimensions.</p>
    </div>
    <table class="param-table"><thead><tr><th>Parameter</th><th>Consideration</th></tr></thead><tbody>
      <tr><td>Geometry</td><td>Head-tube/seat-tube angles, rider fit</td></tr>
      <tr><td>Material</td><td>Steel vs. aluminium trade-off</td></tr>
      <tr><td>Structural check</td><td>Pedaling, braking &amp; impact load cases at weld joints</td></tr>
    </tbody></table>
    <p class="photo-section-title">PHOTOS &amp; RENDERS</p>
    <div class="photo-grid">
      <div class="photo-slot">FRAME CAD<br>— add render —</div>
      <div class="photo-slot">GEOMETRY DRAWING<br>— add image —</div>
      <div class="photo-slot">BUILT BICYCLE<br>— add photo —</div>
    </div>
  </div></section></section>

  <!-- ===================== SKILLS ===================== -->
  <section class="view" id="view-skills">
    <section class="sheet">
      <div class="sheet-tab"><span class="code">SHEET C — SPECS</span></div>
      <div class="sheet-body">
        <h2 class="sheet-title">Skills &amp; Capabilities</h2>
        <div class="spec-grid">
          <div class="spec-cell"><span class="param">CAD SOFTWARE</span><div class="chip-row"><span class="chip">SolidWorks</span><span class="chip">AutoCAD</span><span class="chip">Solid Edge</span></div></div>
          <div class="spec-cell"><span class="param">SIMULATION / CAE</span><div class="chip-row"><span class="chip">Ansys</span></div></div>
          <div class="spec-cell"><span class="param">DESIGN PRACTICE</span><div class="chip-row"><span class="chip">DFM</span><span class="chip">BOM</span><span class="chip">GD&amp;T</span><span class="chip">Technical Drawings</span><span class="chip">Cost Estimation</span></div></div>
          <div class="spec-cell"><span class="param">MANUFACTURING</span><div class="chip-row"><span class="chip">2D AutoCAD Tool Design</span><span class="chip">Wire-Cut CNC Programming</span><span class="chip">CNC Machine Operation</span></div></div>
          <div class="spec-cell"><span class="param">DOMAIN EXPERTISE</span><div class="chip-row"><span class="chip">Orthopedic Implants</span><span class="chip">Surgical Instruments</span><span class="chip">Store &amp; Furniture Design</span><span class="chip">Aerodynamic Parts</span><span class="chip">EV &amp; HV Systems</span></div></div>
          <div class="spec-cell"><span class="param">ADJACENT</span><div class="chip-row"><span class="chip">IoT Overview</span></div></div>
        </div>
      </div>
    </section>
    <section class="sheet alt">
      <div class="sheet-tab"><span class="code">AVAILABILITY</span></div>
      <div class="sheet-body">
        <h2 class="sheet-title">Open to freelance work</h2>
        <p class="sheet-lede">Available for freelance and remote mechanical design projects alongside full-time work — CAD modelling, technical drawings, DFM review, or wire-cut CNC tool design and programming.</p>
        <button class="btn btn-solid" data-view="contact" style="margin-top:14px;">Start a project</button>
      </div>
    </section>
  </section>

  <!-- ===================== RESUME ===================== -->
  <section class="view" id="view-resume">
    <section class="sheet">
      <div class="sheet-tab"><span class="code">SHEET E — RESUME</span></div>
      <div class="sheet-body">
        <h2 class="sheet-title">Resume</h2>
        <p class="sheet-lede">A one-page summary of experience, skills and projects — for anyone who wants the short version.</p>
        <div class="resume-box">
          <h3>Vinay Shishangiya — Resume.pdf</h3>
          <ul class="resume-includes">
            <li>Experience — Monarch Innovation, Healmax Meditech, Prime Engineering</li>
            <li>Core skills — CAD/CAE, DFM, BOM, GD&amp;T, Wire-Cut CNC</li>
            <li>Projects — Coal Transportation, Store Design, Orthopedic Implants, Bicycle Design</li>
            <li>Education &amp; contact details</li>
          </ul>
          <button class="btn btn-solid" id="downloadResumeBtn">Download PDF</button>
          <div id="resumeStatus"></div>
        </div>
      </div>
    </section>
  </section>

  <!-- ===================== CONTACT ===================== -->
  <section class="view" id="view-contact">
    <footer class="footer" style="border-bottom:1px solid var(--line);">
      <h2 class="footer-title">Let's talk shop.</h2>
      <p class="footer-sub">Open to Mechanical Design Engineer roles and freelance / remote design work — CAD, technical drawings, DFM review, wire-cut CNC tool design. Reach out directly, or send a project inquiry below.</p>
      <div class="contact-grid">
        <div class="contact-cell"><span class="label">PHONE</span><a href="tel:+919313436916">+91 93134 36916</a></div>
        <div class="contact-cell"><span class="label">EMAIL</span><a href="mailto:shishangiyavinay@gmail.com">shishangiyavinay@gmail.com</a></div>
        <div class="contact-cell"><span class="label">LINKEDIN</span><a href="https://linkedin.com/in/vinay-shishangiya-70b3543a8" target="_blank" rel="noopener">vinay-shishangiya</a></div>
        <div class="contact-cell"><span class="label">LOCATION</span><span class="val">Ahmedabad, Gujarat, India</span></div>
      </div>

      <div class="inquiry-box">
        <h3>Send a project inquiry</h3>
        <p class="note">This opens your email app with the details filled in, addressed to Vinay — so it lands directly in his inbox (and phone).</p>
        <div class="field"><label for="inqName">Name</label><input type="text" id="inqName" placeholder="Your name"></div>
        <div class="field"><label for="inqEmail">Email</label><input type="email" id="inqEmail" placeholder="you@company.com"></div>
        <div class="field"><label for="inqDetails">Project details</label><textarea id="inqDetails" placeholder="What do you need designed?"></textarea></div>
        <button class="btn btn-solid" id="sendInquiryBtn" type="button">Send inquiry</button>
      </div>

      <div class="footer-meta">
        <span>VINAY SHISHANGIYA — MECHANICAL DESIGN ENGINEER</span>
        <span>OPEN TO FREELANCE &amp; REMOTE WORK</span>
      </div>
    </footer>
  </section>

</div>

<script>
  var projects = [
    {id:"proj-coal", tag:"MATERIAL HANDLING", title:"Coal Transportation Management System", desc:"System layout for bulk coal handling — conveyors, chutes and structural supports."},
    {id:"proj-store", tag:"STORE & FURNITURE", title:"Store Interior — Shelving, Display & Cabinet", desc:"Full store fit-out: wall shelving, a display unit and a storage cabinet."},
    {id:"proj-cnc", tag:"TOOL DESIGN · CNC", title:"Tool Design & Wire-Cut CNC Manufacturing", desc:"2D AutoCAD tool design, wire-cut CNC programming and hands-on machine operation."},
    {id:"proj-screw", tag:"ORTHOPEDIC IMPLANT", title:"VA Locking Head Screw — Self-Tapping", desc:"Self-tapping, variable-angle locking screw design for plate fixation."},
    {id:"proj-plate", tag:"ORTHOPEDIC IMPLANT", title:"Cervical Plate", desc:"Anatomically contoured anterior cervical plate with locking screw holes."},
    {id:"proj-instruments", tag:"ORTHOPEDIC IMPLANT", title:"Surgical Instruments", desc:"Drivers, holders and guides designed for reliable implant engagement."},
    {id:"proj-spacer", tag:"ORTHOPEDIC IMPLANT", title:"Cervical Spacer", desc:"Interbody fusion spacer — endplate geometry, graft window, material study."},
    {id:"proj-bicycle", tag:"PRODUCT DESIGN", title:"Bicycle Design", desc:"Frame geometry, material trade-offs and load-case analysis."}
  ];
  function cardHTML(p){
    return '<button class="work-card" data-view="'+p.id+'" style="text-align:left;">'
      + '<span class="tag">'+p.tag+'</span>'
      + '<h3>'+p.title+'</h3>'
      + '<p>'+p.desc+'</p>'
      + '<span class="go">View case study <span class="arrow">&rarr;</span></span>'
      + '</button>';
  }
  document.getElementById('homeWorkGrid').innerHTML = projects.map(cardHTML).join('');
  document.getElementById('workGrid').innerHTML = projects.map(cardHTML).join('');

  function showView(id){
    document.querySelectorAll('.view').forEach(function(v){ v.classList.remove('is-active'); });
    var target = document.getElementById('view-'+id);
    if(target){ target.classList.add('is-active'); }
    document.querySelectorAll('.navlinks button').forEach(function(b){
      b.classList.toggle('active', b.getAttribute('data-view') === id);
    });
    window.scrollTo({top:0, behavior:'auto'});
    initReveal();
  }
  document.addEventListener('click', function(e){
    var el = e.target.closest('[data-view]');
    if(el){ showView(el.getAttribute('data-view')); }
  });

  var revealObserver = null;
  function initReveal(){
    var els = document.querySelectorAll('.reveal:not(.in)');
    if(!('IntersectionObserver' in window)){ els.forEach(function(el){ el.classList.add('in'); }); return; }
    if(!revealObserver){
      revealObserver = new IntersectionObserver(function(entries){
        entries.forEach(function(entry){ if(entry.isIntersecting){ entry.target.classList.add('in'); revealObserver.unobserve(entry.target); } });
      }, {threshold:0.15});
    }
    els.forEach(function(el){ revealObserver.observe(el); });
  }
  initReveal();

  var RESUME_PDF_BASE64 = "__RESUME_BASE64__";
  function base64ToBytes(base64){
    var binStr = atob(base64);
    var bytes = new Uint8Array(binStr.length);
    for (var i = 0; i < binStr.length; i++){ bytes[i] = binStr.charCodeAt(i); }
    return bytes;
  }
  document.getElementById('downloadResumeBtn').addEventListener('click', async function(){
    var statusEl = document.getElementById('resumeStatus');
    statusEl.textContent = '';
    try{
      var downloads = (window.claude && window.claude.use) ? await window.claude.use('downloads') : null;
      if(!downloads){ statusEl.textContent = "Direct download isn't available in this view — message me and I'll send the PDF over."; return; }
      var bytes = base64ToBytes(RESUME_PDF_BASE64);
      var result = await downloads.save({ filename: 'Vinay_Shishangiya_Resume.pdf', data: bytes });
      statusEl.textContent = result && result.status === 'delivered' ? 'Sent.' : 'Downloaded.';
    }catch(err){
      var code = err && err.code;
      if(code === 'declined'){ statusEl.textContent = ''; }
      else{ statusEl.textContent = "Couldn't download here — message me and I'll send the PDF directly."; }
    }
  });

  document.getElementById('sendInquiryBtn').addEventListener('click', function(){
    var name = document.getElementById('inqName').value.trim();
    var email = document.getElementById('inqEmail').value.trim();
    var details = document.getElementById('inqDetails').value.trim();
    var subject = encodeURIComponent('Project inquiry — ' + (name || 'via portfolio'));
    var body = encodeURIComponent(
      'Name: ' + name + '\n' +
      'Email: ' + email + '\n\n' +
      'Project details:\n' + details
    );
    window.location.href = 'mailto:shishangiyavinay@gmail.com?subject=' + subject + '&body=' + body;
  });
</script>
</body>
</html>
