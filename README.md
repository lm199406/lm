<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, minimum-scale=1, user-scalable=no">
  <script src="./node_modules/amfe-flexible/index.js"></script>
  <title>Document</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    .wrap {
      display: flex;
      justify-content: space-around;
    }
    .item {
      width: 2.4rem; /* 直接设计图上的像素大小 / (设计图的宽度 / 10) */
      height: 2.4rem;
      border: 1px solid #000;
    }
    .one {
      background: lightblue;
    }
    .two {
      background: lightcoral;
    }
    .three {
      background: lightgoldenrodyellow;
    }
    .four {
      background: lightgreen;
    }
  </style>
</head>
<body>
  <!-- 
    移动端 UI 设计图：
      尺寸参考iphone6（375px * 667px）：750 * 1334
      一个宽度：180px
    
   -->
  <div class="wrap">
    <div class="item one">one</div>
    <div class="item two">one</div>
    <div class="item three">one</div>
    <div class="item four">one</div>
  </div>
</body>
</html>
