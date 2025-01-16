# Kullanun-me.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #6c63ff;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        .portfolio-container {
            max-width: 1200px;
            margin: 50px auto;
            padding: 0 20px;
        }
        .about {
            text-align: center;
            margin-bottom: 50px;
        }
        .about h2 {
            margin-bottom: 10px;
        }
        .about p {
            color: #555;
        }
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .project {
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }
        .project img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .project-details {
            padding: 20px;
        }
        .project-details h3 {
            margin: 0 0 10px;
        }
        .project-details p {
            color: #555;
            margin: 0 0 15px;
        }
        .project-details a {
            text-decoration: none;
            color: #6c63ff;
            font-weight: bold;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 50px;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
    </header>

    <div class="portfolio-container">
        <section class="about">
            <h2>About Me</h2>
            <p>Hello! I'm a creative professional passionate about design and development. Here's a showcase of my work.</p>
        </section>

        <section class="projects">
            <div class="project">
                <img src="https://via.placeholder.com/300x200" alt="Project 1">
                <div class="project-details">
                    <h3>Project One</h3>
                    <p>A brief description of the project goes here.</p>
                    <a href="#">View Project</a>
                </div>
            </div>

            <div class="project">
                <img src="https://via.placeholder.com/300x200" alt="Project 2">
                <div class="project-details">
                    <h3>Project Two</h3>
                    <p>A brief description of the project goes here.</p>
                    <a href="#">View Project</a>
                </div>
            </div>

            <div class="project">
                <img src="https://via.placeholder.com/300x200" alt="Project 3">
                <div class="project-details">
                    <h3>Project Three</h3>
                    <p>A brief description of the project goes here.</p>
                    <a href="#">View Project</a>
                </div>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 My Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>
