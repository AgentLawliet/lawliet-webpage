<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lawliet - Personal Webpage</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #f5f5f5;
        }
        header {
            background: linear-gradient(45deg, #00c6ff, #0072ff);
            padding: 40px 0;
            text-align: center;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
        }
        header h1 {
            font-size: 3em;
            color: #fff;
            margin: 0;
        }
        header p {
            font-size: 1.2em;
            color: #d1d1d1;
            margin-top: 10px;
        }
        .container {
            max-width: 900px;
            margin: 40px auto;
            padding: 20px;
            background-color: #1e1e1e;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
        }
        .section-title {
            font-size: 2em;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid #00c6ff;
            position: relative;
        }
        .section-title::after {
            content: '';
            position: absolute;
            width: 50px;
            height: 2px;
            background: #00c6ff;
            bottom: 0;
            left: 0;
            animation: glow 1.5s infinite;
        }
        @keyframes glow {
            0% { box-shadow: 0 0 5px #00c6ff; }
            50% { box-shadow: 0 0 20px #00c6ff; }
            100% { box-shadow: 0 0 5px #00c6ff; }
        }
        .about, .portfolio, .contact {
            margin-bottom: 40px;
        }
        p {
            font-size: 1.1em;
            line-height: 1.6;
        }
        .portfolio-item {
            margin-bottom: 30px;
        }
        .portfolio-item h3 {
            color: #00c6ff;
            font-size: 1.5em;
            margin-bottom: 10px;
        }
        .portfolio-item p {
            color: #d1d1d1;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #1e1e1e;
            color: #d1d1d1;
            border-top: 2px solid #00c6ff;
        }
        a {
            color: #00c6ff;
            text-decoration: none;
            transition: color 0.3s ease;
        }
        a:hover {
            color: #0072ff;
            text-decoration: underline;
        }
        .glow-button {
            display: inline-block;
            padding: 10px 20px;
            background: #00c6ff;
            color: #fff;
            border-radius: 30px;
            box-shadow: 0 0 20px rgba(0, 198, 255, 0.7);
            transition: box-shadow 0.3s ease;
        }
        .glow-button:hover {
            box-shadow: 0 0 30px rgba(0, 198, 255, 1);
        }
    </style>
</head>
<body>
    <header>
        <h1>Lawliet</h1>
        <p>Developer | Student | Tech Enthusiast</p>
    </header>

    <div class="container">
        <!-- About Me Section -->
        <section class="about">
            <h2 class="section-title">About Me</h2>
            <p>Hi, I’m Lawliet, a passionate tech enthusiast currently pursuing my Bachelor’s in Computer Applications. My areas of interest include coding, text analysis, and cybersecurity. I enjoy learning new technologies and working on projects that challenge me.</p>
        </section>

        <!-- Portfolio Section -->
        <section class="portfolio">
            <h2 class="section-title">Portfolio</h2>
            <div class="portfolio-item">
                <h3>Project 1: Credit Card Validator</h3>
                <p>A C-based program that verifies credit card numbers using the Luhn algorithm. Helps ensure the validity of card numbers for safer transactions.</p>
            </div>
            <div class="portfolio-item">
                <h3>Project 2: Readability Index Calculator</h3>
                <p>A tool that analyzes text documents and calculates readability scores using algorithms like the Coleman-Liau Index to determine text complexity.</p>
            </div>
        </section>

        <!-- Contact Section -->
        <section class="contact">
            <h2 class="section-title">Contact</h2>
            <p>Feel free to reach out to me via email for collaboration or inquiries: <a href="mailto:lawliet@example.com">lawliet@example.com</a></p>
            <p><a class="glow-button" href="mailto:lawliet@example.com">Contact Me</a></p>
        </section>
    </div>

    <footer>
        <p>© 2024 Lawliet. All Rights Reserved.</p>
    </footer>
</body>
</html>
