<!DOCTYPE html>
<html>
<head>
    <title>❤ Lauria's Love ❤</title>
    <style>
        body {
            background: url('https://images.unsplash.com/photo-1559563362-c7ba6410e267') fixed;
            background-size: cover;
            font-family: 'Brush Script MT', cursive;
            color: #FF1493;
        }
        .container {
            background: rgba(255, 255, 255, 0.9);
            padding: 20px;
            border-radius: 15px;
            max-width: 600px;
            margin: 50px auto;
        }
        h1 {
            text-shadow: 2px 2px 4px pink;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🦋 致我的法国玫瑰 Lauria 🥀</h1>
        <img src="https://images.unsplash.com/photo-1510525009512-ad7fc13eefab" 
             style="width:100%;border-radius:10px">
        <p>🇨🇳 Guangdong → 🇫🇷 Belgium</p>
        <p id="poem">我们的爱跨越经纬度...</p>
        <button onclick="showLove()">点击收获惊喜</button>
    </div>

    <script>
        const poems = [
            "布鲁塞尔的月光，照在广东的珠江",
            "Je t'aimerai jusqu'à ce que la Tour Eiffel s'effondre",
            "你是我永不凋谢的玫瑰",
            "中国到比利时的直线距离是 8,763 公里，但我们的心是零距离"
        ];
        
        function showLove() {
            const randomPoem = poems[Math.floor(Math.random() * poems.length)];
            document.getElementById('poem').innerHTML = `💌 ${randomPoem}`;
        }
    </script>
</body>
</html>
