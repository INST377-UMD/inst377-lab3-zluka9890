<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rock Paper Scissors</title>
    <link rel="stylesheet" href="lab3.css">
    
</head>
<body>
    <header class="header-footer">
        <h1>Rock Paper Scissors Game</h1>
    </header>
    
    <nav>
        <ul>
            <li><a href="https://www.google.com" target="_blank">Google</a></li>
            <li><a href="https://www.wikipedia.org" target="_blank">Wikipedia</a></li>
            <li><a href="https://www.youtube.com" target="_blank">YouTube</a></li>
        </ul>
    </nav>
    
    <div class="content">
        <main>
            <h2>Play the Game</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <br>
                <label for="choice">Choose:</label>
                <select id="choice" name="choice">
                    <option value="rock">Rock</option>
                    <option value="paper">Paper</option>
                    <option value="scissors">Scissors</option>
                </select>
                <br>
                <button type="submit">Submit</button>
            </form>            
        </main>
        
        <aside>
            <h2>Rules</h2>
            <p>Rock beats Scissors.</p>
            <p>Scissors beats Paper.</p>
            <p>Paper beats Rock.</p>
        </aside>
    </div>
    
    <footer class="header-footer">
        <p>&copy; 2025 Rock Paper Scissors Game</p>
    </footer>
</body>
</html>



