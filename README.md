# Personal-WEBSITE-
Build a personal website that highlights strengths and weakness.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        section {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h1, h2, h3 {
            color: #333;
        }

        .strengths, .weaknesses, .education, .experience, .projects, .contact {
            margin-bottom: 30px;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        form {
            display: flex;
            flex-direction: column;
        }

        label {
            margin-bottom: 8px;
        }

        input, textarea {
            padding: 8px;
            margin-bottom: 16px;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        button {
            background-color: #4caf50;
            color: #fff;
            padding: 10px 15px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }

        button:hover {
            background-color: #45a049;
        }
    </style>
    <title>Your Name - Personal Website</title>
</head>
<body>

    <header>
        <h1>Your Name</h1>
        <p>Web Developer & Enthusiast</p>
    </header>

    <section class="strengths">
        <h2>Strengths</h2>
        <ul>
            <li>Passionate about web development</li>
            <li>Strong problem-solving skills</li>
            <li>Excellent communication skills</li>
            <!-- Add more strengths as needed -->
        </ul>
    </section>

    <section class="weaknesses">
        <h2>Weaknesses</h2>
        <p>While I strive to improve in all areas, I am currently working on:</p>
        <ul>
            <li>Enhancing time management skills</li>
            <li>Learning new technologies more efficiently</li>
            <!-- Add more weaknesses as needed -->
        </ul>
    </section>

    <section class="education">
        <h2>Education</h2>
        <ul>
            <li>
                <h3>University Name</h3>
                <p>Bachelor of Science in Computer Science</p>
                <p>Graduation Year: 20XX</p>
            </li>
            <!-- Add more education details as needed -->
        </ul>
    </section>

    <section class="experience">
        <h2>Work Experience</h2>
        <ul>
            <li>
                <h3>Company Name</h3>
                <p>Position: Web Developer</p>
                <p>Duration: Month/Year - Month/Year</p>
            </li>
            <!-- Add more work experience details as needed -->
        </ul>
    </section>

    <section class="projects">
        <h2>Projects</h2>
        <ul>
            <li>
                <h3>Project Name</h3>
                <p>Description of the project goes here.</p>
            </li>
            <!-- Add more project details as needed -->
        </ul>
    </section>

    <section class="contact">
        <h2>Contact Me</h2>
        <form>
            <label for="name">Your Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Your Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Your Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>Contact: your.email@example.com | Website: yourwebsite.com</p>
    </footer>

</body>
</html>

