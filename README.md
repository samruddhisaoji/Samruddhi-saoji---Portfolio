<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samruddhi Saoji | Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #fff;
            text-align: center;
        }
        header {
            padding: 20px;
            background-color: #1e1e1e;
        }
        section {
            margin: 40px auto;
            width: 80%;
            max-width: 900px;
        }
        .project {
            background-color: #222;
            padding: 15px;
            margin: 10px 0;
            border-radius: 10px;
            transition: transform 0.3s;
        }
        .project:hover {
            transform: scale(1.05);
        }
        a {
            color: #00bcd4;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
        }
        .contact-form button {
            background-color: #00bcd4;
            color: #fff;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Samruddhi Saoji</h1>
        <p>Motion Designer | Video Editor | 3D Artist</p>
    </header>
    
    <section id="about">
        <h2>About Me</h2>
        <p>I'm a passionate motion designer, video editor, and 3D artist with experience in creating stunning visuals and animations. My work blends creativity with precision to deliver engaging storytelling.</p>
    </section>
    
    <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="project">
            <h3>The Oasis</h3>
            <p>Environment Design - A desert transitioning into a lush forest.</p>
            <a href="https://www.artstation.com/artwork/m8KObY" target="_blank">View Project</a>
        </div>
        <div class="project">
            <h3>Motion Design & Video Editing</h3>
            <p>Editing and color grading focused on impactful storytelling.</p>
            <a href="https://www.instagram.com/reel/C9xFj7KqhCJ/" target="_blank">View Project</a>
        </div>
        <div class="project">
            <h3>Product Animation</h3>
            <a href="https://www.instagram.com/reel/CsYlGRzOIc_/" target="_blank">View Project</a>
        </div>
        <div class="project">
            <h3>Online Purchase Motion Design</h3>
            <a href="https://www.behance.net/gallery/196039095/Online-purchase-motion-design" target="_blank">View Project</a>
        </div>
    </section>
    
    <section id="contact">
        <h2>Contact</h2>
        <form class="contact-form">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" rows="4" required></textarea>
            <button type="submit">Send</button>
        </form>
        <p>Email: <a href="mailto:saoji.samruddhi@gmail.com">saoji.samruddhi@gmail.com</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/samruddhi-saoji/" target="_blank">Samruddhi Saoji</a></p>
    </section>
</body>
</html>
