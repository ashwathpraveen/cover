# Ex.06 Book Front Cover Page Design
## Date: 31/10/25

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
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style type="text/css">
        .bookcover {
            width: 400px;
            height: 640px;
            color: black (221, 39, 39);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            background-image: url("image.png");
            background-size: cover;
        }

        .pic {
            position: relative;
            top: 420px;
            left: 5px;
            width: 1px;
            height: 1px;
            background-size: cover;
            color: black (221, 39, 39);
        }
    </style>
    <title> Book Front Cover Page </title>
</head>

<body>
    <div class="bookcover">

        <div class="hr1">
            <hr>
        </div>


        <div class="pic">
            <img src="author.jpeg" width="150" height="150">
        </div>
        <div class="hr2">
            <hr>
        </div>



    </div>
</body>

</html>
```

## OUTPUT:

<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/94aa191b-be99-41bb-b5b8-b79f2e14d809" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
