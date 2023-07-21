<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>my profile</title>
        <style>
	/* Navigation Bar */
nav {
  background-color: blue;
  color: red;
  padding: 10px;
}
.logo {
  font-size: 50px;
  font-weight: bold;
  margin-right: 40px;
}
.nav-links {
  list-style-type: none;
  margin: 0;
  padding: 0;
  display: flex;
}

.nav-links li {
  margin-right: 50px;
}

.nav-links li a {
  color: #131414;
  text-decoration: none;
}

/* Hero Section */
header {
  background-color: #f2f2f2;
  padding: 50px;
  text-align: center;
}

/* About Me Section */
#about {
  padding: 10px;
  text-align: center;
}

/* Skills Section */
#skills {
  padding: 10px;
  background-color: #f2f2f2;;
  text-align: center;
}

.skills-list {
  list-style-type: none;
  padding: 0;
}

.skills-list li {
  display: inline-block;
  margin: 0 10px;
}

/* Projects Section */
#projects {
  padding: 50px;
  text-align: center;
}

.project {
  margin-bottom: 20px;
}

.project a {
  display: block;
  margin-top: 10px;
}

/* Contact Section */
#contact {
  padding: 10px;
  text-align: center;
  background-color:  #f2f2f2;
}

#contact-form {
  display: flex;
  flex-direction: column;
  align-items: center;
  
}

#contact-form label {
  margin-bottom: 10px;
}

#contact-form input,
#contact-form textarea {
  width: 40%;
  padding: 10px;
  margin-bottom: 10px;
  box-sizing: border-box;
}

#contact-form button {
  background-color: #4b4747;
  color: #030303;
  border: blue;
  padding: 10px 10px;
  cursor: pointer;
}

/* Footer */
footer {
  background-color: #8fb3f7;
  color: #0a0a0a;
  padding: 20px;
  text-align: center;
}
        </style>
</head>
    <nav>
        <div class="logo">mahmoud</div>
        <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <header>
        <h1>Welcome my name is mahmoud</h1>
        <a href="https://imgur.com/A3tkwTF"><img src="https://i.imgur.com/A3tkwTF.jpg" title="source: imgur.com" width="50%"/></a>

        <p>some of my skills, projects, and achievements</p>
    </header>

    <section id="about">
        <h2><strong>About me</strong></h2>
        <div class="about-content">
            <p>I study commerce at Helwan University and I live in elMarg.
	</p>  انا ادرس تجارة في جامعه حلوان وعايش في المرج
        </div>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul class="skills-list">
            <ol>
                <li>HTML</li>
                <li>CSS</li>
                <li>JS</li>
            </ol>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <p>it is my first project</p>
        <div class="project">    
        </div>
    </section>

    <section id="contact">
        <h2>Contact with Me</h2>
        <form id="contact-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="Name" required></textarea>
            <button type="submit">Send Message</button>
        </form>
        <a href="https://www.facebook.com/profile.php?id=100024291725101&mibextid=ZbWKwL"><img src="https://imgur.com/fLnLK6z" alt="Facebook"></a>

    <footer>
        <p>&copy; 2023 mahmoud mohamed</p>
    </footer>
