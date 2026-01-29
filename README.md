# bindz2008.github.io
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Web Giới Thiệu Bản Thân</title>
    <style>
        /* PHẦN TÙY CHỈNH MÀU SẮC - Bạn có thể đổi mã màu ở đây */
        :root {
            --primary-pink: #ffafcc; /* Màu nền chính */
            --secondary-pink: #ffc8dd; /* Màu các ô nội dung */
            --accent-pink: #fb607f; /* Màu nút và tiêu đề */
            --text-color: #4a4a4a;
            --white: #ffffff;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--primary-pink);
            color: var(--text-color);
            line-height: 1.6;
        }

        nav {
            background: var(--white);
            padding: 1rem;
            position: sticky;
            top: 0;
            display: flex;
            justify-content: center;
            gap: 20px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            z-index: 1000;
        }

        nav a {
            text-decoration: none;
            color: var(--accent-pink);
            font-weight: bold;
            text-transform: uppercase;
        }

        section {
            padding: 60px 20px;
            max-width: 1000px;
            margin: 0 auto;
        }

        /* TRANG CHỦ */
        .home-container {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            gap: 30px;
            background: var(--white);
            padding: 30px;
            border-radius: 20px;
        }

        .profile-pic {
            width: 340px;
            height: 500px;
            object-fit: cover;
            border-radius: 15px;
            border: 5px solid var(--secondary-pink);
        }

        .info-text h1 {
            font-size: 3rem;
            color: var(--accent-pink);
        }

        .slogan {
            font-style: italic;
            margin-top: 10px;
            color: #666;
            display: block;
        }

        .social-links {
            margin-top: 20px;
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            background: var(--accent-pink);
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-right: 10px;
            transition: 0.3s;
        }

        .media-box {
            margin-top: 30px;
            width: 100%;
            text-align: center;
        }

        video {
            width: 100%;
            max-width: 600px;
            border-radius: 10px;
            margin-bottom: 15px;
        }

        /* GIỚI THIỆU */
        .intro-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }

        .card {
            background: var(--secondary-pink);
            padding: 25px;
            border-radius: 15px;
            border-left: 8px solid var(--accent-pink);
        }

        .card h3 {
            margin-bottom: 15px;
            color: var(--accent-pink);
            font-size: 1.5rem;
        }

        /* HOẠT ĐỘNG */
        .activities {
            background: var(--white);
            padding: 30px;
            border-radius: 20px;
            text-align: center;
        }

        footer {
            text-align: center;
            padding: 20px;
            font-size: 0.9rem;
            opacity: 0.8;
        }

        @media (max-width: 768px) {
            .home-container { flex-direction: column; text-align: center; }
            .intro-grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>

    <nav>
        <a href="#home">Trang chủ</a>
        <a href="#about">Giới thiệu</a>
        <a href="#activities">My Album</a>
    </nav>

    <section id="home">
        <div class="home-container">
            <div>
                <img src="https://i.postimg.cc/x8Tx5zJY/IMG-1322.jpg" alt="Ảnh của tôi" class="profile-pic">
                <span class="slogan">"Vẽ cầu vồng thì thiếu nắng, vẽ tình yêu thì em thiếu vắng."</span>
            </div>
            <div class="info-text">
                <p>Chào mừng bạn đã ghé thăm trang wed giới thiệu bản thân của mình</p>
                               <h1> <strong> Đồng Quốc Bình<strong><h1>
                <div class="social-links">
                    <a href="hhttps://www.facebook.com/share/1ATkyHsC4s/?mibextid=wwXIfr" class="btn">Facebook</a>
                    <a href="mailto:dongquocbinh2008@gmail.com" class="btn"> Email</a>
                </div>
            </div>

            <div class="media-box">
                <h3>Video Giới thiệu</h3>
                <video controls>
                    <source src="https://files.catbox.moe/7ydqee.mp4" type="video/mp4">
                </video>
                <br>
                <audio controls>
                    <source src="https://files.catbox.moe/xsuut8.mp3" type="audio/mpeg">
                </audio>
            </div>
        </div>
    </section>

    <section id="about">
        <div class="intro-grid">
            <div class="card">
                <h3>Học vấn</h3>
                <p>Học tại trường THPT Minh Hoà, học lớp 12A3. dự định sau này sẽ học trường quân sự.</p>
            </div>
            <div class="card">
                <h3>Sở thích</h3>
                <p>Thích chơi game, tập gym và thể thao.</p>
            </div>
        </div>
    </section>

    <section id="activities">
        <div class="activities">
            <h2 style="color: var(--accent-pink); margin-bottom: 20px;">My Album</h2>
            <p></p>
        </div>
    </section>
               <div class="video-bottom-container">
                <div class="video-item">
                    <video controls style="height: 120%; object-fit: cover;">
                        <source src="https://files.catbox.moe/fwb754.mp4" type="video/mp4">
                    </video>
                </div>
                <div class="video-item">
                    <video controls style="height: 120%; object-fit: cover;">
                        <source src="https://files.catbox.moe/lu0a3u.mov" type="video/mp4">
                    </video>
                </div>

    <footer>
        &copy; 2026 Bản quyền thuộc về Đồng Quốc Bình.
    </footer>

</body>
</html>
