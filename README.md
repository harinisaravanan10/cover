# Ex.06 Book Front Cover Page Design
## Date:08.05.2024

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
book.html
<html>
<head>
    <title>Book Cover</title>
    <style>
        
        body{
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: rgb(186, 231, 236); 
        }
        

        .bookpage{
            width: 400px;
            height: 600px;
            color: black;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url('BG.avif');
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
        }

        .linestart{
            width: 160px;
        }

        .bname{
            font-family: 'Times New Roman', Times, serif;
            font-size: larger;
            text-align: center;
        }

        .bsub{
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-size: medium;
            position: relative;
            top: 35px;
        }

        .edition{
            color: darkgreen;
            font-size: medium;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            position: relative;
            top: 85px;
        }

        .foto{
            position: relative;
            top: 140px;
            left: 256px;
            width: 100px;
            height: 100px;
        }
       
        .lineend{
            width: 400px;
            position: relative;
            top: 180px;
        }

        .myname{
            display: inline;
            position: relative;
            color: rgb(107, 168, 237);
            top: 190px;
            font-family: Arial, Helvetica, sans-serif;
            font-size: medium;
        }

        .clg{
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;
            color: antiquewhite;
        }
    </style>
</head>

<body>
    <div class="bookpage">
        <h4 style="color: paleturquoise;"> A Complete Overview On </h4>

        <div class="linestart">
            <hr>
        </div>

        <div class="bname">
            <h1 style="color: royalblue;">Full Stack Development</h1>
        </div>

        <div class="bsub">
            <p style="color:purple;">Learn to operate at a professional level with MySQL</p>   
        </div>

        <div class="foto">
            <img src="harini.jpg" width="120" height="150">
        </div>

        <div class="lineend">
            <hr>
        </div>

        <div class="myname">
            <p>HARINI S </p>
        </div>

        <div class="clg">
            SEC
        </div>

        <div class="edition">
             Second Edition
        </div>

    </div>
</body>
</html>
```

## OUTPUT:

![Screenshot 2024-05-08 004701](https://github.com/harinisaravanan10/cover/assets/149035598/e6d76d82-d69f-4485-bebf-ef05df8e6ab5)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
