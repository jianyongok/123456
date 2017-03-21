<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        *{
            margin: 0;
            padding: 0;
        }
        ul{
            width: 800px;
            height: 300px;
            margin: 100px;
            border: 1px solid #000;
            overflow:hidden;
        }
        ul li {
            list-style: none;
            width: 100px;
            height: 300px;
            background-color: red;
            float: left;
            /*border: 1px solid #000;*/
            /*box-sizing: border-box;*/
            border-image: 0px;
            transition-property: width;
            transition-duration: 0.5s;
        }
        image{
            width: 300px;
            height:300px;
        }
        ul:hover  li{
            width: 100px;
        }
        ul  li:hover{
            width: 300px;
        }
    </style>
</head>
<body>
<ul>
    <li><img src="images/1.jpg" alt=""></li>
    <li><img src="images/2.jpg" alt=""></li>
    <li><img src="images/3.jpg" alt=""></li>
    <li><img src="images/4.jpg" alt=""></li>
    <li><img src="images/5.jpg" alt=""></li>
    <li><img src="images/6.jpg" alt=""></li>
</ul>
</body>
</html>
