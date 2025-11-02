---
layout: default
title: "Sana Khatib"
---

<!-- Pastel Pixel Theme (single-file, easy to edit) -->
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&family=Nunito:wght@400;700&display=swap" rel="stylesheet">

<style>
:root{
  --bg: #fbf9ff;
  --ink: #3e3a55;
  --muted:#7a7594;
  --pink:#f6a6cc;
  --blue:#a9c9ff;
  --purple:#c5b4ff;
}
body{ background:
  radial-gradient(40rem 40rem at -10% -10%, var(--blue) 0%, transparent 45%),
  radial-gradient(35rem 35rem at 110% 110%, var(--pink) 0%, transparent 45%),
  linear-gradient(#fff, var(--bg) 60%); }
.wrapper{
  max-width: 880px; margin: 48px auto; background:#fff; border-radius: 16px;
  box-shadow: 0 10px 28px rgba(62,58,85,0.08); padding: 28px 22px;
}
h1{ font-family: "Press Start 2P", system-ui, monospace; font-size: 1.6rem; color:#5f54d6; letter-spacing:.5px; line-height:1.3; }
.subtitle{ color: var(--muted); margin:.6rem 0 1.2rem; }
p, li{ font-family: "Nunito", system-ui, -apple-system, Segoe UI, Roboto, sans-serif; color: var(--ink); font-size:1.05rem; line-height:1.7; }

.badges{ display:flex; flex-wrap:wrap; gap:10px; margin: 10px 0 18px; }
.badge{
  font-family:"Press Start 2P", monospace; font-size:.72rem; letter-spacing:.2px;
  color:#222; text-decoration:none; padding:10px 12px; border-radius:10px;
  background: linear-gradient(135deg, var(--purple), var(--blue));
  box-shadow: 0 6px 16px rgba(98,84,220,0.18);
}
.badge.pink{ background: linear-gradient(135deg, var(--pink), var(--purple)); }

.grid{
  display:grid; gap:14px; grid-template-columns: repeat(auto-fit, minmax(180px,1fr));
  margin: 16px 0 6px;
}
.card{
  background: #fff; border: 2px solid rgba(98,84,220,0.14); border-radius: 12px; padding: 16px;
  box-shadow: 0 6px 14px rgba(62,58,85,0.06); text-align:center;
}
.pixel-emoji{
  font-size: 40px; line-height: 1; display:inline-block; margin-bottom: 8px;
  image-rendering: pixelated; /* keeps the vibe if you replace with small PNGs */
}
.card h3{ margin:.4rem 0 .2rem; font-size:1rem; }
.card p{ margin:.2rem 0 0; color: var(--muted); font-size:.97rem; }

hr{ border:0; height:1px; margin: 18px 0;
  background: linear-gradient(to right, var(--purple), transparent); }

.footer{
  text-align:center; color: var(--muted); font-size:.95rem; margin-top: 14px;
}
</style>

<div class="wrapper">
  <h1>سناء / Sana Khatib</h1>
  <p class="subtitle"><strong>PhD Student, Systems Biology — Weizmann Institute of Science</strong></p>

  <p>
    I study how <strong>transcription factors</strong> and <strong>IDRs</strong> shape gene regulation. I like tidy experiments,
    readable figures, and a pastel pixel aesthetic. Minimalism, but cute. 🐱⚛️
  </p>

  <!-- Quick Links (edit these) -->
  <div class="badges">
    <a class="badge" href="https://github.com/sanakhatib4" target="_blank">GitHub</a>
    <a class="badge pink" href="#" target="_blank">Weizmann Profile</a>
    <a class="badge" href="#" target="_blank">Barkai Lab</a>
    <a class="badge pink" href="mailto:your-email@weizmann.ac.il">Email</a>
  </div>

  <hr />

  <!-- Pixel interest tiles (emoji now; swap with small PNGs later if you want) -->
  ### Pastel Pixel Interests

  <div class="grid">
    <div class="card">
      <div class="pixel-emoji" aria-hidden="true">🐱</div>
      <h3>Cats</h3>
      <p>Soft chaos, sharp insights.</p>
    </div>
    <div class="card">
      <div class="pixel-emoji" aria-hidden="true">🧬</div>
      <h3>Biology</h3>
      <p>TF–DNA, IDRs, clean assays.</p>
    </div>
    <div class="card">
      <div class="pixel-emoji" aria-hidden="true">💬</div>
      <h3>Languages</h3>
      <p>Arabic · English · Hebrew · Korean</p>
    </div>
    <div class="card">
      <div class="pixel-emoji" aria-hidden="true">🤝</div>
      <h3>People</h3>
      <p>Community, teaching, clear science.</p>
    </div>
  </div>

  <hr />

  ### What I’m Into (now)
  - TF–DNA interaction assays (PBM, DAP-seq)  
  - Protein purification & refolding tricks  
  - Data analysis + reproducible, pretty plots

  <div class="footer">
    © {{ site.time | date: "%Y" }} Sana Khatib · pastel pixel theme (blue · pink · purple)
  </div>
</div>
