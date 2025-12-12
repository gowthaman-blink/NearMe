# Ex04 Places Around Me
## Date: 12.12.2025
# Reference No: 25017622

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
~~~
map.html
---------
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>chennai</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>A.K GOWTHAMAN (25017622)</b></font>
</h3>static



<map>
    <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="t nagarf" title="t nagarf" href="tnagar.html" coords="769,799,964,909" shape="rect">
    <area target="" alt="marina" title="marina" href="Marina.html" coords="1292,748,128" shape="circle">
    <area target="" alt="koyambedu" title="koyambedu" href="Koyambedu.html" coords="418,577,666,663" shape="rect">
    <area target="" alt="royapuram" title="royapuram" href="Royapuram.html" coords="1353,258,89" shape="circle">
</map>
</map>
</body>
</html>



marina.html
------------
<html>
    <head>
        <title>
            Marina
        </title>
    </head>
    <body>
        <center>
            <h1  style="font-size: 50px;"><b>Marina</b></h1>
            <br>
            <img src="marina.avif" width="800">
            <p style="font-size: 30;">
              <b>
               Chennai Plans Modern Revival of MarinaMarina Beach in Chennai, India, is a vast, natural urban shoreline on the Bay of Bengal, famous as one of the world's longest beaches, offering sunrise/sunset views, cultural landmarks (statues, memorials), street food, and lively evening activities like kite flying, though swimming is risky due to strong currents. It's a vibrant hub for locals and tourists, featuring a promenade with historical buildings, the Marina Lighthouse, an aquarium, and bustling food stalls, making it a cultural and recreational heart of the city.
              </b> 
            </p>
        </center>
        
    </body>
</html>


koyembedu.html
--------------
<html>
    <head>
        <title>
            koyambedu
        </title>
    </head>
    <body>
        <center>
            <h1  style="font-size: 50px;"><b>koyambedu</b></h1>
            <br>
            <img src="koyembedu.jpg" width="800">
            <p style="font-size: 30;">
              <b>
               Koyambedu is a bustling commercial and residential hub in West Chennai, famous for the massive Koyambedu Wholesale Market Complex (KWMC), one of Asia's largest fresh produce markets, and the Chennai Mofussil Bus Terminus (CMBT), a major transport hub with extensive metro connectivity. It's a vital trade center for fruits, vegetables, and flowers, featuring wholesale/retail shops, surrounded by Anna Nagar, Vadapalani, and Arumbakkam, and known for its busy markets and transport links. 
              </b> 
            </p>
        </center>
        
    </body>
</html>

royapuram.html
---------------
<html>
    <head>
        <title>
            Royapuram
        </title>
    </head>
    <body>
        <center>
            <h1  style="font-size: 50px;"><b>Royapuram</b></h1>
            <br>
            <img src="royapuram.jpg" width="800">
            <p style="font-size: 30;">
              <b>
               Royapuram is a historic, bustling locality in North Chennai, famous for being home to South India's first railway station (opened 1856) and the significant Royapuram Fishing Harbour, which handles large volumes of catch and attracts daily visitors for auctions, making it a key part of Chennai's fishing industry, as detailed by {Link: Wikipedia and this Wikipedia article on the fishing harbour. It's a diverse residential area with strong transport links, traditional markets, and historic institutions like St. Peter's Church, blending old-world charm with modern urban life. 
              </b> 
            </p>
        </center>
        
    </body>
</html>

tnagar.html
------------
<html>
    <head>
        <title>
            TNagar
        </title>
    </head>
    <body>
        <center>
            <h1  style="font-size: 50px;"><b>TNagar</b></h1>
            <br>
            <img src="tnagar.jpg" width="800">
            <p style="font-size: 30;">
              <b>
               T. Nagar (Thyagaraya Nagar) is Chennai's premier, bustling commercial and residential hub, famous for its vibrant, budget-friendly shopping (especially sarees, jewelry on Ranganathan Street), diverse eateries, and cultural spots like Panagal Park, serving as a major economic center with excellent connectivity to IT parks and the airport. 
              </b> 
            </p>
        </center>
        
    </body>
</html>
~~~


## OUTPUT

![alt text](<Screenshot 2025-12-12 104051.png>)
![alt text](<Screenshot 2025-12-12 104103.png>)
![alt text](<Screenshot 2025-12-12 104116.png>)
![alt text](<Screenshot 2025-12-12 104131.png>)
![alt text](<Screenshot 2025-12-12 104142.png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
