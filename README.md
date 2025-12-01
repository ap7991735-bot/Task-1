# task 1 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Personal Website</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <header>
        <img src="https://via.placeholder.com/150" alt="Profile picture" class="profile-pic">
        <h1>Your Name</h1>
        <p class="tagline">Short bio: a sentence about who you are and what you do.</p>
    </header>

    <section id="education">
        <h2>Education</h2>
        <ul>
            <li><strong>Your Degree</strong> – University Name (Year–Year)</li>
            <li>Any relevant certifications or courses</li>
        </ul>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul class="skills-list">
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>Git & GitHub</li>
            <li>Any others…</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project One</h3>
            <p>Short description of your project. What tech did you use?</p>
        </div>

        <div class="project">
            <h3>Project Two</h3>
            <p>Description of another project.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form>
            <label>Name</label>
            <input type="text" placeholder="Your Name" required>

            <label>Email</label>
            <input type="email" placeholder="your@email.com" required>

            <label>Message</label>
            <textarea placeholder="Write your message…" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>© 2025 Your Name</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
