<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Harsh Shukla | Portfolio</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#0f172a;
    color:white;
    line-height:1.6;
}

header{
    min-height:100vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:20px;
}

h1{
    font-size:4rem;
    margin-bottom:10px;
}

.highlight{
    color:#38bdf8;
}

.subtitle{
    font-size:1.3rem;
    color:#cbd5e1;
}

.btn{
    margin-top:25px;
    padding:12px 24px;
    background:#38bdf8;
    color:black;
    text-decoration:none;
    border-radius:8px;
    font-weight:bold;
}

section{
    padding:80px 10%;
}

.section-title{
    text-align:center;
    margin-bottom:40px;
    color:#38bdf8;
}

.skills{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:15px;
}

.skill{
    background:#1e293b;
    padding:12px 20px;
    border-radius:8px;
}

.project-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.project{
    background:#1e293b;
    padding:20px;
    border-radius:10px;
}

footer{
    text-align:center;
    padding:30px;
    background:#020617;
}
</style>
</head>
<body>

<header>
    <h1>Harsh <span class="highlight">Shukla</span></h1>
    <p class="subtitle">Personal Portfolio Website</p>
    <a href="#contact" class="btn">Contact Me</a>
</header>

<section id="about">
    <h2 class="section-title">About Me</h2>
    <p style="text-align:center;">
        Welcome to my portfolio website. I am Harsh Shukla, passionate about technology,
        learning new skills, and building creative projects.
    </p>
</section>

<section id="skills">
    <h2 class="section-title">Skills</h2>
    <div class="skills">
        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">JavaScript</div>
        <div class="skill">Python</div>
        <div class="skill">Web Development</div>
    </div>
</section>

<section id="projects">
    <h2 class="section-title">Projects</h2>
    <div class="project-grid">
        <div class="project">
            <h3>Portfolio Website</h3>
            <p>Responsive personal portfolio website.</p>
        </div>

        <div class="project">
            <h3>Web Application</h3>
            <p>Add your project details here.</p>
        </div>

        <div class="project">
            <h3>Future Project</h3>
            <p>Add more projects as you build them.</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2 class="section-title">Contact</h2>
    <p style="text-align:center;">
        Email: your-email@example.com
    </p>
</section>

<footer>
    <p>© 2026 Harsh Shukla. All Rights Reserved.</p>
</footer>

</body>
</html>
