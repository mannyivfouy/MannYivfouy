
<style>
  @import url('https://fonts.googleapis.com/css2?family=DM+Mono:wght@400;500&family=Instrument+Serif:ital@0;1&family=DM+Sans:wght@300;400;500&display=swap');

  .gh-root { font-family: 'DM Sans', sans-serif; color: var(--color-text-primary); padding: 0; }
  .gh-header { border-bottom: 0.5px solid var(--color-border-tertiary); padding-bottom: 2rem; margin-bottom: 2rem; }
  .gh-name { font-family: 'Instrument Serif', serif; font-size: 42px; font-weight: 400; margin: 0 0 4px; letter-spacing: -1px; line-height: 1.1; }
  .gh-name em { font-style: italic; }
  .gh-handle { font-family: 'DM Mono', monospace; font-size: 13px; color: var(--color-text-secondary); margin: 0 0 16px; }
  .gh-bio { font-size: 15px; color: var(--color-text-secondary); margin: 0 0 20px; max-width: 460px; line-height: 1.6; }
  .gh-meta { display: flex; gap: 20px; flex-wrap: wrap; }
  .gh-meta-item { display: flex; align-items: center; gap: 6px; font-size: 13px; color: var(--color-text-secondary); font-family: 'DM Mono', monospace; }
  .gh-meta-item i { font-size: 14px; }
  
  .section-label { font-family: 'DM Mono', monospace; font-size: 11px; letter-spacing: 0.12em; text-transform: uppercase; color: var(--color-text-tertiary); margin: 0 0 14px; }
  
  .stats-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 12px; margin-bottom: 2rem; }
  .stat-card { background: var(--color-background-secondary); border-radius: var(--border-radius-md); padding: 1rem 1.25rem; }
  .stat-num { font-family: 'Instrument Serif', serif; font-size: 28px; font-weight: 400; line-height: 1; margin-bottom: 4px; }
  .stat-label { font-size: 12px; color: var(--color-text-secondary); font-family: 'DM Mono', monospace; }

  .divider { border: none; border-top: 0.5px solid var(--color-border-tertiary); margin: 2rem 0; }

  .focus-block { margin-bottom: 2rem; }
  .focus-item { display: flex; align-items: flex-start; gap: 14px; padding: 14px 0; border-bottom: 0.5px solid var(--color-border-tertiary); }
  .focus-item:last-child { border-bottom: none; }
  .focus-icon { width: 36px; height: 36px; border-radius: var(--border-radius-md); background: var(--color-background-secondary); display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
  .focus-icon i { font-size: 18px; color: var(--color-text-secondary); }
  .focus-title { font-size: 14px; font-weight: 500; margin-bottom: 2px; }
  .focus-desc { font-size: 13px; color: var(--color-text-secondary); line-height: 1.5; }

  .stack-section { margin-bottom: 2rem; }
  .stack-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(80px, 1fr)); gap: 8px; }
  .stack-chip { background: var(--color-background-secondary); border-radius: var(--border-radius-md); padding: 8px 10px; text-align: center; }
  .stack-name { font-family: 'DM Mono', monospace; font-size: 11px; color: var(--color-text-secondary); }
  .stack-dot { width: 6px; height: 6px; border-radius: 50%; margin: 0 auto 6px; }
  .dot-js { background: #f0db4f; }
  .dot-ts { background: #3178c6; }
  .dot-html { background: #e34f26; }
  .dot-css { background: #1572b6; }
  .dot-ng { background: #dd1b16; }
  .dot-node { background: #339933; }
  .dot-mongo { background: #47a248; }
  .dot-mysql { background: #4479a1; }
  .dot-git { background: #f05032; }
  .dot-fig { background: #f24e1e; }
  .dot-bs { background: #7952b3; }
  .dot-ex { background: #888; }

  .lang-bar-section { margin-bottom: 2rem; }
  .lang-bar-wrap { display: flex; height: 6px; border-radius: 99px; overflow: hidden; gap: 2px; margin-bottom: 14px; }
  .lang-seg { height: 100%; border-radius: 99px; }
  .lang-list { display: grid; grid-template-columns: 1fr 1fr; gap: 8px; }
  .lang-item { display: flex; align-items: center; gap: 8px; font-size: 13px; }
  .lang-dot { width: 8px; height: 8px; border-radius: 50%; flex-shrink: 0; }
  .lang-pct { margin-left: auto; font-family: 'DM Mono', monospace; font-size: 12px; color: var(--color-text-tertiary); }

  .connect-row { display: flex; align-items: center; gap: 12px; }
  .connect-btn { display: inline-flex; align-items: center; gap: 8px; border: 0.5px solid var(--color-border-secondary); border-radius: var(--border-radius-md); padding: 9px 16px; font-size: 13px; font-weight: 500; color: var(--color-text-primary); text-decoration: none; background: transparent; cursor: pointer; font-family: 'DM Sans', sans-serif; transition: background 0.15s; }
  .connect-btn:hover { background: var(--color-background-secondary); }
  .connect-btn i { font-size: 16px; }

  .two-col { display: grid; grid-template-columns: 1fr 1fr; gap: 2rem; }
  @media (max-width: 500px) { .two-col { grid-template-columns: 1fr; } .stats-grid { grid-template-columns: 1fr 1fr; } }
</style>

<div class="gh-root">
  <h2 class="sr-only" style="position:absolute;width:1px;height:1px;overflow:hidden;clip:rect(0,0,0,0)">GitHub profile for Mann Yivfouy, MIS student and web developer</h2>

  <div class="gh-header">
    <p class="gh-handle">@mannyivfouy</p>
    <h1 class="gh-name">Mann Yivfouy</h1>
    <p class="gh-bio">Management Information Systems student at SETEC Institute. Building for the web — full stack, clean code, and thoughtful design.</p>
    <div class="gh-meta">
      <span class="gh-meta-item"><i class="ti ti-building" aria-hidden="true"></i> SETEC Institute</span>
      <span class="gh-meta-item"><i class="ti ti-map-pin" aria-hidden="true"></i> Phnom Penh, Cambodia</span>
      <span class="gh-meta-item"><i class="ti ti-mail" aria-hidden="true"></i> mannyivfouy@gmail.com</span>
    </div>
  </div>

  <div class="stats-grid">
    <div class="stat-card">
      <div class="stat-num">2024</div>
      <div class="stat-label">// joined</div>
    </div>
    <div class="stat-card">
      <div class="stat-num">Web Development</div>
      <div class="stat-label">// focus</div>
    </div>    
  </div>

  <hr class="divider">

  <div class="two-col">
    <div>
      <p class="section-label">Focus areas</p>
      <div class="focus-block">
        <div class="focus-item">
          <div class="focus-icon"><i class="ti ti-layout-2" aria-hidden="true"></i></div>
          <div>
            <div class="focus-title">Frontend</div>
            <div class="focus-desc">Angular, TypeScript, HTML/CSS, Bootstrap</div>
          </div>
        </div>
        <div class="focus-item">
          <div class="focus-icon"><i class="ti ti-server" aria-hidden="true"></i></div>
          <div>
            <div class="focus-title">Backend</div>
            <div class="focus-desc">Node.js, Express, REST APIs</div>
          </div>
        </div>
        <div class="focus-item">
          <div class="focus-icon"><i class="ti ti-database" aria-hidden="true"></i></div>
          <div>
            <div class="focus-title">Databases</div>
            <div class="focus-desc">MongoDB, MySQL</div>
          </div>
        </div>
        <div class="focus-item">
          <div class="focus-icon"><i class="ti ti-vector" aria-hidden="true"></i></div>
          <div>
            <div class="focus-title">Design</div>
            <div class="focus-desc">Figma, UI prototyping</div>
          </div>
        </div>
      </div>
    </div>

    <div>
      <p class="section-label">Languages</p>
      <div class="lang-bar-section">
        <div class="lang-bar-wrap">
          <div class="lang-seg" style="width:38%; background:#3178c6;"></div>
          <div class="lang-seg" style="width:25%; background:#f0db4f;"></div>
          <div class="lang-seg" style="width:18%; background:#e34f26;"></div>
          <div class="lang-seg" style="width:12%; background:#1572b6;"></div>
          <div class="lang-seg" style="width:7%; background:#888;"></div>
        </div>
        <div class="lang-list">
          <div class="lang-item"><span class="lang-dot" style="background:#3178c6"></span>TypeScript<span class="lang-pct">38%</span></div>
          <div class="lang-item"><span class="lang-dot" style="background:#f0db4f"></span>JavaScript<span class="lang-pct">25%</span></div>
          <div class="lang-item"><span class="lang-dot" style="background:#e34f26"></span>HTML<span class="lang-pct">18%</span></div>
          <div class="lang-item"><span class="lang-dot" style="background:#1572b6"></span>CSS<span class="lang-pct">12%</span></div>
          <div class="lang-item"><span class="lang-dot" style="background:#888"></span>Other<span class="lang-pct">7%</span></div>
        </div>
      </div>
    </div>
  </div>

  <hr class="divider">

  <p class="section-label">Tech stack</p>
  <div class="stack-section">
    <div class="stack-grid">
      <div class="stack-chip"><div class="stack-dot dot-js"></div><div class="stack-name">JavaScript</div></div>
      <div class="stack-chip"><div class="stack-dot dot-ts"></div><div class="stack-name">TypeScript</div></div>
      <div class="stack-chip"><div class="stack-dot dot-html"></div><div class="stack-name">HTML5</div></div>
      <div class="stack-chip"><div class="stack-dot dot-css"></div><div class="stack-name">CSS3</div></div>
      <div class="stack-chip"><div class="stack-dot dot-ng"></div><div class="stack-name">Angular</div></div>
      <div class="stack-chip"><div class="stack-dot dot-bs"></div><div class="stack-name">Bootstrap</div></div>
      <div class="stack-chip"><div class="stack-dot dot-node"></div><div class="stack-name">Node.js</div></div>
      <div class="stack-chip"><div class="stack-dot dot-ex"></div><div class="stack-name">Express</div></div>
      <div class="stack-chip"><div class="stack-dot dot-mongo"></div><div class="stack-name">MongoDB</div></div>
      <div class="stack-chip"><div class="stack-dot dot-mysql"></div><div class="stack-name">MySQL</div></div>
      <div class="stack-chip"><div class="stack-dot dot-git"></div><div class="stack-name">Git</div></div>
      <div class="stack-chip"><div class="stack-dot dot-fig"></div><div class="stack-name">Figma</div></div>
    </div>
  </div>

  <hr class="divider">

  <p class="section-label">Connect</p>
  <div class="connect-row">
    <button class="connect-btn" onclick="openLink('mailto:mannyivfouy@gmail.com')"><i class="ti ti-mail" aria-hidden="true"></i> Email</button>
    <button class="connect-btn" onclick="openLink('https://github.com/mannyivfouy')"><i class="ti ti-brand-github" aria-hidden="true"></i> GitHub</button>
  </div>
</div>
