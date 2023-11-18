# Ex04 Places Around Me
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
image map

<html>
<title>image map</title>
<center>
<h3>CHENNAI</h3>

<img src="img.png" width="1500" height="650" usemap="#imgmap">
<map name="imgmap">
<area  shape="rectangle"  coords="400,650,550,550"  href ="hiddenlake.html"  title="HIDDEN LAKE" >
<area  shape="CIRCLE"  coords="65,350,60,"  href ="airport.html"  title="AIRPORT" >
<area  shape="rectangle"  coords="300,300,450,200"  href ="station.html"  title="RAILWAYS" >
<area  shape="rectangle"  coords="1130,150,1300,200"  href ="mall.html"  title="PHOENIX MALL" >
<area  shape="CIRCLE"  coords="850,250,60,"  href ="temple.html"  title="TEMPLE" >
</map>
<body>
</body>
</html>

hiddenlake.html

<html>
<title>hiddenlake</title>
<center>
<h1>CHENNAI</h1>
<hr>
<body style="background-color:cornflowerblue">
<h2 style="text-align:center;color:rgb(246, 246, 250)">HIDDEN LAKE </h2>
<p style="font-style: italic;font-size: 20;">Hidden lake has always been a place inspired by and made to inspire FUN.</p>
<p style="font-style: italic;font-size: 20;">It is the common water resource for the nearby places. </p>
<p style="font-style: italic;font-size: 20;">A place to Relax with the nature and A small escape from the harsh noisy world. </p>
<p style="font-style: italic;font-size: 20;">This is a suitable place for a small trip or trecking. </p>
</body>
</html>

temple.html

<html>
<title>temple</title>
<center>
<h1 style=>CHENNAI</h1>
<hr>
<body style="background-color:crimson">
    <h2 style="text-align:center;color:rgb(246, 246, 250)">TEMPLE</h2>
    <p style="font-style: italic;font-size: 20;">One of the most famous temples in Nanganallur</p>
    <p style="font-style: italic;font-size: 20;">It brings peace of mind to anyone who visits the place </p>
    <p style="font-style: italic;font-size: 20;">I have only visted the temple a few times but i will remember the aura of the temple for a lifetime.</p>
</body>
</html>

airport.html

<html>
<title>hiddenlake</title>
<center>
<h1>CHENNAI</h1>
<hr>
<body style="background-color:aquamarine">
    <h2 style="text-align:center;color:rgb(246, 246, 250)">AIRPORT </h2>
    <p style="font-style: italic;font-size: 20;">A place in chennai filled with colours of emotion.</p>
    <p style="font-style: italic;font-size: 20;">It acts as a connection betweeen states of INDIA and also between countries and continents.</p>
    <p style="font-style: italic;font-size: 20;">One of the most famous place in chennai. </p>
    <p style="font-style: italic;font-size: 20;">acts as a movie spot and a welcome place for many celebrities creating positive impression on Chennai as well as India </p>
</body>
</html>

station.html

<html>
<title>hiddenlake</title>
<center>
<h1>CHENNAI</h1>
<hr>
<body style="background-color:cadetblue">
    <h2 style="text-align:center;color:rgb(246, 246, 250)">STATION</h2>
    <p style="font-style: italic;font-size: 20;">Always filled by people and their thoughts with intertwined emotions.</p>
    <p style="font-style: italic;font-size: 20;">For a person who cant travel in bus trains has always been an favourite option. </p>
    <p style="font-style: italic;font-size: 20;">Railway travel has been cost effective than bus and it is also a faster way of travel between two places. </p>

</body>
</html>

mall.html

<html>
<title>hiddenlake</title>
<center>
<h1>CHENNAI</h1>
<hr>
<body style="background-color:darkcyan">
    <h2 style="text-align:center;color:rgb(246, 246, 250)">PHOENIX MALL </h2>
    <p style="font-style: italic;font-size: 20;">One of the most famous malls in chennai.</p>
    <p style="font-style: italic;font-size: 20;">It s a bustling shopping destination ,offering a diverse range of retail stores,dinning options,and entertainment facilities  </p>
    <p style="font-style: italic;font-size: 20;">The malls vibrant atmosphere and diverse offering make it a key player in Chennai's retail and entertainment scene. </p>
</body>
</html>
```

## OUTPUT
![Alt text](<Screenshot 2023-11-15 094702.png>)
![Alt text](<Screenshot 2023-11-15 095056.png>)  
![Alt text](<Screenshot 2023-11-15 094715.png>) 
![Alt text](<Screenshot 2023-11-15 094940.png>)
 ![Alt text](<Screenshot 2023-11-15 094959.png>) 
 ![Alt text](<Screenshot 2023-11-15 095015.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
