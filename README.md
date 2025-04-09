<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nozipho | Web Developer</title>
    <style>
        * {
            box-sizing: border-box;
        }

        body {
            font-family: sans-serif;
            margin: 0;
            padding: 0;
            background: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcROPkxovTmxiUK4M28xNHS3YgyaBgDjOkOEtw&s) no-repeat center center fixed;
            background-size: cover;
            color: white;
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 40px;
            background-color: rgba(0, 0, 0, 0.6);
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
            margin: 0;
            padding: 0;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            color: palevioletred;
        }

        .section {
            padding: 60px 20px;
            max-width: 1000px;
            margin: auto;
        }

        h1,
        h2,
        h3,
        h4 {
            margin-top: 0;
        }

        .info {
            text-align: center;
            margin-top: 60px;
        }

        .info h1 {
            font-size: 65px;
            color: black;
        }

        .info h3 {
            font-size: 18px;
            letter-spacing: 1px;
            line-height: 24px;
        }

        .info span {
            color: palevioletred;
        }

        .info a {
            text-decoration: none;
            color: white;
            background-color: rgb(36, 32, 30);
            margin-top: 20px;
            padding: 10px 18px;
            border-radius: 10px;
            display: inline-block;
            transition: 0.3s ease;
        }

        .info a:hover {
            background: rgb(59, 174, 209);
        }

        .image {
            display: flex;
            justify-content: center;
            margin-top: 30px;
        }

        .image img {
            max-width: 100%;
            height: auto;
        }

        .icons {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 30px 0;
        }

        .icons a {
            color: white;
            font-size: 40px;
        }

        .icons a:hover {
            color: rgb(59, 174, 209);
        }

        .container {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            padding: 40px;
            border-radius: 16px;
            width: 100%;
            max-width: 600px;
            margin: auto;
        }

        .container h2 {
            text-align: center;
            font-size: 28px;
            margin-bottom: 30px;
        }

        .form-group {
            margin-bottom: 20px;
        }

        label {
            display: block;
            font-weight: bold;
            margin-bottom: 8px;
        }

        input,
        textarea {
            width: 100%;
            padding: 12px;
            border: none;
            border-radius: 8px;
            font-size: 16px;
        }

        textarea {
            resize: vertical;
        }

        button {
            width: 100%;
            padding: 14px;
            background: #007bff;
            color: #fff;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 18px;
            font-weight: bold;
            transition: background 0.3s ease;
        }

        button:hover {
            background: #0056b3;
        }

        @media (max-width: 768px) {
            header {
                flex-direction: column;
                text-align: center;
            }

            nav ul {
                flex-direction: column;
                gap: 10px;
            }

            .info h1 {
                font-size: 45px;
            }
        }
    </style>
    <script src="https://unpkg.com/ionicons@5.4.0/dist/ionicons.js"></script>
</head>

<body>
    <header>
        <div class="logo">Nozipho</div>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <div class="info">
        <h3>Hi, I'm <span>Nozipho</span>.</h3>
        <h1><span>W</span>EB<span> D</span>EVELOPER</h1>
        <h3>
            Web designer and developer from South Africa, Johannesburg.<br>
            I craft seamless digital experiences by combining code, creativity,<br> and innovation.
        </h3>
        <a href="#contact">Hire Me</a>
    </div>

    <div class="image">
        <img src="girl_coder-removebg-preview.png" alt="girl coder">
    </div>

    <div class="icons">
        <a href="#"><ion-icon name="logo-instagram"></ion-icon></a>
        <a href="#"><ion-icon name="logo-twitter"></ion-icon></a>
        <a href="#"><ion-icon name="logo-facebook"></ion-icon></a>
    </div>

    <section id="about" class="section about">
        <h2>About Me</h2>
        <p>
            Motivated and detail-oriented aspiring web developer with a solid foundation in HTML, CSS, JavaScript, and
            front-end frameworks.
            Successfully honed my skills through personal projects, coursework, and continuous self-learning. Passionate
            about building seamless,
            user-centric websites and eager to contribute to innovative teams.
        </p>
    </section>

    <section id="education" class="section education">
        <h2>Educational Background</h2>
        <p><strong>SHECODES Plus</strong> (Feb 2025 - Apr 2025)<br>
            - Advanced HTML, CSS, responsive design<br>
            - JavaScript & API integration</p>
        <p><strong>SHECODES Basics</strong> (Feb 2025)<br>
            - HTML, CSS, JavaScript basics<br>
            - Simple animations and API integration</p>
    </section>

    <section id="skills" class="section skills">
        <h2>Technical Skills</h2>
        <p>
            <strong>Programming:</strong> React, JavaScript<br>
            <strong>Languages:</strong> HTML, CSS<br>
            <strong>DevOps:</strong> Git, GitHub, APIs<br>
            <strong>Tools:</strong> Bootstrap, Netlify, VS Code, CodeSandbox
        </p>
    </section>

    <section id="contact" class="section">
        <div class="container">
            <h2>Contact Form</h2>
            <form action="#" method="POST">
                <div class="form-group">
                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="subject">Subject:</label>
                    <input type="text" id="subject" name="subject" required>
                </div>
                <div class="form-group">
                    <label for="message">Message:</label>
                    <textarea id="message" name="message" rows="5" required></textarea>
                </div>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>
</body>

</html>
