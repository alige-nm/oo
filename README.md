# oo
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的糖罐子</title>
    <style>
        body {
            background-color: pink;
            text-align: center;
            font-family: Arial, sans-serif;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            width: 80%;
            margin: 20px auto;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        button {
            background: #ff69b4;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background: #ff1493;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🐶 小狗的宝藏卡 💕</h1>
        <p>名称：糖罐小狗</p>
        <p>心情状态：😊</p>
        <button onclick="logHappyEvent()">点击记录今天的开心事！</button>
        <p id="log"></p>
    </div>

    <script>
        function logHappyEvent() {
            const log = document.getElementById("log");
            log.innerHTML = "今天的快乐已记录！🎉";
        }
    </script>
</body>
</html>