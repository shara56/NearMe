# Ex04 Places Around Me
## AIM
To develop a website to display details about the places around my house

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
<!DOCTYPE html>
<html>
    <head>
        <title>
            Image Map
        </title>
    </head>
    <body >
        <h1 align="center" >
            <font color="red" >
                     Map Of My Area
            </font>   
        </h1>
        <h3 align="center">
        <font color="blue" face ="cursive">
            SHARANGINI(212222230143)
        </font>  
        </h3>
        <center>
      <img id="Image-Maps-Com-image-maps-2023-05-17-052514" src="https://app.image-maps.com/m/private/0/v3383mejl3vasrf0q6j026fa7g_screenshot-2023-05-16-111811.jpg" border="0" width="1566" height="913" orgWidth="1566" orgHeight="913" usemap="#image-maps-2023-05-17-052514" alt="" />
<map name="image-maps-2023-05-17-052514" id="ImageMapsCom-image-maps-2023-05-17-052514">
<area  alt="" title="school" href="school.html" shape="rect" coords="1038,448.00001525878906,1088,498.00001525878906" style="outline:none;" target="_self"     />
<area  alt="" title="grt_jewellers" href="grt_jewellers.html" shape="rect" coords="791,585.0000152587891,841,635.0000152587891" style="outline:none;" target="_self"     />
<area  alt="" title="bus_stand" href="bus_stand.html" shape="rect" coords="776,693.0000152587891,826,743.0000152587891" style="outline:none;" target="_self"     />
<area  alt="" title="restaurant" href="restaurant.html" shape="rect" coords="754,312.0000305175781,804,362.0000305175781" style="outline:none;" target="_self"     />
<area  alt="" title="college" href="college.html" shape="rect" coords="640,311.0000305175781,690,361.0000305175781" style="outline:none;" target="_self"     />
<area shape="rect" coords="1564,911,1566,913" alt="Image Map" style="outline:none;" title="Image Map" href="https://www.image-maps.com/" />
</map>

bus_stand.html
<!DOCTYPE html>
<html>
<head>
    <title>
        bus stand
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive" size="9">
       bus stand
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="6">
        <OL  TYPE="1" START="1">
            <LI> Bus stand attendants were helpful.<br></LI>     
            <LI>Very close to Railway station.<br></LI>
            <LI>There was nice cleaning too.<br></LI>
            <LI> Bus for all location start form here.<br></LI>
        </OL>
</p>
</body>
</html>

college.html
<!DOCTYPE html>
<html>
<head>
    <title>
        college
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive" size="9">
       college
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="6">
        <OL  TYPE="1" START="1">
            <LI>Good place for career.<br></LI>     
            <LI>My college has all the required facilities like air conditioner, fans, and all which are in proper working condition.<br></LI>
            <LI>My college's infrastructure is in good condition.<br></LI>
            <LI>There is more importance given to attendence and theory study than practical and training.<br></LI>
        </OL>
</p>
</body>
</html>

grt_jewellers.html
<!DOCTYPE html>
<html>
<head>
    <title>
       grt jewellers
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive" size="9">
       grt jewellers
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="6">
        <OL  TYPE="1" START="1">
            <LI>GRT Jewellers is one of the India's foremost jewellery store having an exquisite collection of jewellery in Gold, Diamond, Platinum and Silver created by the finest artisans of India.<br></LI>     
            <LI>G. Rajendran established GRT which stands for G.R. Thanga Maligai in Chennai, Tamil Nadu.<br></LI>
            <LI>Nayanthara, the brand ambassador of GRT Jewellers, promoting the jewellers gold antique jewellery collections.<br></LI>
            <LI>It's a private unlisted company and is classified as'company limited by shares'.<br></LI>
        </OL>
</p>
</body>
</html>

restaurant.html
<!DOCTYPE html>
<html>
<head>
    <title>
       grt jewellers
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive" size="9">
       grt jewellers
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="6">
        <OL  TYPE="1" START="1">
            <LI>GRT Jewellers is one of the India's foremost jewellery store having an exquisite collection of jewellery in Gold, Diamond, Platinum and Silver created by the finest artisans of India.<br></LI>     
            <LI>G. Rajendran established GRT which stands for G.R. Thanga Maligai in Chennai, Tamil Nadu.<br></LI>
            <LI>Nayanthara, the brand ambassador of GRT Jewellers, promoting the jewellers gold antique jewellery collections.<br></LI>
            <LI>It's a private unlisted company and is classified as'company limited by shares'.<br></LI>
        </OL>
</p>
</body>
</html>

school.html
<!DOCTYPE html>
<html>
<head>
    <title>
       SCHOOL
    </title>
</head>
<body >
<h1 align="center">
    <font color="blue" face="cursive" size="9">
       
         Bharathidhasanar Matriculation Higher Secondary School


    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="6">
        <OL  TYPE="1" START="1">
            <LI>School is the basic foundation of knowledge being imparted to a child.<br></LI>     
            <LI>School is the place where we learn to read and write.<br></LI>
            <LI>It is the most crucial place for a student, and it helps us to learn new things.<br></LI>
            <LI>The teachers are always helpful and teach us important things in life.<br></LI>
        </OL>
</p>
</body>
</html>
```

## OUTPUT
![image](https://github.com/shara56/NearMe/assets/113497104/4e2529b9-ac61-46a0-93e8-905a4094c7de)

![image](https://github.com/shara56/NearMe/assets/113497104/8f044b0a-270a-445f-989e-cea23a12623f)

![image](https://github.com/shara56/NearMe/assets/113497104/e120c0d7-0e6b-4832-9058-1040702ca0f6)

![image](https://github.com/shara56/NearMe/assets/113497104/7e5e05d2-ff46-49b5-b933-2169f2bc08a2)

![image](https://github.com/shara56/NearMe/assets/113497104/61971a84-c1e5-455a-bbd6-2cf4633c4765)

![image](https://github.com/shara56/NearMe/assets/113497104/25f4e2a5-b7b2-477e-9729-7898ea4f4896)


## HTML VALIDATOR

![image](https://github.com/shara56/NearMe/assets/113497104/bda2366e-e17f-48cf-91a5-09ecebddb7cf)



## RESULT
The program for implementing image maps using HTML is executed successfully.
