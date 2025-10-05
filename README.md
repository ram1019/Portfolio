
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pallela Kalyan Ram Reddy | Portfolio</title>
    <link rel="icon" type="image/png" href="images/favicon.png"> 
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
</head>
<body>
  <style>
    
:root {
    --primary-color: #300562; 
    --secondary-color: #cf57dc; 
    --background-color: #f8f9fa; 
    --text-color: #07090b; 
    --font-heading: 'Playfair Display', serif;
    --font-body: 'Roboto', sans-serif;
}

* {
    
    background-repeat: no-repeat;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background: url(https://average-blush-use5kbnhoa.edgeone.app/240_F_1407999459_PNYvgDFLch8cvTm2PyBkO5tCbbVL7I4D.jpg) center/cover no-repeat;
    font-family: var(--font-body);
    color: var(--text-color);
    background-color: var(--background-color);
    line-height: 1.5;
}

h1, h2, h3 {
    font-family: var(--font-heading);
    color: var(--primary-color);
    margin-bottom: 0.5em;
}

h1 { font-size: 3rem; }
h2 { font-size: 2rem; }
h3 { font-size: 1.5rem; }

a {
    text-decoration: none;
    color: var(--primary-color);
    transition: color 0.3s ease;
}

a:hover {
    color: var(--secondary-color);
}

.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1.5rem 5%;
    background-color: deeppink;
text-decoration: underline;
    position: sticky;
    top: 0;
    z-index: 100;
    border: 1px solid black;
}

.logo {
    font-size: 1.5rem;
    font-weight: 700;
    font-style: normal;
}

.nav-links {
    list-style: none;
    display: flex;
    color: navajowhite;

}

.nav-links li {
    margin-left: 2px;

}

.hamburger-menu {
    display: none; 
    background: none;
    border: none;
    font-size: 1.5rem;
    cursor: pointer;
    color: var(--primary-color);
}

.hero-section {
    min-height: 80vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 4rem 5%;
}

.role {
    font-size: 1.25rem;
    color: var(--secondary-color);
    margin-bottom: 1.5rem;
}

.cta-button {
    display: inline-block;
    padding: 10px 20px;
    margin: 0 10px;
    background-color: var(--primary-color);
    color: rgb(153, 14, 14);
    border-radius: 5px;
    font-weight: 700;
    transition: background-color 0.3s ease, transform 0.2s ease;
    border: 2px solid var(--primary-color);
}

.cta-button:hover {
    background-color: #0056b3; 
    transform: translateY(-2px);
}

.cta-button.secondary {
    background-color: transparent;
    color: var(--primary-color);
    border: 2px solid var(--primary-color);
}

.cta-button.secondary:hover {
    background-color: var(--primary-color);
    color: white;
}

section {
    padding: 4rem 5%;
    text-align: center;
    margin-bottom: 2rem;
}

h2{
    text-decoration: double;
}

.about-content {
    display: flex;
    gap: 30px;
    align-items: center;
    text-align: left;
    max-width: 1000px;
    margin: 0 auto 30px;
    font-weight: bold;
}

.profile-photo {
    width: 400px;
    height: 400px;
    object-fit: cover;
    border-radius: 10;
    border: 3px solid var(--primary-color);
}

.skills-showcase ul {
    list-style: none;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 15px;
    margin-top: 15px;
}

.skills-showcase li {
    background-color: var(--primary-color);
    color: rgb(188, 31, 123);
    padding: 8px 15px;
    border-radius: 20px;
    font-size: 0.9rem;
    font-weight: 700;
}


.projects-grid {
    display: grid;
    background-color: rgb(8, 10, 10);
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
    margin-top: 30px;
}

.project-card {
    background-color: deeppink;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: left;
    transition: transform 0.3s ease;
}

.project-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}

.project-card img {
    width: 100%;
    height: 450px;
    object-fit: cover;
    border-radius: 4px;
    margin-bottom: 15px;
}

.tech-stack {
    display: block;
    font-size: 0.8rem;
    color: var(--secondary-color);
    margin: 10px 0;
    font-style: italic;
}

.project-links a {
    margin-right: 15px;
    font-weight: 700;
}



.social-links a {
    font-size: 1.2rem;
    margin: 0 15px;
    font-weight: 700;
}


.footer {
    background-color: var(--text-color);
    color: var(--background-color);
    padding: 1.5rem 5%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 0.9rem;
}

.footer-social-links a {
    color: rgb(223, 85, 85);
    margin-left: 0;
}


@media (max-width: 768px) {
    h1 { font-size: 2.5rem; }
    h2 { font-size: 1.75rem; }
    
    .nav-links {
        display: none;
        flex-direction: column;
        width: 100%;
        position: absolute;
        top: 60px; 
        left: 0;
        background-color: rgb(161, 27, 27);
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        padding: 10px 0;
    }

    .nav-links.active {
        display: flex; 
    }

    .nav-links li {
        margin: 10px 0;
        text-align: center;
    }

    .hamburger-menu {
        display: block; 
    }

    .about-content {
        flex-direction: column;
        text-align: center;
    }
    
    .profile-photo {
        margin-bottom: 20px;
    }

    .skills-showcase ul {
        justify-content: flex-start;
        padding-left: 0;
    }

    .skills-showcase h3 {
        text-align: left;
    }

    .footer {
        flex-direction: column;
        text-align: center;
    }

    .footer-social-links {
        margin-top: 10px;
    }
  
}
  footer p{
      position: relative;
      left: 400px;
    }
    </style>
    <header class="header">
        <div class="logo">Pallela Kalyan Ram Reddy</div>
        <nav class="navbar">
            <ul class="nav-links">
                <img src="https://informal-green-1odbdxsbot.edgeone.app/home%20pinkkkkkk.png" height="25px width:25px;">
                <li><a href="#home">Home</a></li>
                <img src="https://controversial-plum-heffp37lfy.edgeone.app/1876966-200.png" height="25px width:25px">
                <li><a href="#about">About</a></li>
                <img src="https://endless-brown-z9upfaxbyq.edgeone.app/12148682.png" height="25px width:25px;">
                <li><a href="#projects">Projects</a></li>
                <img src="https://desirable-lavender-drars33tze.edgeone.app/pingk.png" height="25px width:25px;">
                <li><a href="#contact">Contact</a></li>
            </ul>
            <button class="hamburger-menu" aria-label="Toggle navigation">&#9776;</button>
        </nav>
    </header>

    <main>
        <section id="home" class="hero-section">
            <div class="hero-content">
                <h1>Hi, I'm Pallela Kalyan Ram Reddy</h1>
                <p class="role"> A Web Developer</p>
               
                <a href="#projects" class="cta-button secondary">View My Work</a>
            </div>
        </section>
        <section id="about" class="about-section">
            <h2>About Me</h2>
            <div class="about-content">
                <img src="https://blank-sapphire-uivuwgsndf.edgeone.app/kalyan%20ram%202025-10-05%20at%2004.24.19_262749e9.jpg " alt="A professional photo of Pallela Kalyan Ram Reddy" class="profile-photo">
                <p>
                I'm Pallela Kalyan Ram Reddy. I was born in Andhra Pradesh, Currently I'm living in Benguluru. My ever time hobbies are playing outdoor and indoor games, Listening to music.<br>
                <span style="color: chocolate;">My Academics</span><br>
                I have passed my 10th in 2023 with a marks of 554, out of 600. My Secondary Education was State syllabus<br>
                Comming to my Intermediate, I have passed my Intermediate in 2025 with a marks of 931, out of 1000. My Intermediate Education was State syllabus.<br>
                <span style="color: rgb(131, 4, 4);">Languages</span><br>
                Telugu<br>
                English<br>
                Hindi
                </p>
            </div>
            <div class="skills-showcase">
                <h2>Technical Skills</h2>
                <ul>
                    <li>HTML / CSS</li>
                    <li>Java</li>
                    <li>JavaScript</li>
                </ul>
            </div>
        </section>
        <section id="projects" class="projects-section">
            <h2>Projects</h2>
            <div class="projects-grid">
                <article class="project-card">
                    <img src="https://endless-aquamarine-iu40iexrp5.edgeone.app/Screenshot%202025-10-05%20051544.png" alt="Screenshot of Project Title 1">
                    <h3>Project-1</h3>
                    <p>Mini Profile Card</p>
                    <span class="tech-stack">HTML | CSS</span>
                    <div class="project-links">
                        <a href="https://github.com/ram1019" target="_blank">GitHub</a>
                       
                    </div>
                </article>
                <article class="project-card">
                    <img src="https://slim-coffee-jlvmx8obk7.edgeone.app/Screenshot%202025-10-05%20072530.png" alt="Screenshot of Project Title 2">
                    <h3>Project-2</h3>
                    <p>Famous Tollywood Actors</p>
                    <span class="tech-stack">HTML | CSS</span>
                    <div class="project-links">
                        <a href="https://github.com/ram1019" target="_blank">GitHub</a>
                      
                    </div>
                </article>
            </div>
        </section>
        <section id="contact" class="contact-section">
            <h2>Get In Touch</h2>
            <p>I'm currently looking for new opportunities. Feel free to connect!<br>Mail to :<span style="color: indigo;">rampallela42@gmail.com</p>
            <div class="social-links">
                <a href="https://www.instagram.com/kk_ram_1019/?next=%2F&hl=en" target="_blank">Instagram</a>
                <a href="https://www.linkedin.com/in/pallela-kalyan-ram-reddy-772096373/" target="_blank">LinkedIn</a>
                <a href="https://github.com/ram1019" target="_blank">GitHub</a>
            </div>
            </section>
    </main>
    <footer class="footer">
        <p>&copy; 2025 Reddy. All rights reserved.</p>
        <div class="footer-social-links">
            <img  src="https://little-turquoise-ttbyyhixdj.edgeone.app/download.png" height="25px width: 25px">
            <a href="https://www.linkedin.com/in/pallela-kalyan-ram-reddy-772096373/" aria-label="LinkedIn profile">In</a>
            <img src="https://critical-emerald-8ew8iabwsx.edgeone.app/git-hub-logo-octocat-9z8a4hy1cg9s8mer.png" height="25px width:25px;">
            <a href="https://github.com/ram1019" aria-label="GitHub profile">Git</a>
        </div>
    </footer>
</body>
</html> 
