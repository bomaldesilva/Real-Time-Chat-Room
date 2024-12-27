<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Real-Time Chat Room App</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 15px 0;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        .content {
            padding: 20px;
        }
        .section {
            margin-bottom: 20px;
        }
        .features, .tech-stack {
            list-style-type: none;
            padding-left: 0;
        }
        .features li, .tech-stack li {
            margin: 10px 0;
            font-size: 1.1em;
        }
        .tech-stack li {
            font-weight: bold;
        }
        .tech-stack li span {
            font-weight: normal;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Real-Time Chat Room App 🌐💬</h1>
    </header>
    
    <div class="content">
        <section class="description section">
            <h2>Overview</h2>
            <p>A real-time chat room application built with Django, enabling seamless communication between users. This app showcases the integration of WebSocket technology for real-time messaging, along with Django's robust backend capabilities.</p>
        </section>

        <section class="features section">
            <h2>Features</h2>
            <ul>
                <li>🔹 <strong>Real-Time Messaging:</strong> Instant communication powered by WebSockets (using Django Channels).</li>
                <li>🔹 <strong>User Authentication:</strong> Secure login and signup functionality for users.</li>
                <li>🔹 <strong>Dynamic Chat Rooms:</strong> Create, join, and manage multiple chat rooms.</li>
                <li>🔹 <strong>Message Persistence:</strong> Stores chat history in a database for later access.</li>
                <li>🔹 <strong>Responsive Design:</strong> Mobile-friendly UI for an optimal experience across devices.</li>
            </ul>
        </section>

        <section class="tech-stack section">
            <h2>Tech Stack</h2>
            <ul>
                <li><span>Frontend:</span> HTML, CSS, JavaScript (with WebSocket integration)</li>
                <li><span>Backend:</span> Django Framework (with Django Channels for WebSocket support)</li>
                <li><span>Database:</span> SQLite (default, replaceable with PostgreSQL/MySQL)</li>
                <li><span>Deployment:</span> Dockerized setup, ready for cloud deployment</li>
            </ul>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Real-Time Chat Room App | All rights reserved.</p>
    </footer>
</body>
</html>
