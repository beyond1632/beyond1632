<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>个人网页</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
        }
        nav a {
            color: #fff;
            padding: 1rem;
            text-decoration: none;
        }
        nav a:hover {
            background: #555;
        }
        .container {
            padding: 2rem;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>欢迎来到我的个人网页</h1>
    </header>
    <nav>
        <a href="#home">主页</a>
        <a href="#about">关于我</a>
        <a href="#works">我的作品</a>
        <a href="#blog">博客</a>
        <a href="#contact">联系我</a>
    </nav>
    <div class="container" id="home">
        <h2>主页</h2>
        <p>这是我的个人主页，在这里你可以了解我以及我的工作。</p>
    </div>
    <div class="container" id="about">
        <h2>关于我</h2>
        <p>这里是关于我的部分。你可以在这里添加个人简介、教育背景、工作经验等信息。</p>
    </div>
    <div class="container" id="works">
        <h2>我的作品</h2>
        <p>这里展示了我的一些作品，你可以添加图片、描述以及链接到详细信息。</p>
    </div>
    <div class="container" id="blog">
        <h2>博客</h2>
        <p>这是我的博客部分，你可以在这里分享你的想法、经验和知识。</p>
    </div>
    <div class="container" id="contact">
        <h2>联系我</h2>
        <p>如果你有任何问题或需要联系我，请填写以下表格：</p>
        <form>
            <label for="name">姓名:</label><br>
            <input type="text" id="name" name="name"><br>
            <label for="email">电子邮件:</label><br>
            <input type="email" id="email" name="email"><br>
            <label for="message">留言:</label><br>
            <textarea id="message" name="message"></textarea><br>
            <input type="submit" value="提交">
        </form>
    </div>
    <footer>
        <p>© 2024 你的名字. 保留所有权利.</p>
    </footer>
</body>
</html>

--->
