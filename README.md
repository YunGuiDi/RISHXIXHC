<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <title>我的第一個網頁</title>
    
    <!-- CSS 區塊：負責外觀 -->
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f2f5;
            text-align: center;
            padding: 50px;
        }
        h1 {
            color: #1877f2;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #00bef0;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <!-- HTML 區塊：負責內容 -->
    <h1>Hello, World!</h1>
    <p>這是我的第一個網頁內容。</p>
    <button id="myButton">點擊我</button>

    <!-- JavaScript 區塊：負責互動 -->
    <script>
        // 抓取按鈕元素，並綁定點擊事件
        document.getElementById('myButton').addEventListener('click', function() {
            alert('你點擊了按鈕！網頁產生了互動。');
        });
    </script>

</body>
</html>

