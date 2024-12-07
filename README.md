# Ex04 Places Around Me
# Date:02-11-2024
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using ```<map>``` tag name the map.

## STEP 4
Create clickable regions in the image using``` <area>``` tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
map.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places around my house</title>
</head>
<body style="background-color: beige;">
    <header>
        <h1 style="background-color: rgb(227, 45, 203);text-align: center;">Places around Me</h1>
    </header>
    <main>
        <img src="C:\Users\admin\Pictures\Screenshots\Screenshot (11).png" title="map places"  usemap="#places-map"  >
        <map name="places-map">
            <area shape="rect" coords="964,433,1002,471"  href="C:\Users\admin\Documents\lake.html" title="Water Falls" />
            <area shape="rect" coords="509,435,636,496"  href="C:\Users\admin\Documents\park.html" title="Park" />
            <area shape="rect" coords="102,316,209,404"  href="C:\Users\admin\Documents\college.html" title="Arts College" />
            <area shape="rect" coords="498,372,549,412"  href="https://maps.app.goo.gl/8wHWbLMnq1bg3aWb6" title=" My Home" />
            <area shape="rect" coords="642,357,742,422"  href="C:\Users\admin\Documents\school.html" title="School" />
        </map>
    </main>
</body>
</html>

hills.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places around my house</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
    </style>
</head>
<body style="background-color: rgb(224, 224, 189);">
    <header>
        <h1 style="font-size: xx-large; font-family: 'Times New Roman';background-color: rgb(128, 233, 173);text-align: center;">Hills</h1>
    </header>
    <main>
        <img src="C:\Users\admin\Documents\clouded-hills (1).jpg" title="HILLS"  usemap="#places-map" class="centreImage"  >
        <map name="places-map">
            <area shape="default"  href="https://maps.app.goo.gl/Wr5Gs42X1TGn733F7" title="hill" />
        </map>
    </main>
    <p style="font-size: x-large; font-family:  'Lucida Grande';">The Palamathi Hills (also Balamathi, Balamathi Hills) are an extension of the Eastern Ghats spread across southeastern parts of Vellore City in Tamil Nadu. The Palamathi Hill range, the nearby Palamathi Reserve Forest, and the Otteri lake are collectively referred to as Palamathi Hills. The area is a thriving hotspot for various birds and various flora. The hill top has a famous Hindu temple (Bala Murugan Kovil). The place is also a developing tourist destination.</p>
    <p style="font-size: x-large; font-family:  'Lucida Grande';">Balamathi Hill, located in Vellore, is often referred to as "Vellore's Ooty" due to its pleasant and chilly weather, particularly in the early morning and post-evenings. With a height of approximately 1640 feet, this mountain range offers a refreshing environment for visitors</p>
</body>
</html>

college.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places around my house</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
        body{
            background-color: azure;
        }
        h1{
            text-decoration-color: black; text-decoration: underline; font-style: italic;
        }
        a,p{
            font-size: x-large; font-family: Arial; text-decoration: aliceblue;
        }
        p{
            margin-left: 50px;
        }
        a:link {color: green;
            background-color: transparent;
            text-decoration: none;
        }

        a:visited {
            color: rgb(3, 3, 214);
            background-color: transparent;
            text-decoration: none;
        }

        a:hover {
        color: red;
        background-color: transparent;
        text-decoration: underline;
        }

        a:active {
        color: yellow;
        background-color: transparent;
        text-decoration: underline;
        }
    </style>
</head>
<body>
    <header style="background-color: rgb(32, 4, 78); height: 80px;">
        <h1 style="text-align: center; font-size: xx-large; font-family: 'Lucida Grande'; color: white;">College</h1>
    </header>
    <main>
        <img src="C:\Users\admin\Documents\college.jpg" title="College"  usemap="#places-map" class="centreImage" width="600px" height="450px">
        <map name="places-map">
            <area shape="default"   href="https://maps.app.goo.gl/fy68TGfLtpC5x4Gd7" title="Arts College" />
        </map>
    </main>
    
    <h1></h1>
    <a href="https://en.wikipedia.org/wiki/Muthurangam_Govt._Arts_College" title="Visit MGAC">Muthurangam Government Arts College</a> 
    <p style="color: black;">Muthurangam Government Arts College (MGAC)located in Bagayam, Vellore, Tamil Nadu, India. The college is affiliated with Thiruvalluvar University. This college offers different courses in arts, commerce and science.
History</p>
    <p>Muthurangam Government Arts College was officially inaugurated on 1 November 1965, by the then Chief Minister of Tamil Nadu, Honorable M. Bhaktavatsalam.</p>
    <br>
    <br>
    <table style="background-color: beige; width: 100%; height: 200px;">
        <tr>
            <th> <p><a href="https://www.mgacvlr.edu.in/"> <img src="college icon.png" style="width: 80px; height: 50px;"></a>MGAC Official Website</p></th>
        </tr>
        <tr>
            <th> <p><a href="https://www.mgacvlr.edu.in/"> <img src="dept.png" style="width: 80px; height: 50px;"></a>Departments</p></th> 
        </tr>
        <tr>
            <th>Contact us<br> 
                Phone: <cite>  0416 226 2068</cite>
                Address:<cite> V4PQ+4G8, Otteri Rd, Vellore, Tamil Nadu 632002</cite>
            </th>
        </tr>
        <tr>
            <th>Follow us on:<br>
                <a href="https://www.youtube.com/"><img src="youtube.jpg" title="youtube" style="width: 80px; height: 50px;"></a><br>
                <a href="https://www.youtube.com/"><img src="insta.jpg" title="Instagram" style="width: 80px; height: 50px;"></a><br>
                <a href="https://www.youtube.com/"><img src="fb.png" title="Face Book" style="width: 80px; height: 50px;"></a>
            </th>
        </tr>
    </table>

park.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places around my house</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
    </style>
</head>
<body style="background-color: rgb(193, 193, 120);">
    <header>
        <h1 style="font-size: xx-large; font-family: 'Times New Roman';background-color: rgb(128, 233, 173); text-align: center">Park</h1>
    </header>
    <main>
        <img src="C:\Users\admin\Pictures\Screenshots\Screenshot (24).png" title="park"  usemap="#places-map" class="centreImage"  >
        <map name="places-map">
            <area shape="default"  href="https://maps.app.goo.gl/Wr5Gs42X1TGn733F7" title="playground" />
        </map>
    </main>
    <p style="font-size: x-large; font-family:  'Lucida Grande';">A park is an area of natural, semi-natural or planted space set aside for human enjoyment and recreation or for the protection of wildlife or natural habitats. Urban parks are green spaces set aside for recreation inside towns and cities.</p>
    <p style="font-size: x-large; font-family:  'Lucida Grande';">laygrounds provide an ideal opportunity for children to master physical skills, such as learning to swing, balance and climb. Personal development may be gained through the enhancement of skills, such as playing, communicating and cooperating with other children and adults in the playground.</p>
</body>
</html>

school.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places around my house</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
        body{
            background-color: rgb(210, 98, 169);
        }
        h1{
            text-decoration-color:white; text-decoration: underline; font-style: italic;
        }
        p{
            font-size: x-large; font-family: Arial; text-decoration: aliceblue;
            margin-left: 50px;
        }
        a:link {color: green;
            background-color: transparent;
            text-decoration: none;
        }

        a:visited {
            color: rgb(3, 3, 214);
            background-color: transparent;
            text-decoration: none;
        }

        a:hover {
        color: red;
        background-color: transparent;
        text-decoration: underline;
        }

        a:active {
        color: yellow;
        background-color: transparent;
        text-decoration: underline;
        }
        table{
            border: 5px solid black;
            border-collapse: collapse;
        }
        tr,th,td{
            border: 2px dashed black;
            border-collapse: collapse;
            text-align: center;
        }
    </style>
</head>
<body>
    <header style="background-color: rgb(42, 147, 227); height: 80px;">
        <h1 style="text-align:center; font-size: xxx-large; font-family: 'Lucida Grande';margin-top: 10px;">School</h1>
    </header>
    <main>
        <img src="C:\Users\admin\Documents\college.jpg" title="College"  usemap="#places-map" class="centreImage" width="600px" height="450px">
        <map name="places-map">
            <area shape="default"   href="https://maps.app.goo.gl/fy68TGfLtpC5x4Gd7" title="School" />
        </map>
    </main>
    <h1></h1>
    <a href="https://sdaschoolvellore.com/" title="Visit SDA"> Seventh-Day Adventist Matriculation Higher Secondary School </a> 
    <p style="color: black;"> The Seventh-day Adventist educational system is the second-largest Christian school system in the world, after the Roman Catholic system.It has a total of 7,804 educational institutions operating in over 100 countries around the world with over 1.5 million students world-wide.The denominationally-based school system began in the 1870s. The church supports holistic education:</p>
    <p>The Education Department team is responsible for the coordination, promotion, training, and quality of the global Seventh-day Adventist educational system, which includes 7,804 schools, colleges and universities, with 84,997 teachers and 1,673,828 students. Working in close cooperation with the Education Department directors in the 13 world divisions, the staff offers services to boards, administrators, and faculty of Adventist colleges and universities worldwide.</p>
    <br>
    <br>
    <table style="background-color: azure; width: 100%; height: 200px; ">
        <tr>
            <th>About SDA</th>
            <th>Infrastructure</th>
            <th>Academics</th>
            <th>Reach us</th>
        </tr>
        <tr>
            <td><a href="https://sdaschoolvellore.com/sample-page/about-sda/">ABOUT SDA</a></td>
            <td><a href="https://sdaschoolvellore.com/sample-page/about-sda/">COMPUTER LAB</a></td>
            <td><a href="https://sdaschoolvellore.com/sample-page/about-sda/">COURSES OFFERED</a></td>
            <td rowspan="4">The Principal,<br>Seventh-Day Adventist <br>Higher Secondary School<br>Arts College Road,<br>Vellore-632002,Tamil Nadu<br><strong>Contact Us:<br>91 416 2261100, 91 416 2262393</strong></td>
            

        </tr>
        <tr>
            <td><a href="https://sdaschoolvellore.com/sample-page/about-sda/">ADVENTIST EDUCATION</a></td>
            <td><a href="https://sdaschoolvellore.com/sample-page/about-sda/">CHEMISTRY LAB</a></td>
            <td><a href="https://sdaschoolvellore.com/sample-page/about-sda/"> EILIGIBILITY</a></td>
        </tr>
        <tr>
            <td><a href="https://sdaschoolvellore.com/sample-page/about-sda/">MISSION & STRATEGY</a></td>
            <td><a href="https://sdaschoolvellore.com/sample-page/about-sda/">PHYSICS LAB</a></td>
            <td><a href="https://sdaschoolvellore.com/sample-page/about-sda/">ADMISSION</a></td>
        </tr>
        <tr>
            <td><br></td>
            <td><a href="https://sdaschoolvellore.com/sample-page/about-sda/">BOLOGY LAB</a></td>
            <td><a href="https://sdaschoolvellore.com/sample-page/about-sda/">EXAM & PROMOTION</a></td>
        </tr>

    </table>
</body>
</html>

lake.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places around my house</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
    </style>
</head>
<body style="background-color: beige;">
    <header>
        <h1 style="font-size: xx-large; font-family: 'Times New Roman';background-color: plum; text-align: center;">Lake</h1>
    </header>
    <main>
        <img src="C:\Users\admin\Pictures\Screenshots\Screenshot (22).png" title="Lake"  usemap="#places-map" class="centreImage"   >
        <map name="places-map">
            <area shape="default"  href="https://maps.app.goo.gl/Wr5Gs42X1TGn733F7" title="Water Falls" />
        </map>
    </main>
    <p style="font-size: x-large; font-family:  'Lucida Grande';">waterfalls form as streams flow from soft rock to hard rock. This happens both laterally (as a stream flows across the earth) and vertically (as the stream drops in a waterfall). In both cases, the soft rock erodes, leaving a hard ledge over which the stream falls.</p>
    <h2>Formation</h2>
    <p style="font-size: x-large; font-family:  'Lucida Grande';">Waterfalls are formed when a body of water, such as a river or stream, falls over a steep drop or rocky ledge into a plunge pool. The most common way this happens is when a river flows over a layer of resistant bedrock and then onto softer rock, which erodes faster. Other causes include movements in the Earth's crust and glaciers cutting away rock. 
    </p>
</body>
</body>
</html>
```

# OUTPUT
![alt text](<imagemap/mapapp/static/Screenshot (28).png>)
![alt text](<Screenshot (48).png>)
![alt text](<Screenshot (49).png>)
![alt text](<Screenshot (50).png>)
![alt text](<Screenshot (51).png>)
![alt text](<Screenshot (52).png>)
![alt text](<Screenshot (53).png>)
![alt text](<Screenshot (54).png>)
![alt text](<Screenshot (55).png>)

# RESULT
The program for implementing image maps using HTML is executed successfully.
