<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jane R - Developer Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        header {
            text-align: center;
        }

        .section-container {
            text-align: right;
            max-width: 800px;
            margin-right: 20px;
        }

        .section-container h2 {
            text-align: left;
        }
    </style>
</head>
<body>
    <header>
        <h1>Jane R</h1>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#portfolio">Projects</a></li>
                <li><a href="#recommendations">Recommendations</a></li>
            </ul>
        </nav>
    </header>

    <div class="section-container" id="about">
        <h2>About Me</h2>
        <p>Welcome to my portfolio website. I am a Developer with a passion for creating web applications and solving complex problems.</p>
    </div>

    <div class="section-container" id="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML/CSS</li>
            <li>JavaScript</li>
            <li>React.js</li>
            <li>Node.js</li>
            <li>Database Management</li>
        </ul>
    </div>

    <div class="section-container" id="portfolio">
        <h2>Projects</h2>
        <!-- Add your projects here -->
        <div class="project">
            <img src="project1.jpg" alt="Project 1">
            <h3>Project 1</h3>
            <p>Description of Project 1.</p>
        </div>
        <div class="project">
            <img src="project2.jpg" alt="Project 2">
            <h3>Project 2</h3>
            <p>Description of Project 2.</p>
        </div>
    </div>

    <div class="section-container" id="recommendations">
        <h2>Recommendations</h2>
        <!-- Add recommendations here -->
        <div class="recommendation">
            <p>"Jane R is an exceptional developer with great problem-solving skills. Highly recommended!" - John Doe, CEO of XYZ Company</p>
        </div>
        <div class="recommendation">
            <p>"I had the pleasure of working with Jane on several projects. Her attention to detail and dedication are impressive." - Jane Smith, Senior Developer</p>
        </div>
    </div>

    <footer>
        <p>Contact: 321-424-454</p>
        <p>&copy; 2023 Jane R</p>
    </footer>
</body>
</html>


