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
        <p>We analyze the '911 Calls' dataset from Kaggle, which includes information on emergency calls in the U.S., such as call types, timestamps, locations, and emergency details. Additionally, we conduct time series analysis on the dataset.</p>
        <a href="https://github.com/hpourmand/Emergency-911-calls" target="_blank" class="btn">View on GitHub</a>
      </div>
      <div class="project">
        <h3>Identifying Future Programming Skills Trends</h3>
        <p>As Data Analysts for a global IT consulting firm, we will identify future skill requirements by analyzing data on in-demand programming skills. Our first task involves gathering information from job postings, training portals, and surveys to determine the top programming languages, database skills, and popular IDEs. We will scrape websites and access APIs to collect data in .csv, Excel, and database formats. After data wrangling, we’ll apply statistical analysis and create a dashboard using IBM Cognos Analytics, culminating in a presentation of our findings.</p>
        <a href="https://github.com/hpourmand/Analyzing-Global-Trends-in-Programming-Database-Skills-and-IDE-Demand" target="_blank" class="btn">View on GitHub</a>
      </div>
      <div class="project">
        <h3>Olympic Performance Analysis by Country</h3>
        <p>Analyzing each country's Olympic performance over time.</p>
        <a href="https://github.com/hpourmand/Olympic-Performance-Analysis" target="_blank" class="btn">View on GitHub</a>
      </div>
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
