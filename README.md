<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>PEKOmenu</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <link href="https://fonts.googleapis.com/css2?family=Source+Code+Pro:wght@400;600&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      background: #050805;
      font-family: 'Source Code Pro', monospace;
      color: #cfeedd;
    }

    .wrapper {
      width: 800px;
      margin: 40px auto;
      background: #08120d;

      /* darker border (no white look) */
      border: 1px solid #0e241a;

      border-radius: 8px;

      /* remove harsh glow */
      box-shadow: 0 0 15px rgba(0,0,0,0.7);
    }

    .topbar {
      padding: 10px 15px;
      background: #0b1812;

      /* darker divider */
      border-bottom: 1px solid #0e241a;

      border-radius: 8px 8px 0 0;
      font-size: 14px;
      color: #7ec9a3;
    }

    .title {
      font-weight: 600;
      color: #eafff5;
    }

    .content {
      padding: 10px;
    }

    .section {
      background: #0a1712;

      /* super subtle borders */
      border: 1px solid #0e241a;

      margin-bottom: 10px;
      border-radius: 6px;
    }

    .section-header {
      padding: 6px 10px;
      background: #0d1f17;

      border-bottom: 1px solid #0e241a;

      border-radius: 6px 6px 0 0;
      font-size: 13px;
      color: #6fd0a2;
    }

    .section-content {
      padding: 8px 10px;
      font-size: 13px;
    }

    .item {
      padding: 2px 0;
      color: #bfe8d3;
    }

    .item::before {
      content: "[ ] ";
      color: #3f8f6c;
    }

    .usage {
      background: #07130e;

      border: 1px solid #0e241a;

      padding: 10px;
      font-size: 13px;
      color: #7ec9a3;
      border-radius: 6px;
    }

    .key {
      background: #0e241a;

      /* remove bright edge */
      border: 1px solid #123526;

      padding: 1px 5px;
      color: #ffffff;
      border-radius: 3px;
    }

    /* remove hover glow entirely */
    .wrapper:hover {
      box-shadow: 0 0 15px rgba(0,0,0,0.7);
    }
  </style>
</head>
<body>

  <div class="wrapper">
    <div class="topbar">
      <span class="title">PEKOmenu</span> — GDH-style menu (v1)
    </div>

    <div class="content">

      <div class="section">
        <div class="section-header">Basic Hacks</div>
        <div class="section-content">
          <div class="item">Auto Retry</div>
          <div class="item">Instant Complete</div>
          <div class="item">No Death Effect</div>
          <div class="item">Safe Mode</div>
          <div class="item">Practice Mode</div>
          <div class="item">Death Counter</div>
        </div>
      </div>

      <div class="section">
        <div class="section-header">Speed</div>
        <div class="section-content">
          <div class="item">Speed Hack</div>
          <div class="item">TPS Unlocker</div>
        </div>
      </div>

      <div class="section">
        <div class="section-header">Gameplay</div>
        <div class="section-content">
          <div class="item">Frame Stepper</div>
          <div class="item">Startpos Switcher</div>
        </div>
      </div>

      <div class="section">
        <div class="section-header">Labels</div>
        <div class="section-content">
          <div class="item">Cheat Indicator</div>
          <div class="item">FPS</div>
          <div class="item">Attempts</div>
          <div class="item">Progress</div>
        </div>
      </div>

      <div class="section">
        <div class="section-header">Visuals</div>
        <div class="section-content">
          <div class="item">Hitboxes</div>
          <div class="item">Hide Glow</div>
          <div class="item">Hide Particles</div>
        </div>
      </div>

      <div class="section">
        <div class="section-header">Config</div>
        <div class="section-content">
          <div class="item">Save / Load (JSON)</div>
        </div>
      </div>

      <div class="usage">
        Press <span class="key">Tab</span> to open/close menu
      </div>

    </div>
  </div>

</body>
</html>
