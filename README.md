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
      background-color: #f7f9fc;
      color: #333;
    }

    h2 {
      color: #007bff;
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

    /* Skill Bars */
    .skill-bar-container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }

    .skill-bar {
      position: relative;
      background-color: #e0e0e0;
      border-radius: 10px;
      margin-bottom: 20px;
      height: 30px;
      width: 80%;
      max-width: 400px;
      margin-left: auto;
      margin-right: auto;
    }

    .skill {
      background-color: #007bff;
      height: 100%;
      border-radius: 10px;
      text-align: left;
      padding-left: 10px;
      line-height: 30px;
      color: white;
      font-weight: 600;
      transition: width 1.5s ease-in-out;
    }

    /* Projects Section */
    .project-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .project {
      background-color: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      width: 280px;
      padding: 20px;
      transition: transform 0.3s ease;
    }

    .project:hover {
      transform: scale(1.05);
    }

    .project h3 {
      background-color: #007bff;
      color: white;
      padding: 10px;
      margin: -20px -20px 15px -20px;
      border-radius: 10px 10px 0 0;
    }

    .project p {
      font-size: 0.9rem;
      margin: 15px 0;
    }

    /* Footer */
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 20px;
    }

    /* Media Queries */
    @media (max-width: 768px) {
      .project-container {
        flex-direction: column;
        align-items: center;
      }

      .skill-bar {
        width: 90%;
      }
    }
  </style>
</head>

<body>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>I am a data analyst passionate about turning raw data into actionable insights. I enjoy working with Python, SQL, and data visualization tools to deliver high-quality results.</p>
  </section>

  <!-- Skills Section -->
  <section id="skills">
    <h2>Skills</h2>
    <div class="skill-bar-container">
      <div class="skill-bar">
        <div class="skill" style="width: 90%;">Python</div>
      </div>
      <div class="skill-bar">
        <div class="skill" style="width: 85%;">SQL</div>
      </div>
      <div class="skill-bar">
        <div class="skill" style="width: 80%;">Tableau</div>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="project-container">
      <div class="project">
        <h3>Customer Retention Analysis</h3>
        <p>Analyzed customer behavior data resulting in an 18% increase in retention.</p>
        <a href="#">View Project</a>
      </div>
      <div class="project">
        <h3>Customer Shopping Trends</h3>
        <p>Identified shopping patterns and optimized marketing strategies.</p>
        <a href="#">View Project</a>
      </div>
      <div class="project">
        <h3>Library Analytics</h3>
        <p>Created a dashboard in Tableau to analyze library book trends.</p>
        <a href="#">View Project</a>
      </div>
      <div class="project">
        <h3>U.S. Stock Market Data</h3>
        <p>Predicted stock trends using historical data and Python.</p>
        <a href="#">View Project</a>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2024 Habibeh Pourmand</p>
  </footer>

</body>
</html>
