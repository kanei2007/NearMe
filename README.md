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
'''map.html


<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Anna Nagar</b></font>
</h1>
<h3 align="center">
<font color="blue">< kaneimozhi S 24005925 </b></font>
</h3>
<center>

    <img src="map.png" usemap="#image-map">

    <map name="image-map">
        <area target="" alt="hotel" title="hotel" href="hotel.html" coords="423,265,140,179" shape="rect">
        <area target="" alt="vr" title="vr" href="vr.html" coords="538,750,113" shape="circle">
        <area target="" alt="kora" title="kora" href="kora.html" coords="1135,334,1443,465" shape="rect">
        <area target="" alt="mithai" title="mithai" href="mithai.html" coords="1657,635,84" shape="circle">
        <area target="" alt="grt" title="grt" href="grt.html" coords="846,485,1091,361" shape="rect">
</centre>
</map>
</body>
</html>

grt.html


<!DOCTYPE html>
<html>
    <body style="background-color: rgb(213, 26, 54);">
        <h1 align="center">GRT</h1>
        <h3 align="center">Jewellery Store</h3>
        <hr>
        <h3>GRT Jewellers (GRT Thanga Maligai) is a renowned jewelry brand in India, founded by G. Rajendran in 1964 in Chennai, Tamil Nadu. It started as a small store specializing in gold jewelry and gradually expanded due to its commitment to quality, craftsmanship, and customer trust. Over the years, GRT has grown into one of India's largest jewelry chains, offering a wide range of gold, diamond, platinum, and silver ornaments.      
        </h3>
    </body>
</html>

hotel.html

<!DOCTYPE html>
<html>
    <body style="background-color: rgb(34, 193, 195);">
        <h1 align="center">Thavusukutti</h1>
        <h3 align="center">Biryani Shop, Anna Nagar</h3>
        <hr>
        <h3>Thavusukutti is a popular biryani shop located in Anna Nagar. Known for its flavorful and aromatic biryani, the shop offers a range of delicious dishes, including chicken, mutton, and vegetarian biryanis, all prepared with traditional spices and fresh ingredients. It has become a local favorite for its consistent quality and satisfying meals.</h3>
    </body>
</html>

kora.html

<!DOCTYPE html>
<html>
    <body style="background-color: rgb(255, 140, 0);">
        <h1 align="center">Kora Food Street</h1>
        <h3 align="center">Food Street, Anna Nagar</h3>
        <hr>
        <h3>Kora Food Street is a vibrant food destination located in Anna Nagar. It offers a variety of delicious street food from local favorites to international cuisines. Known for its lively atmosphere and wide selection of tasty treats, Kora Food Street is a popular hangout spot for food lovers seeking both quick bites and flavorful meals.</h3>
    </body>
</html>

mithai.html

<!DOCTYPE html>
<html>
    <body style="background-color: rgb(255, 193, 7);">
        <h1 align="center">Shree Mithai</h1>
        <h3 align="center">Sweets and Snacks Shop</h3>
        <hr>
        <h3>Shree Mithai is a renowned sweets and snacks shop, offering a wide variety of traditional Indian sweets, savory snacks, and fast food. Known for its high-quality ingredients and authentic taste, it has become a favorite spot for those seeking delicious treats like ladoos, barfis, and chaats. With multiple locations, Shree Mithai is a go-to destination for festive celebrations and everyday indulgence.</h3>
    </body>
</html>

vr.html

<!DOCTYPE html>
<html>
    <body style="background-color: rgb(33, 150, 243);">
        <h1 align="center">VR Mall</h1>
        <h3 align="center">Shopping Mall, Anna Nagar</h3>
        <hr>
        <h3>VR Mall is a premier shopping destination in Anna Nagar, offering a wide range of retail stores, dining options, and entertainment facilities. The mall features international and local brands, a multiplex cinema, and a variety of cafes and restaurants, making it a popular spot for shopping, dining, and leisure activities for all ages.</h3>
    </body>
</html>
'''
## OUTPUT
![image](https://github.com/user-attachments/assets/cfb1e48d-fb0d-48e4-8ddf-6db5f9e62445)
![image](https://github.com/user-attachments/assets/a76a9410-8c19-4991-9411-1567b0326f92)
![image](https://github.com/user-attachments/assets/49e68477-5a0b-4d1d-b086-7046d1e962b5)
![image](https://github.com/user-attachments/assets/15806928-97da-4d67-ae46-a3286aeee13b)
![image](https://github.com/user-attachments/assets/711a6b25-c6c0-43a5-9803-755bf0ed77e6)
![image](https://github.com/user-attachments/assets/a7aa69cb-2acb-4013-b719-6df78db79096)




## RESULT
The program for implementing image maps using HTML is executed successfully.
