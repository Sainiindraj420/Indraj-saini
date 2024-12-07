# Indraj-saini
Android mobile game 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Maze Runner</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Maze Runner Game</h1>
  <div id="maze">
    <!-- Player -->
    <div id="player"></div>
    <!-- Finish Point -->
    <div id="finish"></div>
    <!-- Maze Walls -->
    <div class="wall" style="top: 50px; left: 0; width: 300px; height: 20px;"></div>
    <div class="wall" style="top: 50px; left: 280px; width: 20px; height: 150px;"></div>
    <div class="wall" style="top: 180px; left: 0; width: 300px; height: 20px;"></div>
  </div>
  <button id="reset">Reset Game</button>
  <script src="script.js"></script>
</body>
</html>
