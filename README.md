# jaspershum79.github.io

<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>真心話大冒險</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f0f0;
        }

        h1 {
            margin-top: 50px;
            color: #333;
        }

        button {
            background-color: #4CAF50;
            border: none;
            color: white;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 10px 2px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>真心話大冒險</h1>
    <button id="truth">隨機抽取真心話</button>
    <button id="dare">隨機抽取大冒險</button>
    <p id="output"></p>

    <script>
        const truths = [
            "RC裏面邊個最靚仔？",
            "RC裏面邊個最靚女？",
            "你最後悔的一件事是什麼？",
            "説出曾經做過最尷尬既事",
            "你今日玩得最開心既環節係邊part？",
            "你最喜歡的食物是什麼？",
            "你的初戀是什麼時候？",
        ];

        const dares = [
            "唱一首飲歌(自己最中意既嗰part）",
            "同你右手邊第三個人換位置，並向左右兩位介紹自己",
            "對著你左手邊既人，唱一首你覺得最合適佢既歌",
            "對著你右手邊既人，用一首歌唱出想對佢既心聲",
            "行到全部人中間跳一段一分鐘既舞",
            "邀請你左手邊第二個人，到中間一齊跳我是個茶壺",
            "演繹出自己覺得尷尬的事情",
        ];

        function getRandomItem(arr) {
            return arr[Math.floor(Math.random() * arr.length)];
        }

        document.getElementById("truth").addEventListener("click", () => {
            document.getElementById("output").innerText = "真心話：" + getRandomItem(truths);
        });

        document.getElementById("dare").addEventListener("click", () => {
            document.getElementById("output").innerText = "大冒險：" + getRandomItem(dares);
        });
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>真心話大冒險</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f0f0;
        }

        h1 {
            margin-top: 50px;
            color: #333;
        }

        button {
            background-color: #4CAF50;
            border: none;
            color: white;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 10px 2px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>真心話大冒險</h1>
    <button id="truth">隨機抽取真心話</button>
    <button id="dare">隨機抽取大冒險</button>
    <p id="output"></p>

    <script>
        const truths = [
            "你最喜歡的人是誰？",
            "你最喜歡的電影是什麼？",
            "你最後悔的一件事是什麼？",
            "你曾經偷過什麼東西嗎？",
            "你最害怕的事物是什麼？",
            "你最喜歡的食物是什麼？",
            "你的初戀是什麼時候？",
        ];

        const dares = [
            "模仿動物聲音30秒",
            "用鼻子唱一首歌",
            "把冰塊放在衣服裡1分鐘",
            "向左邊的人道歉並擁抱他們",
            "用腳拿起筷子",
            "背對大家跳舞30秒",
            "說出自己最尷尬的一個經歷",
        ];

        function getRandomItem(arr) {
            return arr[Math.floor(Math.random() * arr.length)];
        }

        document.getElementById("truth").addEventListener("click", () => {
            document.getElementById("output").innerText = "真心話：" + getRandomItem(truths);
        });

        document.getElementById("dare").addEventListener("click", () => {
            document.getElementById("output").innerText = "大冒險：" + getRandomItem(dares);
        });
    </script>
</body>
</html>
