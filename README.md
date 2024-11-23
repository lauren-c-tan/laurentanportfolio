# laurentanportfolio

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lauren Tan Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background: #0077c2;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #003f75;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }
        .container {
            padding: 20px;
            max-width: 900px;
            margin: auto;
        }
        .section {
            margin-bottom: 40px;
        }
        .project {
            margin-bottom: 20px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #003f75;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Lauren Tan</h1>
        <p>Electrical Engineering Portfolio</p>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#resume">Resume</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about" class="section">
            <h2>About Me</h2>
            <p>Hello! I'm Lauren, a 4th-year Electrical Engineering student at UC Davis. I'm passionate about designing innovative electrical systems and tackling challenging problems.</p>
        </section>
        <section id="projects" class="section">
            <h2>Projects</h2>
            <div class="project">
                <h3>DELTA - Wearable Gesture Controller</h3>
                <p><strong>Fall Quarter 2024 - Present</strong></p>
                <ul>
                    <li>Currently designing a wearable device that can detect motion for creating sign language.</li>
                    <li>Uses five sensors connected at the fingertips, with code written for each letter, to identify and display letters onto an interface.</li>
                </ul>
            </div>
            <div class="project">
                <h3>Morselator (Morse Code/Hex Translator)</h3>
                <p><strong>Fall Quarter 2024</strong></p>
                <ul>
                    <li>Designed and programmed a mock IoT product using Altium and a PSoC project.</li>
                    <li>Translates words into Morse code through live transcription in the PuTTY terminal.</li>
                </ul>
            </div>
            <div class="project">
                <h3>Autonomous Car</h3>
                <p><strong>Spring Quarter 2023</strong></p>
                <ul>
                    <li>Built an autonomous vehicle using an Arduino Uno Microcontroller, ultrasonic sensor, Infrared Sensor (IR), and switches.</li>
                    <li>Programmed features including Lane Tracking, Automatic Braking, and Obstacle Detection.</li>
                </ul>
            </div>
            <div class="project">
                <h3>Audio Tracking RSLK Robot</h3>
                <p><strong>Spring Quarter 2023</strong></p>
                <ul>
                    <li>Designed and implemented a dual microphone amplifier circuit attached to an RSLK Robot.</li>
                    <li>Programmed the robot in C to detect and move toward audio sources, including forward, back, left, and right.</li>
                </ul>
            </div>
            <div class="project">
                <h3>PH Neutralizing Dispenser</h3>
                <p><strong>Fall Quarter 2021</strong></p>
                <ul>
                    <li>Utilized an Arduino Uno Microcontroller, color sensor, LEDs, LCD motor, pH paper, and 3D printing.</li>
                    <li>Created the circuit design and programmed the dispenser to detect water acidity and dispense the correct amount of neutralizer, aiding isolated communities affected by acid runoff.</li>
                </ul>
            </div>
        </section>
        <section id="resume" class="section">
            <h2>Resume</h2>
            <p><a href="resume.pdf" target="_blank">Download My Resume</a></p>
        </section>
        <section id="contact" class="section">
            <h2>Contact</h2>
            <p>Email: <a href="mailto:laurentan888@gmail.com">laurentan888@gmail.com</a></p>
            <p>LinkedIn: <a href="https://linkedin.com/in/laurentan" target="_blank">linkedin.com/in/laurentan</a></p>
        </section>
    </div>
    <footer>
        <p>© 2024 Lauren Tan</p>
    </footer>
</body>
</html>


   
