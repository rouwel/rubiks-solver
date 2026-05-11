<style>
  body { font-family: sans-serif; max-width: 600px; margin: 2rem auto; color: #111; }
  h1   { font-size: 22px; font-weight: 500; margin: 0; }
  .sub { font-size: 13px; color: #888; margin: 4px 0 1.5rem; }
  .intro { font-size: 15px; color: #555; line-height: 1.7; margin-bottom: 2rem; }

  .section { border-left: 2.5px solid; padding-left: 1.25rem; margin-bottom: 2rem; }
  .section.blue  { border-color: #378ADD; }
  .section.green { border-color: #1D9E75; }
  .label { font-size: 11px; font-weight: 500; text-transform: uppercase;
            letter-spacing: 0.08em; margin: 0 0 4px; }
  .section.blue  .label { color: #378ADD; }
  .section.green .label { color: #1D9E75; }
  h2 { font-size: 18px; font-weight: 500; margin: 0 0 1rem; }

  .card { background: #f5f5f5; border-radius: 8px; padding: 1rem 1.25rem;
           display: flex; gap: 14px; margin-bottom: 10px; }
  .card.warn { border: 0.5px solid #F0997B; background: #fff8f6; }
  .badge { width: 28px; height: 28px; border-radius: 50%; background: #E6F1FB;
            display: flex; align-items: center; justify-content: center;
            flex-shrink: 0; font-size: 13px; font-weight: 500; color: #185FA5; }
  .badge.warn { background: #FAECE7; color: #993C1D; }
  .card p { font-size: 14px; line-height: 1.65; margin: 0; }
</style>

<h1>Rubik's Cube Solver</h1>
<p class="sub">User interface guide</p>
<p class="intro">This guide walks you through using the solver — covering
  how to input your cube's state and how to read the solution output.</p>

<div class="section blue">
  <p class="label">Section 1</p>
  <h2>Input</h2>

  <div class="card">
    <div class="badge">1</div>
    <p>Place the cube with the <strong>white center facing up</strong>,
      then colour in the top face on the interface.</p>
  </div>

  <div class="card">
    <div class="badge">2</div>
    <p>Go around each face in order. <strong>Follow the face order shown</strong>
      — wrong order means wrong results.</p>
  </div>

  <div class="card warn">
    <div class="badge warn">!</div>
    <p>Incorrect inputs can produce a wrong solution or an error.
      Double-check each face before submitting.</p>
  </div>
</div>

<div class="section green">
  <p class="label">Section 2</p>
  <h2>Output</h2>
  <p style="color:#888;">Coming soon.</p>
</div> error.