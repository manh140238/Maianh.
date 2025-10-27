# Maianh.

<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Giới Thiệu Bản Thân - Nguyễn Thị Mai Anh</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap');

    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #f9d3e3, #ffe5f0);
      color: #333;
      margin: 0;
      padding: 0;
    }

    .container {
      max-width: 800px;
      background: white;
      margin: 50px auto;
      border-radius: 20px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.1);
      overflow: hidden;
      animation: fadeIn 1s ease;
    }

    header {
      background: linear-gradient(135deg, #ff8fab, #ffb3c1);
      color: white;
      text-align: center;
      padding: 40px 20px;
    }

    header h1 {
      font-size: 2.5em;
      margin: 0;
    }

    header p {
      font-size: 1.1em;
      margin-top: 5px;
    }

    .content {
      padding: 30px;
      line-height: 1.8;
    }

    .info {
      margin-bottom: 20px;
    }

    .info h2 {
      color: #ff5d8f;
      border-left: 5px solid #ff5d8f;
      padding-left: 10px;
      margin-bottom: 10px;
    }

    .info p {
      margin: 5px 0;
    }

    .contact a {
      display: inline-block;
      text-decoration: none;
      color: white;
      background: #ff5d8f;
      padding: 10px 20px;
      border-radius: 25px;
      transition: 0.3s;
    }

    .contact a:hover {
      background: #ff85a2;
      transform: scale(1.05);
    }

    footer {
      background: #ffe6ef;
      text-align: center;
      padding: 15px;
      font-size: 0.9em;
      color: #777;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* Hiệu ứng ảnh đại diện */
    .avatar {
      display: flex;
      justify-content: center;
      margin-top: -60px;
    }

    .avatar img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 5px solid white;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }
  </style>
</head>
<body>

  <div class="container">
    <header>
      <h1>Nguyễn Thị Mai Anh</h1>
      <p>Học sinh lớp A2 - K59 - Trường THPT Phú Xuyên A</p>
    </header>

    <div class="avatar">
      <img src="https://i.pinimg.com/564x/12/30/1b/12301b2a95337a7b660f72a88d3a4b92.jpg" alt="Ảnh đại diện">
    </div>

    <div class="content">
      <div class="info">
        <h2>Thông tin cá nhân</h2>
        <p><strong>Ngày sinh:</strong> 14/03/2008</p>
        <p><strong>Giới tính:</strong> Nữ</p>
        <p><strong>Địa chỉ:</strong> Phú Xuyên, Hà Nội</p>
      </div>

      <div class="info">
        <h2>Sở thích</h2>
        <p>🎬 Xem phim</p>
        <p>🎧 Nghe nhạc</p>
      </div>

      <div class="info contact">
        <h2>Thông tin liên hệ</h2>
        <p><strong>Số điện thoại:</strong> 0369 458 308</p>
        <a href="https://www.facebook.com/share/16awY73Mus/" target="_blank">🌸 Facebook của Mai Anh</a>
      </div>
    </div>

    <footer>
      &copy; 2025 Nguyễn Thị Mai Anh | Thiết kế bởi chính mình 💖
    </footer>
  </div>

</body>
</html>
