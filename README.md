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
```
imagemap2.html

<!DOCTYPE html>
<html>
<head>
    <title>Chennai</title>
</head>
<body>
    <h1 align="center">
    <font color="black"><b>Sai Deshiya.K (24005381)</b></font>
    </h1>
    <img src="c:\Users\admin\OneDrive\Pictures\Screenshots\Screenshot 2024-12-16 191059.png" alt="Workplace" usemap="#workmap" height="650" width="1470">
    <map name="workmap">
        <area shape="circle" coords="200,300,30" alt="Avadi" href="file:///C:/Users/admin/area.html">
        <area shape="circle" coords="950,250,30" alt="N4" href="file:///C:/Users/admin/n4.html">
        <area shape="circle" coords="600,350,30" alt="Anna nagar" href="file:///C:/Users/admin/anna%20nagar.html">
        <area shape="circle" coords="700,450,30" alt="t nagar" href="file:///C:/Users/admin/tnagar.html">
        <area shape="circle" coords="170,500,30" alt="ponnamalle" href="file:///C:/Users/admin/poonamali.html">
    </map>
</body>
</html>
```
```
poonamali.html

<html>
    <head>
        <title>Ponnamalle</title>
    </head>
    <body style="background-color: rgb(141, 186, 199);">
        <center>
            <h1 style="color: rgb(225, 0, 255);letter-spacing: 2px;">Chennai</h1>
            <h3 style="color: white; letter-spacing: 2px;">Ponnamalle</h3>
            <hr>
            <p style="font-size: 20px;">Poonamallee is a town and suburb of Chennai, India under the Chennai Metropolitan Area. It was historically called Pushpagirimangalam, later renamed in Tamil as Poovirundhavalli and now colloquially called as Poondhamalli. It is the headquarters of the Poonamallee taluk of the Tiruvallur district in the Indian state of Tamil Nadu.</p>
        </center>
    </body>
</html>
```
```
tnagar.html
<html>
    <head>
        <title>T nagar</title>
    </head>
    <body style="background-color: rgb(130, 185, 130);">
        <center>
            <h1 style="color: rgb(0, 255, 234);letter-spacing: 2px;">Chennai</h1>
            <h3 style="color: white; letter-spacing: 2px;">T nagar</h3>
            <hr>
            <p style="font-size: 20px;"> Thyagaraya Nagar, commonly known as T. Nagar, and historically known as East Mambalam is a very affluent commercial and residential neighbourhood in Chennai, Tamil Nadu, India. It is surrounded by Nungambakkam in the North, Teynampet in the East, Nandanam in the South-East, C.I.T. Nagar (a part of Greater Nandanam region) in the South and West Mambalam and Kodambakkam in the West.</p>
    </body>
</html>
```
```
n4.html
<html>
    <head>
        <title>N4</title>
    </head>
    <body style="background-color: rgb(201, 133, 226);">
        <center>
            <h1 style="color: rgb(86, 78, 141);letter-spacing: 2px;">Chennai</h1>
            <h3 style="color: white; letter-spacing: 2px;">N4</h3>
            <hr>
            <p style="font-size: 20px;">N4 Beach in Chennai, India. Chennai is known for its beautiful Marina Beach, which is the longest urban beach in India and a popular spot for locals and tourists alike. There are also other beaches in Chennai such as Elliot's Beach (Besant Nagar Beach) and Covelong Beach (Kovalam Beach). </p>
        </center>
    </body>
</html>
```
```
area.html
<html>
    <head>
        <title>Avadi</title>
    </head>
    <body style="background-color: palevioletred;">
        <center>
            <h1 style="color: rgb(255, 0, 128);letter-spacing: 2px;">Chennai</h1>
            <h3 style="color: white; letter-spacing: 2px;">Avadi</h3>
            <hr>
            <p style="font-size: 20px;">Avadi is a western suburb of Chennai, and the headquarters of Avadi taluk located within the Thiruvallur district of Tamil Nadu, India. Situated at about 22 kilometres (14 mi) from Chennai Central Railway Station, it is one of the four municipal corporations in the Chennai Metropolitan Area and is governed by the Avadi Municipal Corporation.</p>
        </center>
    </body>
</html>
```
```
anna nagar.html
<html>
    <head>
        <title>GERUNGAPAKAM</title>
    </head>
    <body style="background-color: rgb(223, 222, 153);">
        <center>
            <h1 style="color: rgb(90, 110, 108);letter-spacing: 2px;">Chennai</h1>
            <h3 style="color: rgb(150, 125, 125); letter-spacing: 2px;">GERUNGAPAKAM</h3>
            <hr>
            <p style="font-size: 20px;"> Gerungapakam is a small village located in Tamil Nadu, India. It is known for its rural charm, agricultural lifestyle, and a close-knit community. Surrounded by lush greenery, the village represents traditional Tamil culture and heritage. Its residents primarily engage in farming and local trades, contributing to the region's economy and simplicity of life.</p>
        </center>
    </body>
</html>

```


## OUTPUT

![Screenshot 2024-12-16 191059](https://github.com/user-attachments/assets/f02638b1-2a12-4408-a95a-87d653df3c0d)

![Screenshot (103)](https://github.com/user-attachments/assets/b5cc01f2-b031-405b-a01b-53129fc29001)

![Screenshot (104)](https://github.com/user-attachments/assets/2b91275e-5c15-45d2-b625-3b650fced8ce)

![Screenshot (105)](https://github.com/user-attachments/assets/982a10ed-febc-4ac1-a8f8-aa10875fc4dc)

![Screenshot (107)](https://github.com/user-attachments/assets/9d3d1bef-f4f7-49f4-96cc-fb3f75256264)

![Screenshot (108)](https://github.com/user-attachments/assets/ec2249f2-2a3a-4985-bd3c-4b7329848aaa)



## RESULT
The program for implementing image maps using HTML is executed successfully.
