<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Alarcón</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet" />
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: "Inter", sans-serif;
      background: #fff;
      color: #111;
      max-width: 600px;
      margin: 0 auto;
      padding: 80px 24px;
      line-height: 1.6;
    }

    h1 { font-size: 2rem; font-weight: 700; margin-bottom: 6px; }

    .sub { font-size: 14px; color: #888; margin-bottom: 32px; }

    p { font-size: 15px; color: #444; margin-bottom: 12px; }

    .divider { border: none; border-top: 1px solid #eee; margin: 36px 0; }

    h2 {
      font-size: 12px;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 0.1em;
      color: #999;
      margin-bottom: 16px;
    }

    ul { list-style: none; display: flex; flex-direction: column; gap: 8px; }

    ul li { font-size: 15px; color: #333; padding-left: 16px; position: relative; }

    ul li::before { content: "→"; position: absolute; left: 0; color: #ccc; }

    .footer { margin-top: 48px; font-size: 13px; color: #bbb; }
  </style>
</head>
<body>

  <h1>Hey, I'm Alarcón 👋</h1>
  <p class="sub">Full Stack Developer in progress · Spain 🇪🇸</p>

  <p>I'm currently learning full stack development from scratch. No portfolio yet — but I show up every day and put in the work.</p>
  <p>Driven by results. Long-term thinker. Open to junior opportunities and internships.</p>

  <hr class="divider" />

  <h2>Currently learning</h2>
  <ul>
    <li>HTML & CSS</li>
    <li>JavaScript</li>
    <li>React — coming next</li>
    <li>Node.js & databases — on the roadmap</li>
  </ul>

  <hr class="divider" />

  <h2>A bit about me</h2>
  <ul>
    <li>Based in Spain</li>
    <li>Obsessed with work and results</li>
    <li>I will outwork almost anyone</li>
    <li>Open to junior roles and internships</li>
  </ul>

  <p class="footer">This profile is a work in progress. So am I.</p>

</body>
</html>
