<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- 预加载关键资源 -1->
    <link rel="preload" href="https://cdn.jsdelivr.net/gh/your-repo/rose.jpg" as="image">
    <title>❤ Lauria & 你的名字 ❤</title>
    <style>
        :root {
            --rose-red: #FF0066;
            --gold: #FFD700;
        }
        /* 移动端优先设计 */
        body {
            background: linear-gradient(rgba(255,255,255,0.9), rgba(255,255,255,0.9)), 
                        url('https://cdn.jsdelivr.net/gh/your-repo/rose-pattern.jpg');
            font-family: 'Segoe UI', cursive;
            margin: 0;
            min-height: 100vh;
        }
        .header {
            background: url('https://cdn.jsdelivr.net/gh/your-repo/eiffel-tower.png') center/cover;
            padding: 20px;
            text-align: center;
        }
        /* 防字体加载失败 */
        @font-face {
            font-family: 'RomanticFont';
            src: local('Brush Script MT'), 
                 url('https://fonts.cdnfonts.com/s/12345/romantic.woff') format('woff');
        }
    </style>
</head>
<body>
    <div class="header">
        <h1 style="font-family: RomanticFont, cursive; color: var(--rose-red);">
            Lauria ❤ 你的名字
        </h1>
        <div class="flags">
            <img src="https://flagcdn.com/fr.svg" width="40" alt="法国">
            <img src="https://flagcdn.com/cn.svg" width="40" alt="中国">
        </div>
    </div>

    <div class="content">
        <div id="loveMessage" class="message-box"></div>
        <button onclick="showNewMessage()">新的情话</button>
    </div>

<script>
// 防XSS攻击编码
const escapeHTML = str => str.replace(/[&<>'"]/g, tag => ({
    '&': '&amp;', '<': '&lt;', '>': '&gt;',
    "'": '&#39;', '"': '&quot;'
}[tag]));

const messages = [
    escapeHTML("即使埃菲尔铁塔会生锈，我的爱永不褪色"),
    escapeHTML("Je t'aimerai jusqu'à ce que les roses perdent leurs épines"),
    "广东→布鲁塞尔的距离：<span style='color:var(--gold)'>8763km</span>"
];

function showNewMessage() {
    const container = document.getElementById('loveMessage');
    const randomIndex = Math.floor(Math.random() * messages.length);
    container.innerHTML = messages[randomIndex];
}
// 初始加载
showNewMessage();
</script>
</body>
</html><!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- 预加载关键资源 -->
    <link rel="preload" href="https://cdn.jsdelivr.net/gh/your-repo/rose.jpg" as="image">
    <title>❤ Lauria & 你的名字 ❤</title>
    <style>
        :root {
            --rose-red: #FF0066;
            --gold: #FFD700;
        }
        /* 移动端优先设计 */
        body {
            background: linear-gradient(rgba(255,255,255,0.9), rgba(255,255,255,0.9)), 
                        url('https://cdn.jsdelivr.net/gh/your-repo/rose-pattern.jpg');
            font-family: 'Segoe UI', cursive;
            margin: 0;
            min-height: 100vh;
        }
        .header {
            background: url('https://cdn.jsdelivr.net/gh/your-repo/eiffel-tower.png') center/cover;
            padding: 20px;
            text-align: center;
        }
        /* 防字体加载失败 */
        @font-face {
            font-family: 'RomanticFont';
            src: local('Brush Script MT'), 
                 url('https://fonts.cdnfonts.com/s/12345/romantic.woff') format('woff');
        }
    </style>
</head>
<body>
    <div class="header">
        <h1 style="font-family: RomanticFont, cursive; color: var(--rose-red);">
            Lauria ❤ 你的名字
        </h1>
        <div class="flags">
            <img src="https://flagcdn.com/fr.svg" width="40" alt="法国">
            <img src="https://flagcdn.com/cn.svg" width="40" alt="中国">
        </div>
    </div>

    <div class="content">
        <div id="loveMessage" class="message-box"></div>
        <button onclick="showNewMessage()">新的情话</button>
    </div>

<script>
// 防XSS攻击编码
const escapeHTML = str => str.replace(/[&<>'"]/g, tag => ({
    '&': '&amp;', '<': '&lt;', '>': '&gt;',
    "'": '&#39;', '"': '&quot;'
}[tag]));

const messages = [
    escapeHTML("即使埃菲尔铁塔会生锈，我的爱永不褪色"),
    escapeHTML("Je t'aimerai jusqu'à ce que les roses perdent leurs épines"),
    "广东→布鲁塞尔的距离：<span style='color:var(--gold)'>8763km</span>"
];

function showNewMessage() {
    const container = document.getElementById('loveMessage');
    const randomIndex = Math.floor(Math.random() * messages.length);
    container.innerHTML = messages[randomIndex];
}
// 初始加载
showNewMessage();
</script>
</body>
</html>
