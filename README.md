<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MyFlix</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>MyFlix</h1>
        <div class="controls">
            <input type="text" id="search-bar" placeholder="Search movies...">
            <select id="category-filter">
                <option value="All">All</option>
                <option value="Action">Action</option>
                <option value="Sci-Fi">Sci-Fi</option>
                <option value="Drama">Drama</option>
                <option value="Comedy">Comedy</option>
                <option value="Horror">Horror</option>
                <option value="Documentary">Documentary</option>
            </select>
        </div>
    </header>
    <main id="movies-container"></main>

    <!-- Modal for trailer -->
    <div id="trailer-modal" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeTrailer()">&times;</span>
            <iframe id="trailer-frame" width="100%" height="400" src="" frameborder="0" allowfullscreen></iframe>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
