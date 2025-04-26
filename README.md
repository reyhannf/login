<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Login PKG</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #2c3e50, #3498db);
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      color: #fff;
    }
    .login-box {
      background: rgba(0, 0, 0, 0.5);
      padding: 40px;
      border-radius: 15px;
      width: 320px;
      box-shadow: 0 0 20px rgba(0,0,0,0.4);
      text-align: center;
    }
    .login-box h1 {
      margin-bottom: 30px;
      font-size: 28px;
      letter-spacing: 2px;
      color: #f1c40f;
    }
    .login-box input[type="text"],
    .login-box input[type="password"] {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: none;
      border-radius: 8px;
      outline: none;
    }
    .login-box button {
      background: #f1c40f;
      color: #000;
      border: none;
      padding: 12px;
      width: 100%;
      border-radius: 8px;
      font-weight: bold;
      cursor: pointer;
    }
    .login-box button:hover {
      background: #d4ac0d;
    }
    .footer {
      margin-top: 20px;
      font-size: 14px;
      color: #ddd;
    }
  </style>
</head>
<body>
  <div class="login-box">
    <h1>PKG Login</h1>
    <form action="proses_login.php" method="POST">
      <input type="text" name="username" placeholder="Username" required>
      <input type="password" name="password" placeholder="Password" required>
      <button type="submit">Masuk</button>
    </form>
    <div class="footer">
      © 2025 Grup PKG
    </div>
  </div>
</body>
</html>