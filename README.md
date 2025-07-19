# html-css
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>HTML CSS Page</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
    }

    header {
      background-color: #333;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    nav {
      background-color: #444;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .content {
      padding: 40px;
      text-align: center;
    }

    .content h2 {
      color: #333;
    }

    .content p {
      color: #555;
      font-size: 18px;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 15px 0;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>

  <header>
    <h1>My HTML CSS Page</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>

  <div class="content">
    <h2>Welcome!</h2>
    <p>This is a simple webpage designed using HTML and CSS.</p>
  </div>

  <footer>
    &copy; 2025 My Website
  </footer>

</body>
</html>
