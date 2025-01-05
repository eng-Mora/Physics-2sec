<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Educational Platform</title>
    <style>
        body {
            font-family: 'Helvetica Neue', sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.8;
            color: #222;
            background-color: #eef2f3;
        }
        header {
            background: #2c3e50;
            color: #ecf0f1;
            padding: 1.5rem;
            text-align: center;
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
            color: #ecf0f1;
            text-decoration: none;
            font-weight: bold;
        }
        .video-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 2rem;
            padding: 2rem;
        }
        iframe {
            border-radius: 10px;
            border: 2px solid #2c3e50;
        }
        footer {
            text-align: center;
            padding: 1.5rem;
            background: #2c3e50;
            color: #ecf0f1;
        }
    </style>
    <script>
        console.log('Page loaded successfully');
    </script>
</head>
<body>
    <header>
        <h1>Welcome to My Educational Platform</h1>
        

    <main>
        <section id="videos">
            <h2>Embedded Videos</h2>
            <div class="video-container">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Embedded Video 1" frameborder="0" allowfullscreen></iframe>
                <iframe width="560" height="315" src="https://www.youtube.com/embed/tgbNymZ7vqY" title="Embedded Video 2" frameborder="0" allowfullscreen></iframe>
                <script>
                    console.log('Videos section loaded');
                </script>
            </div>
        </section>

    </main>

    <footer>
        <p>&copy; 2024 Educational Platform</p>
        <script>
            console.log('Footer loaded');
        </script>
    </footer>
