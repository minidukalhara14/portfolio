
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="style.css">
    <link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
/>





    <title>My Portfolio</title>
</head>
<body>
    <nav class="navbar">
    <div class="nav-container">
        <h2 class="logo">Minidu</h2>
        <ul class="nav-links">
            <a href="#home">Home</a>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </div>
</nav>

    
    
    <div class="container">

        <div class="container">

    <section id="home" class="home-section">
    <div class="home-container">
        
        <div class="hero-image">
            <img src="images/mypic.jpg" alt="Minidu Photo">
        </div>

        <h1>Hi, I'm Minidu</h1>
        <h2>Frontend Developer</h2>
        <p>I'm a passionate computer science student learning web development. Welcome to my portfolio!</p>
        
    </div>
</section>

    <section id="about" class="about-section">
    <div class="about-container">

        <!-- About text -->
        <div class="about-text">
            <h2>About Me</h2>
            <p>
                Hi! I'm Minidu, a computer science student and aspiring frontend developer. I love building modern and responsive websites, learning new technologies, and improving my coding skills every day.
            </p>
            <p>
                I am passionate about web development, UI/UX design, and creating projects that solve real-world problems.
            </p>

            <!-- Skills Cards -->
            <div class="skills-cards">
                <div class="skill-card">
                    <i class="fa-brands fa-html5"></i>
                    <h3>HTML</h3>
                    <p>Semantic tags, forms, structure</p>
                </div>
                <div class="skill-card">
                    <i class="fa-brands fa-css3-alt"></i>
                    <h3>CSS</h3>
                    <p>Flexbox, Grid, Responsive design</p>
                </div>
                <div class="skill-card">
                    <i class="fa-brands fa-js-square"></i>
                    <h3>JavaScript</h3>
                    <p>DOM, events, basic logic</p>
                </div>
            </div>
        </div>

        <!-- About Image + Timeline -->
        <div class="about-image">
            <img src="images/pic.jpg" alt="About Me">

            <!-- Timeline -->
            <div class="timeline">
                <div class="timeline-item">
                    <span class="year">2023</span>
                    <p>Started learning HTML, CSS & JavaScript</p>
                </div>
                <div class="timeline-item">
                    <span class="year">2024</span>
                    <p>Built first web projects and portfolio</p>
                </div>
            </div>
        </div>

    </div>
</section>



    <section id="skills">
    <h2>Skills</h2>

    <div class="skills-container">
        <div class="skill-card">
            <i class="fab fa-html5 fa-3x" style="color:#e34c26;"></i>
            <h3>HTML</h3>
            <p>Basic structure, forms, semantic tags</p>
        </div>

        <div class="skill-card">
            <i class="fab fa-css3-alt fa-3x" style="color:#264de4;"></i>
            <h3>CSS</h3>
            <p>Layouts, colors, Flexbox, responsive basics</p>
        </div>

        <div class="skill-card">
            <i class="fab fa-js-square fa-3x" style="color:#f0db4f;"></i>
            <h3>JavaScript</h3>
            <p>DOM manipulation, events, basic logic</p>
        </div>
    </div>
</section>



    <section id="projects" class="projects-section">
    <div class="container">
        <h2>My Projects</h2>
        <div class="projects-grid">
            <div class="project-card">
                <img src="project1.jpg" alt="Project 1">
                <h3>Project One</h3>
                <p>Short description of your project.</p>
                <a href="#" class="btn">View</a>
            </div>
            <div class="project-card">
                <img src="project2.jpg" alt="Project 2">
                <h3>Project Two</h3>
                <p>Short description of your project.</p>
                <a href="#" class="btn">View</a>
            </div>
            <div class="project-card">
                <img src="project3.jpg" alt="Project 3">
                <h3>Project Three</h3>
                <p>Short description of your project.</p>
                <a href="#" class="btn">View</a>
            </div>
        </div>
    </div>
</section>


   <section id="contact" class="contact-section">
    <div class="container">
        <h2>Contact Me</h2>
        <p>If you want to work with me or have any questions, feel free to contact me!</p>

        <div class="contact-wrapper">

            <!-- Contact Info -->
            <div class="contact-info">
                <p><strong>Email:</strong> minidu@example.com</p>
                <p><strong>Phone:</strong> +94 7X XXX XXXX</p>
                <p><strong>Location:</strong> Sri Lanka</p>
            </div>

            <!-- Contact Form -->
            <form class="contact-form">
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" rows="5" required></textarea>
                <button type="submit">Send Message</button>
            </form>

        </div>
    </div>
</section>
<footer class="footer">
    <div class="footer-container">

        <p>© 2026 Minidu Kalhara. All Rights Reserved.</p>

        <div class="social-links">
            <a href="#" aria-label="GitHub"><i class="fa-brands fa-github"></i></a>
            <a href="#" aria-label="LinkedIn"><i class="fa-brands fa-linkedin"></i></a>
            <a href="#" aria-label="Facebook"><i class="fa-brands fa-facebook"></i></a>
        </div>

    </div>
</footer>



<script src="script.js"></script>
</body>
</html>
