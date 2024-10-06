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
            font-size: 1.5em;
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
        }
        a:hover {
            color: #0072ff;
            text-decoration: underline;
        }
        /* Typewriter effect */
        #typewriter {
            font-size: 1.2em;
            color: #d1d1d1;
            white-space: nowrap;
            overflow: hidden;
            border-right: 2px solid #00c6ff;
            width: 0;
            animation: typing 3.5s steps(40, end), blink-caret 0.75s step-end infinite;
        }
        @keyframes typing {
            from { width: 0; }
            to { width: 100%; }
        }
        @keyframes blink-caret {
            from, to { border-color: transparent; }
            50% { border-color: #00c6ff; }
        }
    </style>
</head>
<body>
    <header>
        <h1>Lawliet</h1>
        <p id="typewriter"></p>
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
        </section>
    </div>

    <footer>
        <p>© 2024 Lawliet. All Rights Reserved.</p>
    </footer>

    <script>
        // JavaScript for the typewriter effect
        const typewriterText = "Developer | Student | Tech Enthusiast";
        let index = 0;
        const typewriter = document.getElementById('typewriter');
        const typingSpeed = 100; // speed in milliseconds
        
        function type() {
            if (index < typewriterText.length) {
                typewriter.textContent += typewriterText.charAt(index);
                index++;
                setTimeout(type, typingSpeed);
            }
        }

        // Start typing when the page loads
        window.onload = type;
    </script>
</body>
</html>
# lawliet-webpage
