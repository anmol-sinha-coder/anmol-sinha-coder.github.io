<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anmol Sinha | Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #0073e6;
            color: white;
            padding: 1.5rem 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            background: #005bb5;
            display: flex;
            justify-content: center;
            padding: 0.5rem 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 2rem auto;
        }
        .section {
            margin-bottom: 2rem;
            padding: 1rem;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .section h2 {
            color: #005bb5;
        }
        .skills ul, .projects ul {
            list-style: none;
            padding: 0;
        }
        .skills li, .projects li {
            margin: 0.5rem 0;
        }
        .contact a {
            color: #0073e6;
            text-decoration: none;
        }
        .contact a:hover {
            text-decoration: underline;
        }
        footer {
            text-align: center;
            background: #333;
            color: white;
            padding: 1rem 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Anmol Sinha</h1>
        <p>Big Data Engineer | Data Analyst | Cloud & DevOps Specialist</p>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#experience">Experience</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about" class="section">
            <h2>About Me</h2>
            <p>I am a Big Data Engineer with expertise in tools like Hive, HUDI, Hadoop, Spark, and Kafka. With extensive experience in AWS cloud and DevOps deployments, I specialize in creating scalable data pipelines and optimizing workflows. Additionally, I have worked as a Data Analyst, delivering actionable insights through advanced data processing and visualization techniques.</p>
        </section>
        <section id="skills" class="section">
            <h2>Skills</h2>
            <div class="skills">
                <ul>
                    <li><strong>Big Data Tools:</strong> Hive, HUDI, Hadoop, Spark, Kafka</li>
                    <li><strong>Cloud Platforms:</strong> AWS (S3, EMR, Lambda, Glue)</li>
                    <li><strong>Programming Languages:</strong> Python, Scala, Java, SQL</li>
                    <li><strong>DevOps Tools:</strong> Docker, Kubernetes, Jenkins, Ansible</li>
                    <li><strong>Data Analytics:</strong> Pandas, NumPy, AWS QuickSight</li>
                </ul>
            </div>
        </section>
        <section id="experience" class="section">
            <h2>Work Experience</h2>
            <ul>
                <li><strong>Senior Data Engineer</strong> - KFin Technologies (Apr 2024 - Present)<br> 
                    Spearheaded data lake architecture and integrated AWS Cloud with Big Data for optimized ETL pipelines.
                </li>
                <li><strong>Data Engineer</strong> - KFin Technologies (Jun 2022 - Mar 2024)<br> 
                    Developed scalable workflows for stock exchange data processing and reporting systems.
                </li>
                <li><strong>Data Analytics Intern</strong> - HighRadius (Jan 2021 - Aug 2021)<br>
                    Built ML models and a B2B Invoice Payroll System leveraging Flask and ReactJS.
                </li>
            </ul>
        </section>
        <section id="projects" class="section">
            <h2>Projects</h2>
            <ul>
                <li><strong>Digix:</strong> Automated reporting system using MERN Stack and AWS Glue for Mutual Funds.</li>
                <li><strong>xAlts:</strong> Big Data-powered platform for Alternative Investment Funds (AIFs).</li>
                <li><strong>A.I Emotion Analysis:</strong> Deep Learning-based sentiment recognition tool.</li>
            </ul>
        </section>
        <section id="contact" class="section">
            <h2>Contact</h2>
            <p><strong>Email:</strong> <a href="mailto:anmolsinha.ss5@gmail.com">anmolsinha.ss5@gmail.com</a></p>
            <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/anmol-sinha-2465852b9/">linkedin.com/in/anmol-sinha-2465852b9</a></p>
            <p><strong>GitHub:</strong> <a href="https://github.com/anmol-sinha-coder">github.com/anmol-sinha-coder</a></p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Anmol Sinha. All rights reserved.</p>
    </footer>
</body>
</html>
