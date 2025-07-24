<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>D. Imran Basha | Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background: #1e1e2f;
      color: white;
      padding: 30px 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      background: #2c2c3c;
      padding: 12px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      color: #00ffd5;
    }
    .section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
      text-align: center;
    }
    .section h2 {
      font-size: 2em;
      margin-bottom: 10px;
    }
    .section p {
      font-size: 1.1em;
      color: #555;
    }
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 10px 20px;
      background: #1e1e2f;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      transition: 0.3s;
    }
    .btn:hover {
      background: #00ffd5;
      color: black;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    ul li {
      padding: 5px 0;
      font-weight: 500;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #2c2c3c;
      color: white;
      margin-top: 50px;
    }
  </style>
</head>
<body>

  <header>
    <h1>D. Imran Basha</h1>
    <p>Future Software Engineer | AI Enthusiast | Developer</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#resume">Resume</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="section" id="about">
    <h2>About Me</h2>
    <p>Myself Imran. I'm currently pursuing B.Tech 2nd year in <strong>MITS Deemed University</strong>, in the department of <strong>Computer Science Engineering – Artificial Intelligence</strong>.</p>
    <p>I aim to become a <strong>Software Engineer</strong> with a focus on <strong>Frontend & Backend Development, DevOps Engineering</strong>, and also work toward building advanced models in <strong>Artificial Intelligence</strong>.</p>
  </section>

  <section class="section" id="skills">
    <h2>My Skills</h2>
    <ul>
      <li>C Language</li>
      <li>C++</li>
      <li>Java</li>
      <li>Python</li>
      <li>Data Structures</li>
    </ul>
  </section>

  <section class="section" id="projects">
    <h2>Projects</h2>
    <ul>
      <li><strong>Trigonometric Calculator</strong> – performs sin, cos, tan functions easily</li>
      <li><strong>Tally System</strong> – simple tool for business merchants</li>
      <li><strong>Diet Planner</strong> – helps users maintain a healthy food routine</li>
    </ul>
    <p>You can try one of my projects:</p>
    <a href="calculator.html" class="btn">Try Calculator</a>
  </section>

  <section class="section" id="resume">
    <h2>Resume</h2>
    <a href="your-resume.pdf" class="btn" target="_blank">View My Resume</a>
  </section>

  <section class="section" id="contact">
    <h2>Contact Me</h2>
    <p>Email: yourmail@example.com</p>
    <p>GitHub: github.com/yourusername</p>
    <p>LinkedIn: linkedin.com/in/yourprofile</p>
  </section>

  <footer>
    <p>&copy; 2025 D. Imran Basha. All Rights Reserved.</p>
  </footer>

</body>
</html>
