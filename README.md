<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Deepanshu Choudhary | Portfolio</title>
  <style>
    :root {
      --primary: #6366f1;
      --secondary: #a5b4fc;
      --bg: linear-gradient(to right, #eef2ff, #f5f3ff);
      --card-bg: white;
      --text: #111827;
      --accent: #4f46e5;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    header {
      background: linear-gradient(to right, #4f46e5, #6366f1);
      color: white;
      padding: 3rem 1rem;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: .5rem;
    }

    header p {
      font-size: 1.2rem;
      letter-spacing: 1px;
    }

    .container {
      max-width: 1000px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    section {
      background: var(--card-bg);
      border-radius: 12px;
      padding: 2rem;
      margin-bottom: 2rem;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
      transition: transform 0.3s ease;
    }

    section:hover {
      transform: translateY(-3px);
    }

    h2 {
      font-size: 1.8rem;
      color: var(--accent);
      margin-bottom: 1rem;
      position: relative;
    }

    h2::after {
      content: '';
      display: block;
      width: 70px;
      height: 3px;
      background: var(--secondary);
      margin-top: .5rem;
      border-radius: 2px;
    }

    ul {
      list-style: none;
      padding-left: 1rem;
    }

    ul li {
      margin-bottom: .75rem;
      position: relative;
    }

    ul li::before {
      content: '✓';
      color: var(--primary);
      margin-right: 8px;
    }

    .contact-info a {
      color: var(--accent);
      text-decoration: none;
      transition: 0.2s ease;
    }

    .contact-info a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      padding: 2rem 1rem;
      font-size: .9rem;
      background: #e0e7ff;
      border-top: 1px solid #c7d2fe;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Deepanshu Choudhary</h1>
    <p>Full‑Stack Developer in the making 🚀</p>
  </header>

  <div class="container">
    <section id="about">
      <h2>About Me</h2>
      <p>Hello! I'm Deepanshu, an aspiring full‑stack developer passionate about transforming ideas into modern, responsive web apps. Currently learning JavaScript frameworks, backend APIs, and cloud deployment!</p>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <ul>
        <li>HTML, CSS, JavaScript</li>
        <li>Node.js</li>
        <li>MySQL</li>
      </ul>
    </section>

    <section id="education">
      <h2>Education</h2>
      <p>B.Tech in Computer Science – R.D. Engineering College, Duhai, Ghaziabad (2022–2026)</p>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <ul class="contact-info">
        <li>Email: <a href="mailto:deepanshuchoudhary228@gmail.com">deepanshuchoudhary228@gmail.com</a></li>
        <li>LinkedIn: <a href="https://www.linkedin.com/in/deepanshu-choudhary-9b7a24303" target="_blank" rel="noopener">linkedin.com/in/deepanshu-choudhary-9b7a24303</a></li>
      </ul>
    </section>
  </div>

  <footer>
    &copy; 2025 Deepanshu Choudhary. All rights reserved.
  </footer>

</body>
</html>
