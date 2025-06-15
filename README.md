<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Open My Links</title>
  <style>
    body {
      display: flex;
      flex-direction: column;
      height: 100vh;
      justify-content: center;
      align-items: center;
      background-color: #f9f9f9;
      font-family: Arial, sans-serif;
    }

    button {
      padding: 1em 2em;
      font-size: 1.1em;
      margin: 10px;
      background-color: #28a745;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    button:hover {
      background-color: #218838;
    }
  </style>
</head>
<body>
  <button onclick="openLink('https://example.com/first')">Open First Link</button>
  <button onclick="openLink('https://example.com/second')">Open Second Link</button>

  <script>
    function openLink(url) {
      window.open(url, "_blank");
    }
  </script>
</body>
</html>
