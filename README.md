Ex04 Places Around Me
# Date:17.10.2025
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

# CODE
```
map.html

<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="magenta"><b>PANRUTI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>SUDHARSAN U(25010861)</b></font>
</h3>
<center>
<map name="MyCity">
<img src="Screenshot 2025-10-18 095547.png" usemap="#image-map">

<map name="image-map">
    <area target="_self" alt="temple" title="temple" href="C:\Users\Sudharsan\OneDrive\Desktop\exp  4 reatempt\Image_map\name\mapapp\static\temple.html" coords="903,139,1086,277" shape="rect">
    <area target="_self" alt="mahal" title=" mahal"href="C:\Users\Sudharsan\OneDrive\Desktop\exp  4 reatempt\Image_map\name\mapapp\static\mahal.html" coords="1112,290,1286,338" shape="rect">
    <area target="_self" alt="convention center" title="convention center" href="C:\Users\Sudharsan\OneDrive\Desktop\exp  4 reatempt\Image_map\name\mapapp\static\convention center.html" coords="5,360,195,526" shape="rect">
    <area target="_self" alt="garden restaurent" title="garden restaurent" href="C:\Users\Sudharsan\OneDrive\Desktop\exp  4 reatempt\Image_map\name\mapapp\static\garden restaurent.html" coords="439,460,608,522" shape="rect">
    <area target="_self" alt="turf court" title="turf court" href="C:\Users\Sudharsan\OneDrive\Desktop\exp  4 reatempt\Image_map\name\mapapp\static\turf court.html" coords="1146,170,1368,236" shape="rect">
</map>
</center>
</body>
</html>

mahal.html

<html>
<head>
<title>NKS mahal</title>
</head>
<body bgcolor="yellow">
<h3 align="center">
<font color="red"><b>NKS mahal</b></font>
</h3>
<hr size="8" color="red">
<p align="justify">
<font face="Georgia" size="10">
 NKS Mahal in panruti appears to be a wedding and event venue with air-conditioned halls, ample parking, and facilities for decorations, catering, and other event needs. The venue aims to provide a seamless experience for events like marriages, with dedicated staff and various amenities to assist with planning and execution. It is highlighted as a stunning and technologically advanced venue for various celebrations. 
</p>
</body>
</html>


temple.html

<html>
<head>
<title>sri saranarayana perumal</title>
</head>
<body bgcolor="lightgreen">
<h3 align="center">
<font color="red"><b>sri saranarayana perumal</b></font>
</h3>
<hr size="8" color="red">
<p align="justify">
<font face="Georgia" size="10">
 A"sri saranarayana perumal temple" refers to a temple dedicated to Lord saranarayana , a form of the Hindu deity Lord Vishnu. While the most famous is the sri saranarayana perumal Temple on panruti, many other temples with the same deity, or local variations, exist throughout India, including the sri saranarayana perumal Temple in panruti. These temples are significant places of worship for devotees of Lord Vishnu and often feature intricate architecture, religious rituals, and festivals celebrating various aspects of Hinduism.
</p>
</body>
</html>


covention center.html

<html>
<head>
<title>RKM CONVENTION CENTER</title>
</head>
<body bgcolor="white">
<h3 align="center">
<font color="red"><b>RKM CONVENTION CENTER</b></font>
</h3>
<hr size="8" color="red">
<p align="justify">
<font face="Georgia" size="10">
A convention center (American English; or conference centre in British English) in panruti is a large building that is designed to hold a convention, where individuals and groups gather to promote and share common interests. Convention centers typically offer ample floor space for exhibits, meeting rooms, and auditoriums to accommodate various events such as trade shows, professional conferences, and public exhibitions. They are often equipped with modern amenities, including audio-visual technology, catering services, and accessibility features to support the needs of attendees and organizers.
</p>
</body>
</html>

garden retaurent.html

<html>
<head>
<title>ALEEF GARDEN RESTAURENT</title>
</head>
<body bgcolor="lightblue">
<h3 align="center">
<font color="red"><b>ALEEF GARDEN RESTAURENT</b></font>
</h3>
<hr size="4" color="red">
<p align="justify">
<font face="Georgia" size="10">
Aleef Garden Restaurant in panruti is known for its diverse menu featuring Indian, Chinese, and continental cuisines. The restaurant offers a pleasant dining atmosphere with both indoor and outdoor seating options. It is popular for its flavorful dishes, friendly service, and reasonable prices, making it a favored spot for locals and visitors alike to enjoy a good meal.    
</p>
</body>

turf court.html

<html>
<head>
<title>PAVILION TURF COURT</title>
</head>
<body bgcolor="silver">
<h3 align="center">
<font color="red"><b>PAVILION TURF COURT/b></font>
</h3>
<hr size="8" color="red">
<p align="justify">
<font face="Georgia" size="10">
 pavilion turf grounds in panruti are engineered surfaces that offer consistent playing conditions year-round. They are known for their durability, versatility, and low maintenance, which makes them especially popular for both professional and amateur sports.
</p>
</body>
</html>


```
# OUTPUT

<img width="1904" height="924" alt="image" src="https://github.com/user-attachments/assets/6f7b0107-1b74-4cd6-b0d3-ad455c6a9672" />
<img width="1900" height="883" alt="image" src="https://github.com/user-attachments/assets/a2498308-9ddc-4506-98f0-0dc589f27f93" />
<img width="1906" height="854" alt="image" src="https://github.com/user-attachments/assets/367b1655-e8cf-439a-b38d-f20a36be34f0" />
<img width="1907" height="705" alt="image" src="https://github.com/user-attachments/assets/1a934457-ec27-4c7c-9a46-dd8001b974b5" />
<img width="1914" height="855" alt="image" src="https://github.com/user-attachments/assets/81a9305c-1758-40f5-a278-0f42abd7afa2" />






# RESULT
The program for implementing image maps using HTML is executed successfully.
