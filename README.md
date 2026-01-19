<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Nicolai Phocas — About</title>
  <style>
    :root{--max-width:820px;--accent:#0b5cff;--muted:#555}
    body{margin:0;font-family:system-ui,-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,Arial;background:#ffffff;color:#0b1220}
    .container{max-width:var(--max-width);margin:48px auto;padding:0 20px}
    .center{text-align:center}
    .headshot{width:200px;height:200px;border-radius:50%;object-fit:cover;display:block;margin:18px auto}
    h1{font-size:34px;margin:8px 0}
    p.lead{color:var(--muted);max-width:680px;margin:10px auto 22px;line-height:1.5}

    ul.resume-bullets{list-style:disc;margin:0 auto;padding-left:20px;max-width:640px;text-align:left;font-size:17px}
    ul.resume-bullets li{margin:10px 0}

    .education{display:flex;gap:18px;align-items:center;justify-content:center;margin-top:28px;flex-wrap:wrap}
    .school{display:flex;align-items:center;gap:12px;padding:12px;border-radius:10px;background:#f3f6fb;min-width:260px}
    .school img{height:64px;width:auto;display:block}
    .school img.manoa{height:56px}
    .school .meta{font-size:15px}
    .school .meta strong{display:block}
    .note{color:var(--muted);font-size:13px;margin-top:20px;text-align:center}

    @media (max-width:640px){
      .education{flex-direction:column}
      .school{width:100%;justify-content:flex-start}
    }
  </style>
</head>
<body>
  <div class="container">
    <header class="center">
      <h1>Nicolai Phocas</h1>
      <img src="headshot.jpg" alt="Headshot of Nicolai Phocas" class="headshot" />
      <p class="lead">MBA / MEM candidate at Duke. Climate and energy practitioner with experience in emissions analysis, coalition building, and policy strategy.</p>
    </header>

    <section>
      <ul class="resume-bullets" aria-label="Key points">
        <li>Climate & Energy Lead, Climate Hawai‘i (2024–2025)</li>
        <li>Designed web decision-toolkits and GHG calculators for organization-level decarbonization</li>
        <li>Led stakeholder engagement across government, utilities, and private sector (~200+ participants)</li>
        <li>Skills: Project management, energy modeling, GHG accounting, Python, Excel</li>
      </ul>
    </section>

    <section class="education" aria-label="Education">

      <div class="school">
        <img src="fuqua-logo.svg" alt="Duke Fuqua logo" />
        <div class="meta">
          <strong>Duke University — Fuqua School of Business</strong>
          Master of Business Administration (Expected May 2028)
        </div>
      </div>

      <div class="school">
        <img src="nicholas-logo.jpg" alt="Duke Nicholas School logo" />
        <div class="meta">
          <strong>Duke University — Nicholas School of the Environment</strong>
          Master of Environmental Management (Expected May 2028)
        </div>
      </div>

      <div class="school">
        <img src="manoa-logo.png" alt="University of Hawaii at Manoa logo" class="manoa" />
        <div class="meta">
          <strong>University of Hawaiʻi at Mānoa — SOEST</strong>
          Bachelor of Science in Earth Science (May 2023)
        </div>
      </div>

    </section>

    <div class="note">Logos used here are for factual education context only. Replace or remove if needed.</div>

  </div>
</body>
</html>
