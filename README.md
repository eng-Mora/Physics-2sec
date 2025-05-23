<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Educational Platform</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.8;
            color: #333;
            background-color: #f5f7fa;
        }
        header {
            background: linear-gradient(135deg, #3498db, #2c3e50);
            color: #fff;
            padding: 2rem;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        .subtitle {
            font-size: 1rem;
            margin-top: 0.5rem;
            opacity: 0.9;
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
            background-color: #fff;
            border-radius: 10px;
            margin: 2rem auto;
            max-width: 1200px;
            box-shadow: 0 2px 15px rgba(0,0,0,0.1);
        }
        iframe {
            border-radius: 12px;
            border: none;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            width: 100%;
            max-width: 560px;
            height: auto;
            aspect-ratio: 16/9;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        iframe:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0,0,0,0.15);
        }
        footer {
            text-align: center;
            padding: 1.5rem;
            background: #2c3e50;
            color: #ecf0f1;
            margin-top: 2rem;
        }
        .login-form {
            max-width: 350px;
            margin: 80px auto;
            padding: 30px;
            background: #fff;
            border-radius: 12px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            text-align: center;
        }
        .login-form h2 {
            color: #2c3e50;
            margin-bottom: 20px;
        }
        .login-form input {
            width: 100%;
            padding: 12px;
            margin-bottom: 15px;
            border: 1px solid #ddd;
            border-radius: 6px;
            font-size: 16px;
            transition: border-color 0.3s;
        }
        .login-form input:focus {
            border-color: #3498db;
            outline: none;
        }
        .login-form button {
            width: 100%;
            padding: 12px;
            background: linear-gradient(135deg, #3498db, #2980b9);
            color: white;
            border: none;
            border-radius: 6px;
            font-size: 16px;
            cursor: pointer;
            transition: background 0.3s, transform 0.2s;
        }
        .login-form button:hover {
            background: linear-gradient(135deg, #2980b9, #2c3e50);
            transform: translateY(-2px);
        }
        .login-form button:active {
            transform: translateY(0);
        }
        main {
            padding: 20px;
        }
        /* ستايلات قسم التواصل كما في الصورة */
        .contact-section {
            text-align: center;
            margin: 20px 0;
            font-family: 'Segoe UI', Tahoma, sans-serif;
        }
        .contact-message {
            color: #333;
            font-size: 16px;
            margin-bottom: 15px;
            font-weight: normal;
        }
        .social-buttons {
            display: flex;
            justify-content: center;
            gap: 10px;
        }
        .social-btn {
            background: none;
            border: none;
            padding: 8px;
            cursor: pointer;
        }
        .social-icon {
            color: #000;
            font-size: 28px;
            transition: all 0.2s;
                margin: 0 10px;

        }
        .social-icon:hover {
            opacity: 0.8;
        }
    </style>
</head>
<body>
    <header>
        <h1>The Process Platform</h1>
        <p class="subtitle">Eng: Tarek Mohamed</p>
    </header>

    <main>
        <section class="login-form">
            <h2>Welcome Back!</h2>
            <input type="text" id="userid" placeholder="Enter Your UserID">
            <button onclick="checkLogin()">Login</button>
            
            <!-- قسم التواصل في واجهة الدخول -->
            <div class="contact-section">
                <p class="contact-message">لو واجهتك مشكلة ابعثلي</p>
                <div class="social-buttons">
                        <a href="https://www.facebook.com/mamro8529?mibextid=ZbWKwL" target="_blank">
                            <i class="fab fa-facebook-f social-icon"></i>
                        </a>
                    </button>
                        <a href="https://wa.me/message/5LRM2DVHPZQFM1" target="_blank">
                            <i class="fab fa-whatsapp social-icon"></i>
                        </a>
                    </button>
                        <a href="http://t.me/Mora_mo1" target="_blank">
                            <i class="fab fa-telegram-plane social-icon"></i>
                        </a>
                    </button>
                </div>
            </div>
        </section>

        <section id="videos">
            <div class="video-container">
                <iframe class='sproutvideo-player' src='https://videos.sproutvideo.com/embed/4491d7b4181be0cfcd/2a86e553435b60bc' width='640' height='384' frameborder='0' allowfullscreen referrerpolicy='no-referrer-when-downgrade' title='Video Player'></iframe> 
                <iframe class='sproutvideo-player' src='https://videos.sproutvideo.com/embed/4491d7b4181be1cecd/636e3dd3df1b0486' width='640' height='384' frameborder='0' allowfullscreen referrerpolicy='no-referrer-when-downgrade' title='Video Player'></iframe>
                <iframe class='sproutvideo-player' src='https://videos.sproutvideo.com/embed/d391d7b4181be6c25a/d3d20251d3e491f5' width='640' height='384' frameborder='0' allowfullscreen referrerpolicy='no-referrer-when-downgrade' title='Video Player'></iframe>
                <iframe class='sproutvideo-player' src='https://videos.sproutvideo.com/embed/7091d7b4181be5c6f9/3fd0d885574a1845' width='640' height='384' frameborder='0' allowfullscreen referrerpolicy='no-referrer-when-downgrade' title='Video Player'></iframe>
                <iframe class='sproutvideo-player' src='https://videos.sproutvideo.com/embed/4491d7b4181beac5cd/3538aa27cf1f4000' width='640' height='384' frameborder='0' allowfullscreen referrerpolicy='no-referrer-when-downgrade' title='Video Player'></iframe>
                <iframe class='sproutvideo-player' src='https://videos.sproutvideo.com/embed/d391d7b4181ae1c45a/c9aa840e5bd38aac' width='640' height='384' frameborder='0' allowfullscreen referrerpolicy='no-referrer-when-downgrade' title='Video Player'></iframe> 
                <iframe class='sproutvideo-player' src='https://videos.sproutvideo.com/embed/ea91d7b4181bebca63/e6bcfedfa39f3476' width='640' height='384' frameborder='0' allowfullscreen referrerpolicy='no-referrer-when-downgrade' title='Video Player'></iframe> 
                <iframe class='sproutvideo-player' src='https://videos.sproutvideo.com/embed/4491d7b4181ae1cfcd/9c2c9da01aef89db' width='640' height='384' frameborder='0' allowfullscreen referrerpolicy='no-referrer-when-downgrade' title='Video Player'></iframe>
            </div>
            
            <!-- قسم التواصل في قسم الفيديوهات -->
            <div class="contact-section">
                <p class="contact-message">لو واجهتك مشكلة ابعثلي</p>
                <div class="social-buttons">
                        <a href="https://www.facebook.com/mamro8529?mibextid=ZbWKwL" target="_blank">
                            <i class="fab fa-facebook-f social-icon"></i>
                        </a>
                    </button>
                        <a href="https://wa.me/message/5LRM2DVHPZQFM1" target="_blank">
                            <i class="fab fa-whatsapp social-icon"></i>
                        </a>
                    </button>
                        <a href="http://t.me/Mora_mo1" target="_blank">
                            <i class="fab fa-telegram-plane social-icon"></i>
                        </a>
                    </button>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; Developed by Eng: Amr Mohamed</p>
    </footer>

    <script>
        function checkLogin() {
            const userid = document.getElementById('userid').value;
            const videoContainer = document.getElementById('videos');
            const videos = document.getElementsByClassName('video-container')[0].children;
            if (userid === '2526') {
                document.querySelector('.login-form').style.display = 'none';
                videoContainer.style.display = 'block';
                videos[0].style.display = 'block';
                videos[1].style.display = 'block';
                videos[2].style.display = 'block';
                videos[3].style.display = 'block';
                videos[4].style.display = 'none';
                videos[5].style.display = 'none';
                videos[6].style.display = 'none';
                videos[7].style.display = 'none';

            } else if (userid === '4545') {
                document.querySelector('.login-form').style.display = 'none';
                videoContainer.style.display = 'block';
                videos[4].style.display = 'block';
                videos[5].style.display = 'block';
                videos[6].style.display = 'block';
                videos[7].style.display = 'block';
                videos[0].style.display = 'none';
                videos[1].style.display = 'none';
                videos[2].style.display = 'none';
                videos[3].style.display = 'none';
            } else {
                alert('Invalid UserID');
            }
        }
        console.log('Page loaded successfully');
    </script>
