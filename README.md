<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ứng dụng nhỏ</title>
  <style>
    body {
      background-color: #f2f2f2;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      text-align: center;
    }
    .container {
      background: #fff;
      padding: 30px;
      border-radius: 12px;
      max-width: 500px;
      margin: 50px auto;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    img {
      width: 100%;
      max-width: 300px;
      border-radius: 8px;
    }
    button {
      background-color: #4caf50;
      color: white;
      padding: 12px 24px;
      border: none;
      border-radius: 6px;
      font-size: 16px;
      cursor: pointer;
      margin-top: 20px;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Chào mừng đến với App của bạn!</h1>
    <p>Đây là một giao diện HTML đơn giản, có thể tích hợp vào app.</p>
    <img src="https://via.placeholder.com/300x200" alt="Hình minh họa">
    <br>
    <button onclick="alert('Bạn đã nhấn nút!')">Nhấn tôi</button>
  </div>
</body>
</html>