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
    nav {
      background: linear-gradient(90deg, #006666, #00cccc); /* Gradient Teal */
      padding: 15px 0;
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Soft shadow */
    }
    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      margin: 0;
      padding: 0;
    }
    nav ul li {
      margin: 0 20px;
    }
    nav ul li a {
      color: white;
      text-decoration: none;
      font-size: 1.1rem;
      padding: 10px 20px;
      border-radius: 20px;
      transition: background-color 0.3s ease, transform 0.3s;
    }
    nav ul li a:hover {
      background-color: #005f5f; /* Darker Teal */
      transform: scale(1.1); /* Slight hover effect */
    }
    section {
      padding: 100px 20px; /* Adjusted padding for fixed nav */
      text-align: center;
    }
    h2 {
      color: #008080; /* Teal */
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
    .skill-bar-container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    .skill-bar {
      position: relative;
      background-color: #d3d3d3;
      border-radius: 10px;
      margin-bottom: 20px;
      height: 30px;
      width: 80%;
      max-width: 400px;
      margin-left: auto;
      margin-right: auto;
    }
    .skill {
      background-color: #008080;
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
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      width: 280px;
      padding: 20px;
      transition: transform 0.3s ease, background-color 0.3s;
    }
    .project:hover {
      transform: scale(1.05);
      background-color: #f0f0f0;
    }
    .project h3 {
      background-color: #008080;
      color: white;
      padding: 10px;
      margin: -20px -20px 15px -20px;
      border-radius: 10px 10px 0 0;
    }
    footer {
      background-color: #005f5f;
      color: white;
      text-align: center;
      padding: 20px;
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
    .contact-form {
      display: flex;
      flex-direction: column;
      max-width: 400px;
      margin: 0 auto;
    }
    .contact-form input, .contact-form textarea {
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
      width: 100%;
      font-size: 1rem;
    }
    .contact-form button {
      padding: 10px;
      background-color: #008080;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1.1rem;
    }
    .contact-form button:hover {
      background-color: #005f5f;
    }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <nav>
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
    <p>
    Hi, I’m Habibeh! I’m a data professional with a strong math background and over three years of experience as a Data Analyst. I specialize in transforming complex datasets into actionable insights that drive business success and innovation.
    </p>
  </section>

  <!-- Tech Section -->
  <section id="tech">
    <h2>Tech</h2>
    <!-- More content here -->
  </section>

  <!-- Academic Section -->
  <section id="academic">
    <h2>Academic</h2>
    <!-- More content here -->
  </section>

  <!-- Contact Section -->
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

</body>
</html>
