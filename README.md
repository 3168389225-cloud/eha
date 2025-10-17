
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>二哈的小窝</title>
    <style>  
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box; /* 统一盒模型，避免padding撑大元素 */
        }
        body {
            background-color: #fff5f6; /* 页面背景色，柔和不刺眼 */
            font-family: "Microsoft YaHei", sans-serif; /* 适配中文的字体 */
            color: #333; /* 正文默认颜色，提升可读性 */
        }
        /* 顶部头像栏样式 */
        .header {
            background-color: #f5ccce;
            text-align: center;
            padding: 30px 0; /* 上下内边距30px，左右0，避免文字偏移 */
            box-shadow: 0 2px 8px rgba(245, 204, 206, 0.3); /* 轻微阴影，增加层次感 */
        }
        .header img {
            width: 120px;
            height: 120px;
            border-radius: 50%; /* 头像圆形化，更可爱 */
            border: 4px solid #fff; /* 白色边框，突出头像 */
            transition: transform 0.3s ease; /* 头像hover动画过渡 */
        }
        .header img:hover {
            transform: scale(1.05); /* 鼠标移到头像上，轻微放大 */
        }
        /* 中间内容区样式 */
        .content {
            max-width: 500px;
            margin: 30px auto; /* 上下30px间距，左右自动居中 */
            padding: 25px;
            line-height: 1.8;
            background-color: #fdc8cd;
            border-radius: 12px; /* 圆角边框，柔和不尖锐 */
            box-shadow: 0 3px 10px rgba(253, 200, 205, 0.2);
        }
        .content h1 {
            text-align: center; /* 修正原代码center标签不规范问题 */
            color: #d85a66; /* 标题颜色，呼应主题色 */
            margin-bottom: 20px;
            font-size: 28px;
        }
        .content p {
            margin-bottom: 12px; /* 段落间距，提升阅读体验 */
            font-size: 16px;
        }
        .content strong {
            color: #d85a66; /* 强调QQ号，颜色突出 */
            font-size: 17px;
        }
        /* 底部链接区样式 */
        .footer {
            background-color: #fee3d6;
            text-align: center;
            padding: 30px 0; /* 修正原代码缺失px和padding、font-size顺序问题 */
            font-size: 20px;
            margin-top: 20px;
            border-top-left-radius: 15px; /* 顶部左右圆角，与页面衔接更自然 */
            border-top-right-radius: 15px;
        }
        .footer a {
            color: #d85a66;
            text-decoration: none; /* 去除链接下划线 */
            padding: 8px 16px;
            border-radius: 8px;
            transition: all 0.3s ease; /* 链接hover动画过渡 */
        }
        .footer a:hover {
            background-color: #d85a66; /* 鼠标移到链接上，背景变色 */
            color: #fff; /* 文字变白，对比更明显 */
        }
    </style>
</head>
<body>
    <!-- 顶部头像区域 -->
    <div class="header">
        <img src="https://imgtu.com/uploads/3bqgbmwd/t-image_1758380842638.webp" alt="二哈">
    </div>
    <!-- 中间核心内容区域 -->
    <div class="content">
        <h1>二哈的小屋</h1>
        <p>闲的无聊做的网站，记录一些小日常～</p>
        <p>大家可以提提建议，反正无聊也能慢慢改</p>
        <p>目前还没想好要加什么功能，先放些基础内容～</p>
        <p>虽然一开始不是很想搞，但做着做着也觉得有意思啦</p>
        <p>这是我的QQ，无聊可以找我聊天：</p>
        <strong>3345478992</strong>
        <p>也别忘了关注“二哈喵”，后续可能会更新小内容～</p>
    </div>
    <!-- 底部B站链接区域 -->
    <div class="footer">
        <a href="https://space.bilibili.com/491054886" target="_blank">我的B站空间</a> <!-- 加target="_blank"，新窗口打开链接 -->
    </div>
</body>
</html>
