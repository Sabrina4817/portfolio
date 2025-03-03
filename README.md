# portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        body {
            background-color: #f4f4f4;
            color: #333;
            padding: 20px;
        }
        .container {
            width: 80%;
            margin: auto;
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
        }
        .header {
            display: flex;
            align-items: center;
            gap: 20px;
            border-bottom: 2px solid #ddd;
            padding-bottom: 10px;
        }
        .profile-picture {
            width: 100px;
            height: 100px;
            background: #ddd;
            border-radius: 50%;
        }
        h2 {
            color: #0073e6;
        }
        h3 {
            color: #005bb5;
            margin-bottom: 10px;
        }
        .about, .contact-info {
            margin-top: 20px;
            padding: 15px;
            border-radius: 5px;
            background: #eef5ff;
        }
        .education-skills, .experience-reference {
            display: flex;
            gap: 20px;
            margin-top: 20px;
        }
        .education, .skills, .job-experience, .reference {
            flex: 1;
            padding: 15px;
            border-radius: 5px;
            background: #f9f9f9;
        }
        .skill-bar {
            background: #ddd;
            height: 10px;
            border-radius: 5px;
            margin: 5px 0;
        }
        .skill-level {
            background: #0073e6;
            height: 10px;
            border-radius: 5px;
        }
        .contact-info {
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="profile-picture"></div>
            <div>
                <h2>Most. Nusrat Jahan</h2>
                <p>Passionate Web Developer with expertise in front-end and back-end technologies, creating responsive and user-friendly websites.</p>
            </div>
        </div>
        <div class="about">
            <h3>About Me</h3>
            <p>I am a dedicated web developer with experience in creating and optimizing interactive, user-friendly, and feature-rich websites. My expertise lies in modern web technologies, and I am always eager to learn new skills to stay ahead in the field.</p>
        </div>
        <div class="education-skills">
            <div class="education">
                <h3>Education</h3>
                <p><strong>Bachelor of Science in Computer Science</strong><br>Independent University Bangladesh, 2020 - 2024</p>
                <p>Relevant coursework: Web Development, Data Structures, Software Engineering</p>
            </div>
            <div class="skills">
                <h3>Skills</h3>
                <p>HTML</p>
                <div class="skill-bar"><div class="skill-level" style="width: 90%;"></div></div>
                <p>CSS</p>
                <div class="skill-bar"><div class="skill-level" style="width: 80%;"></div></div>
                <p>JavaScript</p>
                <div class="skill-bar"><div class="skill-level" style="width: 85%;"></div></div>
                <p>Python</p>
                <div class="skill-bar"><div class="skill-level" style="width: 70%;"></div></div>
                <p>C++</p>
                <div class="skill-bar"><div class="skill-level" style="width: 75%;"></div></div>
            </div>
        </div>
        <div class="experience-reference">
            <div class="job-experience">
                <h3>Job Experience</h3>
                <p><strong>Intern Web Developer</strong> - Techtrioz Solutions (2023 - Present)</p>
                <p>Developed responsive websites, optimized site performance, and collaborated with teams to implement innovative UI/UX designs.</p>
                <p><strong>Freelance Web Developer</strong> (2021 - Present)</p>
                <p>Worked with various clients to design and develop dynamic, mobile-friendly websites with a focus on performance and accessibility.</p>
            </div>
            <div class="reference">
                <h3>Reference</h3>
                <p><strong>Mr. Asif Rahman</strong><br>Senior Developer, Techtrioz Solutions<br>Email: asifrahman@gmail.com</p>
                <p><strong>Md. Abu Sayed</strong><br>Professor, Independent University Bangladesh<br>Email: abusayed@iub.edu.bd.</p>
            </div>
        </div>
        <div class="contact-info">
            <h3>Contact Info</h3>
            <p><strong>Email:</strong> nusratjahan@example.com</p>
            <p><strong>Phone:</strong> 01847-951358</p>
            <p><strong>LinkedIn:</strong> linkedin.com/in/nusratjahan</p>
            <p><strong>Portfolio:</strong> www.nusratjahan.dev</p>
        </div>
    </div>
</body>
</html>
