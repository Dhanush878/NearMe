# Ex04 Places Around Me
## Date: 28/11/2024

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
        <title>image map</title>
</head>
   <body><center>
    <img src="map.png.jpg" alt="Sample Image" usemap="#my-map" class="image-map" width="800px" height="680px">
<map name="my-map">
      <area shape="rect" coords="50,50,150,150" href="coffe.html" title="COFFEDAY" alt="Area 1">
     <area shape="circle" coords="300,200,50" href="thousa.html" title="THOUSAND LIGHT" alt="Area 2">
        <area target="" alt="" title="PVR STHATHIYAM CINEMAS" href="pvr.html" coords="466,389,63" shape="circle">
        <area target="" alt="" title="SPENCER PLAZA" href="spen.html" coords="647,55,44" shape="circle">
        <area target="" alt="" title="INDIRA GARDEN" href="indira.html" coords="685,386,71" shape="circle">
  </map></center> 
</body>
</html>

coffe.html

<html>
    <head>COFFEDAY</head>
    <body>
        <p>Good food, would be helpful if the service personnel understood the menu.<br>
            French Toast was ok, Waffles with icecream & Pancake with hazelnut spread was good.<br>
            Tricolour Flamnenkuchen was tasty.Bbq chicken sliders were great.<br>
            Croissants with Writers Hot Chocolate was yummy.Mac&Cheese was not that great.Affogato&Mocha Irish were just ok.</p>
    </body>
</html>

indira.html

<html>
    <head>INDIRA GARDEN</head>
    <body>
        <p>

Indira Garden in Royapettah, Chennai, Tamil Nadu, is a serene residential locality known for its quiet charm.<br>
 Nestled in the bustling city, it offers proximity to prominent landmarks, shopping areas, and eateries.<br>
 The area strikes a balance between urban convenience and a peaceful neighborhood atmosphere, ideal for city living.
        </p>
    </body>
</html>

pvr.html

<html>
    <head>
        PVR STHATHIYAM CINEMAS
    </head>
    <body>
        <p>Amazing Multiplex for Cinema Lovers! Intermission Food and Drinks are extremely expensive!<br>
             But ticket prices and parking charges are nominal.<br>
             Recommended to be your first choice for a complete and immersive theatrical experience!</p>
    </body>
</html>

spen.html

<html>
    <head>SPENCER PLAZA</head>
    <body>
        <p>A popular heritage mall with a history of many years, from British Era.<br>
             An important landmark in city of Chennai. It houses numerous shops owned by several<br>
             people and higher floors are occupied by corporate companies. Best place to buy phones and accessories.</p>
    </body>
</html>

thousa.html

<html>
    <head>THOUSAND LIGHT AREA</head>
    <body>
        <p>Thousand Lights is a vibrant neighborhood in Chennai, Tamil Nadu, known for its rich cultural heritage.<br>
             The area is named after the iconic Thousand Lights Mosque, a historic landmark.<br>
             Bustling with shops, eateries, and cultural hubs, it reflects Chennai's cosmopolitan charm and deep-rooted traditions</p>
    </body>
</html>

```


## OUTPUT
![alt text](<Screenshot 2024-11-28 182808.png>)
![alt text](<Screenshot 2024-11-28 193205.png>)
![alt text](<Screenshot 2024-11-28 193218.png>)
![alt text](<Screenshot 2024-11-28 193231.png>)
![alt text](<Screenshot 2024-11-28 193329.png>)
![alt text](<Screenshot 2024-11-28 193345.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
