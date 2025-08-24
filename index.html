# super-aelo-1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Crocodile Adventure</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(to bottom, #1a5f7a, #159895);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            overflow: hidden;
        }
        
        #game-container {
            width: 800px;
            max-width: 95%;
            position: relative;
        }
        
        #game-canvas {
            background: linear-gradient(to bottom, #87CEEB, #C2E9FB);
            border: 4px solid #2C394B;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.4);
            display: block;
            margin: 0 auto;
        }
        
        #ui-container {
            display: flex;
            justify-content: space-between;
            padding: 10px 20px;
            background: rgba(44, 57, 75, 0.8);
            border-radius: 10px;
            margin-bottom: 10px;
            font-size: 20px;
            font-weight: bold;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        
        #level-display {
            color: #FFD700;
        }
        
        #timer {
            color: #FF5722;
        }
        
        #score {
            color: #4CAF50;
        }
        
        #lives {
            color: #FF5252;
        }
        
        #start-screen, #level-complete, #game-over, #leaderboard {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(28, 40, 54, 0.95);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            border-radius: 10px;
            text-align: center;
            padding: 20px;
        }
        
        #leaderboard {
            display: none;
        }
        
        h1 {
            font-size: 48px;
            color: #FFD700;
            text-shadow: 3px 3px 0 #FF5722;
            margin-bottom: 20px;
        }
        
        h2 {
            font-size: 36px;
            color: #4CAF50;
            margin-bottom: 20px;
        }
        
        p {
            font-size: 20px;
            margin-bottom: 15px;
            max-width: 80%;
        }
        
        button {
            background: #FF5722;
            color: white;
            border: none;
            padding: 15px 40px;
            font-size: 20px;
            border-radius: 50px;
            cursor: pointer;
            box-shadow: 0 4px 0 #D84315;
            transition: all 0.2s;
            margin-top: 20px;
            font-weight: bold;
        }
        
        button:hover {
            background: #FF7043;
            transform: translateY(-2px);
            box-shadow: 0 6px 0 #D84315;
        }
        
        button:active {
            transform: translateY(2px);
            box-shadow: 0 2px 0 #D84315;
        }
        
        .instructions {
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
            text-align: center;
            max-width: 80%;
        }
        
        .key {
            display: inline-block;
            background: rgba(255, 255, 255, 0.2);
            padding: 5px 10px;
            border-radius: 5px;
            margin: 0 5px;
            font-weight: bold;
        }
        
        #leaderboard-list {
            list-style-type: none;
            width: 80%;
            margin: 20px 0;
            max-height: 200px;
            overflow-y: auto;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            padding: 10px;
        }
        
        #leaderboard-list li {
            padding: 10px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.2);
            display: flex;
            justify-content: space-between;
        }
        
        #leaderboard-list li:first-child {
            color: #FFD700;
            font-weight: bold;
            font-size: 1.2em;
        }
        
        #name-input {
            background: rgba(255, 255, 255, 0.2);
            border: 2px solid #FF5722;
            border-radius: 50px;
            padding: 12px 20px;
            color: white;
            font-size: 18px;
            text-align: center;
            margin-top: 10px;
            width: 250px;
        }
        
        #name-input::placeholder {
            color: rgba(255, 255, 255, 0.7);
        }
        
        .crocodile {
            position: absolute;
            width: 60px;
            height: 30px;
            background: #4CAF50;
            border-radius: 10px 10px 20px 20px;
        }
        
        .crocodile::before {
            content: "";
            position: absolute;
            width: 20px;
            height: 20px;
            background: #4CAF50;
            border-radius: 5px;
            top: -10px;
            left: 10px;
        }
        
        .crocodile::after {
            content: "";
            position: absolute;
            width: 15px;
            height: 10px;
            background: #FF5252;
            border-radius: 0 0 5px 5px;
            top: 5px;
            left: 10px;
        }
    </style>
</head>
<body>
    <div id="game-container">
        <div id="ui-container">
            <div>Level: <span id="level-display">1</span></div>
            <div>Time: <span id="timer">00:00</span></div>
            <div>Score: <span id="score">0</span></div>
            <div>Lives: <span id="lives">3</span></div>
        </div>
        
        <canvas id="game-canvas" width="800" height="500"></canvas>
        
        <div id="start-screen">
            <h1>Crocodile Adventure</h1>
            <div class="instructions">
                <p>Help Alex escape from the crocodile-infested jungle!</p>
                <p>Use <span class="key">←</span> <span class="key">→</span> to move and <span class="key">Space</span> to jump</p>
                <p>Collect coins and avoid crocodiles!</p>
            </div>
            <button id="start-button">Start Game</button>
        </div>
        
        <div id="level-complete" style="display: none;">
            <h2>Level Complete!</h2>
            <p>Your time: <span id="level-time">00:00</span></p>
            <p>Total score: <span id="total-score">0</span></p>
            <button id="next-level">Next Level</button>
        </div>
        
        <div id="game-over" style="display: none;">
            <h2>Game Over</h2>
            <p>You were caught by crocodiles!</p>
            <p>Final score: <span id="final-score">0</span></p>
            <button id="restart-button">Play Again</button>
        </div>
        
        <div id="leaderboard">
            <h2>Leaderboard</h2>
            <p>Fastest completions:</p>
            <ul id="leaderboard-list">
                <li>Loading...</li>
            </ul>
            <input type="text" id="name-input" placeholder="Enter your name">
            <button id="submit-score">Submit Score</button>
        </div>
    </div>

    <script>
        // Game variables
        const canvas = document.getElementById('game-canvas');
        const ctx = canvas.getContext('2d');
        const scoreElement = document.getElementById('score');
        const livesElement = document.getElementById('lives');
        const levelDisplay = document.getElementById('level-display');
        const timerElement = document.getElementById('timer');
        const startScreen = document.getElementById('start-screen');
        const levelCompleteScreen = document.getElementById('level-complete');
        const gameOverScreen = document.getElementById('game-over');
        const leaderboardScreen = document.getElementById('leaderboard');
        const startButton = document.getElementById('start-button');
        const nextLevelButton = document.getElementById('next-level');
        const restartButton = document.getElementById('restart-button');
        const submitScoreButton = document.getElementById('submit-score');
        const nameInput = document.getElementById('name-input');
        const leaderboardList = document.getElementById('leaderboard-list');
        const levelTimeElement = document.getElementById('level-time');
        const totalScoreElement = document.getElementById('total-score');
        const finalScoreElement = document.getElementById('final-score');
        
        // Game state
        let gameRunning = false;
        let currentLevel = 1;
        let score = 0;
        let lives = 3;
        let levelTime = 0;
        let totalTime = 0;
        let timerInterval;
        let playerName = "Player";
        
        // Player properties
        const player = {
            x: 50,
            y: 400,
            width: 35,
            height: 55,
            speed: 5,
            jumpForce: 14,
            velocityY: 0,
            jumping: false,
            direction: 1
        };
        
        // Game objects
        let platforms = [];
        let coins = [];
        let crocodiles = [];
        let levelGoal = { x: 0, y: 0, width: 40, height: 40 };
        
        // Key states
        const keys = {};
        
        // Leaderboard data
        let leaderboard = [];
        
        // Level configurations
        const levelConfigs = [
            // Level 1 - Easy
            {
                platforms: [
                    { x: 0, y: 460, width: 800, height: 40 },
                    { x: 200, y: 350, width: 150, height: 20 },
                    { x: 400, y: 250, width: 150, height: 20 },
                    { x: 600, y: 350, width: 150, height: 20 }
                ],
                coins: [
                    { x: 230, y: 320, width: 20, height: 20, collected: false },
                    { x: 430, y: 220, width: 20, height: 20, collected: false },
                    { x: 630, y: 320, width: 20, height: 20, collected: false }
                ],
                crocodiles: [
                    { x: 300, y: 410, width: 60, height: 30, speed: 1.5, direction: 1, moveDistance: 200 }
                ],
                goal: { x: 730, y: 410, width: 40, height: 40 }
            },
            
            // Level 2 - Medium
            {
                platforms: [
                    { x: 0, y: 460, width: 800, height: 40 },
                    { x: 100, y: 350, width: 120, height: 20 },
                    { x: 300, y: 350, width: 120, height: 20 },
                    { x: 500, y: 250, width: 120, height: 20 },
                    { x: 650, y: 350, width: 120, height: 20 },
                    { x: 200, y: 150, width: 100, height: 20 }
                ],
                coins: [
                    { x: 130, y: 320, width: 20, height: 20, collected: false },
                    { x: 330, y: 320, width: 20, height: 20, collected: false },
                    { x: 530, y: 220, width: 20, height: 20, collected: false },
                    { x: 680, y: 320, width: 20, height: 20, collected: false },
                    { x: 230, y: 120, width: 20, height: 20, collected: false }
                ],
                crocodiles: [
                    { x: 200, y: 410, width: 60, height: 30, speed: 2, direction: 1, moveDistance: 150 },
                    { x: 550, y: 410, width: 60, height: 30, speed: 2, direction: -1, moveDistance: 150 }
                ],
                goal: { x: 730, y: 310, width: 40, height: 40 }
            },
            
            // Level 3 - Hard
            {
                platforms: [
                    { x: 0, y: 460, width: 800, height: 40 },
                    { x: 100, y: 380, width: 100, height: 20 },
                    { x: 250, y: 300, width: 100, height: 20 },
                    { x: 400, y: 220, width: 100, height: 20 },
                    { x: 550, y: 300, width: 100, height: 20 },
                    { x: 700, y: 380, width: 100, height: 20 },
                    { x: 300, y: 150, width: 80, height: 20 },
                    { x: 500, y: 150, width: 80, height: 20 }
                ],
                coins: [
                    { x: 130, y: 350, width: 20, height: 20, collected: false },
                    { x: 280, y: 270, width: 20, height: 20, collected: false },
                    { x: 430, y: 190, width: 20, height: 20, collected: false },
                    { x: 580, y: 270, width: 20, height: 20, collected: false },
                    { x: 730, y: 350, width: 20, height: 20, collected: false },
                    { x: 330, y: 120, width: 20, height: 20, collected: false },
                    { x: 530, y: 120, width: 20, height: 20, collected: false }
                ],
                crocodiles: [
                    { x: 150, y: 410, width: 60, height: 30, speed: 2.5, direction: 1, moveDistance: 100 },
                    { x: 400, y: 410, width: 60, height: 30, speed: 2, direction: -1, moveDistance: 200 },
                    { x: 650, y: 410, width: 60, height: 30, speed: 2.5, direction: 1, moveDistance: 100 }
                ],
                goal: { x: 730, y: 330, width: 40, height: 40 }
            },
            
            // Level 4 - Very Hard
            {
                platforms: [
                    { x: 0, y: 460, width: 800, height: 40 },
                    { x: 100, y: 350, width: 80, height: 20 },
                    { x: 250, y: 250, width: 80, height: 20 },
                    { x: 400, y: 350, width: 80, height: 20 },
                    { x: 550, y: 250, width: 80, height: 20 },
                    { x: 700, y: 350, width: 80, height: 20 },
                    { x: 200, y: 150, width: 60, height: 20 },
                    { x: 400, y: 150, width: 60, height: 20 },
                    { x: 600, y: 150, width: 60, height: 20 }
                ],
                coins: [
                    { x: 120, y: 320, width: 20, height: 20, collected: false },
                    { x: 270, y: 220, width: 20, height: 20, collected: false },
                    { x: 420, y: 320, width: 20, height: 20, collected: false },
                    { x: 570, y: 220, width: 20, height: 20, collected: false },
                    { x: 720, y: 320, width: 20, height: 20, collected: false },
                    { x: 220, y: 120, width: 20, height: 20, collected: false },
                    { x: 420, y: 120, width: 20, height: 20, collected: false },
                    { x: 620, y: 120, width: 20, height: 20, collected: false }
                ],
                crocodiles: [
                    { x: 100, y: 410, width: 60, height: 30, speed: 3, direction: 1, moveDistance: 150 },
                    { x: 350, y: 410, width: 60, height: 30, speed: 2.5, direction: -1, moveDistance: 200 },
                    { x: 600, y: 410, width: 60, height: 30, speed: 3, direction: 1, moveDistance: 150 },
                    { x: 250, y: 210, width: 60, height: 30, speed: 2, direction: 1, moveDistance: 80 },
                    { x: 550, y: 210, width: 60, height: 30, speed: 2, direction: -1, moveDistance: 80 }
                ],
                goal: { x: 50, y: 410, width: 40, height: 40 }
            }
        ];
        
        // Event listeners
        window.addEventListener('keydown', (e) => {
            keys[e.key] = true;
        });
        
        window.addEventListener('keyup', (e) => {
            keys[e.key] = false;
        });
        
        startButton.addEventListener('click', startGame);
        nextLevelButton.addEventListener('click', loadNextLevel);
        restartButton.addEventListener('click', restartGame);
        submitScoreButton.addEventListener('click', submitScore);
        
        // Initialize leaderboard from localStorage
        function loadLeaderboard() {
            const savedLeaderboard = localStorage.getItem('crocodileLeaderboard');
            if (savedLeaderboard) {
                leaderboard = JSON.parse(savedLeaderboard);
            } else {
                leaderboard = [
                    { name: "Jungle Master", time: 85, score: 2000 },
                    { name: "Croc Hunter", time: 120, score: 1800 },
                    { name: "Adventurer", time: 160, score: 1500 },
                    { name: "Explorer", time: 200, score: 1200 },
                    { name: "Beginner", time: 250, score: 800 }
                ];
            }
            updateLeaderboardDisplay();
        }
        
        function updateLeaderboardDisplay() {
            leaderboardList.innerHTML = '';
            leaderboard.sort((a, b) => a.time - b.time).forEach(entry => {
                const li = document.createElement('li');
                const minutes = Math.floor(entry.time / 60);
                const seconds = entry.time % 60;
                li.innerHTML = `${entry.name} - ${minutes.toString().padStart(2, '0')}:${seconds.toString().padStart(2, '0')} - ${entry.score} pts`;
                leaderboardList.appendChild(li);
            });
        }
        
        function startGame() {
            loadLeaderboard();
            startScreen.style.display = 'none';
            currentLevel = 1;
            score = 0;
            lives = 3;
            totalTime = 0;
            loadLevel(currentLevel);
        }
        
        function loadLevel(level) {
            const config = levelConfigs[level - 1];
            platforms = JSON.parse(JSON.stringify(config.platforms));
            coins = JSON.parse(JSON.stringify(config.coins));
            crocodiles = JSON.parse(JSON.stringify(config.crocodiles));
            levelGoal = JSON.parse(JSON.stringify(config.goal));
            
            // Reset player position
            player.x = 50;
            player.y = 400;
            player.velocityY = 0;
            player.jumping = false;
            
            // Update UI
            levelDisplay.textContent = level;
            updateScore();
            updateLives();
            
            // Start timer
            levelTime = 0;
            clearInterval(timerInterval);
            timerInterval = setInterval(() => {
                levelTime++;
                totalTime++;
                updateTimer();
            }, 1000);
            
            gameRunning = true;
            gameLoop();
        }
        
        function loadNextLevel() {
            currentLevel++;
            if (currentLevel <= levelConfigs.length) {
                levelCompleteScreen.style.display = 'none';
                loadLevel(currentLevel);
            } else {
                gameComplete();
            }
        }
        
        function gameComplete() {
            clearInterval(timerInterval);
            gameRunning = false;
            leaderboardScreen.style.display = 'flex';
            finalScoreElement.textContent = score;
        }
        
        function restartGame() {
            gameOverScreen.style.display = 'none';
            startGame();
        }
        
        function submitScore() {
            const name = nameInput.value.trim() || playerName;
            leaderboard.push({ name, time: totalTime, score });
            localStorage.setItem('crocodileLeaderboard', JSON.stringify(leaderboard));
            updateLeaderboardDisplay();
            leaderboardScreen.style.display = 'none';
            startScreen.style.display = 'flex';
            startButton.textContent = 'Play Again';
        }
        
        function gameLoop() {
            if (!gameRunning) return;
            
            update();
            render();
            requestAnimationFrame(gameLoop);
        }
        
        function update() {
            // Apply gravity
            player.velocityY += 0.5;
            
            // Move player
            if (keys['ArrowLeft']) {
                player.x -= player.speed;
                player.direction = -1;
            }
            if (keys['ArrowRight']) {
                player.x += player.speed;
                player.direction = 1;
            }
            
            // Jump
            if (keys[' '] && !player.jumping) {
                player.velocityY = -player.jumpForce;
                player.jumping = true;
            }
            
            // Apply velocity
            player.y += player.velocityY;
            
            // Check platform collisions
            player.jumping = true;
            for (const platform of platforms) {
                if (
                    player.x < platform.x + platform.width &&
                    player.x + player.width > platform.x &&
                    player.y + player.height > platform.y &&
                    player.y + player.height <= platform.y + platform.height + player.velocityY
                ) {
                    player.y = platform.y - player.height;
                    player.velocityY = 0;
                    player.jumping = false;
                }
            }
            
            // Screen boundaries
            if (player.x < 0) player.x = 0;
            if (player.x + player.width > canvas.width) player.x = canvas.width - player.width;
            
            // Check if player fell off the screen
            if (player.y > canvas.height) {
                loseLife();
                resetPlayer();
            }
            
            // Update crocodiles
            for (const croc of crocodiles) {
                croc.x += croc.speed * croc.direction;
                
                // Change direction if hitting movement boundaries
                if (croc.direction > 0 && croc.x > croc.initialX + croc.moveDistance) {
                    croc.direction *= -1;
                } else if (croc.direction < 0 && croc.x < croc.initialX) {
                    croc.direction *= -1;
                }
                
                // Check collision with player
                if (
                    player.x < croc.x + croc.width &&
                    player.x + player.width > croc.x &&
                    player.y < croc.y + croc.height &&
                    player.y + player.height > croc.y
                ) {
                    // If player is above crocodile, defeat it
                    if (player.velocityY > 0 && player.y + player.height < croc.y + croc.height / 2) {
                        croc.x = -200; // Remove crocodile
                        player.velocityY = -10; // Bounce
                        score += 100;
                        updateScore();
                    } else {
                        loseLife();
                        resetPlayer();
                    }
                }
            }
            
            // Check coin collisions
            for (const coin of coins) {
                if (
                    !coin.collected &&
                    player.x < coin.x + coin.width &&
                    player.x + player.width > coin.x &&
                    player.y < coin.y + coin.height &&
                    player.y + player.height > coin.y
                ) {
                    coin.collected = true;
                    score += 50;
                    updateScore();
                }
            }
            
            // Check if player reached the goal
            if (
                player.x < levelGoal.x + levelGoal.width &&
                player.x + player.width > levelGoal.x &&
                player.y < levelGoal.y + levelGoal.height &&
                player.y + player.height > levelGoal.y
            ) {
                levelComplete();
            }
        }
        
        function render() {
            // Clear canvas
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            
            // Draw background
            ctx.fillStyle = '#6B8CFF';
            ctx.fillRect(0, 0, canvas.width, canvas.height);
            
            // Draw platforms
            ctx.fillStyle = '#8BC34A';
            platforms.forEach(platform => {
                ctx.fillRect(platform.x, platform.y, platform.width, platform.height);
                
                // Platform top
                ctx.fillStyle = '#7CB342';
                ctx.fillRect(platform.x, platform.y, platform.width, 5);
                ctx.fillStyle = '#8BC34A';
            });
            
            // Draw coins
            coins.forEach(coin => {
                if (!coin.collected) {
                    ctx.fillStyle = '#FFD700';
                    ctx.beginPath();
                    ctx.arc(coin.x + coin.width/2, coin.y + coin.height/2, coin.width/2, 0, Math.PI * 2);
                    ctx.fill();
                    
                    ctx.fillStyle = '#FFC400';
                    ctx.beginPath();
                    ctx.arc(coin.x + coin.width/2 - 3, coin.y + coin.height/2 - 3, 3, 0, Math.PI * 2);
                    ctx.fill();
                }
            });
            
            // Draw crocodiles
            crocodiles.forEach(croc => {
                ctx.fillStyle = '#4CAF50';
                ctx.fillRect(croc.x, croc.y, croc.width, croc.height);
                
                // Crocodile eyes
                ctx.fillStyle = 'white';
                ctx.fillRect(croc.x + 10, croc.y + 5, 8, 8);
                ctx.fillRect(croc.x + 40, croc.y + 5, 8, 8);
                
                ctx.fillStyle = 'black';
                ctx.fillRect(croc.x + 12, croc.y + 7, 4, 4);
                ctx.fillRect(croc.x + 42, croc.y + 7, 4, 4);
                
                // Crocodile teeth
                ctx.fillStyle = 'white';
                for (let i = 0; i < 4; i++) {
                    ctx.fillRect(croc.x + 15 + i*10, croc.y, 5, 5);
                }
            });
            
            // Draw goal
            ctx.fillStyle = '#FF5722';
            ctx.fillRect(levelGoal.x, levelGoal.y, levelGoal.width, levelGoal.height);
            ctx.fillStyle = '#FFD700';
            ctx.beginPath();
            ctx.moveTo(levelGoal.x + levelGoal.width/2, levelGoal.y);
            ctx.lineTo(levelGoal.x + levelGoal.width - 5, levelGoal.y + levelGoal.height);
            ctx.lineTo(levelGoal.x + 5, levelGoal.y + levelGoal.height);
            ctx.closePath();
            ctx.fill();
            
            // Draw player
            ctx.fillStyle = '#3564FC'; // Blue shirt
            ctx.fillRect(player.x, player.y + 15, player.width, player.height - 15);
            
            ctx.fillStyle = '#F4D47C'; // Skin
            ctx.fillRect(player.x + 5, player.y, player.width - 10, 15);
            
            ctx.fillStyle = '#663300'; // Hair
            ctx.fillRect(player.x, player.y, player.width, 5);
            
            ctx.fillStyle = '#3564FC'; // Pants
            ctx.fillRect(player.x, player.y + player.height - 10, player.width, 10);
            
            // Player eyes
            ctx.fillStyle = 'white';
            if (player.direction > 0) {
                ctx.fillRect(player.x + 25, player.y + 5, 5, 5);
            } else {
                ctx.fillRect(player.x + 5, player.y + 5, 5, 5);
            }
        }
        
        function updateScore() {
            scoreElement.textContent = score;
        }
        
        function updateLives() {
            livesElement.textContent = lives;
        }
        
        function updateTimer() {
            const minutes = Math.floor(levelTime / 60);
            const seconds = levelTime % 60;
            timerElement.textContent = `${minutes.toString().padStart(2, '0')}:${seconds.toString().padStart(2, '0')}`;
        }
        
        function loseLife() {
            lives--;
            updateLives();
            
            if (lives <= 0) {
                gameOver();
            }
        }
        
        function resetPlayer() {
            player.x = 50;
            player.y = 400;
            player.velocityY = 0;
        }
        
        function levelComplete() {
            clearInterval(timerInterval);
            gameRunning = false;
            
            // Calculate level bonus (faster completion = more points)
            const timeBonus = Math.max(0, 300 - levelTime) * 2;
            score += timeBonus;
            
            const minutes = Math.floor(levelTime / 60);
            const seconds = levelTime % 60;
            
            levelTimeElement.textContent = `${minutes.toString().padStart(2, '0')}:${seconds.toString().padStart(2, '0')}`;
            totalScoreElement.textContent = score;
            
            levelCompleteScreen.style.display = 'flex';
        }
        
        function gameOver() {
            clearInterval(timerInterval);
            gameRunning = false;
            gameOverScreen.style.display = 'flex';
            finalScoreElement.textContent = score;
        }
        
        // Initialize the game
        loadLeaderboard();
    </script>
</body>
</html>
