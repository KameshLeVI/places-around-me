# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Write your own steps here.
### Step 2:
Add a new imagemap html file in templates and neede images in static folder and define it in settings.
### Step 3:
Type ur image map code in the html with coordinates and target file to redirect on click

### Step 4:
Define your components pages and create content in such a way that it gives information about place which is being clicked

### Step 5:
Include pictures and contents for your subpages and map them using urls and views

## Code:
```
map
<!DOCTYPE html>
<html>
    <head>
        <title>
            IMAGE MAPS
        </title>
    </head>
    <body>
         <h1 align="center" >
            <font color="red" >
                    Image Map Of My Home Town
            </font>
        </h1>
         <h3 align="center">
        <font color="blue" face ="cursive">
            Kamesh (212222240043)
        </font>
        </h3>
        <center>
           <img id="Image-Maps-Com-image-maps-2023-05-17-040541" src="/static/image/map.jpg" border="0" width="1902" height="878" orgWidth="1902" orgHeight="878" usemap="#image-maps-2023-05-17-040541" alt="" />
<map name="image-maps-2023-05-17-040541" id="ImageMapsCom-image-maps-2023-05-17-040541">
<area  alt="" title="GROUND" href="ground.html" shape="rect" coords="200,369,260,417" style="outline:none;" target="_self"     />
<area  alt="" title="SCHOOL" href="school.html" shape="rect" coords="740,261,783,314" style="outline:none;" target="_self"     />
<area  alt="" title="OFFICE" href="office.html" shape="rect" coords="1287,666,1372,721" style="outline:none;" target="_self"     />
<area  alt="" title="HOSTEL" href="hostel.html" shape="rect" coords="1407,267,1492,322" style="outline:none;" target="_self"     />
<area  alt="" title="FOOD" href="food.html" shape="rect" coords="1664,459,1749,514" style="outline:none;" target="_self"     />
<area shape="rect" coords="1900,876,1902,878" alt="Image Map" style="outline:none;" title="Image Map" href="https://www.image-maps.com/" />
</map>
        </center>
         <p align="center">
            <font color="maroon"  face="Comic Sans MS" >
                This Image Map shows various locations around my home.<br>
                Click the location and get information about it.
            </font>
        </p>
    </body>
</html>

ground
<!DOCTYPE html>
<html>
    <head>
        <title>
            GROUND
        </title>

    </head>
    <body bgcolor ="cyan">
        <h1 align="center">
            <font color = "blue">
                <b>
                    THIRUPATHUR
                </b>
            </font>
            <h1>
            <h3 align="center">
            <font color = "red">
                <b>
                   GROUND
                </b>
            </font>
            
        </h3>
<hr size="3" color="orange">
<p align="justify">
    <font face="Courier New" size="5">
        <b>
            A playground is a place where kids can play. Typically, they have playthings for kids to use, like slides, swings, and seesaws. A playground can improve your pavement surface and make your kids enjoy the playground more. Usually, they are outside, but occasionally, they are inside a building.

The playthings could be made of plastic, wood, or metal. If a youngster falls, the surface beneath the apparatus won’t be hard. You might find sand, woodchips, or a rubber floor there. You might find sand, woodchips, or a rubber floor there
        </b>
    </font>
</p>
    </body>
</html>

school
<!DOCTYPE html>
<html>
    <head>
        <title>
            SCHOOL
        </title>

    </head>
    <body bgcolor ="cyan">
        <h1 align="center">
            <font color = "blue">
                <b>
                    THIRUPATHUR
                </b>
            </font>
            <h1>
            <h3 align="center">
            <font color = "red">
                <b>
                   SCHOOL
                </b>
            </font>
            
        </h3>
<hr size="3" color="orange">
<p align="justify">
    <font face="Courier New" size="5">
        <b>
            School is the place where we learn to read and write. It is the most crucial place for a student, and it helps us to learn new things. The teachers are always helpful and teach us important things in life. We must always be regular to school as missing classes can lead to problems during exams.21
        </b>
    </font>
</p>
    </body>
</html>

office
<!DOCTYPE html>
<html>
    <head>
        <title>
            OFFICE
        </title>

    </head>
    <body bgcolor ="cyan">
        <h1 align="center">
            <font color = "blue">
                <b>
                    THIRUPATHUR
                </b>
            </font>
            <h1>
            <h3 align="center">
            <font color = "red">
                <b>
                   COLLECTOR 
                   OFFICE
                </b>
            </font>
            
        </h3>
<hr size="3" color="orange">
<p align="justify">
    <font face="Courier New" size="5">
        <b>
            The seat of the District Collector/District Magistrate in india is usually located in the district headquarters, which is the administrative center of the district. The District Collector's office is commonly referred to as the Collector's Office or the District Collectorate or DC Office, etc.

Deputy Commissioner (DC) is a post that is primarily used in the states of Assam, Punjab, Haryana, Himachal Pradesh, and Karnataka in India. The role of a Deputy Commissioner is similar to that of a District Collector in other states of India.

In these states, the Deputy Commissioner is responsible for the overall administration of the district and has a wide range of responsibilities
        </b>
    </font>
</p>
    </body>
</html>

school
<!DOCTYPE html>
<html>
    <head>
        <title>
            HOSTEl
        </title>

    </head>
    <body bgcolor ="cyan">
        <h1 align="center">
            <font color = "blue">
                <b>
                    THIRUPATHUR
                </b>
            </font>
            <h1>
            <h3 align="center">
            <font color = "red">
                <b>
                   HOSTEL
                </b>
            </font>
            
        </h3>
<hr size="3" color="orange">
<p align="justify">
    <font face="Courier New" size="5">
        <b>
           It teaches them a sense of responsibility and they become self-dependent. Hostel life teaches many lessons — self-dependence, self-reliance, and disciplined way of life. Most importantly they will adjust to all kinds of situations.20
        </b>
    </font>
</p>
    </body>
</html>

food
<!DOCTYPE html>
<html>
    <head>
        <title>
            FOOD
        </title>

    </head>
    <body bgcolor ="cyan">
        <h1 align="center">
            <font color = "blue">
                <b>
                    THIRUPATHUR
                </b>
            </font>
            <h1>
            <h3 align="center">
            <font color = "red">
                <b>
                   FOOD
                </b>
            </font>
            
        </h3>
<hr size="3" color="orange">
<p align="justify">
    <font face="Courier New" size="5">
        <b>
            Food is the substance we eat every day for energy and strength. There are many different types of food, such as fruits, vegetables, rice, and pasta. We need to eat a variety of foods to get all the essential nutrients the body needs. Not eating a healthy and balanced diet leads to weakness and deficiency diseases.
        </b>
    </font>
</p>
    </body>
</html>
```

## Output:
![image](https://github.com/KameshLeVI/places-around-me/assets/120780633/fdcb7ded-70c9-4000-aefa-7a4c3781989a)
![Screenshot 2023-06-08 003335](https://github.com/KameshLeVI/places-around-me/assets/120780633/f2c51c54-13c8-45d8-b43f-d380caa0621c)
![Screenshot 2023-06-08 003351](https://github.com/KameshLeVI/places-around-me/assets/120780633/321ca6aa-3f93-4823-90e0-2685d9c3f997)
![Screenshot 2023-06-08 003405](https://github.com/KameshLeVI/places-around-me/assets/120780633/b7142ce2-22e6-4fa7-812e-aee6349646c8)
![Screenshot 2023-06-08 003420](https://github.com/KameshLeVI/places-around-me/assets/120780633/5e547de7-ce5a-41a8-a1f7-eebc7bb0b463)






## Result:
The program for implementing image map is executed successfully
