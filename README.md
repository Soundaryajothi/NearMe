# Ex04 Places Around Me
## Date: 20.11.2023

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
        <title> MY CITY </title>
    </head>
    <body>
        <h1 align="center">
            <font color="green"><b>GINGEE</b></font>
            </h1>
            <h3 align="center">
            <font color="red"><b>SOUNDARYA J (23006091)</b></font>
            </h3>
            <centre>
                <img src="map.png" usemap="#MYCITY" height="610" width="1450">
                <map name="MYCITY">
                    <area shape="rect" coords="700,250,770,320" href="home.html" title="MY HOME TOWN">
                    <area shape="rect" coords="950,120,1100,140" href="stone.html" title="Hill View Point">
                    <area shape="circle" coords="300,300,60"  href="template.html" title="Gingee Fort">
                    <area shape="circle" coords="300,400,60" href="garden.html" title="The Elephant Pond">
                    <area shape="circle" coords="1200,570,60" href="lake.html" title="Farmhouse">
                    
                    

                    
                    
                </map>
            </centre>
    </body>
</html>

home.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="violet">
        <h1 align="center">
         <font color="red"><b>GINGEE</b></font>   
        </h1>
        <h3 align="center">
            <font color="blue"><b>ANATHUR - My Home Town</b></font>
        </h3>
        <hr size="3"color="red">
        <p align="justify">
            <font face="Georgia"size="5">
                According to Census 2011 information the location code or village code of Anathur village is 632386. Anathur village is located in Gingee taluka of Viluppuram district in Tamil Nadu, India. Viluppuram and Gingee are the district & sub-district headquarters of Anathur village respectively. As per 2009 stats, Anathur village is also a gram panchayat.
                The total geographical area of village is 457.97 hectares. Anathur has a total population of 852 peoples, out of which male population is 436 while female population is 416. Literacy rate of anathur village is 70.42% out of which 78.21% males and 62.26% females are literate. There are about 205 houses in anathur village. Pincode of anathur village locality is 604202.
                Gingee is nearest town to anathur for all major economic activities, which is approximately 7km away.


            </font>
        </p>
    </body>
</html>

stone.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Gingee</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>The Hill View - The tourists attraction</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The granitic area in the area is formed towards the end of the archean era due to magnetic action loading to the melting of the older genissic rocks and younger granitic complex varies from 5 to 25 km. Virpattu is locatd in gingee in tamilnadu, india. Villupuram and gingee are the district sub district headquarters in gingee major town to virpattu for all economic activities.
The hill view is a breathtaking tableau of nature's grandeur, where undulating slopes adorned with lush greenery create a mesmerizing panorama. As the sun gracefully ascends or descends, casting its warm hues upon the landscape, the interplay of light and shadow adds depth and character to the scene. From the summit, one can witness a tapestry of colors as the foliage transitions through the seasons, painting the hills in a kaleidoscope of autumnal reds, winter blues, and springtime greens. The air at this elevated vantage point is crisp and invigorating, carrying with it the subtle scents of wildflowers and pine. Whether shrouded in morning mist or bathed in the golden glow of sunset, the hill view beckons contemplation and awe, offering a serene retreat from the hustle and bustle of everyday life. It is a reminder of the Earth's enduring beauty and the harmony that exists between the natural world and those fortunate enough to behold it.






</p>
</body>
</html>

garden.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="lime">
        <h1 align="center">
         <font color="red"><b>GINGEE</b></font>   
        </h1>
        <h3 align="center">
            <font color="blue"><b>The Elephant Pond</b></font>
        </h3>
        <hr size="3"color="red">
        <p align="justify">
            <font face="Georgia"size="5">
                The Elephant Pond, a serene and picturesque water body, holds a distinct charm that resonates with both nature enthusiasts and those seeking tranquility. Nestled amid lush landscapes, this pond derives its name from its historical association with elephants, often utilized for royal baths or ceremonial purposes in certain cultures. The still waters of the Elephant Pond reflect the verdant surroundings and often mirror the azure sky above, creating a captivating scene. Tall grasses and aquatic plants fringe its edges, providing a habitat for various bird species and adding to the overall ecological richness of the area. Visitors are often drawn to the peaceful ambiance that envelops the Elephant Pond, making it an ideal spot for contemplation or leisurely strolls along its banks. Whether it's the ripple of water disturbed by a gentle breeze or the occasional sighting of aquatic life, the Elephant Pond stands as a testament to the harmonious coexistence of nature and the cultural heritage that may be intertwined with such serene locales.






             
            </font>
        </p>
    </body>
</html>

lake.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">
         <font color="cyan"><b>GINGEE</b></font>   
        </h1>
        <h3 align="center">
            <font color="lime"><b>AN Ganeshagounder-Farmhouse</b></font>
        </h3>
        <hr size="3"color="red">
        <p align="justify">
            <font face="Georgia"size="5"color="white">
                A farmhouse is a rustic haven, a bucolic retreat that encapsulates the essence of rural living. Surrounded by open fields, rolling hills, or orchards, a farmhouse serves as a sanctuary away from the hustle and bustle of city life. The architecture often exudes a quaint charm, with pitched roofs, wide verandas, and perhaps a weathered barn nearby. These dwellings are not merely structures; they are a connection to the land and the cycles of nature. A farmhouse typically features a working kitchen, cozy living spaces, and ample windows that frame panoramic views of the countryside. The air is infused with the scent of earth and vegetation, and the soundtrack is a symphony of chirping birds and the occasional rustle of leaves. Beyond just a residence, a farmhouse embodies a lifestyle—a slower pace that invites contemplation, appreciation for seasonal rhythms, and a sense of community often rooted in agrarian traditions. Whether used for agricultural pursuits or simply as an escape to the simplicity of rural existence, a farmhouse epitomizes a retreat where one can find solace in the embrace of nature.






                
                
            </font>
            
        </p>
    </body>
</html>

template.html

<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">
         <font color="cyan"><b>GINGEE</b></font>   
        </h1>
        <h3 align="center">
            <font color="lime"><b>AN Ganeshagounder-Farmhouse</b></font>
        </h3>
        <hr size="3"color="red">
        <p align="justify">
            <font face="Georgia"size="5"color="white">
                A farmhouse is a rustic haven, a bucolic retreat that encapsulates the essence of rural living. Surrounded by open fields, rolling hills, or orchards, a farmhouse serves as a sanctuary away from the hustle and bustle of city life. The architecture often exudes a quaint charm, with pitched roofs, wide verandas, and perhaps a weathered barn nearby. These dwellings are not merely structures; they are a connection to the land and the cycles of nature. A farmhouse typically features a working kitchen, cozy living spaces, and ample windows that frame panoramic views of the countryside. The air is infused with the scent of earth and vegetation, and the soundtrack is a symphony of chirping birds and the occasional rustle of leaves. Beyond just a residence, a farmhouse embodies a lifestyle—a slower pace that invites contemplation, appreciation for seasonal rhythms, and a sense of community often rooted in agrarian traditions. Whether used for agricultural pursuits or simply as an escape to the simplicity of rural existence, a farmhouse epitomizes a retreat where one can find solace in the embrace of nature.






                
                
            </font>
            
        </p>
    </body>
</html>
```


## OUTPUT
![Alt text](<Screenshot (2).png>)
![Alt text](<Screenshot (3).png>)
![Alt text](<Screenshot (4).png>)
![Alt text](<Screenshot (5).png>)
![Alt text](<Screenshot (6).png>)
![Alt text](<Screenshot (7).png>)




## RESULT
The program for implementing image maps using HTML is executed successfully.
