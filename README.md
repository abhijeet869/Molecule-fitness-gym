<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Warrior Fitness</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #006400, #333);
            color: #fff;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            animation: fadeIn 1s ease-in-out;
        }
        h1 {
            font-size: 4em;
            color: #d4af37; /* Gold for Warrior */
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.6);
        }
        p {
            font-size: 1.4em;
            color: #bbb;
            margin: 20px 0;
            text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.5);
        }
        .cta-button {
            background-color: #d4af37;
            color: #333;
            padding: 18px 36px;
            font-size: 1.3em;
            border: none;
            cursor: pointer;
            border-radius: 50px;
            transition: all 0.3s ease-in-out;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
            text-transform: uppercase;
            font-weight: bold;
        }
        .cta-button:hover {
            background-color: #b38b2d;
            transform: translateY(-5px);
            box-shadow: 0 6px 18px rgba(0, 0, 0, 0.4);
        }
        .cta-button:active {
            transform: translateY(1px);
        }
        footer {
            background-color: rgba(0, 0, 0, 0.8);
            color: #bbb;
            padding: 20px;
            position: absolute;
            width: 100%;
            bottom: 0;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
    </style>
</head>
<body>
    <div>
        <h1>Warrior Fitness</h1>
        <p>Unleash Your Power</p>
        <button class="cta-button" onclick="window.location.href='#'">Join Now</button>
    </div>
    
    <footer>
        <p>&copy; 2024 Warrior Fitness. All Rights Reserved.</p>
    </footer>
</body>
</html>
