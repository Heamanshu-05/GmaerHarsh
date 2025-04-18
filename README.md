<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gamerharsh</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: white;
            text-align: center;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }
        header {
            background-color: #000;
            padding: 30px 0;
        }
        header img {
            width: 150px;
            border-radius: 10px;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            flex: 1;
        }
        h1, h2 {
            font-size: 2.5em;
            margin: 20px 0;
        }
        p {
            font-size: 1.2em;
            line-height: 1.6;
            max-width: 800px;
            margin: 20px auto;
        }
        .about-me, .channel-section, .video-section {
            background-color: #222;
            padding: 40px 20px;
            border-radius: 10px;
            margin-top: 30px;
        }
        .btn {
            background-color: red;
            color: white;
            padding: 15px 30px;
            font-size: 1.2em;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
        }
        .btn:hover {
            background-color: darkred;
        }
        footer {
            background-color: #000;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        iframe {
            width: 100%;
            max-width: 800px;
            height: 450px;
            border: none;
            margin: 20px auto;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://yt3.googleusercontent.com/pnOnZT99K_qOeDmAIY06F3wyJpcmBHvzczrpVm2B3nTJirHYpmWWe3nqVdZUO8ifpHe750FIR_A=s160-c-k-c0x00ffffff-no-rj" alt="Gamerharsh Logo">
        <h1>Welcome to Gamerharsh!</h1>
    </header>

    <div class="container">
        <section class="about-me">
            <h2>About Me</h2>
            <p>Hi, I’m Gamerharsh! I’m a passionate gamer and content creator, bringing you exciting gaming videos, walkthroughs, and much more. Join me on my journey to explore new games, strategies, and experiences in the gaming world. Don't forget to subscribe to my YouTube channel for the latest updates!</p>
        </section>

        <!-- New Section with YouTube Channel Button -->
        <section class="channel-section">
            <h2>Check Out My YouTube Channel</h2>
            <p>Want to see more awesome gaming content? Click the button below to visit my YouTube channel!</p>
            <a href="https://www.youtube.com/c/Gamerharsh" target="_blank" class="btn">Visit My Channel</a>
        </section>

        <!-- New Section with Video -->
        <section class="video-section">
            <h2>Check Out This Video!</h2>
            <p>Here's a quick gaming video from my channel. Enjoy!</p>
            <iframe src="https://www.youtube.com/embed/y3ZYOreGplk" title="YouTube video player"></iframe>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Gamerharsh. All Rights Reserved.</p>
    </footer>
</body>
</html>

