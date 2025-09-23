# Ex04 Places Around Me
## Date:20.9.25

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
map.html
<html>
    <head>
        <title>
            the sample
        </title>
        <link rel="stylesheet" href="style.css">
         
    </head>
    <body>
        <h1>Villupuram city</h1>
        <h2>K.Suvetha(25014616)</h2>
        <img src="map.png" usemap="#image-map" height="610">

<map name="image-map">
    <area target="" alt="ES Arts and Science College" title="ES Arts and Science College" href="college.html" coords="223,380,429,465" shape="rect">
    <area target="" alt="GRT Jewellers" title="GRT Jewellers" href="GRT.html" coords="650,224,85" shape="circle">
    <area target="_blank" alt="Dr. MGR Govt College" title="Dr. MGR Govt College" href="govt college.html" coords="560,559,676,600,725,478,556,563,602,610,833,570,711,567,721,459,591,545,609,551,594,561,709,575,605,611,742,725,890,600,725,461,711,446" shape="poly">
    <area target="" alt="Isha" title="Isha" href="Isha.html" coords="62,311,283,338" shape="rect">
    <area target="" alt="koliyanur" title="koliyanur" href="koliyanur.html" coords="1513,385,1633,441" shape="rect">
</map>  
    </body>
</html>

College.html
<html>
    <head>
        <title>
            ES College
        </title>
    </head>
    <body bgcolor="Yellow">
        <h1>Villupuram city(25014616)</h1>
        <h2>Villupuram Main Road</h2>
        <hr size="10">

        <p>ES College is best college in villupuram.It is the Arts And science College</p>
    </body>    
</html>

GRT.html

<html>
    <head>
        <title>
            GRT Jewellers
        </title>
    </head>
    <body bgcolor="Green">
        <h1>villupuram city(25014616)</h1>
        <h2>Main road</h2>
        <hr>

        <p>It is Famous Jewellery in villupuram.The showroom has good customer ratings.

            
        </p>
    </body>

    govt college.html
    <html>
    <head>
        <title>
            MGR govt college
        </title>
    </head>
    <body bgcolor="Blue">
        <h1>Villupuram city(25014616)</h1>
        <h2>main road</h2>
        <hr>

        <p>It is a womens Govt college in villupuram.It is best womens College in villupuram</p>

    </body>
</html>

Isha.html
<html>
    <head>
        <title>
            Isha nursery 
        </title>
    </head>
    <body bgcolor="pink">
        <h1>villupuram city(25014616)</h1>
        <h2>main road</h2>
        <hr>

        <p>It is a famous nursery in villupuram.Because it is wholesales,price trends to be reasonable for bulk or larger orders</p>
    </body>
</html>

koliyanur.html
<html>
    <head>
        <title>
            koliyanur
        </title>
    </head>
    <body bgcolor="purple">
        <h1>villupuram city(25014616)</h1>
        <h2>main road</h2>
        <hr>

        <p>It is famous town in villupuram.valeeshwarar temple is famous temple in koliyanur</p>
    </body>
</html>

```
## OUTPUT
![alt text](<Screenshot (20).png>)
![alt text](<Screenshot (21).png>)
![alt text](<Screenshot (22).png>)
![alt text](<Screenshot (23).png>)
![alt text](<Screenshot (24).png>)
![alt text](<Screenshot (25).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
