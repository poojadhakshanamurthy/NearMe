# Ex03 Places Around Me
## Date: 28.11.2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
<html>
    <head>
        <title>MAP</title>
    </head>
    <body>
        <h1 align="center">
        <font color="red"><b>THIRUVANAMALAI-ARANI CITY</b></font>
        </h1>
        <br>
        <h2 align="center">
        <font color="green"><b>POOJA D (25016436)</b></font>
        </h2>
        <img src="Screenshot 2025-11-27 222630.png" usemap="#image-map">
        <br>
<map name="image-map">
    <area target="" alt="apatsahayeshwarar temple" title="apatsahayeshwarar temple" href="temple.html" coords="368,246,538,336" shape="rect">
    <area target="" alt="paiyur bridge" title="paiyur bridge" href="bridge.html" coords="1352,278,1443,281,1482,330,1423,363,1328,353,1313,305" shape="poly">
    <area target="" alt="ramraj cotton" title="ramraj cotton" href="cotton.html" coords="1142,266,106" shape="circle">
    <area target="" alt="arani new bus stand" title="arani new bus stand" href="bus.html" coords="879,368,1057,456" shape="rect">
    <area target="" alt="kkk hitech rice mill" title="kkk hitech rice mill" href="mill.html" coords="1403,571,1498,563,1547,602,1449,634,1396,612,1404,573" shape="poly">
</map>
    </body>
</html>
 
 <bus.html>
<html>
<head>
    <title>MY TEMPLE</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="blue"><b>ARANI</b></font>
</h1>
<h3 align="center ">
<font color="blue"><b>NEW BUS STAND</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="5">
 Arani has two main bus stations: the Arani Fort Bus Terminus, which is the central hub near the fort, and the Arani New Bus Station in Arani Palayam. While Arani Fort Bus Terminus is a major terminus, the Arani New Bus Station is currently closed, and there are ongoing discussions and plans for a new, integrated bus station to replace the existing facilities, which have been deemed inadequate.  
</p>
</font> 
</body>
</html> 

<mill.html>
<html>
<head>
    <title>MY TEMPLE</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>ARANI</b></font>
</h1>
<h3 align="center">
<font color="red"><b>KKK HITECH RICE MILL</b></font>
</h3>
<hr size="3" color="yellow">
<p align="justify">
<font face="Georgia" size="5">
  KKK Hi-Tech Rice Mill is located in Arani, Tamil Nadu, and specializes in various grain products like Basmati Rice, Rolled Oats, Poha, and Soya Products. The mill aims to provide quality products and maintain positive customer relationships. It is a part of the larger rice industry in Arani, a region known for its many rice mills.
</p>
</font>
</body>
</html>   

<cotton.html>
<html>
<head>
    <title>MY TEMPLE</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="green"><b>ARANI</b></font>
</h1>
<h3 align="center">
<font color="green"><b>RAMRAJ COTTON</b></font>
</h3>
<hr size="3" color="blue">
<p align="justify">
<font face="Georgia" size="5">
Ramraj Cotton is a retailer with a presence in Arani, located on Pudhukamoor Road, that specializes in traditional Indian readymade garments, particularly dhotis and sarees. The store is known for its high-quality cotton products that are breathable and comfortable, reflecting Indian culture and heritage. It has a high customer rating and is a popular destination for both local and visiting customers seeking traditional attire for various occasions. 
</p>
</font>
</body>
</html>

<temple.html>
<html>
<head>
    <title>MY TEMPLE</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="blue"><b>ARANI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>APATSAHAYESHWARAR TEMPLE</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5"> 
 Apatsahayesvarar Temple, Alangudi or Guru Sthalam or Tiru Irum Poolai is a Hindu temple dedicated to Shiva located in the valagaiman Town near Alangudi sub in the Valangaiman taluk of Tiruvarur district, Tamil Nadu, India. Shiva is worshipped as Apathsahyesvarar, and is represented by the lingam. His consort Parvati is depicted as Elavarkuzhali. The presiding deity is revered in the 7th-century Tamil Saiva canonical work, the Tevaram, written by Tamil saint poets known as the Nayanmars and classified as Paadal Petra Sthalam.
</font>
</p>
</body>
</html>

<bridge.html>
<html>
<head>
    <title>MY TEMPLE</title>
</head>
<body bgcolor="blue">
<h1 align="center">
<font color="black"><b>ARANI</b></font>
</h1>
<h3 align="center">
<font color="black"><b>PAIYUR BRIDGE</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
  The query "paiyur bridge arani" likely refers to the new bridge being constructed across the Arani River in the Tiruvallur district, which is nearing completion and will ease travel for locals. While the specific name "Paiyur bridge" is not widely used, it could be a local or informal name for this bridge, which is in a region near Arani. Additionally, there are many weighbridges, including some near Paiyur, in the Arani area. 
</font>
</body>
</html>   


```


## OUTPUT
![alt text](<pooja/mapapp/static/png 0.png>)
![alt text](<pooja/mapapp/static/png1.png>)
![alt text](<pooja/mapapp/static/png 2.png>)
![alt text](<pooja/mapapp/static/png 3.png>)
![alt text](<pooja/mapapp/static/png 4.png>)
![alt text](<pooja/mapapp/static/png 5.png>)




## RESULT
The program for implementing image maps using HTML is executed successfully.
