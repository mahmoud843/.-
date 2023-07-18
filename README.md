<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>my profile</title>
        <style>
          /* For mobile phones: */
[class*="col-"] {
  width: 100%;
}

@media only screen and (min-width: 600px) {
  /* For tablets: */
  .col-s-1 {width: 8.33%;}
  .col-s-2 {width: 16.66%;}
  .col-s-3 {width: 25%;}
  .col-s-4 {width: 33.33%;}
  .col-s-5 {width: 41.66%;}
  .col-s-6 {width: 50%;}
  .col-s-7 {width: 58.33%;}
  .col-s-8 {width: 66.66%;}
  .col-s-9 {width: 75%;}
  .col-s-10 {width: 83.33%;}
  .col-s-11 {width: 91.66%;}
  .col-s-12 {width: 100%;}
}

@media only screen and (min-width: 768px) {
  /* For desktop: */
  .col-1 {width: 8.33%;}
  .col-2 {width: 16.66%;}
  .col-3 {width: 25%;}
  .col-4 {width: 33.33%;}
  .col-5 {width: 41.66%;}
  .col-6 {width: 50%;}
  .col-7 {width: 58.33%;}
  .col-8 {width: 66.66%;}
  .col-9 {width: 75%;}
  .col-10 {width: 83.33%;}
  .col-11 {width: 91.66%;}
  .col-12 {width:100%;}
}

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

/* About Me Section *
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
@media screen and (max-width: 480px) {
    /*CSS MOBILE DEVICE */
}
@media screen and (min-width: 1024px) {
    /* CSS LAPTOP */
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
            <p>I study commerce at Helwan University and I live in elMarg.</p>
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
