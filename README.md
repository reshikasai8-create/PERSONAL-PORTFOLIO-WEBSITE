# PERSONAL-PORTFOLIO-WEBSITE
Designed and developed a responsive job application website that allows users to explore job opportunities and submit their application details through a clean and user-friendly interface. Implemented structured layouts, forms, navigation, and responsive styling using HTML and CSS.  
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My Portfolio</title>

    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f5f7fa;
            color: #222;
            line-height: 1.6;
        }

        /* Navigation */
        nav {
            background-color: #222;
            color: white;
            padding: 15px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav h2 {
            color: #4f9cff;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 25px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
        }

        nav ul li a:hover {
            color: #4f9cff;
        }

        /* Hero Section */
        .hero {
            min-height: 80vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 40px 20px;
            background-color: #eaf3ff;
        }

        .hero h1 {
            font-size: 50px;
            margin-bottom: 10px;
        }

        .hero h1 span {
            color: #2878d8;
        }

        .hero p {
            font-size: 20px;
            color: #555;
            margin-bottom: 25px;
        }

        .button {
            display: inline-block;
            background-color: #2878d8;
            color: white;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 5px;
        }

        .button:hover {
            background-color: #185ca8;
        }

        /* Common Section */
        section {
            padding: 60px 8%;
        }

        .section-title {
            text-align: center;
            font-size: 32px;
            margin-bottom: 35px;
        }

        /* About */
        .about {
            background-color: white;
        }

        .about-content {
            max-width: 800px;
            margin: auto;
            text-align: center;
            color: #555;
        }

        /* Skills */
        .skills {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .skill {
            background-color: white;
            padding: 20px 35px;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.08);
            font-weight: bold;
        }

        /* Projects */
        .projects {
            background-color: white;
        }

        .project-container {
            display: flex;
            justify-content: center;
            gap: 25px;
            flex-wrap: wrap;
        }

        .project-card {
            width: 300px;
            padding: 25px;
            background-color: #f5f7fa;
            border-radius: 10px;
            text-align: center;
            border: 1px solid #ddd;
        }

        .project-card h3 {
            margin-bottom: 10px;
            color: #2878d8;
        }

        .project-card p {
            color: #666;
        }

        /* Contact */
        .contact {
            text-align: center;
        }

        .contact p {
            margin: 10px;
        }

        /* Footer */
        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 20px;
        }

        /* Mobile */
        @media (max-width: 600px) {

            nav {
                flex-direction: column;
                gap: 10px;
            }

            nav ul {
                gap: 15px;
            }

            .hero h1 {
                font-size: 38px;
            }

            .hero p {
                font-size: 17px;
            }
        }
    </style>
</head>

<body>

    <!-- Navigation -->
    <nav>
        <h2>MyPortfolio</h2>

        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>


    <!-- Home -->
    <section class="hero" id="home">

        <div>
            <h1>Hello, I'm <span>Your Name</span></h1>

            <p>
                Beginner Web Developer | HTML & CSS Learner
            </p>

            <a href="#projects" class="button">
                View My Projects
            </a>
        </div>

    </section>


    <!-- About -->
    <section class="about" id="about">

        <h2 class="section-title">About Me</h2>

        <div class="about-content">

            <p>
                Hello! I am a student who is interested in web development.
                I am currently learning HTML and CSS and enjoy creating
                simple and responsive websites.
            </p>

            <br>

            <p>
                My goal is to improve my development skills by building
                projects and learning new technologies.
            </p>

        </div>

    </section>


    <!-- Skills -->
    <section id="skills">

        <h2 class="section-title">My Skills</h2>

        <div class="skills">

            <div class="skill">HTML</div>

            <div class="skill">CSS</div>

            <div class="skill">Responsive Design</div>

            <div class="skill">Problem Solving</div>

        </div>

    </section>


    <!-- Projects -->
    <section class="projects" id="projects">

        <h2 class="section-title">My Projects</h2>

        <div class="project-container">

            <div class="project-card">

                <h3>Personal Portfolio</h3>

                <p>
                    A personal portfolio website created using
                    HTML and CSS to showcase my skills and projects.
                </p>

            </div>


            <div class="project-card">

                <h3>Restaurant Website</h3>

                <p>
                    A simple restaurant landing page with a menu,
                    navigation bar, and contact section.
                </p>

            </div>

        </div>

    </section>


    <!-- Contact -->
    <section class="contact" id="contact">

        <h2 class="section-title">Contact Me</h2>

        <p>📧 Email: yourname@email.com</p>

        <p>📱 Phone: +91 XXXXX XXXXX</p>

        <p>📍 Location: Your City, India</p>

    </section>


    <!-- Footer -->
    <footer>

        <p>© 2026 Your Name | My Portfolio</p>

    </footer>

</body>
</html>
