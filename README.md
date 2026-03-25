<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Toey - 成绩查询</title>
    <style>
        body { margin: 0; background-color: #f7f8fa; display: flex; justify-content: center; font-family: sans-serif; }
        .page-container { position: relative; width: 100%; max-width: 414px; }
        .bg-img { width: 100%; display: block; }
        
        /* 覆盖在“查看详细”按钮上的点击区域 */
        #jump-btn {
            position: absolute;
            top: 73.5%; 
            left: 63%;  
            width: 28%; 
            height: 4.5%; 
            background-color: rgba(0, 0, 0, 0); 
            cursor: pointer;
            z-index: 10;
        }
    </style>
</head>
<body>

<div class="page-container">
    <img id="main-pic" src="IMG_6882.png" class="bg-img">
    
    <div id="jump-btn" onclick="showScore()"></div>
</div>

<script>
    function showScore() {
        // 点击后，将图片地址更换为第二张图
        const pic = document.getElementById('main-pic');
        const btn = document.getElementById('jump-btn');
        
        pic.src = 'IMG_6882.png'; // 切换到成绩单
        btn.style.display = 'none'; // 隐藏点击区域，防止二次点击
        
        // 自动滚动到顶部，模拟页面跳转感
        window.scrollTo(0, 0);
    }
</script>

</body>
</html>
