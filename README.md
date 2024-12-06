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
![alt text](<Screenshot 2024-10-24 110018-1.png>)

![alt text](<Screenshot 2024-10-24 110040-1.png>)
![alt text](<Screenshot 2024-10-24 110059-1.png>)

![alt text](<Screenshot 2024-10-24 110117-1.png>)
![alt text](<Screenshot 2024-10-24 110133-1.png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
