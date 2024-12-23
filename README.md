<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kritika Khanagwal - Yoga Instructor</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;700&display=swap" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #f5f7fa, #c3cfe2);
            color: #2c3e50;
            scroll-behavior: smooth;
        }
        header {
            background: linear-gradient(135deg, #70c1b3, #4ecdc4);
            color: white;
            text-align: center;
            padding: 100px 20px;
            position: relative;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        header h1 {
            font-size: 3.5em;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 3px;
            margin: 0;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
        }
        header p {
            font-size: 1.5em;
            margin-top: 20px;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #2c3e50;
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 10;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 20px;
            font-weight: bold;
            font-size: 1.2em;
            position: relative;
        }
        nav a::after {
            content: '';
            display: block;
            width: 0;
            height: 3px;
            background: #70c1b3;
            transition: width 0.3s;
            margin: auto;
        }
        nav a:hover::after {
            width: 100%;
        }
        section {
            padding: 50px 20px;
            margin: 20px auto;
            max-width: 900px;
            background: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            border-radius: 10px;
            animation: fadeIn 1s;
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        h1, h2 {
            color: #4ecdc4;
            text-align: center;
        }
        footer {
            text-align: center;
            background: #2c3e50;
            color: white;
            padding: 20px;
            margin-top: 20px;
        }
        footer a {
            color: #70c1b3;
            text-decoration: none;
            font-weight: bold;
        }
        footer a:hover {
            text-decoration: underline;
        }
        .services-list li {
            position: relative;
            padding: 10px;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .services-list li:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }
        .contact-btn {
            display: inline-block;
            background: #4ecdc4;
            color: white;
            padding: 15px 25px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            font-size: 1.2em;
            transition: background 0.3s;
        }
        .contact-btn:hover {
            background: #3bb4a4;
        }
        .icon {
            font-size: 24px;
            margin-right: 10px;
            color: #4ecdc4;
        }
    </style>
</head>
<body>
    <header>
        <h1>Kritika Khanagwal</h1>
        <p>Yoga Instructor | Jaipur, Rajasthan</p>
    </header>

    <nav>
        <a href="#about">About Me</a>
        <a href="#experience">Experience</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>I am an experienced and passionate yoga instructor with over 2 years of experience teaching yoga to individuals and small groups. My goal is to help people achieve physical and mental well-being through customized yoga sessions.</p>
    </section>

    <section id="experience">
        <h2>Experience</h2>
        <ul>
            <li><strong>Yoga Instructor</strong> (Self-Employed, 2022 – 2024)
                <ul>
                    <li>Provided personalized yoga training to clients, focusing on improving flexibility, strength, and mental peace.</li>
                    <li>Designed and implemented effective yoga routines tailored to individual needs.</li>
                    <li>Built long-term relationships with clients, resulting in positive word-of-mouth referrals.</li>
                </ul>
            </li>
        </ul>
    </section>

    <section id="services">
        <h2>Services</h2>
        <p>I offer the following yoga services:</p>
        <ul class="services-list">
            <li>One-on-one personalized yoga sessions</li>
            <li>Group yoga classes</li>
            <li>Online yoga training</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>If you are interested in my yoga sessions or have any questions, feel free to reach out!</p>
        <p><i class="fas fa-envelope icon"></i>Email: <a href="mailto:khanagwalkritika8@gmail.com">khanagwalkritika8@gmail.com</a></p>
        <p><i class="fas fa-phone icon"></i>Phone: +91 70141 33294</p>
        <a href="contact.html" target="_blank" class="contact-btn">Contact Me</a>
    </section>

    <footer>
        <p>&copy; 2024 Kritika Khanagwal. All Rights Reserved.</p>
        <a href="#about">Back to Top</a>
    </footer>
</body>
</html>
