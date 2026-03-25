<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Toey - 模拟官网</title>
    <style>
        body { margin: 0; background-color: #f7f8fa; display: flex; justify-content: center; }
        .page-container { position: relative; width: 100%; max-width: 414px; }
        .bg-img { width: 100%; display: block; }
        /* 这里的透明按钮覆盖在“查看详细”位置 */
        .hidden-button {
            position: absolute;
            top: 73.5%; 
            left: 63%;  
            width: 28%; 
            height: 4.5%; 
            background-color: rgba(0, 0, 0, 0); 
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="page-container">
        <img src="IMG_6882.png" class="bg-img">
        
        <a href="IMG_6915.jpeg" class="hidden-button"></a>
    </div>
</body>
</html>
