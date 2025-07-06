<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Search Evolution with MCP</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto+Mono&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #0d1117;
      --text: #c9d1d9;
      --accent: #58a6ff;
      --card: #161b22;
    }
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto Mono', monospace;
    }
    body {
      background-color: var(--bg);
      color: var(--text);
      padding: 2rem;
    }
    h1 {
      font-size: 2rem;
      margin-bottom: 1rem;
      color: var(--accent);
    }
    .banner {
      width: 100%;
      max-height: 300px;
      object-fit: cover;
      border-radius: 10px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.5);
      margin-bottom: 2rem;
    }
    .post-list {
      display: grid;
      gap: 1.5rem;
    }
    .post-card {
      background-color: var(--card);
      padding: 1rem;
      border-radius: 8px;
      transition: transform 0.2s ease;
    }
    .post-card:hover {
      transform: translateY(-5px);
    }
    a {
      color: var(--accent);
      text-decoration: none;
    }
    .footer {
      margin-top: 3rem;
      font-size: 0.8rem;
      text-align: center;
      color: #888;
    }
  </style>
</head>
<body>
  <h1>🔍 Search Evolution with MCP</h1>
  <img src="images/mcp-intro-banner.jpeg" alt="MCP Banner" class="banner" />  <section class="post-list">
    <div class="post-card">
      <h2><a href="blog-posts/part-1-intro-to-MCP.md">📘 Part 1: Introduction to MCP</a></h2>
      <p>What is MCP? How it's different from traditional search engines, and why it's the future.</p>
    </div>
    <div class="post-card">
      <h2><a href="#">📘 Part 2: MCP vs Traditional Search (Coming Soon)</a></h2>
      <p>A deep dive into how MCP compares to traditional search models like Google.</p>
    </div>
  </section>  <div class="footer">
    © 2025 Habib — Built with GitHub Pages | Dark Mode Friendly
  </div>
</body>
</html>
