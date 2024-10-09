<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Habibeh Pourmand Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    /* General Styling */
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      background-color: #f4f4f4;
      color: #333;
    }

    h2, h3 {
      color: #333;
      text-align: center;
      margin-top: 0;
    }

    section {
      padding: 60px 20px;
    }

    a {
      text-decoration: none;
      color: #fff;
      background-color: #007bff;
      padding: 10px 20px;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }

    a:hover {
      background-color: #0056b3;
    }

    /* Fancy Animations */
    .skill-bar {
      position: relative;
      background-color: #e0e0e0;
      border-radius: 10px;
      margin-bottom: 20px;
      height: 25px;
      width: 80%;
      margin-left: auto;
      margin-right: auto;
    }

    .skill {
      background-color: #007bff;
      height: 100%;
      border-radius: 10px;
      text-align: center;
      line-height: 25px;
      color: white;
      font-weight: 600;
      animation: growSkill 2s ease-in-out;
    }

    @keyframes growSkill {
      from { width: 0; }
      to { width: 100%; }
    }

    /* Card Style for Projects */
    .project {
      display: inline-block;
      background: #fff;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      border-radius: 10px;
      margin: 20px;
      width: 300px;
      transition: transform 0.3s ease;
    }

    .project:hover {
      transform: translateY(-10px);
    }

    .project h3 {
      background-color: #007bff;
      color: #fff;
      padding: 15px;
      border-radius: 10px 10px 0 0;
    }

    .project p {
      padding: 20px;
      font-size: 0.9rem;
    }

    .project a {
      display: block;
      text-align: center;
      margin-bottom: 15px;
      background-color: #ff6600;
      padding: 10px;
    }

    /* Footer */
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 20px;
    }

    /* Smooth Scrolling */
    html {
      scroll-behavior: smooth;
    }

    /* Media Queries for Responsiveness */
    @media (max-width: 768px) {
      .project {
        width: 100%;
        margin: 10px 0;
      }
    }
  </style>
</head>

<body>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p style="text-align: center;">I am a data analyst passionate about turning raw data into actionable insights. I enjoy working with Python, SQL, and data visualization tools to deliver high-quality results.</p>
  </section>

  <!-- Skills Section with Animated Skill Bars -->
  <section id="skills">
    <h2>Skills</h2>
    <div class="skill-bar">
      <div class="skill" style="width: 90%;">Python</div>
    </div>
    <div class="skill-bar">
      <div class="skill" style="width: 85%;">SQL</div>
    </div>
    <div class="skill-bar">
      <div class="skill" style="width: 80%;">Tableau</div>
    </div>
  </section>

  <!-- Projects Section with Fancy Card Layouts -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Customer Retention Analysis</h3>
      <p>Used Python and SQL to analyze customer behavior data, which led to an 18% increase in customer retention over 6 months.</p>
      <a href="#">View Project</a>
    </div>

    <div class="project">
      <h3>Customer Shopping Trends</h3>
      <p>Identified shopping patterns using data visualization tools, leading to optimized marketing strategies and increased sales.</p>
      <a href="#">View Project</a>
    </div>

    <div class="project">
      <h3>Library Analytics</h3>
      <p>Developed a dashboard in Tableau to analyze book lending trends, resulting in better inventory management for popular titles.</p>
      <a href="#">View Project</a>
    </div>

    <div class="project">
      <h3>U.S. Stock Market Data</h3>
      <p>Utilized historical stock data to predict future trends and provided insights for investment strategies.</p>
      <a href="#">View Project</a>
    </div>

    <div class="project">
      <h3>Emergency 911 Calls</h3>
      <p>Analyzed 911 call data to identify common emergencies, helping local authorities improve response times.</p>
      <a href="#">View Project</a>
    </div>

    <div class="project">
      <h3>Global Trends in Programming and Database Skills</h3>
      <p>Analyzed global demand for programming languages and database technologies, influencing corporate training programs.</p>
      <a href="#">View Project</a>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2024 Habibeh Pourmand</p>
  </footer>

</body>
</html>
