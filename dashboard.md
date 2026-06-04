<style>
  :root {
    --ink: #172033;
    --muted: #667085;
    --line: #d7dde8;
    --panel: #ffffff;
    --surface: #f5f7fb;
    --accent: #1d7d8f;
    --accent-2: #d79922;
  }

  .dashboard-shell {
    max-width: 980px;
    margin: 0 auto;
    padding: 28px;
    color: var(--ink);
    font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    background:
      linear-gradient(135deg, rgba(29, 125, 143, 0.08), rgba(215, 153, 34, 0.08)),
      var(--surface);
    border: 1px solid var(--line);
    border-radius: 8px;
  }

  .dashboard-heading {
    margin: 0 0 6px;
    font-size: 30px;
    line-height: 1.15;
    letter-spacing: 0;
  }

  .dashboard-subtitle {
    margin: 0 0 24px;
    color: var(--muted);
    font-size: 15px;
  }

  .dashboard-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(190px, 1fr));
    gap: 16px;
  }

  .dashboard-tile {
    display: grid;
    gap: 12px;
    align-content: start;
    min-height: 220px;
    padding: 18px;
    color: var(--ink);
    text-decoration: none;
    background: var(--panel);
    border: 1px solid rgba(23, 32, 51, 0.12);
    border-radius: 8px;
    box-shadow: 0 8px 18px rgba(23, 32, 51, 0.08);
    transform: translateY(0) scale(1);
    transition:
      transform 180ms ease,
      box-shadow 180ms ease,
      border-color 180ms ease,
      background 180ms ease;
  }

  .dashboard-tile:hover {
    transform: translateY(-6px) scale(1.025);
    border-color: rgba(29, 125, 143, 0.48);
    box-shadow: 0 18px 34px rgba(23, 32, 51, 0.14);
  }

  .dashboard-tile:focus-visible {
    outline: 3px solid rgba(29, 125, 143, 0.35);
    outline-offset: 3px;
  }

  .dashboard-tile:active {
    transform: translateY(-1px) scale(0.97);
    animation: tile-click 180ms ease;
  }

  .dashboard-icon-wrap {
    width: 112px;
    aspect-ratio: 1;
    display: grid;
    place-items: center;
    overflow: hidden;
    border-radius: 8px;
    background:
      linear-gradient(145deg, rgba(255, 255, 255, 0.92), rgba(255, 255, 255, 0.48)),
      rgba(255, 255, 255, 0.62);
    border: 1px solid rgba(255, 255, 255, 0.72);
    box-shadow:
      inset 0 1px 0 rgba(255, 255, 255, 0.9),
      inset 0 0 0 1px rgba(23, 32, 51, 0.06),
      0 10px 22px rgba(23, 32, 51, 0.12);
    backdrop-filter: blur(14px) saturate(1.15);
  }

  .dashboard-icon {
    width: 72%;
    height: 72%;
    object-fit: contain;
    transition: transform 220ms ease;
  }

  .dashboard-tile:hover .dashboard-icon {
    transform: scale(1.08) rotate(1.5deg);
  }

  .dashboard-title {
    margin: 0;
    font-size: 18px;
    line-height: 1.25;
    letter-spacing: 0;
  }

  .dashboard-copy {
    margin: 0;
    color: var(--muted);
    font-size: 14px;
    line-height: 1.45;
  }

  .dashboard-cta {
    margin-top: auto;
    color: var(--accent);
    font-size: 13px;
    font-weight: 700;
  }

  @keyframes tile-click {
    0% {
      box-shadow: 0 18px 34px rgba(23, 32, 51, 0.14);
    }
    60% {
      box-shadow: 0 0 0 7px rgba(29, 125, 143, 0.13);
    }
    100% {
      box-shadow: 0 8px 18px rgba(23, 32, 51, 0.08);
    }
  }

  @media (max-width: 560px) {
    .dashboard-shell {
      padding: 18px;
    }

    .dashboard-heading {
      font-size: 24px;
    }

    .dashboard-tile {
      min-height: 196px;
    }

    .dashboard-icon-wrap {
      width: 92px;
    }
  }
</style>

<section class="dashboard-shell" aria-labelledby="dashboard-title">
  <h1 id="dashboard-title" class="dashboard-heading">Workspace Dashboard</h1>
  <p class="dashboard-subtitle">Quick access to core tools and reports.</p>

  <div class="dashboard-grid">
    <a class="dashboard-tile" href="https://muuc.sek-lab.com" aria-label="Open Finance">
      <span class="dashboard-icon-wrap">
        <img class="dashboard-icon" src="./assets/dashboard-icons/finance.svg" alt="" />
      </span>
      <h2 class="dashboard-title">Finance</h2>
      <p class="dashboard-copy">Review balances, forecasts, approvals, and financial snapshots.</p>
      <span class="dashboard-cta">Open</span>
    </a>

    <a class="dashboard-tile" href="https://muuc-upload.sek-lab.com/" aria-label="Open Upload Portal">
      <span class="dashboard-icon-wrap">
        <img class="dashboard-icon" src="./assets/dashboard-icons/upload-portal.svg" alt="" />
      </span>
      <h2 class="dashboard-title">Upload Portal</h2>
      <p class="dashboard-copy">Submit files, receipts, statements, and shared records.</p>
      <span class="dashboard-cta">Open</span>
    </a>

    <a class="dashboard-tile" href="https://muuc-trip.sek-lab.com/" aria-label="Open Trip Organizer">
      <span class="dashboard-icon-wrap">
        <img class="dashboard-icon" src="./assets/dashboard-icons/trip-organizer.svg" alt="" />
      </span>
      <h2 class="dashboard-title">Trip Organizer</h2>
      <p class="dashboard-copy">Plan routes, itineraries, lodging, documents, and dates.</p>
      <span class="dashboard-cta">Open</span>
    </a>

    <a class="dashboard-tile" href="https://muuc.sek-lab.com/treasury-report" aria-label="Open Treasury Report 2025">
      <span class="dashboard-icon-wrap">
        <img class="dashboard-icon" src="./assets/dashboard-icons/treasury-report-2025.svg" alt="" />
      </span>
      <h2 class="dashboard-title">Treasury Report 2025</h2>
      <p class="dashboard-copy">Access annual reporting, treasury figures, and supporting documents.</p>
      <span class="dashboard-cta">Open</span>
    </a>
  </div>
</section>
