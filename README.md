# Ex04 Places Around Me
# Date:02/11/2024
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <header>
        <h1>places around me</h1>
    </header>
    <main>
        <img src="C:\Users\admin\Pictures\Screenshots\Screenshot (2).png" title="map places" usemap="#places-map">
        <map name="places-map">
            <area shape="react" coords="552,152,638,223" href=" title="thillai natarajar kovil"/>
            <area shape="react" coords="711,231,768,288"href="C:\Users\admin\Downloads\axis bank.html" title="axis bank"/>
            <area shape="react" coords="635,93,679,148"href="C:\Users\admin\Downloads\hotel.jpg" title="anandha bavan"/>
            <area shape="react" coords="848,375,897,429"href="C:\Users\admin\Downloads\railway station.jpg" title="Railway station"/>
            <area shape="react" coords="834,499,875,548"href="C:\Users\admin\Downloads\resort.jpg"title="Farm resort"/>
            </map>
</body>
</html>
~~~
# OUTPUT:
![Screenshot (24)](https://github.com/user-attachments/assets/d390a199-1250-48a0-9a9b-b27098fa5666)
![Screenshot (26)](https://github.com/user-attachments/assets/11a1aa58-209c-4217-9134-f9bddb4dd4a8)
![Screenshot (25)](https://github.com/user-attachments/assets/2970468c-3015-4b93-99af-26201a313a72)
![Screenshot (28)](https://github.com/user-attachments/assets/bbaa206b-7a1c-41bf-aa50-ef4327d5f91e)
![Screenshot (27)](https://github.com/user-attachments/assets/c321a184-f7eb-486e-8443-af19176eae44)
![Screenshot (29)](https://github.com/user-attachments/assets/c6600140-cc38-4bd7-91ef-4849bcca550d)

# RESULT
The program for implementing image maps using HTML is executed successfully.
