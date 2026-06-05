<style>
  :root {
    --ink: #ffffff;
    --muted: rgba(255, 255, 255, 0.68);
    --line: rgba(255, 255, 255, 0.14);
    --panel: rgba(255, 255, 255, 0.08);
    --surface: #00091d;
    --accent: #ffffff;
    --accent-2: rgba(255, 255, 255, 0.72);
  }

  html,
  body {
    min-height: 100%;
    margin: 0;
    background: var(--surface);
  }

  body {
    padding: 0;
    box-sizing: border-box;
  }

  .dashboard-shell {
    position: relative;
    min-height: 100vh;
    margin: 0;
    padding: 0;
    color: var(--ink);
    font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    background: var(--surface);
    overflow: hidden;
  }

  .dashboard-heading {
    position: absolute;
    z-index: 3;
    top: 28px;
    left: 28px;
    margin: 0;
    font-size: 30px;
    line-height: 1.15;
    letter-spacing: 0;
    text-shadow: 0 2px 14px rgba(0, 0, 0, 0.45);
  }

  .dashboard-subtitle {
    position: absolute;
    z-index: 3;
    top: 68px;
    left: 28px;
    margin: 0;
    color: rgba(255, 255, 255, 0.82);
    font-size: 15px;
    text-shadow: 0 2px 14px rgba(0, 0, 0, 0.45);
  }

  .dashboard-grid {
    display: grid;
    min-height: 100vh;
    grid-template-columns: repeat(4, minmax(0, 1fr));
    gap: 0;
  }

  .dashboard-tile {
    position: relative;
    isolation: isolate;
    box-sizing: border-box;
    display: grid;
    overflow: hidden;
    gap: 14px;
    align-content: center;
    min-height: 100vh;
    padding: 128px 28px 34px;
    color: var(--ink);
    text-decoration: none;
    background: transparent;
    border: 0;
    border-radius: 0;
    box-shadow: none;
    transform: translateY(0) scale(1);
    transition:
      transform 180ms ease,
      filter 180ms ease;
  }

  .dashboard-tile::before {
    position: absolute;
    inset: 0;
    z-index: -2;
    content: "";
    background-image: var(--panel-image);
    background-position: var(--panel-position, center);
    background-repeat: no-repeat;
    background-size: var(--panel-size, cover);
    transform: scale(1.01);
    transition: transform 240ms ease;
  }

  .dashboard-tile::after {
    position: absolute;
    inset: 0;
    z-index: -1;
    content: "";
    background:
      linear-gradient(180deg, rgba(0, 0, 0, 0.1), rgba(0, 0, 0, 0.14) 36%, rgba(0, 0, 0, 0.42)),
      var(--panel-tint);
  }

  .dashboard-tile:hover {
    filter: saturate(1.08) contrast(1.04);
    transform: translateY(0) scale(1);
  }

  .dashboard-tile:hover::before {
    transform: scale(1.06);
  }

  .dashboard-tile.finance-theme {
    --panel-image: url("./assets/backgrounds/finance-underwater.webp");
    --panel-tint: linear-gradient(180deg, rgba(117, 103, 242, 0.1), rgba(45, 24, 105, 0.28));
  }

  .dashboard-tile.finance-theme:hover {
    box-shadow: none;
  }

  .dashboard-tile.finance-theme .dashboard-icon-wrap {
    background:
      linear-gradient(145deg, rgba(255, 255, 255, 0.15), rgba(255, 255, 255, 0.025)),
      rgba(117, 103, 242, 0.055);
    border-color: rgba(255, 255, 255, 0.16);
  }

  .dashboard-tile.upload-theme {
    --panel-image: url("./assets/backgrounds/upload-underwater.jpg");
    --panel-tint: linear-gradient(180deg, rgba(18, 55, 46, 0.08), rgba(10, 40, 34, 0.28));
  }

  .dashboard-tile.upload-theme:hover {
    box-shadow: none;
  }

  .dashboard-tile.upload-theme .dashboard-icon-wrap {
    background:
      linear-gradient(145deg, rgba(255, 255, 255, 0.15), rgba(255, 255, 255, 0.025)),
      rgba(18, 55, 46, 0.055);
    border-color: rgba(255, 255, 255, 0.16);
  }

  .dashboard-tile.trip-theme {
    --panel-image: url("./assets/backgrounds/trip-aerial-ray.webp");
    --panel-position: 42% center;
    --panel-size: cover;
    --panel-tint: linear-gradient(180deg, rgba(56, 182, 200, 0.08), rgba(16, 98, 115, 0.28));
  }

  .dashboard-tile.trip-theme:hover {
    box-shadow: none;
  }

  .dashboard-tile.trip-theme .dashboard-icon-wrap {
    background:
      linear-gradient(145deg, rgba(255, 255, 255, 0.15), rgba(255, 255, 255, 0.025)),
      rgba(56, 182, 200, 0.055);
    border-color: rgba(255, 255, 255, 0.16);
  }

  .dashboard-tile.treasury-theme {
    --panel-image: url("./assets/backgrounds/treasury-underwater.jpg");
    --panel-tint: linear-gradient(180deg, rgba(18, 63, 80, 0.1), rgba(5, 38, 54, 0.28));
  }

  .dashboard-tile.treasury-theme:hover {
    box-shadow: none;
  }

  .dashboard-tile.treasury-theme .dashboard-icon-wrap {
    background:
      linear-gradient(145deg, rgba(255, 255, 255, 0.15), rgba(255, 255, 255, 0.025)),
      rgba(18, 63, 80, 0.055);
    border-color: rgba(255, 255, 255, 0.16);
  }

  .dashboard-tile:focus-visible {
    outline: 3px solid rgba(255, 255, 255, 0.35);
    outline-offset: 3px;
  }

  .dashboard-tile:active {
    transform: scale(0.995);
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
      linear-gradient(145deg, rgba(255, 255, 255, 0.16), rgba(255, 255, 255, 0.025)),
      rgba(255, 255, 255, 0.055);
    border: 1px solid rgba(255, 255, 255, 0.16);
    box-shadow:
      inset 0 1px 0 rgba(255, 255, 255, 0.18),
      inset 0 0 0 1px rgba(255, 255, 255, 0.035),
      0 10px 22px rgba(0, 0, 0, 0.28);
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
    text-shadow: 0 2px 14px rgba(0, 0, 0, 0.5);
  }

  .dashboard-copy {
    margin: 0;
    color: rgba(255, 255, 255, 0.78);
    font-size: 14px;
    line-height: 1.45;
    text-shadow: 0 2px 14px rgba(0, 0, 0, 0.5);
  }

  .dashboard-cta {
    margin-top: auto;
    color: var(--accent);
    font-size: 13px;
    font-weight: 700;
  }

  @keyframes tile-click {
    0% {
      box-shadow: 0 18px 34px rgba(0, 0, 0, 0.28);
    }
    60% {
      box-shadow: 0 0 0 7px rgba(255, 255, 255, 0.12);
    }
    100% {
      box-shadow: 0 8px 18px rgba(0, 0, 0, 0.18);
    }
  }

  @media (max-width: 560px) {
    body {
      padding: 0;
    }

    .dashboard-shell {
      min-height: 100%;
      overflow-x: hidden;
      overflow-y: auto;
    }

    .dashboard-grid {
      min-height: 100%;
      grid-template-columns: 1fr;
    }

    .dashboard-heading {
      top: 20px;
      left: 20px;
      font-size: 24px;
    }

    .dashboard-subtitle {
      top: 52px;
      left: 20px;
      right: 20px;
    }

    .dashboard-tile {
      min-height: 62vh;
      padding: 112px 20px 26px;
    }

    .dashboard-icon-wrap {
      width: 92px;
    }
  }
</style>

<section class="dashboard-shell" aria-labelledby="dashboard-title">
  <h1 id="dashboard-title" class="dashboard-heading">MUUC tools</h1>
  <p class="dashboard-subtitle">Quick access to tools and reports.</p>

  <div class="dashboard-grid">
    <a class="dashboard-tile finance-theme" href="https://muuc.sek-lab.com" aria-label="Open Finance">
      <span class="dashboard-icon-wrap">
        <img class="dashboard-icon" src="./assets/dashboard-icons/finance.svg" alt="" />
      </span>
      <h2 class="dashboard-title">Finance</h2>
      <p class="dashboard-copy">Review club finances, updated monthly.</p>
    </a>

    <a class="dashboard-tile upload-theme" href="https://muuc-upload.sek-lab.com/" aria-label="Open Upload Portal">
      <span class="dashboard-icon-wrap">
        <img class="dashboard-icon" src="./assets/dashboard-icons/upload-portal.svg" alt="" />
      </span>
      <h2 class="dashboard-title">Upload Portal</h2>
      <p class="dashboard-copy">Upload and track your receipts, invoices, refund requests.</p>
    </a>

    <a class="dashboard-tile trip-theme" href="https://trip.muuc.org.au" aria-label="Open Trip Organiser">
      <span class="dashboard-icon-wrap">
        <img class="dashboard-icon" src="./assets/dashboard-icons/trip-organizer.svg" alt="" />
      </span>
      <h2 class="dashboard-title">Trip Organiser</h2>
      <p class="dashboard-copy">Track Memberships, Gear and Boat payments.</p>
    </a>

    <a class="dashboard-tile treasury-theme" href="https://muuc.sek-lab.com/treasury-report" aria-label="Open Treasury Report">
      <span class="dashboard-icon-wrap">
        <img class="dashboard-icon" src="./assets/dashboard-icons/treasury-report-2025.svg" alt="" />
      </span>
      <h2 class="dashboard-title">Treasury Report</h2>
      <p class="dashboard-copy">Access the 2025 Treasury Report.</p>
    </a>
  </div>
</section>
