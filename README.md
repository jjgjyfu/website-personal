
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday, Aa unangg kuu sayangggg!</title>
    <style>
        body {
            background-color: #f7f7f7;
            font-family: 'Arial', sans-serif;
            text-align: center;
            padding: 50px;
            overflow: hidden;
        }
        h1 {
            color: #ff6b6b;
            font-size: 48px;
            margin-bottom: 20px;
            opacity: 0;
            animation: fadeIn 2s ease-in-out forwards, slideIn 1s ease-out;
        }
        p {
            color: #333;
            font-size: 24px;
            margin-bottom: 30px;
            opacity: 0;
            animation: fadeIn 3s ease-in-out forwards;
        }
        .heart {
            color: red;
            font-size: 100px;
            margin: 20px 0;
            opacity: 0;
            animation: pulse 1s infinite, fadeIn 4s ease-in-out forwards;
        }
        a.button {
            display: inline-block;
            padding: 15px 25px;
            font-size: 20px;
            color: white;
            background-color: #ff6b6b;
            border-radius: 50px;
            text-decoration: none;
            opacity: 0;
            animation: fadeIn 5s ease-in-out forwards, bounceIn 2s ease-in-out 5s;
        }
        a.button:hover {
            background-color: #ff5252;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideIn {
            from { transform: translateY(-30px); }
            to { transform: translateY(0); }
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
        @keyframes bounceIn {
            0%, 20%, 50%, 80%, 100% {
                transform: translateY(0);
            }
            40% {
                transform: translateY(-20px);
            }
            60% {
                transform: translateY(-10px);
            }
        }
    </style>
</head>
<body>
    <h1>sayaaaanggkuu</h1>
    <p>selamatt datanggg dii hadiahhh driii ayanggmu yang cntik iniiiii hehehee klikk yaa aku ada kejutan buatt ayanggg</p>
    <p class="heart">&hearts;</p>
    <p>With all my love,<br>pacar kamu Denisss cantikkkkkk</p>
    <a href="sayang.html" class="button">Click inii syanggg kuuuu!</a>
</body>
</html>
