# Ex04 Places Around Me
## Date: 23/04/25

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
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Places in Kumbakonam</title>
    <style>
        body {
            background-color: #0fee4e;
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }

        h1, h2 {
            color: white;
            text-align: center;
        }

        .map-container {
            width: 100%;
            max-width: 1200px;
            margin: auto;
        }

        .map-container img {
            width: 100%;
            height: auto;
            display: block;
        }

        area {
            cursor: pointer;
        }
    </style>
</head>
<body>

    <h1>Kumbakonam</h1>
    <h2>Created By Kaneimozhi S (212224040147)</h2>

    <div class="map-container">
        <img src="map.png" alt="Kumbakonam map" usemap="#Kumbakonam-map" id="map">
        <map name="Kumbakonam-map">
            <area shape="rect" coords="1012,517,1047,547" href="temple.html" title="Temple">
            <area shape="rect" coords="968,478,1003,507" href="nageshwarar.html" title="Temple">
            <area shape="rect" coords="303,497,343,533" href="swamimalai.html" title="Temple">
            <area shape="rect" coords="894,468,955,510" href="sarangapani.html" title="Temple">
            <area shape="rect" coords="1108,545,1138,568" href="railway.html" title="Railway Station">
        </map>
    </div>

    <!-- ✅ Add JS for responsive map areas -->
    <script src="https://cdn.jsdelivr.net/npm/image-map-resizer@1.0.10/js/imageMapResizer.min.js"></script>
    <script>
        window.onload = function () {
            imageMapResize();
        };
    </script>

</body>
nageshwarar.html
<html>
    <head>
        <title>nageshwarar temple Kumbakonam</title>
    </head>
    <body bgcolor="LightSteelBlue">
        <h1 align="center">nageshwarar temple Kumbakonam</h1>
        <h2 align="center">Kumbakonam</h2>
        <hr size="3" color="CornflowerBlue">
        <br><br>
        <p><h3>Aditya Chola constructed this temple during the 9th century.
        It is great marvel of Chola architecture, building technology and astronomy.
         The orientation is structured in such a way that it allows sunlight inside
         the temple, right on the sanctum only during the Tamil month of Chithirai.
         The temple is one of the prominent Shiva temples in Kumbakonam.The temple
          shows early Chola art in its best form particularly in the form 
          of human figures..</h3>
        </p>
    </body>
</html>
railway.html
<html>
    <head>
        <title>railway station,Kumbakonam</title>
    </head>
    <body bgcolor="LightSteelBlue">
        <h1 align="center">railway station,kumbakonam</h1>
        <h2 align="center">railway station</h2>
        <hr size="3" color="CornflowerBlue">
        <br><br>
        <p><h3>Railway station,kumbakonam identified by the code KMU, is a significant
             rail hub in the Trichirapalli division of the Southern Railway in India.
             It serves the city of Kumbakonam, connecting it to various parts of
             Tamil Nadu and the rest of the country. The station is known for its
             cleanliness, having been recognized as the cleanest in Tamil Nadu and
             ranked among the top nationally.</h3>
        </p>
    </body>
</html>
sarangapani.html
<html>
    <head>
        <title>sarangapani temple</title>
    </head>
    <body bgcolor="LightSteelBlue">
        <h1 align="center">sarangapani temple</h1>
        <h2 align="center">valayapettai agraharam</h2>
        <hr size="3" color="CornflowerBlue">
        <br><br>
        <p><h3>Sarangapani Temple Chariot is 118 feet high in Tamil Nadu.
             This chariot is held annually in the month of Chitra. Sarangapani Temple,
              located in Kumbakonam, is the third of the 108 Vaishnava temples.
            </h3>
        </p>
    </body>
</html>
swamimalai.html
<html>
    <head>
        <title>swaminatha swamy temple</title>
    </head>
    <body bgcolor="LightSteelBlue">
        <h1 align="center">swaminatha swamy temple</h1>
        <h2 align="center">swamimalai kumabakonam</h2>
        <hr size="3" color="CornflowerBlue">
        <br><br>
        <p><h3>Murugan, the son of Shiva, extolled the meaning of the Pranava Mantra
             (AUM) to his father at this place and hence attained the name 
             Swaminathaswamy.he Sangam period from 2nd century BC and was believed 
             to have been modified and rebuilt by Parantaka Chola I. The temple was
              greatly damaged during the Anglo-French war between Hyder Ali and
             British in 1740..</h3>
        </p>
    </body>
</html>
temple.html
<html>
    <head>
         </title> Mahamaham tank </title>
    </head>
    <body bgcolor="LightSteelBlue">
        <h1 align="center">Mahamaham tank</h1>
        <h2 align="center">Mahamaham kulam,Kumbakonam</h2>
        <hr size="3" color="CornflowerBlue">
        <br><br>
        <p>
        <h3>Mahamaham, also known as Mahamagham or Mamangam, is a Hindu festival
             celebrated every 12 years in the  Mahamaham tank located in the city of 
             Kumbakonam in Tamil Nadu in the south of India. This 20-acre square tank 
             surrounded by Shiva mandapams is believed by Tamil Hindus to be ancient, 
             and the holy confluence of nine Indian river goddesses: Ganga, Yamuna, 
             Sarasvati, Narmada, Godavari, Krishna, Tungabhadra, Kaveri, and Sarayu.
         </h3>
        </p>
    </body>
</html>
'''
## OUTPUT
![alt text](<Screenshot 2025-05-29 091516.png>)
![alt text](<Screenshot 2025-05-29 091620.png>)
![alt text](<Screenshot 2025-05-29 091644.png>)
![alt text](<Screenshot 2025-05-29 091740.png>)
![alt text](<Screenshot 2025-05-29 091800.png>)
![alt text](<Screenshot 2025-05-29 091831.png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
