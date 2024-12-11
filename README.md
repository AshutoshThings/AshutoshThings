<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ashutosh's GitHub</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: #121212;
            color: #e0e0e0;
            overflow-x: hidden;
        }
        header {
            text-align: center;
            padding: 100px 20px;
            background: linear-gradient(135deg, #333333, #555555);
            color: white;
            clip-path: polygon(0 0, 100% 0, 100% 85%, 0 100%);
            animation: fadeIn 2s;
            position: relative;
        }
        header h1 {
            font-size: 3.5em;
            margin: 0;
            animation: bounceIn 2s ease-in-out;
        }
        header p {
            font-size: 1.5em;
            animation: fadeText 3s ease-in-out;
        }
        @keyframes bounceIn {
            0% {
                transform: scale(0.9);
                opacity: 0.5;
            }
            50% {
                transform: scale(1.1);
                opacity: 0.8;
            }
            100% {
                transform: scale(1);
                opacity: 1;
            }
        }
        @keyframes fadeText {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            max-width: 1200px;
            margin: 40px auto;
            padding: 20px;
        }
        .card {
            background: #1e1e1e;
            border-radius: 15px;
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.3);
            padding: 20px;
            transition: transform 0.4s, box-shadow 0.4s;
            position: relative;
            overflow: hidden;
            width: 300px;
            text-align: center;
        }
        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 25px rgba(0, 0, 0, 0.5);
        }
        .card h2 {
            font-size: 1.5em;
            color: #00adb5;
        }
        .card ul {
            list-style: none;
            padding: 0;
        }
        .card li {
            margin: 10px 0;
        }
        a {
            color: #00adb5;
            text-decoration: none;
            transition: color 0.3s;
        }
        a:hover {
            color: #ff5722;
        }
        footer {
            text-align: center;
            padding: 40px;
            background: linear-gradient(135deg, #333333, #555555);
            color: white;
            clip-path: polygon(0 20%, 100% 0, 100% 100%, 0 100%);
            animation: slideUp 2s;
        }
        footer a {
            margin: 0 10px;
            font-size: 1.5em;
        }
        footer a i {
            color: #00adb5;
            transition: color 0.3s;
        }
        footer a:hover i {
            color: #ff5722;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        @keyframes slideUp {
            from { transform: translateY(100px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
</head>
<body>
    <header>
        <h1>Hi there, I'm Ashutosh! 👋</h1>
        <p>Welcome to my tech journey 🌟</p>
    </header>
    <div class="container">
        <div class="card">
            <h2>🌟 About Me</h2>
            <ul>
                <li>🔭 Exploring projects like <strong>RetroChat</strong>.</li>
                <li>🎓 Aspiring <strong>Software Development Engineer</strong>.</li>
                <li>🌌 Inspired by movies and creativity fuels my code.</li>
                <li>🌱 Diving deeper into recursion and socket programming.</li>
            </ul>
        </div>
        <div class="card">
            <h2>🚀 Skills</h2>
            <ul>
                <li><strong>Languages:</strong> C, Java, Python</li>
                <li><strong>Web Development:</strong> HTML, CSS</li>
                <li><strong>Tools:</strong> Microsoft Azure, Arduino</li>
                <li><strong>Projects:</strong> RetroChat, Server-Client Model</li>
            </ul>
        </div>
        <div class="card">
            <h2>📈 Goals</h2>
            <ul>
                <li>📚 Master DSA & low-level programming.</li>
                <li>💼 Land a summer internship in India.</li>
                <li>🌐 Explore decentralized systems.</li>
                <li>🎨 Arduino applications for everyday use.</li>
            </ul>
        </div>
        <div class="card">
            <h2>🎬 Favorites</h2>
            <ul>
                <li><strong>Movies:</strong> Gladiator, WALL-E, Ex Machina</li>
                <li><strong>Series:</strong> Stranger Things, Narcos</li>
            </ul>
        </div>
    </div>
    <footer>
        <p>✨ Let’s Connect!</p>
        <p>
            <a href="https://www.linkedin.com/in/ashutoshv1089/" target="_blank"><i class="fab fa-linkedin"></i></a>
            <a href="https://www.instagram.com/ashutosh_things/" target="_blank"><i class="fab fa-instagram"></i></a>
            <a href="mailto:ashutoshv9648@gmail.com" target="_blank"><i class="fas fa-envelope"></i></a>
        </p>
    </footer>
</body>
</html>
