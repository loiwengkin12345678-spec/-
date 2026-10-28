HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Awesome Website</title>
    <style>
      body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        color: white;
        height: 100vh;
        margin: 0;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
      }
      .card {
        background: rgba(255, 255, 255, 0.15);
        padding: 40px;
        border-radius: 20px;
        backdrop-filter: blur(10px);
        box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
        border: 1px solid rgba(255, 255, 255, 0.18);
      }
      h1 {
        margin-top: 0;
        font-size: 2.5rem;
      }
      p {
        font-size: 1.2rem;
        opacity: 0.9;
      }
    </style>
  </head>
  <body>
    <div class="card">
      <h1>Hello, World! ✨</h1>
      <p>My website is live and looking modern on GitHub Pages!</p>
    </div>
  </body>
</html>
