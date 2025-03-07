# -geeksforgeeks

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GeeksforGeeks - Home</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Simple styles for layout */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #2E2E2E;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        .navbar {
            background-color: #4CAF50;
            overflow: hidden;
        }

        .navbar a {
            float: left;
            display: block;
            color: white;
            padding: 14px 16px;
            text-align: center;
            text-decoration: none;
        }

        .navbar a:hover {
            background-color: #ddd;
            color: black;
        }

        .hero-section {
            background-color: #333;
            color: white;
            padding: 80px 0;
            text-align: center;
        }

        .hero-section h1 {
            font-size: 3em;
        }

        .hero-section p {
            font-size: 1.2em;
        }

        .content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }

        .card {
            background-color: white;
            border-radius: 8px;
            width: 30%;
            margin: 15px;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .card img {
            width: 100%;
            border-radius: 8px;
        }

        .card h3 {
            margin-top: 10px;
            font-size: 1.5em;
        }

        .footer {
            background-color: #2E2E2E;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>

<body>
    <header>
        <h1>GeeksforGeeks</h1>
        <p>Learn and improve your skills in coding and programming</p>
    </header>

    <div class="navbar">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#tutorials">Tutorials</a>
        <a href="#questions">Questions</a>
        <a href="#forum">Forum</a>
    </div>

    <section class="hero-section">
        <h1>Welcome to GeeksforGeeks</h1>
        <p>Your portal to the world of programming, coding, and problem solving.</p>
    </section>

    <div class="content">
        <div class="card">
            <img src="https://via.placeholder.com/300" alt="Tutorials">
            <h3>Tutorials</h3>
            <p>Get the best tutorials on algorithms, data structures, programming languages, and more.</p>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/300" alt="Problems">
            <h3>Practice Problems</h3>
            <p>Test your skills with coding challenges and improve your problem-solving abilities.</p>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/300" alt="Interview Questions">
            <h3>Interview Questions</h3>
            <p>Prepare for interviews with our vast collection of questions asked in top companies.</p>
        </div>
    </div>

    <footer class="footer">
        <p>&copy; 2025 GeeksforGeeks | All Rights Reserved</p>
    </footer>
</body>

</html>





