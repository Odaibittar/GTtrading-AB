<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Snake Game</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Snake Game</h1>
        <div class="dashboard">
            <div>Score: <span id="score">0</span></div>
            <div>High Score: <span id="highScore">0</span></div>
            <button id="restartBtn">Restart</button>
        </div>
        <canvas id="gameCanvas" width="400" height="400"></canvas>
    </div>
    <script src="game.js"></script>
</body>
</html>
