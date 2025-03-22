<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Task</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #4CAF50;
            padding: 20px;
            text-align: center;
            color: white;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
        }

        main {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            padding: 20px;
        }

        .card {
            background: white;
            padding: 20px;
            margin: 15px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
            width: 300px;
        }

        h2 {
            color: #4CAF50;
        }

        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 200px;
        }

        footer a {
            color: #4CAF50;
            text-decoration: none;
            margin: 0 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Your Website Task</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <div class="card">
            <h2>About CSS</h2>
            <p>Cascading Style Sheets (CSS) allow you to style and layout your web pages, adding colors, spacing, and more.</p>
        </div>
        <div class="card">
            <h2>Box Model</h2>
            <p>The CSS box model describes the rectangular boxes generated for elements. It includes margins, borders, padding, and the actual content.</p>
        </div>
        <div class="card">
            <h2>Responsive Design</h2>
            <p>Responsive design ensures your webpage looks great on all devices, from desktops to mobile phones.</p>
        </div>
    </main>

    <footer>
        <p>Created by Yuvraj Gupta | Follow us on 
            <a href="#">Instagram</a> | 
            <a href="#">Twitter</a> | 
            <a href="#">LinkedIn</a>
        </p>
    </footer>
</body>
</html>
