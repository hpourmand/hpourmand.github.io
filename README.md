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
      background-color: #f4f4f9; /* Light gray background */
      color: #333; /* Dark gray text */
      display: flex; /* Use flexbox for layout */
    }
    .navbar {
      background-color: #005f5f; /* Darker teal for navbar */
      padding: 20px;
      width: 200px; /* Set a fixed width for the navbar */
      height: 100vh; /* Full height */
      position: fixed; /* Fixed position */
      overflow-y: auto; /* Scroll if necessary */
      text-align: center; /* Center-align content */
    }
    .profile-picture {
      width: 100px; /* Adjust width to fit */
      height: auto;
      border-radius: 50%; /* Make it circular */
      margin-bottom: 15px; /* Space below the picture */
    }
    .navbar a {
      color: white;
      text-decoration: none;
      display: block; /* Make links block elements */
      padding: 10px;
      margin: 5px 0; /* Space between links */
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }
    .navbar a:hover {
      background-color: #008080; /* Teal on hover */
    }
    .content {
      margin-left: 220px; /* Space for the navbar */
      padding: 20px; /* Padding for content */
      flex-grow: 1; /* Allow content to grow */
    }
    h2 {
      color: #008080; /* Teal */
      text-align: center;
      margin-bottom: 30px;
    }
    section {
      padding: 60px 20px;
      text-align: center;
    }
    p {
      margin-bottom: 40px;
      font-size: 1.1rem;
      line-height: 1.6;
    }
    a.btn {
      text-decoration: none;
      color: #fff;
      background-color: #008080; /* Teal */
      padding: 10px 20px;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }
    a.btn:hover {
      background-color: #005f5f; /* Darker teal */
    }
    .skill-bar-container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    .skill-bar {
      position: relative;
      background-color: #ddd; /* Light gray for skill bars */
      border-radius: 10px;
      margin-bottom: 20px;
      height: 30px;
      width: 80%;
      max-width: 400px;
      margin-left: auto;
      margin-right: auto;
    }
    .skill {
      background-color: #008080; /* Teal */
      height: 100%;
      border-radius: 10px;
      text-align: left;
      padding-left: 10px;
      line-height: 30px;
      color: white;
      font-weight: 600;
      transition: width 1.5s ease-in-out;
    }
    .project-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .project {
      background-color: #fff; /* White for project cards */
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
      width: 280px;
      padding: 20px;
      transition: transform 0.3s ease, background-color 0.3s;
    }
    .project:hover {
      transform: scale(1.05);
      background-color: #f0f0f0; /* Slightly darker gray on hover */
    }
    .project h3 {
      background-color: #008080; /* Teal for project titles */
      color: white;
      padding: 10px;
      margin: -20px -20px 15px -20px;
      border-radius: 10px 10px 0 0;
    }
    .project p {
      font-size: 0.9rem;
      margin: 15px 0;
      color: #333; /* Dark gray text for project descriptions */
    }
    footer {
      background-color: #005f5f; /* Darker teal */
      color: white;
      text-align: center;
      padding: 20px;
    }
    .social-links a {
      margin: 0 10px;
      transition: color 0.3s ease;
    }
    .social-links a:hover {
      color: #008080; /* Teal */
    }
  </style>
</head>
<body>

  <div class="navbar">
    <img src="profile.jpg" alt="My Picture" class="profile-picture">
    <h2>Navigation</h2>
    <a href="#about">About Me</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </div>

  <div class="content">
    <section id="about">
      <h2>About Me</h2>
      <p>Hi, I’m Habibeh! I’m a data professional with a strong math background and over three years of experience as a Data Analyst. I specialize in transforming complex datasets into actionable insights that drive business success and innovation.</p>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <div class="skill-bar-container">
        <div class="skill-bar">
          <div class="skill" style="width: 95%;">Python</div>
        </div>
        <div class="skill-bar">
          <div class="skill" style="width: 90%;">SQL</div>
        </div>
        <div class="skill-bar">
          <div class="skill" style="width: 95%;">Tableau</div>
        </div>
        <div class="skill-bar">
          <div class="skill" style="width: 90%;">Azure</div>
        </div>
        <div class="skill-bar">
          <div class="skill" style="width: 90%;">Power BI</div>
        </div>
        <div class="skill-bar">
          <div class="skill" style="width: 95%;">Excel</div>
        </div>
        <div class="skill-bar">
          <div class="skill" style="width: 85%;">Apache Spark</div>
        </div>
        <div class="skill-bar">
          <div class="skill" style="width: 80%;">Snowflake</div>
        </div>
      </div>
    </section>

    <section class="project-container" id="projects">
      <h2>Projects</h2>
      <!-- Add project cards here -->
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <div class="social-links">
        <a href="mailto:habibeh.pourmand@gmail.com">Email</a>
        <a href="https://www.linkedin.com/in/habibehpourmand" target="_blank">LinkedIn</a>
        <a href="https://github.com/hpourmand" target="_blank">GitHub</a>
      </div>
    </section>
  </div>

  <footer>
    <p>© 2024 Habibeh Pourmand. All rights reserved.</p>
  </footer>

</body>
</html>

