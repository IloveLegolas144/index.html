<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Cat</title>
    <style>
        body {
            background-color: #f0e68c;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
            margin: 0;
        }

        #container {
            position: relative;
            width: 400px;
            height: 200px;
            overflow: hidden;
        }

        #cat {
            position: absolute;
            bottom: 10px;
            left: 0;
            width: 100px;
            animation: move-cat 5s linear infinite;
        }

        #sign {
            position: absolute;
            top: -30px;
            left: 15px;
            width: 70px;
            text-align: center;
            color: white;
            background-color: #ff5733;
            border-radius: 5px;
            padding: 5px;
            font-family: Arial, sans-serif;
        }

        #balloon {
            position: absolute;
            top: -50px;
            width: 30px;
            left: 80px;
            animation: float-balloon 3s ease-in-out infinite;
        }

        @keyframes move-cat {
            0% {
                left: 0;
            }
            50% {
                left: 300px;
            }
            100% {
                left: 0;
            }
        }

        @keyframes float-balloon {
            0% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-10px);
            }
            100% {
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <div id="container">
        <img id="cat" src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/bc/Orange_tabby_cat_sitting.jpg/1200px-Orange_tabby_cat_sitting.jpg" alt="Orange Cat">
        <div id="sign">Happy Birthday!</div>
        <img id="balloon" src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Balloon.svg/2048px-Balloon.svg.png" alt="Balloon">
    </div>
    <script>
        // Optional: Add any additional JavaScript here
    </script>
</body>
</html>
