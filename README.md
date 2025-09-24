<img width="1920" height="1080" alt="4" src="https://github.com/user-attachments/assets/2f797f69-0166-4e7a-9fbb-bceb5ae34d9b" /># Ex04 Places Around Me
## Date: 20.09.2025

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
    <title>TIRUNELVELI CITY</title>
    </head>
    <body>
        <h1 align="center">
        <font color="red"><b>Tirunelveli city</b></font>
        </h1>
        <h3 align="center">
        <font color=""blue><b>MurugaPerumal P (25016797)</b></font>
        </h3>
        <center>
        <img src="C:\Users\acer\NearMe\muruga\mapapp\static\Screenshot 2025-09-20 142112.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="melapalayamVillage" title="melapalayamVillage" href="melapalayam.html" coords="718,573,42" shape="circle">
    <area target="" alt="manimutharFalls" title="manimutharFalls" href="manimuthar.html" coords="655,42,761,87" shape="rect">
    <area target="" alt="palayankottai" title="palayankottai" href="palayankottai.html" coords="1180,280,1206,276,1228,285,1248,306,1245,318,1240,344,1228,354,1184,371,1163,358,1132,335,1141,310,1133,275,1144,267,1168,248" shape="poly">
    <area target="" alt="suttamalliVillage" title="suttamalliVillage" href="suttamalli.html" coords="123,414,248,487" shape="rect">
    <area target="" alt="pettai" title="pettai" href="pettai.html" coords="448,376,64" shape="circle">
</map>
        </center>
           
    </body>
</html>


manimuthar.html
<html>
<head>
<title>manimuthar</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
    <font color="red"><b>My Home Town</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>manimuthar</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
It is the biggest reservoir of the Tirunelveli district.
This dam was built in 1958 near Singampatti and Kallidaikurichi,
by the then Tamil Nadu Chief Minister K. Kamaraj, and K T Kosalram MP
to prevent mixing of rainwater with the Bay of Bengal during the rainy season.</font>
</p>
</body>
</html>

palayankottai.html
<html>
<head>
<title>palayankottai</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
    <font color="red"><b>My Home Town</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>palayankottai</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Palayamkottai is a residential and educational centre
in the Tirunelveli urban agglomeration. A major hub
for Christian missions in southern India, it has private 
Christian schools and colleges, and it has other colleges
affiliated with Manonmaniam Sundaranar University in Tirunelveli.</font>
</p>
</body>
</html>

suttamalli.html
<html>
<head>
<title>suttamalli</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
    <font color="red"><b>My Home Town</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>suttamalli</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Suthamalli, a remarkable village, unfolds its wonders with hills,
a stunning river, lush fields, vibrant gardens, the melody of
chirping birds, serene temples, and a captivating dam. 
This hidden gem in Tirunelveli holds the charm of an undiscovered paradise.
</font>
</p>
</body>
</html>

petai.html
<html>
<head>
<title>pettai</title>
</head>
<body bgcolor="white">
<h1 align="center">
    <font color="red"><b>My Home Town</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>pettai</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Industrial suburban area in Tirunelveli
Pettai is an industrial suburban area in Tirunelveli.
 It is approximately 6 kilometers of downtown Tirunelveli
along the Southern Railway line to Tenkasi. It is being 
by the Tirunelveli City Municipal Corporation
</font>
</p>
</body>
</html>

melapalayam.html
<html>
<head>
<title>melapalayam</title>
</head>
<body bgcolor="pink">
<h1 align="center">
    <font color="red"><b>My Home Town</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>melapalayam</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Melapalayam was known as Keela Veera Ragavapuram during British Rule. 
The old Tamil name for the region is Mangai Maa Nagar.
Melapalayam is a Muslim majority town.Back in 14th century,
7 families(40 members) of Arab traders or 40 families of Arab traders
were came to the Kollam (kerala) port. They were decided to go Kayalpattinan
(another Muslim village). On their way, they found the mesmerizing Thamirabarani
river and paddy fields. They decided to stay there and preach Islam. Marrying 
local people of the place and converting lots of natives. That is how the 
Melapalayam become Muslim majority in modern days. The Arab family names are 
thakkadi, tharvesh , kattai, Mohamed sabbani, lebbai, maayatti etc.
</font>
</p>
</body>
</html>



```

## OUTPUT

<img width="1920" height="1080" alt="1" src="https://github.com/user-attachments/assets/f50ba86d-4fbd-4c6c-bbd3-97dbf7ed40e7" />
<img width="1920" height="1080" alt="2" src="https://github.com/user-attachments/assets/aeb6743c-a051-4dc8-a809-ebd2e332b4a6" />
<img width="1920" height="1080" alt="3" src="https://github.com/user-attachments/assets/68388573-81a2-4e68-b482-98c92fb33a46" />
<img width="1920" height="1080" alt="4" src="https://github.com/user-attachments/assets/33aaab8f-1ad8-4031-9a3d-acfe39752978" />
<img width="1920" height="1080" alt="5" src="https://github.com/user-attachments/assets/0552b034-f634-41b0-be48-7b7dd97c7068" />






## RESULT
The program for implementing image maps using HTML is executed successfully.
