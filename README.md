# Portfolio
This is a personal portfolio website developed using HTML and CSS to showcase my skills, projects, certifications, and contact details in a clean and responsive design.


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, Helvetica, sans-serif;
        }

        body {
            line-height: 1.6;
            color: #333;
        }

        /* Navbar */
        nav {
            background: #222;
            color: #fff;
            padding: 15px 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            background: #10b3b3;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
        }

        .hero-container {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 40px;
            flex-wrap: wrap;
            text-align: center;
        }

        .hero-text {
            max-width: 500px;
        }

        .hero-text h1 {
            font-size: 48px;
            margin-bottom: 10px;
        }

        .hero-text p {
            font-size: 18px;
            margin-bottom: 20px;
        }

        .hero button {
            padding: 12px 25px;
            border: none;
            background: #222;
            color: white;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
        }

        .hero-image img {
            width: 250px;
            height: 250px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid white;
        }

        /* Sections */
        section {
            padding: 60px 20px;
            text-align: center;
        }

        section h2 {
            color: #10b3b3;
            margin-bottom: 20px;
        }

        /* Skills */
        .skills {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
        }

        .skill {
            background: #222;
            color: white;
            padding: 10px 25px;
            border-radius: 20px;
        }

        .skill:hover {
            background: #10b3b3;
        }

        /* Projects */
        .projects {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .project-card {
            width: 250px;
            padding: 20px;
            border-radius: 8px;
            background: #f5f5f5;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            transition: 0.3s;
        }

        .project-card:hover {
            transform: scale(1.05);
        }

        /* Certifications */
        .certifications {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .cert-card {
            width: 260px;
            padding: 20px;
            background: #f5f5f5;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        /* Internships */
        .internships {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .intern-card {
            width: 280px;
            padding: 20px;
            background: #f5f5f5;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        /* Contact */
        .contact a {
            display: block;
            color: #10b3b3;
            margin: 8px 0;
            text-decoration: none;
        }

        /* Footer */
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 15px;
        }

        /* Responsive */
        @media (max-width: 600px) {
            .hero-text h1 {
                font-size: 36px;
            }

            nav {
                flex-direction: column;
                gap: 10px;
            }

            .hero-container {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <nav>
        <h2>MyPortfolio</h2>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#certifications">Certifications</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Hero -->
    <section class="hero" id="home">
        <div class="hero-container">
            <div class="hero-text">
                <h1>Hello, I'm Renuka Madugundu</h1>
		<p> Computer science student aspiring java. HTML|CSS|Java|Python|DSA|Git and GitHub.I design and build simple, responsive websites.</p>
                <button onclick="location.href='#projects'">View My Work</button>
            </div>

            <div class="hero-image">
                <img src="C:\Users\MADUGUNDU VEERESH\OneDrive\reddykandukuri\Camera Roll\Renuka_photo.jpeg">
            </div>
        </div>
    </section>

    <!-- About -->
    <section id="about">
        <h2>About Me</h2>
        <p>I am a passionate Computer Science and Engineering (CSE) student with a strong interest in Java programming and software development. I enjoy building logical solutions and continuously improving my coding skills.
I have a keen enthusiasm for learning new technologies and staying updated with the latest trends in the tech world. My curiosity drives me to explore concepts beyond academics and apply them in practical projects.
I am a quick learner, a problem-solver, and someone who believes in consistent growth. My goal is to develop efficient and impactful software solutions while expanding my technical knowledge.</p>
    </section>

    <!-- Skills -->
    <section id="skills">
        <h2>Skills</h2>
        <div class="skills">
            <div class="skill">C</div>
            <div class="skill">HTML</div>
            <div class="skill">CSS</div>
            <div class="skill">Java</div>
            <div class="skill">Python</div>
            <div class="skill">DSA with Java</div>
        </div>
    </section>

    <!-- Projects -->
    <section id="projects">
        <h2>Projects</h2>
        <div class="projects">
            <div class="project-card">
                <h3>Portfolio Website</h3>
                <p>Personal portfolio using HTML and CSS.</p>
                <p>Photography portfolio using HTML, CSS, Javascript and Bootstrap</p>
            </div>
        </div>
    </section>

    <!-- Certifications -->
    <section id="certifications">
        <h2>Certifications</h2>
        <div class="certifications">
            <div class="cert-card">
                <h3>AI Skills</h3>
                <p>AI Skills Passport by EY</p>
                <p><strong>Platform:</strong> Microsoft</p>
            </div>
            <div class="cert-card">
                <h3>NPTEL Courses</h3>
                <p>Certificate of DBMS and English Language for Competetive Exams</p>
                <p><strong>Platform:</strong> NPTEL</p>
            </div>
	    <div class="cert-card">
                <h3>Ai & Ml</h3>
                <p>Internship completion of Ai & Ml</p>
                <p><strong>Platform:</strong>SmartBridge Educational Services Pvt. Ltd</p>
            </div>

        </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <a href="mailto:example@gmail.com">Email: renukamadugundu30@gmail.com</a>
        <a href="#">GitHub: https://github.com/renukamadugundu</a>
        <a href="#">LinkedIn: https://www.linkedin.com/in/madugundu-renuka-a616a7378</a>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 My Portfolio</p>
    </footer>

</body>
</html>
