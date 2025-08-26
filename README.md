<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Project</title>
  <style>
    /* General Reset */
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      background-color: black;   /* full-page black background */
      color: white;
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 20px;
      min-height: 100vh;
    }

    /* Header */
    .header {
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .header-img {
      width: 200px;
      border-radius: 50%;  /* circular */
      margin-bottom: 15px;
      transition: transform 0.3s ease;
    }

    .header-img:hover {
      transform: scale(1.1) rotate(5deg);
    }

    .title {
      font-size: 2.5rem;
      color: #ffcc00;
      text-shadow: 2px 2px 8px #ff0099;
    }

    /* Nav styling */
    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
      justify-content: center;
      margin-top: 15px;
    }

    nav a {
      color: #ffcc00;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease, text-shadow 0.3s ease;
    }

    nav a:hover {
      color: #ff0099;
      text-shadow: 0 0 10px #ff0099;
    }

    /* Main */
    .colorful {
      color: #00ffcc;
      margin-top: 30px;
    }

    .intro {
      margin-top: 10px;
      font-size: 1.2rem;
    }

    /* Footer */
    footer {
      margin-top: 40px;
      font-size: 0.9rem;
      color: #aaa;
    }
  </style>
</head>

<body>
  <header>
    <div class="header">
      <img src="https://static.wikia.nocookie.net/dragonball/images/b/ba/Goku_anime_profile.png" 
           alt="Goku profile" class="header-img">
      <h1 class="title">My Project</h1>
    </div>

    <nav>
      <ul>
        <li><a href="#contact">Contact</a></li>
        <li><a href="#details">Details</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h2 class="colorful">It’s Normal</h2>
    <p class="intro">This is my first website 🚀</p>
  </main>

  <footer>
    <p>&copy; 2024 My Project. All rights reserved.</p>
  </footer>
</body>
</html>
