<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shivanshi Tiwari's GitHub Page</title>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet">
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

   body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-image: url('[https://raw.githubusercontent.com/shivanshitiwari/newone/main/final2.jpg](https://github.com/shivanshitiwari/stiwari/blob/main/final2.jpg)');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat; /* Ensure the image doesn't repeat */
  background-attachment: fixed; /* Makes the background stay fixed when scrolling */
  text-align: center;
  color: black;  /* Font color set to black for readability */
}

    /* Header */
    header {
      background-color: transparent; /* Remove the black strip */
      color: black; /* Make the text black */
      padding: 20px 0;
      font-size: 24px;
      font-weight: bold;
      position: relative;
    }

    /* Top-right navigation */
    .nav {
      position: absolute;
      right: 20px;
      top: 20px;
    }

    .nav a {
      margin-left: 20px;
      color: black; /* Set to black */
      text-decoration: none;
      font-size: 18px;
    }

    .nav a:hover {
      color: #007BFF;
    }

    /* Updated Main Container */
.container {
  display: flex;
  flex-direction: column;
  align-items: center; /* Center align content horizontally */
  justify-content: center;
  min-height: 80vh;
  background-color: transparent;
  text-align: center; /* Set text alignment to center */
}

    /* Profile Section */
    .profile-pic {
      width: 250px;  /* Increased size */
      height: 250px;
      border-radius: 50%;
      border: 5px solid white;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.3);
      margin-bottom: 20px;
      position: relative;
      right: -20px; /* Shifted slightly to the right */
    }

    /* Introduction */
    h1 {
      font-size: 36px;
      margin-bottom: 10px;
      color: black;  /* Set text to black */
    }

    h1 span {
      color: #FF9900;
    }

    p {
      font-size: 18px;
      margin-bottom: 20px;
      color: black; /* Set text to black */
    }

    /* About Me Button */
    .about-button {
      background-color: #007BFF;
      color: white;
      padding: 12px 25px;
      border-radius: 25px;
      text-decoration: none;
      font-size: 18px;
      transition: background-color 0.3s ease;
    }

    .about-button:hover {
      background-color: #0056b3;
    }

    /* Social Icons */
    .social-links {
      margin-top: 30px;
    }

    .social-links a {
      color: black; /* Set to black */
      font-size: 30px;
      margin: 0 15px;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    .social-links a:hover {
      color: #007BFF;
    }

    /* About Section */
    .about-section {
      padding: 50px;
      text-align: left;
      background-color: rgba(0, 0, 0, 0.7); /* Transparent background for better readability */
      color: white;
    }

    .about-section h2 {
      font-size: 30px;
      color: white;
      margin-bottom: 20px;
    }

    .about-section p {
      font-size: 18px;
      color: white;
      line-height: 1.6;
    }

    /* SCU Logo */
    .scu-logo {
      position: fixed;
      bottom: 20px;
      right: 20px;
      width: 100px; /* Smaller size */
      height: auto;
      opacity: 0.8; /* Slight transparency */
    }

    /* Footer */
    footer {
      margin-top: 50px;
      background-color: rgba(0, 0, 0, 0.8);
      color: white;
      padding: 10px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>

  <header>
    Welcome To my Git Page
    <div class="nav">
      <a href="#about">About</a>
      <a href="https://drive.google.com/file/d/1TBGhJWRBN4ZwbGMnLvA_jcsZBqVs2-z-/view?usp=sharing" target="_blank">Resume</a>
    </div>
  </header>

  <div class="container">
    <img class="profile-pic" src="https://github.com/shivanshitiwari/stiwari/blob/main/WhatsApp%20Image%202024-09-24%20at%2000.10.03.jpeg![image](https://github.com/user-attachments/assets/77090499-ce58-46e9-82a8-17639783faf5)
" alt="Shivanshi Tiwari">
    <h1>Hi There, I'm <span>Shivanshi Tiwari</span></h1>
    <p> Business Analyst</p>
    <a href="#about" class="about-button">About Me</a>

    <!-- Social Media Icons -->
    <div class="social-links">
      <a href="https://www.linkedin.com/in/st1405/" target="_blank"><i class="fab fa-linkedin"></i></a>
      <a href="https://github.com/shivanshitiwari" target="_blank"><i class="fab fa-github"></i></a>
      <a href="mailto:shivanshi9914@gmail.com" target="_blank"><i class="fas fa-envelope"></i></a>
    </div>
  </div>
  <!-- SCU Logo -->
  <img class="scu-logo" src="https://github.com/shivanshitiwari/stiwari/blob/main/SCUlogo.png" alt="SCU Logo">

  <!-- About Section -->
  <section id="about" class="about-section">
    <h2>About Me</h2>
    <p>Hi! I'm Shivanshi Tiwari, a passionate and results-driven professional with 3 years of experience in business analytics. I specialize in transforming data into actionable insights through expertise in data analytics, machine learning, and business strategy. Currently pursuing my Master of Science in Business Analytics at Santa Clara University, focusing on machine learning, econometrics, and prescriptive analytics.</p>
    <p>My academic and professional journey includes data science, machine learning, big data, and business analytics projects. I'm passionate about solving complex business challenges and leveraging data-driven solutions to drive growth. Feel free to connect with me on LinkedIn or view my projects on GitHub.</p>
  </section>

  <footer>
    &copy; 2024 Shivanshi Tiwari | Powered by GitHub Pages
  </footer>

</body>
</html>
