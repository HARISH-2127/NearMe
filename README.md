# Ex04 Places Around Me
## Date: 04-12-2024

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
map.html
```
<html>
    <head>
        <title>
            My City
        </title>
    </head>
    <body>
        <h1 align="center">
            <font color="magenda"><b>ANDHRA</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b>Mannam Varun Chowdary</b> (212221040098)</b></font>
        </h3>
        <center>
            
<map name="MyCity">
    <area shape="rect" coords="100,100,900,900" href="expmap.html" title="My Home Town"</map>
    

    <img src="map.png" usemap="#image-map">

<map name="image-map">
    <map name="image-map">    
    
            <area target="_blank" alt="Kadapa" title="Kadapa" href="kadapa.html" coords="231,77,47" shape="rect">
            <area target="_blank" alt="ongole" title="ongole" href="ongole.html" coords="720,174,71" shape="circle">
            <area target="_blank" alt="guntur" title="machupalle" href="guntur.html" coords="1156,263,1284,318" shape="poly">
            <area target="_blank" alt="tirupati" title="tirupati" href="tirupati.html" coords="563,547,775,619" shape="rect">    
    </map>
</map>
        </center>
    </body>

</html>
```
nellore.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">
        <font color="black"><b>Andhra Pradesh</b></font>
        </h1>
        <h3 align="center">
        <font color="black"><b>Nellore</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            Nellore is a city located on the banks of Penna River, in Nellore district of Andhra Pradesh, India.
        </font>
        </p>
    </body>
</html>
```
college.html
```<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">
        <font color="black"><b>Nellore</b></font>
        </h1>
        <h3 align="center">
        <font color="black"><b>Narayana Medical College</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            State of the Art teaching & learning facilities, Research Facilities, One and only recognised Incubation center in Medical Institutions in AP.
        </font>
        </p>
    </body>
</html>
```
temple.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">
        <font color="black"><b>Nellore</b></font>
        </h1>
        <h3 align="center">
        <font color="black"><b>Ayappa Swamy Temple</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            Andhra Pradesh Nellore . Ayyappa Swamy Temple. OpenOpens at 6:00-12:00,18:00-21:00.. Grand Trunk Road, Auto Nagar, Nellore, Andhra Pradesh 524004, India. Map.
        </font>
        </p>
    </body>
</html>
```
nawapet.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="gray">
        <h1 align="center">
        <font color="black"><b>Nellore</b></font>
        </h1>
        <h3 align="center">
        <font color="black"><b>Nawapet</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            Nawabpet is one of the localities in Nellore. This locality is near Kisan Nagar, Stonehouse Pet and Saraswathi Nagar. 
        </font>
        </p>
    </body>
</html>
```


## OUTPUT
![382710303-99bac25a-75c9-4197-ac92-afd226c1361a](https://github.com/user-attachments/assets/f156cc14-c01a-4e91-bb75-1fb49e4d2f39)
![382710411-d3b19419-2e94-4ef4-ae87-f8a6117e3738](https://github.com/user-attachments/assets/022b48bd-e459-4293-bb54-3d43e0ac7d19)

![382710496-5574a29f-ab3b-48f9-91e8-0cc5152d9fe4](https://github.com/user-attachments/assets/9bc514be-fcf3-4c5d-869c-696d38fc0b8f)
![382710591-b6cb4d9d-1ced-4dce-abf6-8b9f9a2a6546](https://github.com/user-attachments/assets/b4a7212d-e628-43df-83b3-081808f04ed8)
![382710671-5ee52847-a3fa-44a2-92a4-efc14a4af17a](https://github.com/user-attachments/assets/70af21a0-c78e-4ca0-b768-d2a752019e9b)

## RESULT
The program for implementing image maps using HTML is executed successfully.
