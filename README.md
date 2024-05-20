<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تبریک تولد ساناز</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #ffe6e6;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            overflow: hidden;
            position: relative;
        }
        .container {
            text-align: center;
            padding: 20px;
            border-radius: 10px;
            background: linear-gradient(45deg, #ff9999, #ff4d4d);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            z-index: 10;
        }
        .birthday-message {
            font-size: 36px;
            color: #fff;
            animation: fadeIn 2s ease-in-out infinite alternate;
        }
        @keyframes fadeIn {
            0% { opacity: 0; transform: scale(0.9); }
            100% { opacity: 1; transform: scale(1.1); }
        }
        .balloon {
            position: absolute;
            bottom: -100px;
            animation: float 6s ease-in-out infinite;
        }
        .balloon:nth-child(1) {
            left: 10%;
            animation-delay: 0s;
        }
        .balloon:nth-child(2) {
            left: 30%;
            animation-delay: 2s;
        }
        .balloon:nth-child(3) {
            left: 50%;
            animation-delay: 4s;
        }
        .balloon:nth-child(4) {
            left: 70%;
            animation-delay: 6s;
        }
        .balloon:nth-child(5) {
            left: 90%;
            animation-delay: 8s;
        }
        @keyframes float {
            0% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
            100% { transform: translateY(0); }
        }
        .cake {
            position: absolute;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
        }
    </style>
</head>
<body>
    <div class="container">
        <p class="birthday-message">تولدت مبارک ساناز</p>
    </div>
    <img src="https://i.ibb.co/fH9N7ty/balloon.png" class="balloon" alt="balloon">
    <img src="https://i.ibb.co/fH9N7ty/balloon.png" class="balloon" alt="balloon">
    <img src="https://i.ibb.co/fH9N7ty/balloon.png" class="balloon" alt="balloon">
    <img src="https://i.ibb.co/fH9N7ty/balloon.png" class="balloon" alt="balloon">
    <img src="https://i.ibb.co/fH9N7ty/balloon.png" class="balloon" alt="balloon">
    <img src="https://i.ibb.co/R7x2dxk/cake.png" class="cake" alt="cake">
</body>
</html>
