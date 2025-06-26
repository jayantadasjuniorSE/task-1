# task-2
HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <link rel="stylesheet" href="portfolio.css" />
</head>
<body>

  <header class="intro">
    <img src="your-photo.jpg" alt="Your Photo" class="profile-pic" />
    <h1>Hello, I'm Jane Doe</h1>
    <p>Front-End Web Developer | Designer | Student</p>
  </header>

  <section class="about">
    <h2>About Me</h2>
    <p>I am a beginner web developer passionate about building beautiful, responsive websites. I love to learn and grow every day.</p>
  </section>

  <section class="projects">
    <h2>Projects</h2>
    <div class="project-list">
      <div class="project">
        <h3>Landing Page</h3>
        <p>A simple and responsive landing page using HTML & CSS.</p>
      </div>
      <div class="project">
        <h3>Portfolio Website</h3>
        <p>This very site is a portfolio made from scratch!</p>
      </div>
    </div>
  </section>

  <section class="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>Responsive Design</li>
    </ul>
  </section>

  <section class="contact">
    <h2>Contact</h2>
    <p>Email: janedoe@example.com</p>
    <p>LinkedIn: <a href="#">linkedin.com/in/janedoe</a></p>
    <p>GitHub: <a href="#">github.com/janedoe</a></p>
  </section>

  <footer>
    <p>© 2025 Jane Doe. All rights reserved.</p>
  </footer>

</body>
</html
  
CSS
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #fafafa;
  color: #333;
}

header.intro {
  text-align: center;
  background-color: #0077cc;
  color: white;
  padding: 40px 20px;
}

.profile-pic {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  margin-bottom: 20px;
}

section {
  padding: 40px 20px;
  max-width: 900px;
  margin: auto;
}

.projects, .skills {
  background-color: #f1f1f1;
}

.project-list {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

.project {
  flex: 1;
  min-width: 250px;
  background: white;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.skills ul {
  list-style-type: none;
  padding: 0;
}

.skills li {
  background-color: #0077cc;
  color: white;
  display: inline-block;
  padding: 10px 15px;
  margin: 5px;
  border-radius: 5px;
}

.contact a {
  color: #0077cc;
  text-decoration: none;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 20px;
  margin-top: 40px;
}
