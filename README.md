<!DOCTYPE html>
<html>
<head>
    <title>My Website</title>
    <style>
        /* Basic styling for navigation */
        ul.navbar {
            list-style-type: none;
            margin: 0;
            padding: 0;
            overflow: hidden;
            background-color: #333;
        }

        ul.navbar li {
            float: left;
        }

        ul.navbar li a {
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }

        ul.navbar li a:hover {
            background-color: #111;
        }
    </style>
</head>
<body>
    <ul class="navbar">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>

    <h1 id="home">Welcome to My Website!</h1>
    <p>This is a simple HTML website with navigation.</p>

    <h2 id="about">About</h2>
    <p>This website showcases the basics of HTML and navigation.</p>

    <h2 id="contact">Contact</h2>
    <p>You can reach me at example@example.com.</p>
</body>
</html>
