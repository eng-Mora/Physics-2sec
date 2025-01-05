<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
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
        .video-container, #videos {
            display: none;
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
            width: 100%;
            max-width: 560px;
            height: auto;
            aspect-ratio: 16/9;
        }
        footer {
            text-align: center;
            padding: 1.5rem;
            background: #2c3e50;
            color: #ecf0f1;
        }
        .login-form {
            max-width: 300px;
            margin: 50px auto;
            padding: 20px;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .login-form input {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .login-form button {
            width: 100%;
            padding: 10px;
            background: #2c3e50;
            color: white;
            border: none;
            border-radius: 5px;
        }
    </style>
    <script>
        function checkLogin() {
            const userid = document.getElementById('userid').value;
            const videoContainer = document.getElementById('videos');
            const videos = document.getElementsByClassName('video-container')[0].children;
            if (userid === '2526') {
                document.querySelector('.login-form').style.display = 'none';
                videoContainer.style.display = 'block';
                videos[0].style.display = 'block';
                videos[1].style.display = 'none';
            } else if (userid === '4545') {
                document.querySelector('.login-form').style.display = 'none';
                videoContainer.style.display = 'block';
                videos[0].style.display = 'none';
                videos[1].style.display = 'block';
            } else {
                alert('Invalid UserID');
            }
        }
        console.log('Page loaded successfully');
    </script>
</head>
<body>
    <header>
        <h1>The Process platform</h1>
         <h1 style="font-size: smaller;">Eng: Tarek mohamed</h1>

    </header>

    <main>
        <section class="login-form">
            <h2>Login</h2>
            <input type="text" id="userid" placeholder="Enter UserID">
            <button onclick="checkLogin()">Login</button>
        </section>

        <section id="videos">
            <h2>Embedded Videos</h2>
            <div class="video-container">
                <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Embedded Video 1" frameborder="0" allowfullscreen></iframe>
                <iframe src="https://www.youtube.com/embed/tgbNymZ7vqY" title="Embedded Video 2" frameborder="0" allowfullscreen></iframe>
            </div>
        </section>

    </main>

    <footer>
        <p>&copy; Developed by Eng: Amr Mohamed</p>
    </footer>
