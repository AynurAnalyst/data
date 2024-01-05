<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Your Portfolio</title>
</head>
<body>
    <header>
        <div class="container">
            <h1>Your Name</h1>
            <p>Web Developer</p>
        </div>
    </header>

    <section id="projects">
        <div class="container">
            <h2>Projects</h2>
            <!-- Add your project cards here -->
            <div class="project-card">
                <h3>Project 1</h3>
                <p>Description of Project 1.</p>
                <a href="#">View on GitHub</a>
            </div>
            <div class="project-card">
                <h3>Project 2</h3>
                <p>Description of Project 2.</p>
                <a href="#">View on GitHub</a>
            </div>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Write a brief introduction about yourself here.</p>
        </div>
    </section>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
}

.container {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 50px 0;
}

header h1 {
    margin: 0;
}

header p {
    margin: 10px 0;
}

section {
    margin: 40px 0;
}

.project-card {
    border: 1px solid #ddd;
    padding: 20px;
    margin: 20px 0;
}

.project-card h3 {
    margin: 0;
}

.project-card p {
    margin: 10px 0;
}

.project-card a {
    display: block;
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    text-decoration: none;
    border-radius: 5px;
}

.project-card a:hover {
    background-color: #555;
}
