<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stone-paper-scissor Game</title>
    <link rel="stylesheet" href="paper.css">
</head>
<body>
    <h1>Rock Paper Scissor</h1>
    <div class="choices">
        <div class="choice" id="rock">
            <img src="./rock.png" />
        </div>
        <div class="choice" id="paper">
            <img src="./paper.png" />
        </div>
        <div class="choice" id="scissors">
            <img src="./scissors.png" />
        </div>
    </div>
    <div class="score-board">
        <div class="score">
            <p id="user-score">0</p>
            <p>You</p>
        </div>
        <div class="score">
            <p id="comp-score">0</p>
            <p>Comp</p>
        </div>
    </div>
    <div class="msg-container">
        <p id="msg">Play your move</p>
    </div>
    <script src="p.js"></script>
</body>
</html>





