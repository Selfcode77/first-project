<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Animation Small Project Made by SelfCode</title>
    <Style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        .container{
            background-color: bisque;
            height: 100vh;
            width: 100vw;
            border: 4px solid black;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .box{
            width: 195px;
            height: 100px;
            background-color: rgba(223, 178, 231, 0.769);
            border: 2px solid red;
            margin: 10px;
            padding: 4px;
            border-radius: 5px;
            box-shadow: 10px 10px 5px 5px rgba(11, 92, 101, 0.532);
            animation-name: inset;
        }
        button{
            font-size: 50px;
            font-family: Arial, sans-serif;
            text-shadow: 3px 4px rgba(9, 55, 101, 0.4);
            border: 3px solid green;
            margin: 10px;
            padding: 5px;
            border-radius: 5px;
            cursor: pointer;
            background-color: lightgreen;
            transition: all 0.2s ease;
        } 
        button:active{
            transform: scale(0.100);
            background-color: rgba(66, 228, 121);
            box-shadow: 5px 5px 5px rgba(0, 0, 0, 0, 0.5);
        }
        button:hover{
            transform: scale(1.1);
            background-color: rgba(163, 227, 242, 0.845);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
        }
    </Style>
</head>
<body>
    <div class="container">
        <div class="box">
           <button>Button</button>

        </div>
    </div>
</body>
</html>
