<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>My Games Hub</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background: #222;
    color: white;
    margin: 0;
    padding: 20px;
    text-align: center;
  }
  h1 {
    margin-bottom: 30px;
  }
  .btn {
    background-color: #28a745;
    border: none;
    padding: 15px 30px;
    margin: 10px;
    color: white;
    font-size: 18px;
    border-radius: 8px;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
  .btn:hover {
    background-color: #218838;
  }
  iframe {
    margin-top: 30px;
    width: 100%;
    max-width: 800px;
    height: 600px;
    border: 3px solid #444;
    border-radius: 8px;
  }
  /* Container for embedded games */
  .game-container {
    margin-top: 40px;
    display: flex;
    flex-direction: column;
    gap: 60px;
    align-items: center;
  }
  .game-frame {
    width: 800px;
    height: 600px;
    border: 3px solid #444;
    border-radius: 8px;
  }
</style>
</head>
<body>

<h1>Welcome to My Games Hub</h1>

<button class="btn" onclick="loadGame('https://ayan-web21.github.io/game/')">Play Flappy Bird</button>
<button class="btn" onclick="loadGame('https://ayan-web21.github.io/croosroads/')">Play Crossroads</button>

<div>
  <iframe id="gameFrame" src="" frameborder="0" allowfullscreen></iframe>
</div>

<h2 style="margin-top:60px;">Or scroll to play both games below:</h2>
<div class="game-container">
  <div>
    <h3>Flappy Bird</h3>
    <iframe class="game-frame" src="https://ayan-web21.github.io/game/" frameborder="0" allowfullscreen></iframe>
  </div>
  <div>
    <h3>Crossroads</h3>
    <iframe class="game-frame" src="https://ayan-web21.github.io/croosroads/" frameborder="0" allowfullscreen></iframe>
  </div>
</div>

<script>
  function loadGame(url) {
    const iframe = document.getElementById('gameFrame');
    iframe.src = url;
  }
</script>

</body>
</html>
