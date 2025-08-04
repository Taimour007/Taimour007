<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mechanical Engineering Profile</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #1a1a1a;
            color: #fff;
            overflow-x: hidden;
        }
        .container {
            text-align: center;
            padding: 20px;
        }
        .profile-pic {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #00ccff;
        }
        .header {
            font-size: 2.5em;
            color: #ff4444;
            text-shadow: 2px 2px #00ccff;
            margin-bottom: 10px;
        }
        .bio {
            font-size: 1.2em;
            max-width: 600px;
            margin: 0 auto;
        }
        .background {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            background: url('https://via.placeholder.com/100x50.png?text=F1+Car') repeat;
            animation: moveBackground 10s linear infinite;
            opacity: 0.5;
        }
        @keyframes moveBackground {
            0% { background-position: 0 0; }
            100% { background-position: -100px -50px; }
        }
        .links {
            margin-top: 20px;
        }
        .links a {
            color: #00ccff;
            text-decoration: none;
            margin: 0 10px;
            font-size: 1.1em;
        }
        .links a:hover {
            color: #ff4444;
        }
    </style>
</head>
<body>
    <div class="background"></div>
    <div class="container">
        <img src="https://via.placeholder.com/150" alt="Profile Picture" class="profile-pic">
        <h1 class="header">THE RACING ZONE</h1>
        <p class="bio">
            Mechanical Engineering Enthusiast | F1 Technology | Vehicle Dynamics | Robotics
        </p>
        <div class="links">
            <a href="https://github.com/your-username">GitHub</a>
            <a href="https://linkedin.com/in/your-username">LinkedIn</a>
            <a href="https://twitter.com/your-username">Twitter</a>
        </div>
    </div>

    <script>
        // Simple animation to mimic dynamic movement
        function animate() {
            const bio = document.querySelector('.bio');
            bio.style.opacity = '0.9';
            setTimeout(() => {
                bio.style.opacity = '1';
            }, 500);
        }
        setInterval(animate, 2000);
    </script>
</body>
</html>
