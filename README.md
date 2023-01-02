<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Happy New Year - 2023</title>
        <style>
            *{
                margin: 0;
                padding: 0;
                box-sizing: border-box;
                overflow: hidden;
            }

            .container{
                width: 100%;
                height: 100vh;
                display: flex;
                justify-content: center;
                align-items: center;
                background: linear-gradient(#00003e, #00340e);
            }

            .box{
                width: 600px;
                height: 190px;
                background: linear-gradient(#1e1e1e, #000000);
                border-radius: 40px;
                box-shadow: 5px 5px 30px rgba(255, 255, 255, 0.5);
                font-size: 52px;
                color: #fff;
                display: flex;
                justify-content: center;
                align-items: center;
                font-family: cursive;
                -webkit-text-stroke: 1px #000;
                cursor: pointer;
                transition: 0.5s;
                transform-origin: center;
                transform-style: preserve-3d;
            }

            .box:hover{
                background: #01bee8;
                color: #000;
                -webkit-text-stroke: 1px #ffffff;
                box-shadow: 0px 0px 80px #00fbff;
            }
        </style>
    </head>
    <body>
        <div class="container">
            <div class="box">Happy New Year 2023</div>
        </div>
        <script>
            let box = document.querySelector(".box");
            let num = 1;

            setInterval(() => {
                num += 1;
                // console.log(num);
                let num2 = parseInt(num, null);
                // console.log(num2 + "px");

                box.style.transform = `perspective(400px) rotateY(${num2}deg)`;
            }, 15);
        </script>
        <!-- Thank You For Watching -->
        <!-- Please Like And Subscribe -->
        <!-- And Happy New Year -->
    </body>
</html>
