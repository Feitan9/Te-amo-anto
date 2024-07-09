<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Te amo Antonella Benedetti</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f8ff;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        h1 {
            font-size: 3em;
            color: #ff69b4;
            text-shadow: 2px 2px #ff1493;
            margin-bottom: 20px;
        }
        .flower {
            position: relative;
            width: 100px;
            height: 150px;
        }
        .flower .petal {
            position: absolute;
            width: 100px;
            height: 100px;
            background-color: #ff69b4;
            border-radius: 50%;
        }
        .flower .petal:nth-child(1) {
            top: 0;
            left: 0;
        }
        .flower .petal:nth-child(2) {
            top: 0;
            right: 0;
        }
        .flower .petal:nth-child(3) {
            top: 25px;
            left: -25px;
        }
        .flower .petal:nth-child(4) {
            top: 25px;
            right: -25px;
        }
        .flower .petal:nth-child(5) {
            top: 50px;
            left: 0;
        }
        .flower .petal:nth-child(6) {
            top: 50px;
            right: 0;
        }
        .flower .center {
            position: absolute;
            top: 25px;
            left: 25px;
            width: 50px;
            height: 50px;
            background-color: #ff1493;
            border-radius: 50%;
        }
        .stem {
            width: 10px;
            height: 200px;
            background-color: #008000;
            margin: 0 auto;
        }
        .leaf {
            position: absolute;
            width: 20px;
            height: 40px;
            background-color: #008000;
            border-radius: 20px 20px 0 0;
        }
        .leaf.left {
            top: 50%;
            left: -20px;
            transform: rotate(-45deg);
        }
        .leaf.right {
            top: 50%;
            right: -20px;
            transform: rotate(45deg);
        }
    </style>
</head>
<body>
    <h1>Te amo Antonella Benedetti</h1>
    <div class="flower">
        <div class="petal"></div>
        <div class="petal"></div>
        <div class="petal"></div>
        <div class="petal"></div>
        <div class="petal"></div>
        <div class="petal"></div>
        <div class="center"></div>
        <div class="stem"></div>
        <div class="leaf left"></div>
        <div class="leaf right"></div>
    </div>
</body>
</html>
