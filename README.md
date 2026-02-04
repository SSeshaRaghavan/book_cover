# Ex.05 Book Front Cover Page Design
# Date:04-02-2026
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
bookcover.html
```
<html>
    <head>
        <title>Book Cover</title>
        <style>
            body{
                margin: 0;
                padding: 0;
                background-color: black;
                align-items: center;
                justify-content: center;
                height: 100vh;
                font-family: Verdana, Geneva, Tahoma, sans-serif;
            }
            
            .Book-cover{
                width: 400px;
                height: 600px;
                background: linear-gradient(120deg, #1e3c72 0%, #2a5298 50%, #4b0082 100%); 
                border: 2px solid #fff;
                padding: 40px 30px;
                display: flex;
                flex-direction: column;
                border-radius: 20px;
                justify-content: space-between;
                margin-left: auto;
                margin-right: auto;
            }

            .title {
                font-size: 25px;
                font-weight: bold;
                color: #ffffff;
                text-align: center;
                line-height: 1.2;
                text-shadow: 2px 2px 8px #000;
            }

            .subtitle {
                font-size: 20px;
                margin-top: 10px;
                text-align: center;
                font-style: italic;
                color: #cccccc;
                text-shadow: 1px 1px 6px #000;
            }

            .image {
                flex: 1;
                margin: 30px 0;
                display: flex;
                justify-content: center;
                align-items: center;
            }

            .image img {
                max-width: 100%;
                max-height: 80%;
                border-radius: 12px;
                box-shadow: 0 5px 15px rgba(0,0,0,0.5);
            }

            .author {
                font-size: 18px;
                text-align: center;
                color: #f0f0f0;
                margin-top: 20px;
                text-shadow: 1px 1px 5px #000;
            }

            .line {
                height: 3px;
                background: #fff;
                width: 60px;
                margin: 10px auto;
                border-radius: 5px;
            }
        </style>
    </head>
    <body>
        <div class="Book-cover">
            <div>
                <div class="title">Man's Search for Meaning</div>
                <div class="line"></div>
                <div class="subtitle">Viktor E Frankl</div>
            </div>
            <div class="image">
                <img src="images.png">
            </div>
            <div>
                <div class="author"></div>
            </div>
        </div>
    </body>
</html>
```
# OUTPUT:
<img width="1919" height="1139" alt="Screenshot 2026-02-04 100950" src="https://github.com/user-attachments/assets/a1c51503-48c0-4ad0-ba97-f65535b1417e" />

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
