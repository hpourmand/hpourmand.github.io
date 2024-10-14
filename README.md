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
    a {
      text-decoration: none;
      color: #fff;
      background-color: #008080; /* Teal */
      padding: 10px 20px;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }
    a:hover {
      background-color: #005f5f; /* Darker Teal */
    }
    .skill-bar-container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    .skill-bar {
      position: relative;
      background-color: #d3d3d3; /* Soft Gray */
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
      background-color: #fff; /* White */
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      width: 280px;
      padding: 20px;
      transition: transform 0.3s ease, background-color 0.3s;
    }
    .project:hover {
      transform: scale(1.05);
      background-color: #f0f0f0; /* Lighter Gray */
    }
    .project h3 {
      background-color: #008080; /* Teal */
      color: white;
      padding: 10px;
      margin: 0 -20px 15px -20px; /* Remove top margin and adjust */
      border-radius: 10px 10px 0 0;
      display: block; /* Ensure it's on a separate line */
    }
    .project p {
      font-size: 0.9rem;
      margin: 15px 0;
      color: #333;
    }
    footer {
      background-color: #005f5f; /* Darker Teal */
      color: white;
      text-align: center;
      padding: 20px;
    }
    .social-links a {
      margin: 0 10px;
      color: #fff; /* Make text white for better visibility */
      font-weight: bold; /* Bold text */
    }
    .social-links a:hover {
      color: #005f5f;
    }
  </style>
</head>
<body>

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
      <p>We analyze the '911 Calls' dataset from Kaggle, which includes information on emergency calls in the U.S., such as call types, timestamps, locations, and emergency details. Additionally, we conduct time series analysis on the dataset</p>
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
      <a href="https://github.com/hpourmand/Olympics" target="_blank" class="btn">View on GitHub</a>
    </div>
  </section>

  <footer>
    <p>© 2024 Habibeh Pourmand</p>
  </footer>

</body>
</html>
