<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>練習問題　レスポンシブ</title>
    <style>
        .contents{
            display: grid;
            grid-template-columns: 1fr 1fr 1fr 1fr;
            background-color: #f00;
            width: 800px;
            height: 500px;
            text-align: center;
            margin-left: auto;
            margin-right: auto;
        }
        .text{
            background-color: #00f;
            width: 800px;
            height: 100px;
            margin: 0 auto;
        }
        .box{
            background-color: rgb(72, 255, 72);
            width: 100px;
            height: 100px;
            margin: 0 auto;
        }

       @media(max-width:767px){
        .body{
            background-color: #00f;
        }
        .contents{
            grid-template-columns: 1fr 1fr;
        }
       }
    </style>  
</head>
<body>
    <div class="contents">
        <div class="box"></div>
        <div class="box"></div>
        <div class="box"></div>
        <div class="box"></div>
    </div>
    <div class="text">bbbbb</div>
</body>
</html>
