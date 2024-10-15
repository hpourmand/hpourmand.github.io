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
      margin: -20px -20px 15px -20px;
      border-radius: 10px 10px 0 0;
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
      color: #fff;
      font-weight: bold;
    }
    .social-links a:hover {
      color: #005f5f;
    }
    .sub-heading {
      font-size: 1.5rem;
      margin-bottom: 20px;
      color: #005f5f;
    }
    ul {
      text-align: left;
      margin: 0 auto;
      max-width: 600px;
      padding-left: 0;
      list-style-type: none;
    }
    ul li {
      background-color: #fff;
      padding: 15px;
      margin-bottom: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    ul li a {
      color: #008080;
      font-weight: bold;
    }
    ul li a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <section id="tech">
    <h2>Tech Section</h2>
    <h3 class="sub-heading">Skills</h3>
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

    <h3 class="sub-heading">Projects</h3>
    <div class="project-container">
      <div class="project">
        <h3>Customer Shopping Trends Analysis</h3>
        <p>This project analyzes customer shopping trends using Exploratory Data Analysis (EDA), Behavioral Segmentation, and Predictive Modeling.</p>
        <a href="https://github.com/hpourmand/Customer-Shopping-Trends-" target="_blank">View on GitHub</a>
      </div>
      <div class="project">
        <h3>Analyzing Late Book Returns</h3>
        <p>Analyzing data to understand late book returns for a local library and identifying causes to reduce them.</p>
        <a href="https://github.com/hpourmand/Library" target="_blank">View on GitHub</a>
      </div>
      <div class="project">
        <h3>Analysis of 911 Calls Dataset</h3>
        <p>Time series analysis of 911 calls dataset to uncover emergency trends and patterns.</p>
        <a href="https://github.com/hpourmand/Emergency-911-calls" target="_blank">View on GitHub</a>
      </div>
      <div class="project">
        <h3>Identifying Future Programming Skills Trends</h3>
        <p>Analyzing in-demand programming skills by gathering data from job postings and surveys, culminating in a dashboard created using IBM Cognos.</p>
        <a href="https://github.com/hpourmand/Analyzing-Global-Trends-in-Programming-Database-Skills-and-IDE-Demand" target="_blank">View on GitHub</a>
      </div>
      <div class="project">
        <h3>Olympic Performance Analysis by Country</h3>
        <p>Analyzing each country's Olympic performance over time.</p>
        <a href="https://github.com/hpourmand/Olympics" target="_blank">View on GitHub</a>
      </div>
    </div>
  </section>

  <section id="academic">
    <h2>Academic Section</h2>
    <h3 class="sub-heading">Publications</h3>
    <ul>
      <li>Pourmand, H., et al. (2021). <a href="https://link-to-publication.com" target="_blank">Title of Publication 1</a></li>
      <li>Pourmand, H., et al. (2020). <a href="https://link-to-publication.com" target="_blank">Title of Publication 2</a></li>
      <li>Pourmand, H., et al. (2019). <a href="https://link-to-publication.com" target="_blank">Title of Publication 3</a></li>
    </ul>

    <h3 class="sub-heading">Talks</h3>
    <ul>
      <li><a href="https://link-to-talk.com" target="_blank">Keynote Speaker at Data Science Conference 2021</a></li>
      <li><a href="https://link-to-talk.com" target="_blank">Invited Talk on Machine Learning at XYZ University</a></li>
      <li><a href="https://link-to-talk.com" target="_blank">Talk on Advanced Data Analysis at ABC Symposium</a></li>
    </ul>
  </section>

  <footer>
    <p>© 2024 Habibeh Pourmand</
