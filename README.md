<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تسجيل دخول - مشابه لفيسبوك</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f2f5;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .login-container {
            background-color: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            width: 300px;
            text-align: center;
        }

        .login-container h2 {
            color: #1877f2;
        }

        .input-field {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 4px;
        }

        .login-btn {
            background-color: #1877f2;
            color: white;
            width: 100%;
            padding: 10px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }

        .login-btn:hover {
            background-color: #166fe5;
        }

        .signup-link {
            color: #1877f2;
            text-decoration: none;
            font-size: 14px;
        }

        .signup-link:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <h2>تسجيل دخول</h2>
        <form action="#" method="post">
            <input type="text" class="input-field" placeholder="البريد الإلكتروني أو رقم الهاتف" required><br>
            <input type="password" class="input-field" placeholder="كلمة المرور" required><br>
            <button type="submit" class="login-btn">تسجيل دخول</button>
        </form>
        <br>
        <a href="#" class="signup-link">هل نسيت كلمة المرور؟</a><br>
        <a href="#" class="signup-link">إنشاء حساب جديد</a>
    </div>
</body>
</html>
