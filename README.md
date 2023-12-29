<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Sports Hub - Home</title>
</head>
<body>
    <header>
        <h1>Sports Hub</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="football.html">Football</a></li>
                <li><a href="basketball.html">Basketball</a></li>
                <li><a href="tennis.html">Tennis</a></li>
                <li><a href="cycling.html">Cycling</a></li>
                <li><a href="swimming.html">Swimming</a></li>
            </ul>
        </nav>
    </header>
    
    <section>
        <h2>Welcome to Sports Hub!</h2>
        <p>Explore the latest news and information about various sports.</p>
    </section>

    <script src="script.js"></script>
</body>
</html>
<!-- football.html -->
<!-- Similar structure to index.html, but with content related to football -->
<!-- basketball.html -->
<!-- Similar structure to index.html, but with content related to basketball -->
<!-- tennis.html -->
<!-- Similar structure to index.html, but with content related to tennis -->
<!-- cycling.html -->
<!-- Similar structure to index.html, but with content related to cycling -->
<!-- swimming.html -->
<!-- Similar structure to index.html, but with content related to swimming -->
/* styles.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav li {
    display: inline;
    margin-right: 20px;
}

section {
    padding: 20px;
}
// script.js
document.addEventListener('DOMContentLoaded', function () {
    const dynamicElement = document.createElement('p');
    dynamicElement.textContent = 'Check out our latest articles!';
    document.querySelector('section').appendChild(dynamicElement);
});
