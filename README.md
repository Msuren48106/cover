# Ex.06 Book Front Cover Page Design
## Date:18.04.2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<html>
    <head>
        <meta name="viewport"
        content="width=device-width, initial-scale=1.0">
        <style>
            .bookpage{
                width: 400px;
                height: 600px;
                color: rgb(2, 248, 76);
                margin-left: auto;
                margin-right: auto;
                padding: 50px;
                font-family: cursive;
                background-image: url(background1.png.jpg);
                background-size: cover;
            }
            .insight{
                color: rgb(255, 0, 225);

            }
            .hrstyle{
                width: 100px;
            }
            .author{
                display: inline;
                position: relative;
                color: rgb(255, 0, 179);
                top: 300px;
                font-family: Georgia;
                font-size: medium;
            }
            .booktitle{
                font-family: 'Times New Roman', Times, serif;
                font-size: larger;
                text-align: center;
                position: relative;
                top: 30px;

            
            }
            .id{
                width: px;
                position: relative;
                top: 300px;

            }
            .pub{
                font-size: medium;
                position: relative;
                top: 250px;
                left: 330px;
            }
            .ed{
                color: rgb(19, 247, 2);
                font-size: medium;
                font-family: Verdana;
                position: relative;
                top: 200px;

            }
            .subtitle{
                font-family: 'Tahoma';
                font-size: large;
                position: relative;
                top: 75px;
            }
            .mypic{
                position: relative;
                top: 240px;
                left: 260px;
                width: 100px;
                height: 100px;
                background-size: cover;
            }
        </style>
        <title>publication</title>

    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                Google
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(249, 5, 225)">
            </div>
            <div class="booktitle">
                <h1> AI </h1>
            </div>
            <div class="subtitle">
                Ai Revelution
            </div>
            <div class="mypic">
                <img src="mypic.png.png" width="110" height="140" >
            </div>
            <div class="id">
                <hr style="color: rgb(241, 249, 3)">
            </div>
            <div class="author">
                <p><b>M.suren</b></p>
            </div>
            <div class="pub">
                Elon Musk
            </div>
            <div class="ed">
                <b>Ai depth</b>
            </div>
        </div>
   </body>
</html>


```

## OUTPUT:
![alt text](<Screenshot (13).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
