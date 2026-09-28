<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Fram Late</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #f5f7f6;
            color: #222;
        }

        header {
            background: #ffffff;
            padding: 16px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 2px 10px rgba(0,0,0,0.08);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #159447;
        }

        nav a {
            text-decoration: none;
            color: #333;
            margin-left: 15px;
            font-size: 14px;
        }

        .hero {
            min-height: 80vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 30px 20px;
            background: linear-gradient(135deg, #e9fff1, #ffffff);
        }

        .hero h1 {
            font-size: 42px;
            color: #159447;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 17px;
            color: #555;
            max-width: 600px;
            margin: auto;
            line-height: 1.6;
        }

        .buttons {
            margin-top: 25px;
        }

        .btn {
            display: inline-block;
            padding: 13px 24px;
            border-radius: 8px;
            text-decoration: none;
            margin: 5px;
            font-weight: bold;
        }

        .primary {
            background: #159447;
            color: white;
        }

        .secondary {
            background: white;
            color: #159447;
            border: 1px solid #159447;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #ffffff;
            color: #777;
            font-size: 14px;
        }

        @media (max-width: 600px) {
            .hero h1 {
                font-size: 34px;
            }

            nav a {
                margin-left: 8px;
                font-size: 12px;
            }
        }
    </style>
</head>

<body>

<header>
    <div class="logo">Fram Late</div>

    <nav>
        <a href="#">Home</a>
        <a href="#">Login</a>
        <a href="#">Register</a>
    </nav>
</header>

<section class="hero">
    <div>
        <h1>Welcome to Fram Late</h1>

        <p>
            A modern platform built for our community.
            Your journey starts here.
        </p>

        <div class="buttons">
            <a href="#" class="btn primary">Get Started</a>
            <a href="#" class="btn secondary">Learn More</a>
        </div>
    </div>
</section>

<footer>
    © 2026 Fram Late. All rights reserved.
</footer>

</body>
</html>