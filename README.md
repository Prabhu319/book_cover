# Ex.06 Book Front Cover Page Design
# Date:28/10/24
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
## html code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>prabhu books</title>
    <link rel="stylesheet" href="kar.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bowlby+One+SC&family=Labrada:ital,wght@0,100..900;1,100..900&family=Lobster&family=Paytone+One&family=Spicy+Rice&display=swap" rel="stylesheet">
</head>
<body>
    <div>
        <img src="karnan.jpg" alt="">
        <div class="F1">
          <h1>KARANA</h1>
          <div class="f2">THE SON OF SUN</div>
        </div>
    </div>
    

</body>
</html>
```
## css:
```
body{
    background-color:antiquewhite;
    backdrop-filter: blur(2px);
}





img{
    width: 32rem;
    display: flex;
    margin-left: 32%;
    border-radius: 1%;
    filter: brightness(-100);
    box-shadow: 0 4px 50px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
.F1{
    font-family: "Spicy Rice", serif;
    font-weight: 400;
    font-style: normal;
    font-size: 60px;
    position: absolute;
    top: 60%;
    left: 49%;
    transform: translate(-49%, -50%);
    color: #f58852;
}
.f2{
    font-size: 40px;
    margin-left: 19%;
    margin-top: -15%;
    font-family: "Lobster", serif;
    font-weight: 400;
    font-style: normal
}
```
# OUTPUT:
![Screenshot 2024-12-07 195523](https://github.com/user-attachments/assets/8f23fc4d-48ea-4272-a56b-c2308d7080d0)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
