
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Game hub</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 50px;
      background-color: #f0f4f8;
    }
    h1 {
      margin-bottom: 30px;
    }
    .link-group {
      margin-bottom: 40px;
    }
    button {
      font-size: 18px;
      padding: 12px 24px;
      margin: 10px;
      border: none;
      border-radius: 8px;
      background-color: #007BFF;
      color: white;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

  <h1>Flappybird link </h1>

  <div class="link-group">
    <h2>Game Link</h2>
    <button onclick="window.open('https://ayan-web21.github.io/game/', '_blank')">Open Game in New Tab</button>
    <button onclick="window.location.href='https://ayan-web21.github.io/game/'">Open Game in Same Tab</button>
  </div>

  <div class="link-group">
    <h2>Croosroads Link</h2>
    <button onclick="window.open('https://ayan-web21.github.io/croosroads/', '_blank')">Open Croosroads in New Tab</button>
    <button onclick="window.location.href='https://ayan-web21.github.io/croosroads/'">Open Croosroads in Same Tab</button>
  </div>

</body>
</html>
