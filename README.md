# Hug-tothemoon1
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Portfolio</title>
  <style>
    :root {
      --main-color: #000;
      --accent-color: #f29d35;
      --bg-color: #f9f9f9;
      --font: 'Helvetica Neue', sans-serif;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: var(--font);
      background: var(--bg-color);
      color: var(--main-color);
      line-height: 1.6;
    }

    header {
      padding: 60px 20px;
      text-align: center;
      background: white;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.1rem;
      color: #555;
    }

    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 24px;
      background: var(--accent-color);
      color: white;
      text-decoration: none;
      border-radius: 8px;
      transition: background 0.3s;
    }

    .btn:hover {
      background: #e58610;
    }

    section {
      padding: 80px 20px;
      max-width: 1000px;
      margin: 0 auto;
    }

    section h2 {
      font-size: 2rem;
      margin-bottom: 30px;
      text-align: center;
    }

    .about p {
      max-width: 700px;
      margin: 0 auto;
      text-align: center;
    }

    .works {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }

    .work-card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
      padding: 20px;
      text-align: center;
      transition: transform 0.3s;
    }

    .work-card:hover {
      transform: translateY(-5px);
    }

    .work-card img {
      width: 100%;
      border-radius: 6px;
    }

    .contact {
      text-align: center;
    }

    .contact a {
      color: var(--accent-color);
      text-decoration: none;
      margin: 0 10px;
    }

    footer {
      padding: 40px 20px;
      text-align: center;
      font-size: 0.9rem;
      color: #999;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
      section h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Hi, I’m [Your Name]</h1>
    <p>Web制作とデザインで「伝わる」Webを作ります。</p>
    <a href="#works" class="btn">View Work</a>
  </header>

  <section class="about" id="about">
    <h2>About Me</h2>
    <p>
      FigmaとHTML/CSSを使い、スピーディで効率的なWeb制作を行っています。<br/>
      LP制作・バナー制作・Webサイト全体の設計など、幅広く対応可能です。
    </p>
  </section>

  <section class="works" id="works">
    <h2>My Works</h2>
    <div class="works">
      <div class="work-card">
        <img src="https://via.placeholder.com/300x200" alt="Project 1" />
        <h3>LPデザイン制作</h3>
        <p>シンプルで高コンバージョンなランディングページ。</p>
      </div>
      <div class="work-card">
        <img src="https://via.placeholder.com/300x200" alt="Project 2" />
        <h3>バナー制作</h3>
        <p>印象に残るバナーをスピーディに作成。</p>
      </div>
      <div class="work-card">
        <img src="https://via.placeholder.com/300x200" alt="Project 3" />
        <h3>HTMLサイト構築</h3>
        <p>Figmaデザインを忠実にコーディング。</p>
      </div>
    </div>
  </section>

  <section class="contact" id="contact">
    <h2>Contact</h2>
    <p>お気軽にご相談ください。</p>
    <p>
      <a href="mailto:your@email.com">Email</a> |
      <a href="https://twitter.com/yourhandle" target="_blank">Twitter</a>
    </p>
  </section>

  <footer>
    © 2025 [Your Name] - Portfolio
  </footer>

</body>
</html>
