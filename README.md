# Ex04 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
'''
map.html
<!DOCTYPE html>
<html>
<head>
    My City

</head>
<body>

<h1 align="center">
    <font color="blue">Tiruchirappalli</font>

</h1>
<h3 align="center">
    <font color="red">sajeev manoj k (25011586)</font>
</h3>
<img src="Screenshot 2025-12-11 204126.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="" title="" href="lakshimi.html" coords="754,139,956,289" shape="rect" name="lakshmi">
    <area target="" alt="" title="" href="amma.html" coords="1050,418,1246,557" shape="rect" name="amma">
    <area target="" alt="" title="" href="anantham.html" coords="296,300,531,465" shape="rect" name="anantham">
</map>
</body>
</html>

anantham.html
<!DOCTYPE HTML>
<html>
<head>
    <title>anantham</title>
<style>
    body {
        font-family: Arial, sans-serif;
        font-weight: lighter;
        background-color: lightgreen;
    }
    #line {
        width: 100%;
        height: 2px;
        background-color: black;
        margin-top: 10px;
        margin-bottom: 10px;
    }
</style>
</head>
<body>
<h1 align="center">
    <font color="blue">anantham</font>
</h1>
<div id="line"></div>
<h2>
this is a clothing store with a long tradition in handloom product,known for
     its authentic silk and handloom textiles
</h2>
<img src="anantham.png">
</body>

</html>

</html>

anantham.html
<!DOCTYPE HTML>
<html>
<head>
    <title>anantham</title>
<style>
    body {
        font-family: Arial, sans-serif;
        font-weight: lighter;
        background-color: lightgreen;
    }
    #line {
        width: 100%;
        height: 2px;
        background-color: black;
        margin-top: 10px;
        margin-bottom: 10px;
    }
</style>
</head>
<body>
<h1 align="center">
    <font color="blue">anantham</font>
</h1>
<div id="line"></div>
<h2>
this is a clothing store with a long tradition in handloom product,known for
     its authentic silk and handloom textiles
</h2>
<img src="anantham.png">
</body>

</html>

</html>
'''

## OUTPUT
## RAMANTHAPURAM
![alt text](<Screenshot 2025-12-11 204126.png>)

## anantham
![alt text](<Screenshot 2025-12-15 130326.png>)

## lakshimi park
![alt text](<Screenshot 2025-12-15 130851.png>)

## amma park
![alt text](<Screenshot 2025-12-15 131008.png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
