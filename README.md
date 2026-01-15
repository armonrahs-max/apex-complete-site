<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width,initial-scale=1" />
    <title>Apex Complete</title>
    <meta
      name="description"
      content="Apex Complete connects homeowners and facilities with trusted trades for repairs, installs, and maintenance."
    />
    <style>
      :root { color-scheme: light; }
      body { margin: 0; font-family: Arial, Helvetica, sans-serif; background:#0b1220; color:#eef2ff; }
      a { color: inherit; }
      .wrap { max-width: 980px; margin: 0 auto; padding: 32px 18px 60px; }
      .badge { display:inline-block; padding:8px 12px; border-radius:999px; background:rgba(255,255,255,.08); border:1px solid rgba(255,255,255,.12); font-size:13px; }
      .hero { margin-top: 22px; padding: 28px; border-radius: 18px; background: linear-gradient(135deg, rgba(99,102,241,.25), rgba(34,197,94,.18)); border:1px solid rgba(255,255,255,.12); }
      h1 { margin: 10px 0 10px; font-size: 40px; line-height: 1.1; letter-spacing: -.4px; }
      .sub { font-size: 18px; line-height: 1.5; color: rgba(238,242,255,.88); margin: 0; }
      .ctaRow { display:flex; flex-wrap: wrap; gap: 12px; margin-top: 18px; }
      .btn { display:inline-block; padding: 12px 16px; border-radius: 12px; text-decoration:none; font-weight: 700; }
      .btnPrimary { background:#22c55e; color:#07130c; }
      .btnGhost { background:rgba(255,255,255,.08); border:1px solid rgba(255,255,255,.14); }
      .grid { display:grid; grid-template-columns: repeat(12, 1fr); gap: 14px; margin-top: 18px; }
      .card { grid-column: span 12; padding: 16px; border-radius: 16px; background: rgba(255,255,255,.06); border:1px solid rgba(255,255,255,.10); }
      .card h3 { margin: 0 0 8px; font-size: 16px; }
      .card p { margin: 0; color: rgba(238,242,255,.82); line-height: 1.5; }
      .list { margin: 10px 0 0; padding-left: 18px; color: rgba(238,242,255,.82); }
      .list li { margin: 6px 0; }
      .muted { color: rgba(238,242,255,.70); font-size: 13px; }
      .footer { margin-top: 26px; padding-top: 16px; border-top: 1px solid rgba(255,255,255,.10); display:flex; flex-wrap:wrap; gap:10px; align-items:center; justify-content: space-between; }
      @media (min-width: 740px){
        .card.span6 { grid-column: span 6; }
        .card.span4 { grid-column: span 4; }
      }
    </style>
  </head>

  <body>
    <div class="wrap">
      <div class="badge">Now Live • Coming Soon Updates</div>

      <section class="hero">
        <h1>Apex Complete</h1>
        <p class="sub">
          Connecting <strong>Homeowners</strong> and <strong>Facilities</strong> with trusted <strong>Trades</strong> for repairs,
          installs, and ongoing maintenance — all in one place.
        </p>

        <div class="ctaRow">
          <a class="btn btnPrimary" href="mailto:armonrahs@gmail.com?subject=Apex%20Complete%20-%20Request%20Info">
            Email Us
          </a>
          <a class="btn btnGhost" href="tel:+17138552811">Call Now: (713) 855-2811</a>
          <a class="btn btnGhost" href="#how-it-works">How It Works</a>
          <a class="btn btnGhost" href="#services">Services</a>
        </div>

        <p class="muted" style="margin-top:12px;">
          Launch focus: Colorado • New York • Texas • Ohio
        </p>
      </section>

      <section class="grid" id="how-it-works" aria-label="How it works">
        <div class="card span6">
          <h3>For Homeowners</h3>
          <p>Post a job, compare qualified pros, and get help fast — from small fixes to major upgrades.</p>
          <ul class="list">
            <li>Post jobs in minutes</li>
            <li>Transparent scheduling</li>
            <li>Verified trade profiles</li>
          </ul>
        </div>

        <div class="card span6">
          <h3>For Facilities</h3>
          <p>Streamline maintenance requests across properties with consistent standards and trusted vendors.</p>
          <ul class="list">
            <li>Multi-location support</li>
            <li>Work-order style tracking</li>
            <li>Preferred vendor management</li>
          </ul>
        </div>

        <div class="card span12">
          <h3>For Trades</h3>
          <p>Find real jobs, build your reputation, and grow your business with steady local work.</p>
          <ul class="list">
            <li>Job discovery + bidding</li>
            <li>Profile, credentials, and portfolio</li>
            <li>Scheduling and customer messaging</li>
          </ul>
        </div>
      </section>

      <section class="grid" id="services" aria-label="Services">
        <div class="card span4">
          <h3>Core Trades</h3>
          <p>Plumbing, electrical, carpentry, painting, drywall, flooring, and more.</p>
        </div>
        <div class="card span4">
          <h3>Grounds & Exterior</h3>
          <p>Lawn care, trees, cleanup, fencing, minor exterior repairs.</p>
        </div>
        <div class="card span4">
          <h3>Facilities Maintenance</h3>
          <p>Turns, preventative maintenance, vendor dispatch, and routine service calls.</p>
        </div>
      </section>

      <section class="card" style="margin-top:14px;">
        <h3>Contact</h3>
        <p>
          Email: <a href="mailto:armonrahs@gmail.com?subject=Apex%20Complete%20-%20Inquiry">armonrahs@gmail.com</a><br />
          Phone: <a href="tel:+17138552811">(713) 855-2811</a>
        </p>
      </section>

      <div class="footer">
        <div class="muted">© <span id="y"></span> Apex Complete • All rights reserved</div>
        <div class="muted">Official site: <a href="https://www.apexcomplete.co">www.apexcomplete.co</a></div>
      </div>
    </div>

    <script>
      document.getElementById("y").textContent = new Date().getFullYear();
    </script>
  </body>
</html>
