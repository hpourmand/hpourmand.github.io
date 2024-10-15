<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: 'Raleway', sans-serif;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      background-color: #f4f4f9; /* Light Gray */
      color: #333; /* Darker Text */
    }
    header {
      background-color: #008080; /* Teal */
      color: white;
      padding: 20px 0;
      position: fixed;
      width: 100%;
      top: 0;
      left: 0;
      z-index: 1000;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }
    nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
    }
    nav ul li {
      margin: 0 15px;
    }
    nav ul li a {
      text-decoration: none;
      color: white;
      font-size: 1.2rem;
      padding: 5px 10px;
    }
    nav ul li a:hover {
      background-color: #005f5f; /* Darker Teal */
      border-radius: 5px;
    }
    section {
      padding: 100px 20px 60px; /* Adjust padding to account for the fixed navbar */
      text-align: center;
    }
    h2 {
      color: #008080; /* Teal */
      margin-bottom: 30px;
    }
    /* Other styles remain the same */
  </style>
</head>
<body>

  <!-- Navbar -->
  <header>
    <nav>
      <ul>
        <li><a href="#about">About Me</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- About Me Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>Hi, I’m Habibeh! I’m a data professional with a strong math background and over three years of experience as a Data Analyst. I specialize in transforming complex datasets into actionable insights that drive business success and innovation.</p>
  </section>

  <!-- Skills Section -->
  <section id="skills">
    <h2>Skills</h2>
    <div class="skill-bar-container">
      <!-- Skills bar code remains the same -->
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="project-container">
    <h2>Projects</h2>
    <div class="project">
      <!-- Projects remain the same -->
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <p>If you'd like to get in touch, feel free to reach out via any of the links below.</p>
    <div class="social-links">
      <a href="https://www.linkedin.com/in/your-profile" target="_blank">LinkedIn</a>
      <a href="https://github.com/your-profile" target="_blank">GitHub</a>
      <a href="mailto:habibeh@example.com">Email</a>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2024 Habibeh Pourmand</p>
  </footer>

</body>
</html>
