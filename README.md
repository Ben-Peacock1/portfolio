# portfolio
<!DOCTYPE html>
<html>
<head>
  <title>My Portfolio</title>
  <link rel="stylesheet" type="text/css" href="app.css">
</head>
<body>
  <header>
    <h1>My Portfolio</h1>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>My name is Ben Peacock and I am a web developer with experience in building websites using HTML, CSS, and JavaScript</p>
    </section>
    <section id="projects">
      <h2>My Projects</h2>
      <ul>
        <li><a href="#">Project 1</a></li>
        <li><a href="#">Project 2</a></li>
        <li><a href="#">Project 3</a></li>
      </ul>
    </section>
    <section id="contact">
      <h2>Contact Me</h2>
      <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
        <label for="email">Email:</label>
        <input type="email" id="email" name="email">
        <label for="message">Message:</label>
        <textarea id="message" name="message"></textarea>
        <input type="submit" value="Send">
      </form>
    </section>
  </main>
  <footer>
    <p>Copyright © 2022 My Portfolio</p>
  </footer>
</body>
</html>
