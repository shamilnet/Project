<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f2f2f2;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .login-box {
      background: #fff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0px 4px 6px rgba(0,0,0,0.1);
      width: 320px;
      text-align: center;
    }
    .login-box h2 {
      margin-bottom: 20px;
    }
    .login-box input {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 14px;
    }
    .login-box button {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: none;
      border-radius: 6px;
      font-size: 14px;
      cursor: pointer;
    }
    .login-btn {
      background: #007BFF;
      color: white;
    }
    .login-btn:hover {
      background: #0056b3;
    }
    .register-bus {
      background: #28a745;
      color: white;
    }
    .register-bus:hover {
      background: #1e7e34;
    }
    .register-college {
      background: #ffc107;
      color: black;
    }
    .register-college:hover {
      background: #e0a800;
    }
  </style>
</head>
<body>
  <div class="login-box">
    <h2>Login</h2>
    <form action="#" method="post">
      <input type="text" name="username" placeholder="Username" required>
      <input type="password" name="password" placeholder="Password" required>
      <button type="submit" class="login-btn">Login</button>
    </form>
    <hr>
    <button class="register-bus">Register as Bus Owner</button>
    <button class="register-college">Register as College</button>
  </div>
</body>
</html>