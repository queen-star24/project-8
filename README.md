
<!DOCTYPE html>
<html>
    <head>
        <title>blog-preview-card-main</title>
        <style>
            body{
                width: 1440px;
                background-color: hsl(47, 88%, 63%);
            }
            main{
                background-color: hsl(0, 0%, 100%);
                width: 35%;
                height: 90vh;
                margin-left: 39%;
                margin-top: 40px;
                border-radius: 20px;
                border: 4px solid black;
                border-bottom: 10px solid black;

            }
            .one{
                padding-left: 30px;
                padding-top: 30px;
                font-family: 'Times New Roman', Times, serif;
            
            }
            .one :hover{
                background-color: hsl(0, 0%, 42%);
                cursor: pointer;
            }
            p{
              font-size: 23px;  
              color: grey;
            }
            .three{
                display: flex;
                font-size: 20px;
                align-items: flex-start;
                gap: 10px;
            
            }
            
            h1{
                font-size: 35px;
                font-weight: bold;
            }
            button{
                font-size: 20px;
                width: 90px;
                height: 35px;
                background-color: hsl(47, 88%, 63%);
                border-radius: 2px;
                margin-top: 10px;
            }
            .two{
                width: 410px;
                border-radius: 10px;
            }
        </style>
    </head>
<body>
    <main>
    <div class="one">
        <img class="two" src="assest/illustration-article.svg" alt="">
        <br>
        <button>Learning</button>
        <p>published 21 Dec 2024</p>
        <h1>HTML & CSS foundations</h1>
        <p>These Languages are the backbone of every<br>
             website, defining structure, content, and <br>
              presentation.</p>
        <div class="three">
            <img src="assest/image-avatar.webp" alt="">

             <h4>Greg Hooper </h4>
        </div>
    </div>
    </main>
</body>
</html>

