<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            margin: 0;
            padding-bottom: 10px;
        }
        p {
            margin: 10px 0;
        }
        .skills, .projects {
            margin: 20px 0;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
        }
        .contact-form input, .contact-form textarea {
            margin: 10px 0;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .contact-form button {
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 4px;
        }
        .contact-form button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
    </header>
    <div class="container">
        <section>
            <h2>About Me</h2>
            <p>Hi, I'm [Your Name], a passionate web developer with a knack for creating beautiful and functional websites.</p>
        </section>
        <section class="skills">
            <h2>Skills</h2>
            <p>HTML, CSS, JavaScript, React, Node.js, and more.</p>
        </section>
        <section class="projects">
            <h2>Projects</h2>
            <p>Here are some of my recent projects:</p>
            <ul>
                <li>Project 1: Description</li>
                <li>Project 2: Description</li>
                <li>Project 3: Description</li>
            </ul>
        </section>
        <section class="contact">
            <h2>Contact Me</h2>
            <form class="contact-form">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" rows="4" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </div>
    <script>
        document.querySelector('.contact-form').addEventListener('submit', function(event) {
            event.preventDefault();
            alert('Message sent successfully!');
        });
    </script>
</body>
</html>
