# Ex.06 Book Front Cover Page Design
## Date:4/12/2024

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
<!DOCTYPE html>
<html>

<head>
    <title>Book cover</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url("web png.jpeg");
            background-size: cover;
        }
            
        
        .insight{
            color:azure;
            font-family: Trebuchet;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            
            position: relative;
            color:white;
            top:170px;
            font-size: medium;
            font-family: 'Times New Roman', Times, serif;
            text-align: left;
        
        }
        .booktitle{
            color:azure;
            font-family: 'Times New Roman';
            font-size: large;
            text-align: left;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            color:azure;
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        
        .subtitle{
            color:azure;
            
            font-size: large;
            position: relative;
            top:60px;
        }
        .sub{
            color:rgb(255, 255, 255);
            font-family:Arial, Helvetica, sans-serif;
            font-size: large;
            position: relative;
            top:380px;
        }
        .mypic{
            position: relative;
            top:180px;
            left:270px;
        
        }
        .lpic{
            position: relative;
            bottom: 100px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                FIRST EDITION
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(0, 0, 0)">
            </div>
            <div class="booktitle">
                <h1 style="font-family: 'Times New Roman', Times, serif; color:rgb(185, 168, 136); text-align: center;">ALPHABET C TO PROGRAMMING C</h1></div>
            
                
            <div class="subtitle" style="text-align: center;color: rgb(189, 229, 126);">
                 
            </div>
            <div class="subtitle" style="color: rgb(193, 172, 133);text-align: center;">
                 REVISED CONTENT
            </div>
            <div class="sub" style="color: rgb(255, 255, 255);text-align: left;">
                BASICS OF C PROGRAMMING
           </div>
           <div class="mypic">
                <img src="GL.jpg" height="120">
            
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>GAJA LAKSHMI M</b></p>
            </div>
        </div>
        </body>
        

</html>
```



## OUTPUT:
![alt text](<Screenshot 2024-12-04 105358.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
