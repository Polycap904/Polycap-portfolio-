<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Polycap Nyachiro | Programmer</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Polycap Nyachiro</h1>
    <p>Programmer | Kisii Town</p>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I’m a passionate programmer with skills in web and software development.</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
      <li>Python</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project-card">
      <h3>Portfolio Website</h3>
      <p>A responsive site built with HTML, CSS, and JS.</p>
    </div>
    <!-- Add more projects here -->
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <form action="submit.py" method="POST">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
    <p>Located in Kisii Town, Kenya.</p>
  </section>

  <footer>
    <p>&copy; 2025 Polycap Nyachiro</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
