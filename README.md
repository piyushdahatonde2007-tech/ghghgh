<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cute IP Opener</title>

    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #ffb6c1, #ffe4e1);
            font-family: "Poppins", sans-serif;
        }

        .card {
            background: #ffffffdd;
            backdrop-filter: blur(10px);
            padding: 40px;
            width: 300px;
            border-radius: 20px;
            text-align: center;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            animation: pop 0.4s ease;
        }

        @keyframes pop {
            from { transform: scale(0.8); opacity: 0; }
            to { transform: scale(1); opacity: 1; }
        }

        h2 {
            margin-bottom: 15px;
            color: #ff6f91;
        }

        p {
            color: #b71a1a;
            font-size: 14px;
        }

        button {
            margin-top: 20px;
            padding: 12px 20px;
            font-size: 15px;
            border: none;
            border-radius: 25px;
            background-color: #ff6f91;
            color: white;
            cursor: pointer;
            transition: 0.2s;
            box-shadow: 0 5px 15px rgba(255, 111, 145, 0.4);
        }

        button:hover {
            background-color: #ff507b;
            transform: translateY(-2px);
        }

        button:active {
            transform: translateY(0px);
        }
    </style>
</head>
<body>

    <div class="card">
        <h2>💖 Open IP Address</h2>
        <p>Click the cute button below to open your device IP.</p>

        
        <button onclick="window.open('https://www.youtube.com/', '_blank')">
            🌸 Open Now 🌸
        </button>
    </div>

</body>
</html>
