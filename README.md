<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ayush Kumar Gupta | Portfolio</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background-color: #0d1117;
      color: #c9d1d9;
      line-height: 1.6;
    }

    header {
      text-align: center;
      padding: 4rem 1rem;
    }

    header h1 {
      font-size: 2.5rem;
      color: #58a6ff;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 0.5rem;
    }

    .resume-btn {
      display: inline-block;
      padding: 10px 20px;
      margin-top: 1rem;
      background-color: #58a6ff;
      color: #0d1117;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }
    .resume-btn:hover {
      background-color: #1f6feb;
      color: white;
    }

    section {
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    h2 {
      color: #58a6ff;
      margin-bottom: 1rem;
      border-bottom: 2px solid #30363d;
      padding-bottom: 0.5rem;
    }

    .skills, .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }

    .skill, .project {
      background-color: #161b22;
      padding: 1rem;
      border-radius: 8px;
      box-shadow: 0 0 5px rgba(255, 255, 255, 0.05);
    }

    .project a {
      color: #58a6ff;
      text-decoration: none;
    }

    footer {
      text-align: center;
      padding: 2rem 1rem;
      background-color: #161b22;
      margin-top: 3rem;
    }

    .socials a {
      color: #c9d1d9;
      margin: 0 0.5rem;
      font-size: 1.5rem;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    .socials a:hover {
      color: #58a6ff;
    }

    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 1rem;
      background: #0d1117;
      border: 1px solid #30363d;
      color: #c9d1d9;
      border-radius: 4px;
    }

    form button {
      background-color: #58a6ff;
      color: #0d1117;
      border: none;
      padding: 10px 20px;
      font-weight: bold;
      border-radius: 4px;
      cursor: pointer;
    }

    form button:hover {
      background-color: #1f6feb;
      color: white;
    }
  </style>
</head>
<body>
  <header data-aos="fade-down">
    <h1>Ayush Kumar Gupta</h1>
    <p>Machine Learning Enthusiast</p>
    <a href="resume.pdf" download class="resume-btn">Download Resume</a>
  </header>

  <section id="about" data-aos="fade-up">
    <h2>About Me</h2>
    <p>I am passionate about building intelligent systems using machine learning and AI. I enjoy working on projects that involve data, automation, and innovation.</p>
  </section>

  <section id="skills" data-aos="fade-up">
    <h2>Skills</h2>
    <div class="skills">
      <div class="skill">Python</div>
      <div class="skill">TensorFlow</div>
      <div class="skill">OpenCV</div>
      <div class="skill">MediaPipe</div>
      <div class="skill">Pandas</div>
      <div class="skill">Scikit-learn</div>
    </div>
  </section>

  <section id="projects" data-aos="fade-up">
    <h2>Projects</h2>
    <div class="projects">
      <div class="project">
        <h3>Hand Gesture Control</h3>
        <p>Control your PC using hand gestures using OpenCV and MediaPipe.</p>
        <a href="#">View Project</a>
      </div>
      <div class="project">
        <h3>ML Model Deployment</h3>
        <p>Deploy machine learning models using Flask and Streamlit.</p>
        <a href="#">View Project</a>
      </div>
    </div>
  </section>

  <section id="contact" data-aos="fade-up">
    <h2>Contact</h2>
    <p>Feel free to reach out:</p>
    <form action="https://formspree.io/f/yourFormID" method="POST">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="_replyto" placeholder="Your Email" required>
      <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
      <button type="submit">Send Message</button>
    </form>
    <div class="socials">
      <a href="mailto:ayushkumargupta36@gmail.com"><i class="fas fa-envelope"></i></a>
      <a href="https://www.linkedin.com/in/ayush-kumar-gupta-102981245?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank"><i class="fab fa-linkedin"></i></a>
      <a href="https://github.com/yourusername" target="_blank"><i class="fab fa-github"></i></a>
      <a href="https://www.instagram.com/ayush_gupta_63?utm_source=qr&igsh=MWNlMGw0cTEzc3A3dw==">i class="fab fa-instagram"></i></a>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Ayush Kumar Gupta. All rights reserved.</p>
  </footer>

  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init();
  </script>
</body>
</html>
