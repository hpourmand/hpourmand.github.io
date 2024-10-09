
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
    <p>Hi, I’m Habibeh! I’m a data professional with a strong math background and over three years of experience as a Data Analyst. I specialize in transforming complex datasets into actionable insights that drive business success and innovation.
</p>
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
        <div class="skill" style="width: 90%;">Excel</div>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>Projects</h2>
    <!-- Project 1 -->
    <div class="project">
        <h3>Customer Retention Analysis</h3>
        <p>Analyzed customer behavior data using Python, SQL, and Tableau, resulting in an 18% increase in customer retention within 8 months.</p>
        <a href="https://github.com/hpourmand/Customer-Shopping-Trends-" target="_blank" class="btn">View on GitHub</a>
    </div>
    
    <!-- Project 2 -->
    <div class="project">
        <h3>Sales Forecasting Model</h3>
        <p>Built a predictive model using machine learning algorithms to forecast sales trends, leading to a 15% improvement in inventory management.</p>
        <a href="https://github.com/yourusername/sales-forecasting-model" target="_blank" class="btn">View on GitHub</a>
    </div>
    
    <!-- Project 3 -->
    <div class="project">
        <h3>Interactive Data Dashboard</h3>
        <p>Developed a dynamic Tableau dashboard to visualize KPIs, which improved decision-making speed for marketing and sales teams by 30%.</p>
        <a href="https://github.com/yourusername/data-dashboard" target="_blank" class="btn">View on GitHub</a>
    </div>
</section>


  <!-- Footer -->
  <footer>
    <p>&copy; 2024 Habibeh Pourmand</p>
  </footer>

</body>
</html>
