<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My First Website</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f4f4;
    }
    header {
      background: #6a5acd;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #333;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      color: #ffd700;
    }
    .container {
      padding: 30px;
      text-align: center;
    }
    .card {
      background: white;
      padding: 20px;
      margin: 20px auto;
      max-width: 400px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 10px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to My Website</h1>
    <p>This is my first web page 🚀</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Projects</a>
    <a href="#">Contact</a>
  </nav>

  <div class="container">
    <div class="card">
      <h2>About Me</h2>
      <p>Hello! I'm learning web development and this is my first website.</p>
    </div>

    <div class="card">
      <h2>My Goal</h2>
      <p>To become a great developer and build amazing websites 💙</p>
    </div>
  </div>

  <footer>
    <p>© 2026 My Website | Made with ❤️</p>
  </footer>

</body>
</html>
