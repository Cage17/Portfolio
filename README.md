Portfolio/HTML
<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
        <button id="darkModeToggle">Toggle Dark Mode</button>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Me</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="home">
        <h2>Welcome to My Portfolio</h2>
        <p>Hi, I'm Charles John L. Ramos, a passionate software engineer.</p>
    </section>
    <section id="about">
        <h2>About Me</h2>
        <p>"Enthusiastic and dedicated Software Engineer with a strong foundation in various programming languages..."</p>
    </section>
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>C#</li>
        </ul>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
        </div>
        <div class="project">
            <h3>Project 2</h3>
        </div>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: ramoscharlesjohn@gmail.com</p>
        <p>Phone Number: +639270557313</p>
        <button onclick="showAlert()">Click Me!</button>
    </section>
    <footer>
        <p>&copy; 2025 Charles John L. Ramos. All rights reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
