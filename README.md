<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Top Tech Developers - Navigation Bar</title>
    <style>
        /* General body styling */
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background-color: #f5f5f5;
        }

        /* Navigation bar container */
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 30px;
            background: linear-gradient(90deg, #ff8a00, #da1b60, #5851db, #0f9b8e);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        /* Company logo */
        .navbar .logo {
            font-size: 28px;
            font-weight: bold;
            color: #fff;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
            cursor: pointer;
        }

        /* Navigation links */
        .navbar .nav-links {
            list-style: none;
            display: flex;
            margin: 0;
            padding: 0;
        }

        .navbar .nav-links li {
            margin: 0 15px;
        }

        .navbar .nav-links a {
            text-decoration: none;
            color: white;
            font-size: 16px;
            font-weight: 500;
            padding: 8px 16px;
            transition: 0.3s ease;
            border-radius: 5px;
        }

        /* Hover effect for links */
        .navbar .nav-links a:hover {
            background-color: rgba(255, 255, 255, 0.3);
            color: black;
        }

        /* Call-to-action button */
        .navbar .cta {
            background-color: #fff;
            color: #0f9b8e;
            font-weight: bold;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 25px;
            box-shadow: 0 3px 6px rgba(0, 0, 0, 0.2);
            transition: 0.3s ease;
        }

        .navbar .cta:hover {
            background-color: #0f9b8e;
            color: #fff;
        }
    </style>
</head>
<body>
    <div class="navbar">
        <div class="logo">Top Tech Developers</div>
        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
        <a href="#join-us" class="cta">Join Us</a>
    </div>
</body>
</html>
