# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1: Create a new django project and app

### Step 2: Add a new imagemap html file in templates and neede images in static folder and define it in settings.

### Step 3: Type ur image map code in the html with coordinates and target file to redirect on click

### Step 4: Define your components pages and create content in such a way that it gives information about place which is being clicked

### Step 5: Include pictures and contents for your subpages and map them using urls and views

## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>My City</title>
        <h1 align="center">
        <font colour="red"><b>thakkolam</b></font>
        </h1>
        <h3 align="center">
        <font colour="blue"><b>KEERTHANA S(22009006)</b></font>
        </h3>
    </head>
    <body>

        <img id="Image-Maps-Com-image-maps-2023-01-20-035312" src="images/map.png" border="0" width="1100" height="708" orgWidth="1100" orgHeight="708" usemap="#Mycity" alt="" />
        <map name="Mycity" id="ImageMapsCom-image-maps-2023-01-20-035312">
        <area alt="" title="state bank of india TAKKOLAM" href="SBIT.html" shape="rect" coords="255,625,292,657" style="outline:none;" target="_self"     />
        <area alt="" title="thakkolam town panchayat office " href="thakkolamtownpanchayatoffice.html" shape="rect" coords="468,572,505,604" style="outline:none;" target="_self"     />
        <area alt="" title="Srinivasa super market" href="Srinivasasupermarket.html" shape="rect" coords="190,427,227,459" style="outline:none;" target="_self"     />
        <area alt="" title="Takkolam post office" href="Takkolampostoffice.html" shape="rect" coords="159,241,196,270" style="outline:none;" target="_self"     />
        <area alt="" title="shri shakthivinayagar temple" href="shrishakthivinayagartemple.html" shape="rect" coords="229,138,266,167" style="outline:none;" target="_self"     />
        <area shape="rect" coords="1098,706,1100,708" alt="Image Map" style="outline:none;" title="Image Map" href="https://www.image-maps.com/" />
        </map>
    
    </body>
</html>
```

## Output:

### MAP 
![ex04(1)](https://user-images.githubusercontent.com/119477890/214836169-7b626586-7870-4949-8524-aa033a132620.png)

### MAP POINTER
![ex 4](https://user-images.githubusercontent.com/119477890/214836450-80874673-c968-4b2b-b4bb-2f494fb96f0e.png)


### PLACE DESCRIPTION
![ex 4(3)](https://user-images.githubusercontent.com/119477890/214836517-b2258a4a-17d9-44f3-bfb4-bfc3af8c3f9e.png)


### Validation Report
![Screenshot 2023-01-26 183039](https://user-images.githubusercontent.com/119477890/214842054-45c0cb81-cdc9-4948-88a2-664f1d54c8b4.png)


## Result:
Image mapping website created and executed successfully
