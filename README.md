<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      background-color: #f4f4f9; /* Light gray background */
      color: #333; /* Dark gray text */
    }

    /* Navigation Bar */
    nav {
      background-color: #008080; /* Teal */
    }

    nav ul li a {
      color: white;
    }

    nav ul li a:hover {
      background-color: #005f5f; /* Darker teal */
      color: #f4f4f9; /* Light gray text */
    }

    /* Sticky Effect */
    .sticky {
      background-color: rgba(0, 128, 128, 0.95); /* Slightly transparent teal */
    }

    h2 {
      color: #008080; /* Teal for headings */
    }

    .sub-heading {
      color: #005f5f; /* Darker teal for sub-headings */
    }

    footer {
      background-color: #005f5f; /* Darker teal */
      color: white;
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
    <p>&copy; 2024 All rights reserved.</p> <!-- Removed your name -->
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
