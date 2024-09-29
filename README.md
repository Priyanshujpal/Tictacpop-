# Tictacpop-
Game 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tic-Tac-Toe</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>Tic-Tac-Toe</h1>
    <div class="game-board">
      <div class="cell" data-cell></div>
      <div class="cell" data-cell></div>
      <div class="cell" data-cell></div>
      <div class="cell" data-cell></div>
      <div class="cell" data-cell></div>
      <div class="cell" data-cell></div>
      <div class="cell" data-cell></div>
      <div class="cell" data-cell></div>
      <div class="cell" data-cell></div>
    </div>
    <div class="game-info">
      <p id="statusText"></p>
      <button id="restartBtn">Restart Game</button>
    </div>
  </div>

  <!-- Game Over Screen -->
  <div class="game-over" id="gameOverScreen">
    <div class="message">
      <h2 id="resultMessage"></h2>
      <button id="newGameBtn">New Game</button>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
