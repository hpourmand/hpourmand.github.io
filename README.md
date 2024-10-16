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
      background-color: #f4f4f9;
      color: #333;
    }

    /* Navigation Bar */
    nav {
      background-color: #008080; /* Teal */
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* Shadow under nav */
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
      transition: background-color 0.3s ease, box-shadow 0.3s ease; /* Transition effect */
    }

    nav ul {
      list-style: none;
      display: flex; /* Flexbox to align in one line */
      justify-content: center; /* Centers the nav items */
      align-items: center; /* Aligns them vertically in the middle */
      margin: 0;
      padding: 0;
    }

    nav ul li {
      margin: 0 25px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-size: 1.2rem;
      padding: 8px 15px;
      transition: background-color 0.3s ease, color 0.3s ease; /* Smooth hover transitions */
      border-radius: 20px;
    }

    nav ul li a:hover {
      background-color: #005f5f; /* Darker teal */
      color: #f4f4f9; /* Light gray text */
    }

    /* Sticky Effect */
    .sticky {
      background-color: rgba(0, 128, 128, 0.95); /* Slightly transparent */
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* More prominent shadow when scrolling */
    }

    /* Section styles */
    section {
      padding: 80px 20px; /* Added padding for fixed nav */
      text-align: center;
    }

    h2 {
      color: #008080;
      text-align: center;
      margin-bottom: 30px;
    }

    .sub-heading {
      font-size: 1.5rem;
      margin-bottom: 20px;
      color: #005f5f;
    }

    p {
      margin-bottom: 40px;
      font-size: 1.1rem;
      line-height: 1.6;
    }

    /* Skills, Projects, and Contact Form */
    .skill-bar-container,
    .project-container,
    .contact-form {
      margin-top: 50px;
    }

    footer {
      background-color: #005f5f;
      color: white;
      text-align: center;
      padding: 20px;
    }

  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <nav id="navbar">
    <ul>
      <li><a href="#about">About Me</a></li>
      <li><a href="#tech">Tech</a></li>
      <li><a href="#academic">Academic</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- About Me Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>Hi, I’m Habibeh Pourmand! I’m a data professional with a strong math background and over three years of experience as a Data Analyst. I specialize in transforming complex datasets into actionable insights that drive business success and innovation.</p>
  </section>

  <!-- Tech Section -->
  <section id="tech">
    <h2>Tech</h2>
    <h3 class="sub-heading">Skills</h3>
    <!-- Skills Bars -->
    <h3 class="sub-heading">Projects</h3>
    <!-- Projects Listing -->
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
  </section>

  <!-- Academic Section -->
  <section id="academic">
    <h2>Academic</h2>
    <!-- Education, Talks, and Publications -->
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact</h2>
    <!-- Contact Form -->
  </section>



 <section id="contact">
    <h2>Contact</h2>
    <div class="contact-form">
      <input type="text" placeholder="Name">
      <input type="email" placeholder="Email">
      <textarea rows="5" placeholder="Message"></textarea>
      <button type="submit">Send Message</button>
    </div>
  </section>

  <footer>
    <p>&copy; 2024 Habibeh Pourmand. All rights reserved.</p>
  </footer>


  <!-- Footer -->
  <footer>
    <p>&copy; 2024 Habibeh Pourmand. All rights reserved.</p>
  </footer>

  <!-- JavaScript for Sticky Navbar -->
  <script>
    // Sticky Navbar Functionality
    window.onscroll = function() {makeNavSticky()};

    var navbar = document.getElementById("navbar");
    var sticky = navbar.offsetTop;

    function makeNavSticky() {
      if (window.pageYOffset > sticky) {
        navbar.classList.add("sticky");
      } else {
        navbar.classList.remove("sticky");
      }
    }
  </script>

</body>
</html>

