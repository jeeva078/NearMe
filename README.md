# Ex04 Places Around Me
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
### map.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>My City</title>
    </head>
    <body>
    <h1 align="center">
        <font color="red"><b>Mannargudi</b></font>
    </h1>
    <h3 align="center">
        <font color="black"><b>JEEVANANDAM M(212222220017)</b></font>
    </h3>
    <centre>
    <img id="Image-Maps-Com-image-maps-2023-05-10-172105" src="Around me.png" border="0" width="1693" height="728" 
         orgWidth="1693" orgHeight="728" usemap="#image-maps-2023-05-10-172105" alt="" />
<map name="image-maps-2023-05-10-172105" id="ImageMapsCom-image-maps-2023-05-10-172105">
<area  alt="" title="Mariyamman Kovil" href="temple.html" shape="rect" coords="703,650,890,722" style="outline:none;
                    " target="_self"/>
<area  alt="" title="MRGovernment Arts College" href="college.html" shape="rect" coords="735,262,870,385" 
              style="outline:none;" target="_self"/>
<area  alt="" title="Agriculture Office" href="AOoffice.html" shape="rect" coords="1106,268,1302,329" 
              style="outline:none;" target="_self"/>
<area  alt="" title="Findlay Higher Secondary School Ground" href="ground.html" shape="rect" coords="741,44,937,105" 
              style="outline:none;" target="_self"/>
<area  alt="" title="Newtunkids International School" href="school.html" shape="rect" coords="904,385,1077,486" 
              style="outline:none;" target="_self"/>
<area shape="rect" coords="1691,726,1693,728" alt="Image Map" style="outline:none;" title="Image Map" 
             href="https://www.image-maps.com/"/>
</map>
        </centre>
    </body>
</html>

```
### college.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>College</title>
    </head>
    <body bgcolor="#F3E5AB">
        <h1 align="center">
            <font color="red"><b>Mannargudi</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>MRGovernment Arts and Science College</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
                It is the ancient arts and science college in our city. This college is in under of government.This college 
                becomes very famous and populated college in our surroundings.The college was commissioned on 07.07.1971.
                The then Chief Minister Dr. M. Karunanithi formally inaugurated the college on 13.08.1971. 
                The college has a sylvan campus of forty acres and two hundred and twenty six square feet which was 
                provided by Mannargudi Rajagopalaswamy Temple.The Government of Tamil Nadu paid the price for the land to the 
                temple in 1987-88.The course B.A. History was started in 1972.
                B.A. English Literature in 1978;B. Sc. Botany in 1978; B.Sc. Physics in 1979; B. Sc. Chemistry in 1980; 
                B. Sc. Mathematics in 1985;B. Com. In 1990; B. Sc. Computer in 1996; M.A. Tamil Literature,M. Sc. Chemistry, 
                M.A. History, B. Sc. Microbiology and B.B.A. courses were started in 2004-05. M. Sc. Computer Science,
                M. Com. And M. Sc. Mathematics were started in 2005-06.Students are now studying in this college. 
                The college, which was earlier affiliated to the University of Madras, was affiliated to the 
                Bharathidasan University,Trichirappalli in the academic year 1982-83. 
 

                "A college degree is not a sign of a finished product but 
                    an indication a person is prepared for life"
                                                                      -Edward A. Malloy
            </font>
        </p>
    </body>
</html>
```
### school.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>School</title>
    </head>
    <body bgcolor="#FFF9E3">
        <h1 align="center">
            <font color="red"><b>Mannargudi</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Newtunkids International School</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
                Newtunkids International school is the school where I completed my primary classes.
                It is a private International school.The infrastructure of the campus is quite impressive.
                The teachers are very kind and take care of each and very student.
                They also teach other extra curricular activites such as dance, music, yoga and sports.
                The fees structure of the school is very genuine and affordable as compared to other
                international primary school.I thoroughly enjoyed my days while I was studying here.

                "Creativity is the key to success in the future,
                         and primary education is 
                    where teachers can bring creativity
                         in childrenat that level."
                                                  -Abdul kalam
            </font>
        </p>
    </body>
</html>
```
### AOoffice.html
```

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>AOoffice</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b>Mannargudi</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Agriculture Office</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
                In Mannargudi AOoffice is a new builed building.Our District head officers were decied to rise a 
                agriculture office in our city and make it is head of AOoffice to our district.
                The Agricultural Department has taken up the challenge to achieve higher growth rate in agriculture 
                by implementing several development schemes and also propagation of relevant technologies to step up the 
                production. Intensive Integrated Farming System NMSA, Massive Wasteland Development Programme,
                Mission on Sustainable Dry land Agriculture,Collective farming, Comprehensive watershed development activities,
                Water management through Micro Irrigation Systems, Soil health improvement through Bio-Fertilizer including 
                Green Manuring,Sustainable Sugarcane Initiative, Organic Farming,adoptation of Integrated Nutrient Management.

                Infra-structure Facilities:
                            Fertilizer Control Laboratory Thiruvarur (Mannargudi)
                            Soil Testing Laboratory Thiruvarur (Mannargudi)
                            Mobile Soil Testing Laboratory Thiruvarur (Mannargudi)
            </font>
        </p>
    </body>
</html>
```
### temple.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Temple</title>
    </head>
    <body bgcolor="#ADDFFF">
        <h1 align="center">
            <font color="red"><b>Mannargudi</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Mariyamman Kovil</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
                Asesham Mariyamman Kovil is temple where our mariyamman is living and blessing the disciples.
                Our mariyamman is also called as "GOD OF RAIN".In our city,this temple is consider as very ancient 
                and famous temple.Our farmers has a huge faith on this god for rain before they harvest.
                It is believed by the devotees that the Goddess has enormous powers over curing illnesses and hence, 
                it is a ritual to buy small metallic replicas,made with silver or steel, of various body parts that need 
                to be cured, and these are deposited in the donation box.The temple attracts thousands of devotees on Sundays,
                Tuesdays and Fridays, the holy days for Mariamman.
                

                "The Temple of our purest thoughts is silence"
                                                         -Sarah Josepha Hale
            </font>
        </p>
    </body>
</html>
```
### ground.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Ground</title>
    </head>
    <body bgcolor="#C3FDB8">
        <h1 align="center">
            <font color="red"><b>Mannargudi</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Findlay Higher Secondary School Ground</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Arial" size="5">
                It is a famous and huge playing ground in our city.This ground is owned by Findlay Higher Secondary school.
                At early morning old age people used to use this ground for walking,teenage people were used to play cricket,
                football,hockey.This ground is common to all the school students.Monthly once they conduct cricket,footbal 
                tournament or something else.At noon most of them used to learn driving in the ground. Most of the college
                 and school will conduct thier anual sports day in this ground.In that way this ground is very useful to 
                all the schools and colleges.


                "The world is your playground-play with a sense of density"
                                                                        -Edward Boyden
            </font>
        </p>
    </body>
</html>
```
## OUTPUT
### MAP
![Screenshot (90)](https://github.com/jeeva078/NearMe/assets/147048597/d4ea16eb-680b-4969-ba89-771b2cd946a0)



### SCHOOL
![image](https://github.com/jeeva078/NearMe/assets/147048597/795046e2-27e5-4efa-97c5-1ba0e0b487b6)
### COLLEGE
![image](https://github.com/jeeva078/NearMe/assets/147048597/c432e8bc-3c7b-4904-a41e-f364c03192ee)
### AOoffice
![image](https://github.com/jeeva078/NearMe/assets/147048597/bf7f9a9e-2700-4d91-abda-70e7ea6e4909)
### TEMPLE
![image](https://github.com/jeeva078/NearMe/assets/147048597/59bb4f6b-c9fa-4275-850e-3a6447195903)
### GROUND
![image](https://github.com/jeeva078/NearMe/assets/147048597/bd9faa75-9a6c-4ad5-a544-58a299f94df3)





## RESULT
The program for implementing image maps using HTML is executed successfully.
