<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mathodology</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
        }
        /* Header Section */
        header {
            background-color: #4caf50;
            color: white;
            padding: 1.5rem 0;
            text-align: center;
        }
        header h1 {
            font-size: 2.5rem;
        }
        header p {
            font-size: 1.2rem;
        }
        /* Navigation Bar */
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 1rem 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1.5rem;
            font-size: 1.1rem;
        }
        nav a:hover {
            text-decoration: underline;
            color: #4caf50;
        }
        /* Main Content */
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }
        .section {
            margin-bottom: 2rem;
        }
        .section h2 {
            font-size: 2rem;
            color: #4caf50;
            margin-bottom: 1rem;
        }
        .section p {
            font-size: 1.1rem;
        }
        ul {
            list-style: none;
        }
        ul li {
            margin: 0.5rem 0;
        }
        ul li a {
            color: #4caf50;
            text-decoration: none;
        }
        ul li a:hover {
            text-decoration: underline;
        }
        /* Footer Section */
        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 1.5rem 0;
            margin-top: 2rem;
        }
        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }
            nav a {
                margin: 0 0.5rem;
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Mathodology</h1>
        <p>Your ultimate guide for math concepts and problem-solving</p>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#videos">Videos</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about" class="section">
            <h2>About</h2>
            <p>Mathodology is your go-to platform for understanding complex math topics, solving challenging problems, and excelling in your mathematical journey.</p>
        </section>
        <section id="videos" class="section">
            <h2>Latest Videos</h2>
            <ul>
                <li><a href="#">Ring Theory in One Shot</a></li>
                <li><a href="#">Fixed Point Iteration Explained</a></li>
                <li><a href="#">Bisection Method Simplified</a></li>
            </ul>
        </section>
        <section id="contact" class="section">
            <h2>Contact</h2>
            <p>Have questions or suggestions? Reach out at <strong>ummemaryam1122@gmail.com</strong>.</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Mathodology. All Rights Reserved.</p>
    </footer>
</body>
</html>
