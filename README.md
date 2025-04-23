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
''
map.html
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="yellow"><b>Redhills</b></font>
</h1>
<h3 align="center">
<font color="red"><b>Priyadharshini R(24900285)</b></font>
</h3>
<center>

<img src="map.png" usemap="#image-map"height="610" width="1450">

<map name="image-map">
    <area target="" alt="Skls mall" title="Skls mall" href="mall.html" coords="960,521,743,442" shape="rect">
    <area target="" alt="grt" title="grt" href="grt.html" coords="870,395,1113,429" shape="rect">
    <area target="" alt="rela hospital" title="rela hospital" href="hospital.html" coords="727,297,117" shape="circle">
    <area target="" alt="sub" title="sub" href="sub.html" coords="915,232,1122,322" shape="rect">
    <area target="" alt="stag" title="stag" href="stag.html" coords="800,300,110,400" shape="rect">
</map>
</center>
</body>
</html>

mall.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="blue"><b>Redhills<b></font>
</h1>
<h3 align="center">
<font color="red"><b>SKLS Galaxy Mall</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="5">
Skls Galaxy Mall is a significant entertainment hub in the Red Hills area, offering a variety of amenities and attractions that cater to both locals and visitors.
Skls mall is a large, enclosed shopping complex that houses a variety of retail stores, restaurants, and entertainment facilities under one roof. It is designed to 
offer a convenient, one-stop destination for shopping, dining, and leisure activities, often featuring amenities like cinemas, play areas, and parking spaces. 
Skls Mall serve as popular social and recreational hubs for communities.</font>
</p>
</body>
</html>

hospital.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="green">
<h1 align="center">
<font color="blue"><b>Redhills<b></font>
</h1>
<h3 align="center">
<font color="red"><b>Rela Hospital</b></font>
</h3>
<hr size="3" color="navy">
<p align="justify">
<font face="Georgia" size="5">
Dr. Rela Institute & M S Hospital in Redhills, Chennai is a multi-specialty hospital that offers a wide range of services.
The hospital is committed to being an internationally significant health care system with the state-of-the art infrastructure
facilities. Rela Hospital is designed to provide highly specialised care in all specialties with special focus on care of the 
critically ill and multi-organ transplantation patients.</font>
</p>
</body>
</html>

grt.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="gold">
<h1 align="center">
<font color="blue"><b>Redhills<b></font>
</h1>
<h3 align="center">
<font color="black"><b>GRT jewellers</b></font>
</h3>
<hr size="3" color="purple">
<p align="justify">
<font face="Georgia" size="5">
GRT Jewellers in Redhills, Chennai, boasts an extensive collection of jewelry, catering to different occasions and styles. 
From traditional gold and diamond jewelry to contemporary designs, they offer a wide range of options to suit every taste and 
budget.GRT Jewellers mainly manufacture and sell bangles, necklaces, earrings, rings, pendants, bracelets, nose pins, chains
 made out of gold, platinum, silver, diamonds, rose gold apart from this they also sell silver articles and corporate gifts.</font>
</p>
</body>
</html>

sub.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="blue"><b>Redhills<b></font>
</h1>
<h3 align="center">
<font color="purple"><b>Sub Register Office</b></font>
</h3>
<hr size="3" color="brown">
<p align="justify">
<font face="Georgia" size="5">
The Sub Registrar Office is a government institution tasked with registering various property-related documents. 
These documents could range from sale deeds, property agreements, wills, and other legal documents related to land 
and property.Established in the year 1992, Sub Registrar Office in Redhills,Chennai listed under Government Organisations 
in Chennai. Rated 3.8 based on  Customer customer reviews. </font>
</p>
</body>
</html>

stag.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="blue"><b>Redhills<b></font>
</h1>
<h3 align="center">
<font color="green"><b>STAG Cricket Ground</b></font>
</h3>
<hr size="3" color="white">
<p align="justify">
<font face="Georgia" size="5">
STAG Cricket Ground is a newly constructed fully turf ground situated in the lavish green landscape of Red Hills - Chennai.
The main objective to have a cricket ground in Chennai is to promote the game of cricket in Chennai by providing a world class 
ground & wicket. STAG Cricket ground can be used to hold cricket tournament ,One - Day games, and for T20 Games. 
STAG Cricket ground is known for its high standards.</font>
</p>
</body>
</html>

## OUTPUT
![image](https://github.com/user-attachments/assets/cfb1e48d-fb0d-48e4-8ddf-6db5f9e62445)
![image](https://github.com/user-attachments/assets/a76a9410-8c19-4991-9411-1567b0326f92)
![image](https://github.com/user-attachments/assets/49e68477-5a0b-4d1d-b086-7046d1e962b5)
![image](https://github.com/user-attachments/assets/15806928-97da-4d67-ae46-a3286aeee13b)
![image](https://github.com/user-attachments/assets/711a6b25-c6c0-43a5-9803-755bf0ed77e6)
![image](https://github.com/user-attachments/assets/a7aa69cb-2acb-4013-b719-6df78db79096)




## RESULT
The program for implementing image maps using HTML is executed successfully.
