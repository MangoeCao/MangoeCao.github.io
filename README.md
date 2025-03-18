
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Home Section</h2>
        <p>This is the home section of your website.</p>
    </section>

    <section id="about">
        <h2>About Section</h2>
        <p>This is the about section where you tell people about your website.</p>
    </section>

    <section id="contact">
        <h2>Contact Section</h2>
        <p>Here is how you can contact me!</p>
    </section>

    <footer>
        <p>&copy; 2025 My Website</p>
    </footer>

    <script src="scripts.js"></script>
</body>

/* Reset some default styling */
body, h1, h2, p, ul, li {
    margin: 0;
    padding: 0;
}

/* Basic page styling */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;
}

header nav ul {
    list-style-type: none;
}

header nav ul li {
    display: inline;
    margin: 0 10px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

section {
    padding: 20px;
    margin: 10px 0;
}

section#home {
    background-color: #fff;
}

section#about {
    background-color: #f8f8f8;
}

section#contact {
    background-color: #fff;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}

</html>

