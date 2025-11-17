<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Frame</title>

    <style>
        body {
            background: #111;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            color: white;
            font-family: Arial;
        }

        .frame-box {
            width: 300px;
            padding: 20px;
            border: 3px solid transparent;
            border-image: linear-gradient(45deg, #ff007f, #00eaff) 1;
            border-radius: 15px;
            text-align: center;
        }

        .frame-box img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 10px;
        }

        .frame-box h2 {
            margin: 0;
            font-size: 22px;
        }

        .frame-box p {
            margin: 5px 0;
            font-size: 14px;
        }
    </style>
</head>

<body>
    <div class="frame-box">
        <img src="blue_border.png" alt="Profile">
        <h2>Your Name</h2>
        <p>Web Developer | C, C++, Python</p>
    </div>
</body>
</html>
