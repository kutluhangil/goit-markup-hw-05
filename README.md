<h1>GOIT Markup Homework #05 — Forms & Modal</h1>

<p>
  This homework implements <strong>accessible forms</strong> (newsletter in footer + application form inside a modal)
  and a fully styled <strong>modal dialog</strong> with a backdrop.
  All styles live in <code>css/styles.css</code>, assets in <code>images/</code>, icons in an SVG sprite
  (<code>images/icons.svg</code>). The project uses semantic HTML, <strong>modern-normalize</strong>, and
  <strong>Prettier</strong>.
</p>

<p><strong>Live Demo:</strong> <a href="#" target="_blank" rel="noopener">https://kutluhangil.github.io/goit-markup-hw-05/</a></p>

<hr>

<h2>📚 Table of Contents</h2>
<ol>
  <li><a href="#about">About the Project</a></li>
  <li><a href="#acceptance">Acceptance Criteria (Mentor Checklist)</a></li>
  <li><a href="#modal">Modal Window Requirements</a></li>
  <li><a href="#forms">Forms Requirements</a></li>
  <li><a href="#design">Design & Interactions</a></li>
  <li><a href="#structure">Project Structure</a></li>
  <li><a href="#validation">Validation & Formatting</a></li>
  <li><a href="#setup">How to Run</a></li>
</ol>

<hr>

<h2 id="about">📖 About the Project</h2>
<ul>
  <li>Footer <strong>newsletter subscription form</strong> with labeled inputs, placeholder text, and submit button.</li>
  <li><strong>Modal dialog</strong> containing an application form. Dialog opens by toggling <code>is-open</code> on the backdrop.</li>
  <li><strong>SVG sprite</strong> (<code>images/icons.svg</code>) holds all inline icons, including form/checkbox icons.</li>
  <li>Focus/hover visual states and smooth transitions specified by the style guide.</li>
</ul>

<hr>

<h2 id="acceptance">✅ Acceptance Criteria (Mentor Checklist)</h2>

<h3>A. Project</h3>
<ul>
  <li><strong>A1</strong> — All styles are written in a single file: <code>css/styles.css</code>.</li>
  <li><strong>A2</strong> — Source code is formatted with <strong>Prettier</strong>.</li>
  <li><strong>A3</strong> — All images and text are taken from the layout.</li>
  <li><strong>A4</strong> — <strong>modern-normalize</strong> is enabled.</li>
  <li><strong>A5</strong> — Code follows the guidelines.</li>
</ul>

<hr>

<h2 id="modal">🪟 Modal Window Requirements</h2>
<ul>
  <li><strong>B1</strong> — Backdrop (semi-transparent dark overlay) is styled.</li>
  <li><strong>B2</strong> — Backdrop covers <code>100%</code> of viewport width & height and is fixed.</li>
  <li><strong>B3</strong> — Modal dialog is fully styled.</li>
  <li><strong>B4</strong> — Modal is vertically & horizontally centered within the backdrop.</li>
  <li><strong>B5</strong> — A styled close button is placed at the top-right of the modal.</li>
  <li><strong>B6</strong> — By default, backdrop and modal are hidden.</li>
  <li><strong>B7</strong> — Adding <code>.is-open</code> to the backdrop makes both backdrop and modal visible.</li>
</ul>

<hr>

<h2 id="forms">📝 Forms Requirements</h2>
<ul>
  <li><strong>C1</strong> — All layout elements are properly marked up in HTML.</li>
  <li><strong>C2</strong> — Semantic tags are used according to meaning.</li>
  <li><strong>C3</strong> — Footer newsletter form (and its elements) is fully marked up.</li>
  <li><strong>C4</strong> — Application form inside the modal (and all elements) is fully marked up.</li>
  <li><strong>C5</strong> — Every input has a <code>name</code> attribute.</li>
  <li><strong>C6</strong> — <code>name</code> values clearly describe the purpose of each field.</li>
  <li><strong>C7</strong> — Each input is associated with a <code>&lt;label&gt;</code> (via <code>for</code>/<code>id</code>).</li>
  <li><strong>C8</strong> — If the layout shows hint text, inputs have <code>placeholder</code> attributes.</li>
  <li><strong>C9</strong> — The email input includes <code>placeholder="E-mail"</code>.</li>
  <li><strong>C10</strong> — Submit buttons have <code>type="submit"</code>.</li>
  <li><strong>C11</strong> — Any new form icons are added to the SVG sprite (<code>images/icons.svg</code>).</li>
</ul>

<hr>

<h2 id="design">🎨 Design & Interactions</h2>
<ul>
  <li><strong>D1</strong> — Footer newsletter form elements are fully styled.</li>
  <li><strong>D2</strong> — Modal’s application form elements are fully styled.</li>
  <li><strong>D3</strong> — On input focus, the border and icon color change (as per design).</li>
  <li><strong>D4</strong> — The legal-agreement checkbox’s native control is visually hidden.</li>
  <li><strong>D5</strong> — The custom checkbox is designed using an SVG checkmark from the sprite.</li>
  <li><strong>D6</strong> — All hover/focus transitions use <code>250ms</code> and
      <code>cubic-bezier(0.4, 0, 0.2, 1)</code>, with explicit properties (no <code>all</code>).</li>
</ul>

<hr>

<h2 id="structure">📁 Project Structure</h2>
<pre><code>.
├─ index.html
├─ css/
│  └─ styles.css
├─ images/
│  ├─ icons.svg      ← SVG sprite (form icons, checkbox tick, etc.)
│  └─ ...            ← raster/vector assets
└─ README.md
</code></pre>

<hr>

<h2 id="validation">🧪 Validation & Formatting</h2>
<ul>
  <li>Format with <strong>Prettier</strong>.</li>
  <li>Enable <strong>modern-normalize</strong> (CDN or local).</li>
  <li>Ensure <strong>every input</strong> has a label and descriptive <code>name</code>.</li>
  <li>Check keyboard focus states for all interactive controls (accessibility).</li>
  <li>Verify transitions and focus/hover styles match the mockup.</li>
</ul>

<hr>

<h2 id="setup">🚀 How to Run</h2>
<ol>
  <li>Open <code>index.html</code> in your browser.</li>
  <li>Ensure <code>css/styles.css</code> is linked and <code>images/icons.svg</code> contains used icon IDs.</li>
  <li>Toggle the modal by adding/removing <code>.is-open</code> on the backdrop element.</li>
  <li>Publish via GitHub Pages (Settings → Pages) and add the live link in the repo’s About section.</li>
</ol>

<hr>

<p><em>Tips:</em> Keep labels explicitly bound to inputs, hide native checkbox accessibly (not display:none), and animate only intended properties for performance.</p>
