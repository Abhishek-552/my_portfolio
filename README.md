# my_portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio.google.com</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1c1c1b;
            color: white;
        }
        header {
            background-color: #716666;
            color: white;
            padding: 16px;
            text-align: center;
        }
        nav {
            text-align: center;
            margin-top: 8px;
        }
        nav a {
            text-decoration: none;
            color: #bd9393;
            font-weight: bold;
            padding: 8px 16px;
            display: inline-block;
            transition: background-color 0.3s;
        }
        nav a:hover {
            background-color: #9d8484;
            color: #0d0c0c;
        }
        section {
            max-width: 800px;
            margin: 16px auto;
            padding: 16px;
            background: #6f6e6e;
            border-radius: 10px;
        }
        h1, h2 {
            text-align: center;
        }
        .about {
            text-align: center;
        }
        .about img {
            width: 150px;
            height: 150px;
            border-radius: 10px;
            object-fit: cover;
            display: block;
            margin: 0 auto;
        }
        .projects {
            text-align: center;
        }
        .project {
            background-color: #757577;
            padding: 16px;
            border-radius: 5px;
            display: inline-block;
            margin: 8px;
            width: calc(100% - 32px); 
        }
        footer {
            text-align: center;
            padding: 16px;
            background-color: #333;
            color: white;
        }
        .contact {
            background-color: #f9f9f9; 
            padding: 16px;
            border-radius: 8px;
            color: #0c0c0c;
        }
        #contact a {
            color: #0c0c0c;
            text-decoration: none; 
        }
        #contact a:hover {
            text-decoration: underline; 
        }
        @media (max-width: 600px) {
            body {
                padding: 8px;
            }
            nav a {
                padding: 8px 12px;
            }
            section {
                padding: 12px;
            }
            .about img {
                width: 100px;
                height: 100px;
            }
            .project {
                padding: 12px;
                width: calc(100% - 24px);
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>ABHISHEK RAGHAV</h1>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#projects">Projects</a>
        <a href="#Education">Education</a>
        <a href="#skill">Skills</a>
        <a href="#objective">Objective</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="about">
        <h2>ABOUT ME</h2>
        <div class="about">
            <img src="d:\memories\1690440480593_121853.jpg" alt="Profile Photo">
            <p>Hello! I'm <strong>Abhishek Raghav</strong>, a passionate Computer Science student, excited to learn and explore the world of technology. With a strong foundation in programming fundamentals and a passion for creative design, I've started to dip my toes into software development and competitive coding. Through hands-on experience and online courses, I've gained a basic understanding of C++, Python, and web designing.</p>
            <p><strong>ASPIRING SOFTWARE DEVELOPER || BTECH (CSE) STUDENT</strong></p>
        </div>
    </section>
    <section id="projects">
        <h2>PROJECTS</h2>
        <div class="projects">
            <div class="project">
                <h3>Project 1: My Personal Portfolio</h3>
                <p>A web page that defines myself and my career objective.</p>
            </div>
        </div>
    </section>
    <section id="Education">
        <h2>EDUCATION</h2>
        <div class="Education">
            <h3>GRADUATION</h3>
            <p><strong>Coer University</strong></p>
            <p>B.Tech (CSE) - (pursuing)</p>
            <h3>HIGHER SECONDARY CERTIFICATE</h3>
            <p><strong>Nature International School</strong></p>
            <p>CBSE (2023-2024)</p>
            <h3>SECONDARY CERTIFICATE</h3>
            <p><strong>Nature International School</strong></p>
            <p>CBSE (2021-2022)</p>
        </div>
    </section>
    <section id="skill">
        <h2>SKILLS</h2>
        <ol>
            <li>Python</li>
            <li>C</li>
            <li>C++</li>
            <li>Web Designing (HTML, CSS, JavaScript)</li>
        </ol>
    </section>
    <section id="objective">
        <h2>OBJECTIVE</h2>
        <p>I'm eager to continue learning, growing, and collaborating with like-minded individuals to bring ideas to life. Let's connect and explore the tech world together.</p>
    </section>
    <section id="contact">
        <h2>CONTACT</h2>
        <p>If you'd like to get in touch, feel free to reach out via email: <strong><a href="mailto:abhishekraghav752@gmail.com">abhishekraghav752@gmail.com</a></strong>.</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/abhishek-raghav-9758ba320?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">Abhishek Raghav</a></p>
        <p>Phone: <strong>+91-8171808960</strong></p>
    </section>
    <footer>
        <p>&copy; 2024 My Portfolio</p>
    </footer>
</body>
</html>
