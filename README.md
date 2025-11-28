# Ex03 Places Around Me
## Date: 28.11.2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
map.html
<html>
    <head>
        <title>Sample page</title>
    </head>
    <body>
        <h1 align="center">TIRUPUR CITY</h1>
        <h2 align="center">Rithani.P(25017521)</h2>
        <img src="Screenshot 2025-11-28 112344.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Sri Sukreeswarar Temple" title="Sri Sukreeswarar Temple" href="temple.html" coords="1333,248,1622,331" shape="rect">
    <area target="" alt="RBR CRICKET GROUND" title="RBR CRICKET GROUND" href="cricket.html" coords="1436,758,92" shape="circle">
    <area target="" alt="SkyTech" title="SkyTech" href="tech.html" coords="1070,565,1011,613,1126,619" shape="poly">
    <area target="" alt="Ganapathipalayam" title="Ganapathipalayam" href="area.html" coords="1129,704,1237,749,1214,850,1051,851,1021,749" shape="poly">
    <area target="" alt="A.Thirumuruganpoondi" title="A.Thirumuruganpoondi" href="place.html" coords="1177,163,924,154,833,364,1107,366,1175,163,1177,163" shape="poly">
    </body>
</html>

area.html
<html>
    <head>
        <title>Ganapathipalayam</title>
    </head>
    <body bgcolor="green">
        <h1>Ganapathipalayam</h1>
        <p>Ganapathipalayam is a village located in the Palladam taluk of the Tiruppur district in Tamil Nadu, India, known for its textile industry. The village has a population of over 14,000 residents and is a part of Tiruppur, a major industrial center in the region. </p>
    </body>
</html>

place.html
<html>
    <head>
        <title>A.Thirumuruganpoondi</title>
    </head>
    <body bgcolor="purple">
        <h1>A.Thirumuruganpoondi</h1>
        <p>Thirumuruganpoondi is a municipality in Tamil Nadu's Tiruppur district, notable for the ancient Thirumuruganatheswarar Temple dedicated to Lord Shiva. Located about 7 km south of Tiruppur city, the temple is a significant pilgrimage site and a Paadal Petra Sthalam, featuring unique Dravidian architecture without a rajagopuram. The area's name is linked to a legend where Lord Murugan worshipped Shiva here to absolve a brahmmahathi dosham (sin) after defeating the demon Soorapadman. </p>
    </body>
</html>

tech.html
<html>
    <head>
        <title>SkyTech</title>
    </head>
    <body bgcolor="blue">
        <h1>SkyTech</h1>
        <p>There are multiple "SkyTech" businesses in Tirupur, with the most prominent being Sky Tech Roofing, which supplies premium UPVC and Spanish-style roofing sheets, and Sky Tech Engineering Supplies, which deals in waterproofing chemicals and construction-related products. Other businesses include Sky Tech Readymix Concrete and potentially other entities in construction and engineering services. </p>
    </body>
</html>

cricket.html
<html>
    <head>
        <title>RBR CRICKET GROUND</title>
    </head>
    <body bgcolor="pink">
        <h1>RBR CRICKET GROUND</h1>
        <p>RBR Cricket Ground in Tiruppur appears to be a cricket facility that is currently temporarily closed. While it was previously advertised, with details like an astro turf, practice nets, restaurant, and other amenities, recent information indicates it is not operational at this time. </p>
    </body>
</html>

temple.html
<html>
    <head>
        <title>Sri Sukreeswarar Temple</title>
    </head>
    <body bgcolor="red">
        <h1>Sri Sukreeswarar Temple</h1>
        <p>The Sri Sukreeswarar Temple is an ancient, heritage Shiva temple located in Sarkar Periyapalayam, about 8 kilometers from Tiruppur, Tamil Nadu. It is a protected monument under the Archaeological Survey of India and is believed to be at least 2,500 years old. The temple's main deity is Sugreeswarar, believed to have been worshipped by the monkey king Sugreeva, and the goddess is known as Aavudai Nayaki Amman. The temple is constructed from carved stones in a style reminiscent of the Pandya period. </p>
    </body>
</html>

```

## OUTPUT


![alt text](<Screenshot (18).png>)
![alt text](<Screenshot (19).png>)
![alt text](<Screenshot (20).png>)
![alt text](<Screenshot (21).png>)
![alt text](<Screenshot (22).png>)
![alt text](<Screenshot (23).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
