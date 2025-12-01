# Ex04 Places Around Me
# Date:01.12.2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
map.html:
<html>
    <head>
        <title>My City</title>
    </head>
<body>
<h1 align="center">
<font color ="red"><b>Meenambakkam</b></font>   
</h1>
<h3 align="center">
<font color="blue"><b>Logitha L</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="circle" coords="777,70,893,171" href="airport.html" title="Chennai International Airport">
<area shape="circle" coords="636,532,804,552" href="mall.html" title="Aerohub East">
<area shape="circle" coords="375,641,526,672" href="pvr.html" title="PVR Grand Galada">
<area shape="circle" coords="869,444,1008,462" href="metro.html" title="Meenambakkam Metro">
</map>
</center>
</body>
</html>
```

airport.html:
```
<html>
    <head>
        <title>My Favourite Place</title>
    </head>
    <body bgcolor="pink">
    <h1 align="center">
    <font color="purple"><b>Meenambakkam</b></font>
    </h1>
    <h3 align="center">
    <font color="blue"><b>Chennai International Airport</b></font>
    </h3>
    <hr size="3" color="purple">
    <p align="justify">
    <font face="Georgia" size="5">
    Chennai International Airport (MAA) is one of India’s busiest airports and the primary aviation hub of Tamil Nadu, located in Meenambakkam, Chennai. It operates both domestic and international flights through its modern terminals and serves as a major gateway connecting South India to destinations across Asia, the Middle East, Europe, and beyond. Known for its steadily growing passenger traffic, upgraded infrastructure, and new integrated terminal, the airport offers efficient travel facilities, cargo services, and strong connectivity to the city through road and metro networks.

    </p>
    </body>
</html>
```

mall.html:
```
<html>
    <head>
        <title>My Favourite Place</title>
    </head>
    <body bgcolor="pink">
    <h1 align="center">
    <font color="purple"><b>Meenambakkam</b></font>
    </h1>
    <h3 align="center">
    <font color="blue"><b>Aerohub East</b></font>
    </h3>
    <hr size="3" color="purple">
    <p align="justify">
    <font face="Georgia" size="5">
    "Experience the ultimate shopping spree at Aerohub East. Aerohub East embodies excellence in every aspect, making each visit unforgettable with elevated shopping, dining, and entertainment. Explore our world-class offerings today, where luxury and convenience converge seamlessly. With a diverse range of stores, including internationally renowned brands and other favourites, our mall provides an unrivalled selection of products. Our prime location at Meenambakkam near Chennai International Airport ensures easy accessibility by road, metro rail, and suburban rail. Visit us today and explore the best in shopping, dining, and entertainment. Aerohub East, where every visit is a memorable experience!"
    </p>
    </body>
</html>
```
pvr.html:
```
<html>
    <head>
        <title>My Favourite Place</title>
    </head>
    <body bgcolor="pink">
    <h1 align="center">
    <font color="purple"><b>Meenambakkam</b></font>
    </h1>
    <h3 align="center">
    <font color="blue"><b>PVR Grand Galada</b></font>
    </h3>
    <hr size="3" color="purple">
    <p align="justify">
    <font face="Georgia" size="5">
    The largest and most premium film exhibitor in India with 1732 screens across 113 cities (India and Sri Lanka) with 363 properties and an aggregate seating capacity of 3.60 lakh seats. Over the years, we have consistently increased our screen count, both organically and inorganically, through strategic investments and acquisitions, which include ‘Cinemax Cinemas’ in November 2012, ‘DT Cinemas’ in May 2016, and SPI Cinemas’ in August 2018. We recently completed the merger with INOX Leisure Limited, which has added to our storied history of becoming game changers in the film exhibition industry for over 25 years and transforming the out-of-home entertainment in the country
    </p>
    </body>
</html>
```
metro.html:
```
<html>
    <head>
        <title>My Favourite Place</title>
    </head>
    <body bgcolor="pink">
    <h1 align="center">
    <font color="purple"><b>Meenambakkam</b></font>
    </h1>
    <h3 align="center">
    <font color="blue"><b>Meenambakkam Metro</b></font>
    </h3>
    <hr size="3" color="purple">
    <p align="justify">
    <font face="Georgia" size="5">
    The station lies in the Chennai Beach–Tambaram section of the Chennai Suburban Railway Network, the first suburban section of the city. With the completion of track-lying work in March 1931, which began in 1928, the suburban services were started on 11 May 1931 between Beach and Tambaram, and was electrified on 15 November 1931, with the first MG EMU services running on 1.5 kV DC. The section was converted to 25 kV AC traction on 15 January 1967.
    </p>
    </body>
</html>
```
# OUTPUT
![alt text](web/mapapp/static/map.png)

# RESULT
The program for implementing image maps using HTML is executed successfully.
