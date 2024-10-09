<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Habibeh Pourmand Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --main-bg-color: #f7f9fc;
      --main-text-color: #333;
      --main-link-color: #007bff;
      --main-link-hover-color: #0056b3;
      --main-skill-bg-color: #007bff;
    }
    [data-theme="dark"] {
      --main-bg-color: #1e1e1e;
      --main-text-color: #ccc;
      --main-link-color: #007bff;
      --main-link-hover-color: #0056b3;
      --main-skill-bg-color: #007bff;
    }
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      background-color: var(--main-bg-color);
      color: var(--main-text-color);
      transition: background-color 0.3s, color 0.3s;
    }
    h2 {
      color: var(--main-link-color);
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
      background-color: var(--main-link-color);
      padding: 10px 20px;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }
    a:hover {
      background-color: var(--main-link-hover-color);
    }
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
      background-color: var(--main-skill-bg-color);
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
      background-color: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      width: 280px;
      padding: 20px;
      transition: transform 0.3s ease, background-color 0.3s;
    }
    .project:hover {
      transform: scale(1.05);
      background-color: #f0f0f0;
    }
    .project h3 {
      background-color: var(--main-link-color);
      color: white;
      padding: 10px;
      margin: -20px -20px 15px -20px;
      border-radius: 10px 10px 0 0;
    }
    .project p {
      font-size: 0.9rem;
      margin: 15px 0;
    }
    footer {
      background-color: var(--main-text-color);
      color: white;
      text-align: center;
      padding: 20px;
    }
    .dark-toggle {
      position: absolute;
      top: 20px;
      right: 20px;
      cursor: pointer;
      background-color: var(--main-link-color);
      color: white;
      padding: 10px;
      border: none;
      border-radius: 5px;
    }
  </style>
</head>
<body>
  <button class="dark-toggle" onclick="toggleDarkMode()">Toggle Dark Mode</button>
  <h2>Habibeh Pourmand Portfolio</h2>

  <section id="about">
    <h2>About Me</h2>
    <p>Hi, I’m Habibeh! I’m a data professional with a strong math background and over three years of experience as a Data Analyst. I specialize in transforming complex datasets into actionable insights that drive business success and innovation.
    </p>
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
        <div class="skill" style="width: 90%;">Tableau</div>
      </div>
      <div class="skill-bar">
        <div class="skill" style="width: 90%;">Excel</div>
      </div>
    </div>
  </section>

  <section class="project-container" id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Customer Retention Analysis</h3>
      <p>Analyzed customer behavior data using Python, SQL, and Tableau, resulting in an 18% increase in customer retention within 8 months.</p>
      <a href="https://github.com/hpourmand/Customer-Shopping-Trends-" target="_blank" class="btn">View on GitHub</a>
    </div>
    <div class="project">
      <h3>Library</h3>
      <p>Built a predictive model using machine learning algorithms to forecast sales trends, leading to a 15% improvement in inventory management.</p>
      <a href="https://github.com/hpourmand/Library" target="_blank" class="btn">View on GitHub</a>
    </div>
    <div class="project">
      <h3>Emergency-911-calls</h3>
      <p>Developed a dynamic Tableau dashboard to visualize KPIs, which improved decision-making speed for marketing and sales teams by 30%.</p>
      <a href="https://github.com/hpourmand/Emergency-911-calls" target="_blank" class="btn">View on GitHub</a>
    </div>
    <div class="project">
      <h3>Analyzing-Global-Trends-in-Programming-Database-Skills-and-IDE-Demand</h3>
      <p>Built a predictive model using machine learning algorithms to forecast sales trends, leading to a 15% improvement in inventory management.</p>
      <a href="https://github.com/hpourmand/Analyzing-Global-Trends-in-Programming-Database-Skills-and-IDE-Demand" target="_blank" class="btn">View on GitHub</a>
    </div>
    <div class="project">
      <h3>U.S.-Stock-Market</h3>
      <p>Built a predictive model using machine learning algorithms to forecast sales trends, leading to a 15% improvement in inventory management
