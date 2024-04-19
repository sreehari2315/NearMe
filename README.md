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
```ht.html
<html>
<head>
<title> my city</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Tambaram</b></front>
</h1>
<h3 align="center">
<font color="blue"><b>Sunil kumar T (23001650)</b></fornt>
</h3>
<center>
<img src="map.png" usemap="#Mycity" height="610" width="1450">
<map name="Mycity">
<area shape="rect" coords="200,300,300,400" href="tambaram.html" title="My Home Town">
<area shape="rect" coords="200,500,600,600" alt="bus stand" href="bus.html">
<area shape="rect" coords="200,300,900,900" alt="College" href="mcc.html">
<area shape="circle" coords="28,26,303,300" alt="park" href="park.html">
<area shape="rect" coords="300,100,800,800" alt="railway station" href="railway.html">
</map>
</center>
</body>
</html>
```

```mcc.html
<!DOCTYPE html>
<html>
    <head>
        <title>MADRAS CHRISTEIN COLLEGE</title>
    </head>
    <body>
        MADRAS CHRISTEIN COLLEGE:
        <br>
        about MCC:
        <br>Madras Christian College traces its origin to the General Assembly School founded by the Rev. John Anderson, a Missionary from the Church of Scotland, on 3rd April 1837. Anderson was a pioneer in introducing English medium education in South India. He was ably assisted by Rev.
        
    </body>
</html>
```

```tam.html
<!DOCTYPE html>
<html>
    <head>
        <title>Tambaram</title>
    </head>
    <body>
        Tambaram:
        <br>
        about Tambaram:
        <br>Tambaram is an ancient town referred to as Taamapuram in an inscription of the 13th century. There are many other places of historical interest more ancient than Old Tambaram within a radius of about 10 kms from it. Implements of Stone Age men have been found in this area and also large stone monuments of the Iron Age. The earliest Pallava stone inscription and a Pallava temple of the 7th century A.D. are found here. Sekkilar, the author of Periapuranam lived here and Sriperumbudoor the birth place of Ramanuja the Vaishnava saint is not very far from this area. One of the famous battles of Pallava history was fought in this region. The later Cholas, the Pandias and the Vijayanagar kings also ruled this region. Even the flowers in the jungle are connected with our history.
        
    </body>
</html>
```

```park.html
<!DOCTYPE html>
<html>
    <head>
        <title>park</title>
    </head>
    <body>
        park:
        <br>
        about park:
        <br>
        Big Peaceful place for Tambaram Area People. U can see Morning and Evening, a lot of people Walking with Relax Mind. It reduces work stress when we visit here.
It's just Awesome Place.
    </body>
</html>
```


```railway.html
<!DOCTYPE html>
<html>
    <head>
        <title>Tambaram sanatorium</title>
    </head>
    <body>
        Tambaram sanatorium:
        <br>
        about Tambaram sanatorium:
        <br>
        Tambaram Sanatorium railway station is one of the railway stations of the Chennai Beach–Chengelpet section of the Chennai Suburban Railway Network. It serves the neighbourhood of Tambaram Sanatorium and surrounding areas. It is situated about 27 km from Chennai Beach and has an elevation of 32 m (105 ft) above sea level.
    </body>
</html>
```
## OUTPUT
Register number: 212223230212

Name: SREE HARI K


![map](https://github.com/sreehari2315/NearMe/assets/139331590/2a807363-f340-45b4-b9a9-d5eec6f842c4)
![mcc](https://github.com/sreehari2315/NearMe/assets/139331590/c086dd9a-3f77-471c-af55-2a66098ffbac)
![tambaram](https://github.com/sreehari2315/NearMe/assets/139331590/94e813ac-0b97-4eec-90c4-02567aad8587)

![park](https://github.com/sreehari2315/NearMe/assets/139331590/a208cd99-8789-45a6-b47a-f4b64cf1a129)

![railway station](https://github.com/sreehari2315/NearMe/assets/139331590/97fc9c7c-a254-4723-b0e9-8b8d88f40053)


## RESULT
The program for implementing image maps using HTML is executed successfully.
