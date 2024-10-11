<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>

  <style>
    body {
      font-family: 'Raleway', sans-serif;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      background-color: #f0f0f0; /* Light background */
      color: #333; /* Dark text */
      background-image: url('/Users/hpourmand/Desktop.prof.jpg'); /* Add your background image here */
      background-size: cover;
      background-position: center;
      background-attachment: fixed;
    }
    nav {
      background-color: #ffffff; /* White background for the navbar */
      padding: 15px 0;
      position: sticky;
      top: 0;
      width: 100%;
      z-index: 1000;
    }
    nav ul {
      list-style-type: none;
      display: flex;
      justify-content: center;
      margin: 0;
      padding: 0;
    }
    nav ul li {
      margin: 0 20px;
    }
    nav ul li a {
      color: #006400; /* Dark green links */
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
    }
    nav ul li a:hover {
      color: #008000; /* Lighter green on hover */
    }
    h2 {
      color: #006400; /* Dark green headings */
      text-align: center;
      margin-bottom: 30px;
    }
    section {
      padding: 60px 20px;
      text-align: center;
      background-color: #ffffff; /* White background for sections */
    }
    p {
      margin-bottom: 40px;
      font-size: 1.1rem;
      line-height: 1.6;
    }
    a {
      text-decoration: none;
      color: white;
      background-color: #006400; /* Dark green buttons */
      padding: 10px 20px;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }
    a:hover {
      background-color: #008000; /* Lighter green on hover */
    }
    .skill-bar-container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    .skill-bar {
      position: relative;
      background-color: #ddd; /* Light background for skill bars */
      border-radius: 10px;
      margin-bottom: 20px;
      height: 30px;
      width: 80%;
      max-width: 400px;
      margin-left: auto;
      margin-right: auto;
    }
    .skill {
      background-color: #006400; /* Dark green for the skill bars */
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
      background-color: #ffffff; /* White background for project cards */
      border: 1px solid #ddd; /* Light border */
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      width: 280px;
      padding: 20px;
      transition: transform 0.3s ease, background-color 0.3s;
    }
    .project:hover {
      transform: scale(1.05);
      background-color: #f0f0f0; /* Light hover effect */
    }
    .project h3 {
      background-color: #006400; /* Dark green for project headers */
      color: white;
      padding: 10px;
      margin: -20px -20px 15px -20px;
      border-radius: 10px 10px 0 0;
    }
    footer {
      background-color: #ffffff; /* White footer */
      color: #333;
      text-align: center;
      padding: 20px;
    }
    .social-links a {
      margin: 0 10px;
      color: #006400; /* Green social links */
      transition: color 0.3s ease;
    }
    .social-links a:hover {
      color: #008000; /* Lighter green on hover */
    }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <nav>
    <ul>
      <li><a href="#about">About Me</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact Me</a></li>
    </ul>
  </nav>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>Hi, I’m Habibeh! I’m a data professional with a strong math background and over three years of experience as a Data Analyst. I specialize in transforming complex datasets into actionable insights that drive business success and innovation.</p>
  </section>

  <!-- Skills Section -->
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
        <div class="skill" style="width: 90%;">Azure</div>
      </div>
      <div class="skill-bar">
        <div class="skill" style="width: 95%;">Power BI</div>
      </div>
      <div class="skill-bar">
        <div class="skill" style="width: 95%;">Excel</div>
      </div>
      <div class="skill-bar">
        <div class="skill" style="width: 95%;">Apache Spark</div>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section class="project-container" id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Customer Shopping Trends Analysis</h3>
      <p>This project analyzes customer shopping trends using a dataset from www.kaggle.com. The analysis includes Exploratory Data Analysis (EDA), Behavioral Segmentation, and Predictive Modeling to uncover insights into customer behaviors, purchase patterns, and factors affecting customer satisfaction and loyalty.</p>
      <a href="https://github.com/hpourmand/Customer-Shopping-Trends-" target="_blank" class="btn">View on GitHub</a>
    </div>
    <div class="project">
      <h3>Analyzing Late Book Returns</h3>
      <p>A local library is facing frequent late returns of books and needs help understanding why this is happening. They want to analyze the data to identify causes and find ways to reduce late returns.</p>
      <a href="https://github.com/hpourmand/Library" target="_blank" class="btn">View on GitHub</a>
    </div>
    <div class="project">
      <h3>Analysis of 911 Calls Dataset</h3>
      <p>We analyze the '911 Calls' dataset from Kaggle, which includes information on emergency calls in the U.S., such as call types, timestamps, locations, and emergency details. Additionally, we conduct time series analysis on the dataset</p>
      <a href="https://github.com/hpourmand/Emergency-911-calls" target="_blank" class="btn">View on GitHub</a>
    </div>
    <div class="project">
      <h3>Identifying Future Programming Skills Trends</h3>
      <p>As Data Analysts for a global IT consulting firm, we will identify future skill requirements by analyzing data on in-demand programming skills. Our first task involves gathering information from job postings, training portals, and surveys to determine the top programming languages, database skills, and popular IDEs.</p>
      <a href="https://github.com/hpourmand/Analyzing-Global-Trends-in-Programming-Database-Skills-and-IDE-Demand" target="_blank" class="btn">View on GitHub</a>
    </div>
    <div class="project">
      <h3>Olympic Performance Analysis by Country</h3>
      <p>Analyzing each country's Olympic performance over time.</p>
      <a href="https://github.com/hpourmand/Olympics" target="_blank" class="btn">View on GitHub</a>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2024 Habibeh Pourmand. All rights reserved.</p>
    <div class="social-links">
      <a href="https://github.com/hpourmand" target="_blank">GitHub</a> |
      <a href="https://www.linkedin.com/in/hpourmand" target="_blank">LinkedIn</a>
    </div>
  </footer>

</body>
</html>
