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
    <p>Hi, I'm Habibeh Pourmand, a data scientist and researcher based in Toronto with a deep interest in using data to drive decision-making...</p>
  </section>

  <!-- Tech Section -->
  <section id="tech">
    <h2>Tech</h2>
    <h3 class="sub-heading">Skills</h3>
    <!-- Skills Bars -->
    <h3 class="sub-heading">Projects</h3>
    <!-- Projects Listing -->
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
