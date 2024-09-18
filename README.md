# wizportfolio

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE-edge">
    <title>Wisdom Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#About">About</a></li>
                <li><a href="#Projects">Projects</a></li>
                <li><a href="#Contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <h1>Hi, I'm Wisdom</h1>
        <p>A Frontend Developer Passionate about building user-friendly web applications.</p>
        <button><a href="#" class="btn">View My Work</a></button>
    </section>

    <section id="about">
        <h2>About me</h2>
        <img src="wizz.jpg">
        <p>My name's Wisdom Penuel A. a front-end web developer and software specialist, mainly based on hypertext mark-up language (html), cascading style stylesheet
            (CSS) and JavaScript(js)
        </p>
    </section>

    <section id="Projects">
        <h2>My Projects</h2>
        <div class="Project-lists">
            <div class="Project">
                <h3>Project 1</h3>
                <p>Description of the project goes here. You can explain the technologies used and the challenges you solved.</p>
                <a href="<https://github.com/your-github-link/project1>" target="_blank">View Project</a>
            </div>
            <!--Add more projects similarly-->
            <div class="Project">
                <h3>Project 2</h3>
                <p>Description of the project goes here. You can explain the technologies used and the challenges you solved.</p>
                <a href="<https://github.com/your-github-link/project1>" target="_blank">View Project</a>
            </div>
            <div class="Project">
                <h3>Project 3</h3>
                <p>Description of the project goes here. You can explain the technologies used and the challenges you solved.</p>
                <a href="<https://github.com/your-github-link/project1>" target="_blank">View Project</a>
            </div>
        </div>
    </section>

    <section id="Contact">
        <h2>Contact Me</h2>
        <p>Interested in working together? fill out the form below</p>

        <form action="submit-form.php" method="POST">
            <input type="text" name="name" placeholder="Your Name" required><br><br>
            <input type="email" name="email" placeholder="Your Email" required><br><br>
            <textarea name="message" placeholder="Your Message" required></textarea><br><br>
            <button>SEND</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Wisdom. All rights reserved.</p>
    </footer>
</body>
</html>
