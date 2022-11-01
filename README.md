# RedRockHomework
红岩网校前端作业
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    .big{
        text-align: center;
        background-color: aqua;
        width: 700px;
	    height: 550px;
        display: flex; 
        position: absolute;
        left: 35%;
        top: 20%;
        margin-left:-100px;
        margin-top:-50px;
    }
    .smallbig{
        flex-wrap: wrap;
        align-items: center;
        justify-content: center;
    }
    .bigone{
        border-radius:15px;
        background-color: rgb(29, 29, 146);
        width: 300px;
	    height: 100px;
        text-align: center;        
        position: absolute;
        left: 43%;
        top: 45%;
        margin-left:-100px;
        margin-top:-50px;

    }

    .bigtwo{
        margin: 20px;
    }
    .bigthird{
        width: 220px;
	    height: 80px;
        background-color: aqua;
        text-align: center;
        display: flex;
        flex: 1;
    }
    .bigforth{
        width: 220px;
	    height: 80px;
        background-color: rgb(11, 11, 117);
        justify-content: flex-start; 
        display: flex;
        flex: 1;
        justify-content: left;
        text-align: center;
    }
    .bigfifth{
        width: 220px;
	    height: 80px;
        background-color: rgb(5, 5, 66);
        justify-content: flex-end;
        display: flex;
        flex: 1;
        justify-content: right;
        text-align: center;
    }

    .flex-item {
      /* 内边距，根据需要去设置 */
      padding: auto;
      /* 弹性布局 */
      display: flex;
      /* 平分父div的宽度 */
      justify-content:space-around;
      background-color: rgb(115, 223, 241);
    }
</style>
<body>
    <div class="big">
    <div class="smallbig">
    <div>我是一个h2，跑中间来啦</div>
    <div class="bigone">我不仅垂直居中，我的框框还是圆角的</div>
    <div class="bigtwo">上面的圆角框框是300px*100px的噢，而且我跟上下都相距20px</div>    
    <div class="flex-item">
    <div class="bigforth">我是220px*80px的左护法</div>    
    <div class="bigthird">整个蓝色的大框是<br/>600px*320px的</div>
    <div class="bigfifth">我是220px*80px的右边护法</div>
    </div>
    </div>
    </div>
</body>
</html>
