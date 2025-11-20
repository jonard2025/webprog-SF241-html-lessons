<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WEBPROG SF241 - Jonard Bacani</title>

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: "Poppins", sans-serif;
            background: linear-gradient(135deg, #6EC6FF, #A66CFF);
            color: #333;
        }

        .container {
            width: 90%;
            max-width: 900px;
            margin: 40px auto;
        }

        h1 {
            text-align: center;
            color: white;
            font-size: 2.5rem;
            margin-bottom: 30px;
            text-shadow: 2px 2px 5px rgba(0,0,0,0.3);
        }

        .card {
            background: white;
            padding: 25px;
            border-radius: 15px;
            margin-bottom: 30px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }

        .section-title {
            font-size: 1.4rem;
            font-weight: 600;
            color: #5A2FC2;
            margin-bottom: 10px;
        }

        img {
            width: 100%;
            max-width: 500px;
            border-radius: 15px;
            display: block;
            margin: 15px auto;
            box-shadow: 0 3px 12px rgba(0,0,0,0.2);
        }

        p {
            line-height: 1.7;
            font-size: 1rem;
        }

        .tag-list {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .tag {
            background: #6EC6FF;
            color: white;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 600;
        }

        footer {
            text-align: center;
            padding: 20px;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<div class="container">

    <h1>WEBPROG SF241 - Jonard Bacani</h1>

    <div class="card">
        <div class="section-title">Picture Gallery</div>
        <img src="https://media.licdn.com/dms/image/v2/D5603AQFD757q3IPmxg/profile-displayphoto-shrink_800_800/profile-displayphoto-shrink_800_800/0/1693400289128?e=1765411200&v=beta&t=IgFdn7g39qe5Tx9mqau7CgL4jyhfDU66yAMOXuEs4Uo" alt="Profile Image">
    </div>

    <div class="card">
        <div class="section-title">About Me</div>
        <p>
            A dynamic, motivated, and highly accomplished professional with over 4 years of experience in customer service,
            account management, and administrative support.

            <br><br>
            Skilled in building long-term relationships, critical thinking, and adapting quickly to new technologies.  
            Fluent in English and Tagalog with strong written and verbal communication skills.
        </p>
    </div>

    <div class="card">
        <div class="section-title">Education</div>
        <p><strong>Asia Pacific College</strong><br>
        Bachelor of Science in Computer Science (Cybersecurity & Forensics)</p>
    </div>

    <div class="card">
        <div class="section-title">Interests</div>
        <div class="tag-list">
            <span class="tag">Cybersecurity</span>
            <span class="tag">Traveling</span>
            <span class="tag">Snorkeling</span>
            <span class="tag">Gaming</span>
        </div>
    </div>

    <div class="card">
        <div class="section-title">Goals</div>
        <p>To maintain focus, achieve personal and academic goals, and build a successful future in cybersecurity.</p>
    </div>

    <div class="card">
        <div class="section-title">Picture Gallery</div>
        <img src="https://www.w3schools.com/tags/img_girl.jpg" alt="Profile Image 2">
    </div>

</div>

<footer>
    © 2025 Jonard Bacani — WEBPROG SF241
</footer>

</body>
</html>
