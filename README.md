<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to the Healthy Lifestyle Program</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #28a745;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #222;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #575757;
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        h2 {
            color: #333;
        }
        .content-section {
            margin-bottom: 40px;
        }
        .content-section img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            margin-top: 20px;
        }
        .content-section p {
            margin: 10px 0;
        }
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
        .tips {
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            margin-top: 20px;
        }
        .tips ul {
            list-style-type: disc;
            padding-left: 20px;
        }
        .tips li {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to the Healthy Lifestyle Program</h1>
        <p>Your journey to a healthier life begins here</p>
    </header>

    <nav>
        <a href="#healthy-food">Healthy Food</a>
        <a href="#lifestyle-tips">Lifestyle Tips</a>
        <a href="#contact">Contact Us</a>
    </nav>

    <div class="container">
        <!-- Healthy Food Section -->
        <section id="healthy-food" class="content-section">
            <h2>Healthy Food</h2>
            <img src="https://example.com/healthy-food.jpg" alt="Healthy food">
            <p>Eating a variety of foods is essential to good health. Incorporating fruits, vegetables, whole grains, and lean proteins into your diet helps ensure that you get all the necessary nutrients.</p>
        </section>

        <!-- Lifestyle Tips Section -->
        <section id="lifestyle-tips" class="content-section">
            <h2>Lifestyle Tips</h2>
            <img src="https://example.com/lifestyle-tips.jpg" alt="Healthy lifestyle tips">
            <div class="tips">
                <ul>
                    <li>Stay hydrated by drinking plenty of water throughout the day.</li>
                    <li>Get at least 30 minutes of physical activity daily.</li>
                    <li>Prioritize sleep by aiming for 7-9 hours each night.</li>
                    <li>Practice mindfulness or meditation to reduce stress.</li>
                    <li>Limit processed foods and focus on whole, natural ingredients.</li>
                </ul>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="content-section">
            <h2>Contact Us</h2>
            <div class="contact-form">
                <form action="#" method="post">
                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name" required>

                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>

                    <label for="message">Message:</label>
                    <textarea id="message" name="message" rows="5" required></textarea>

                    <button type="submit">Submit</button>
                </form>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Healthy Lifestyle Program. All rights reserved.</p>
    </footer>
</body>
</html>
