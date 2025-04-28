<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile của Tôi</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .profile {
            background: white;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            text-align: center;
            width: 300px;
        }

        .avatar {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 15px;
        }

        h1 {
            margin: 10px 0;
            font-size: 24px;
        }

        .title {
            color: #777;
            font-size: 18px;
        }

        .description {
            font-size: 14px;
            color: #555;
            margin: 15px 0;
        }

        .social-links {
            margin-top: 20px;
        }

        .social-links a {
            text-decoration: none;
            color: #007BFF;
            margin: 0 10px;
            font-weight: bold;
        }

        .social-links a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile">
            <img src="avatar.jpg" alt="Ảnh đại diện" class="avatar">
            <h1>Lê Phát Đạt</h1>
            <p class="title">Lập trình viên Full Stack</p>
            <p class="description">Tôi là một lập trình viên đam mê công nghệ và yêu thích việc phát triển phần mềm. Tôi có ít kinh nghiệm trong việc xây dựng các ứng dụng web và di động.</p>
            <div class="social-links">
                <a href="https://github.com/lephatdatcr123/lephatdatcr123/edit/main/README.md" target="_blank">GitHub</a>
            </div>
        </div>
    </div>
</body>
</html>
