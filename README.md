# Ex04 Places Around Me
## Date: 18.11.2023

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
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="purple"><b>VIRUDHUNAGAR</b></font>
</h1>
<h3 align="center">
<font color="red"><b>HEMA LOKITHA P(23007550)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords= "700,250,850,400" href="home.html" title="My Home Town">
<area shape="circle" coords= "200,440,100" href="rajapalayam.html" title="rajapalayam">
<area shape="circle" coords= "590,450,30" href="sivakasi.html" title="sivakasi">
<area shape="circle" coords= "1120,50,40" href="madurai.html" title="Madurai">
<area shape="circle" coords= "450,320,100" href="srivilliputhur.html" title="Krishankovil">

</map>
</center>
</body>
</html>

home.html
<html>
    <head>
        <title>My Home Town</title>
    </head>
<body bgcolor="red">
<h1 align="center">
    <font color="yellow"><b>VIRUDHUNAGAR</b></font>
</h1>
   <h3 align="center">
    <font color="blue"><b>VIRUDHUNAGAR</b></font>
   </h3>
<hr color="black" size="3">
<p align=""justify">
<font face="Georgia" size="5">
Virudhunagar District is a district (an administrative district) of Tamil Nadu state in south India.     Virudhunagar is the district headquarters of Virudhunagar district.
 Virudhunagar district was formed by the separation of Old Ramanathapuram District in 1987 into Ramanathapuram District, Sivagangai District and the west part as Virudhunagar District. 
 Virudhunagar District was formerly called Karmavirer Kamarajar District. As of 2011, Virudhunagar district had a population of 1,942,288 with a sex-ratio of 1,007 females for every 1,000 males. 
Sivakasi is the most populous and largest city in the district.
</font></p>
</body>
</html>

madurai.html
<html>
    <head>
        <title>My Home Town</title>
    </head>
<body bgcolor="pink">
<h1 align="center">
    <font color="charcoal"><b>MADURAI</b></font>
</h1>
<hr color="black" size="3">
<p align=""justify">
<font face="Georgia" size="5">
    Madurai is called by various nicknames like Athens of the East, Thoonga Nagaram (City that never Sleeps), Naan maada koodal (City of Four junctions), Malligai Managar (City of Jasmine), Koodal Managar (City of Junction) Koil Nagar (Temple city), etc.
     The main kingdoms which ruled Madurai during various times are the Pandyas and the Nayaks.
    The district is bounded by Theni in the west, Sivaganga in the east, Dindigul in the north, Virudhunagar in the south and small parts of Tiruchirappalli in the northeast. 
    Madurai district witnessing hot and humid weather throughout the year and considered as hottest district of Tamil Nadu as well hottest city.
    Climate
</font></p>
</body>
</html>

rajapalayam.html
<html>
    <head>
        <title>My Home Town</title>
    </head>
<body bgcolor="purple">
    <h1 align="center">
        <font color="yellow"><b>VIRUDHUNAGAR</b></font>
    </h1>
<h3 align="center">
    <font color="yellow"><b>RAJAPALAYAM</b></font>
</h3>
  
<hr color="black" size="3">
<p align=""justify">
<font face="Georgia" size="5">
    Rajapalayam  is a town in the Indian state of Tamil Nadu. It is the largest municipality in the Virudhunagar district[citation needed]. Rajapalayam is located on the Madurai to Quilon National Highway at a distance of 562 km south of the state capital Chennai. The economy is primarily industrial with several mills for spinning and weaving. The town is known for its mango and the Rajapalayam breed of dogs.
    The principal industry was initially agriculture. In 1936, Thiru P. A. C. Ramasamy Raja started the first cotton spinning mill, called Rajapalayam Mills Ltd. Later, more textile mills were started. Today, Rajapalayam is a major hub of the textile industry, famous for bandages, woven fabric, nightwear, and other products.
     The neighboring town of Chatrapatti (Virudhunagar Dist.) is a large player in producing surgical cotton gauze, and nearby Dhalavaipuram and Muhavoor manufacture women's nightwear.
</font></p>
</body>
</html>

sivakasi.html
<html>
    <head>
        <title>My Home Town</title>
    </head>
<body bgcolor="grey">
    <h1 align="center">
        <font color="yellow"><b>VIRUDHUNAGAR</b></font>
    </h1>
<h3 align="center">
    <font color="white"><b>SIVAKASI</b></font>
</h3>
   
<hr color="black" size="3">
<p align=""justify">
<font face="Georgia" size="5">
    Sivakasi is a city in Virudhunagar District in the Indian state of Tamil Nadu. The city is known for firecrackers and match factories that produce 70% of the country's produce. The printing industries in Sivakasi produce 30% of the total diaries produced in India. The industries in Sivakasi employ over 25,000 people and the estimated turnover of the firecracker, match making and printing industries in the city is around ₹20 billion (US$250 million). The major issues in the city are the frequent accidents in the firecracker factories and the high level of child labour.

    Sivakasi was established in the 15th century during the reign of the Pandya king Harikesari Parakkirama Pandian. The city was a part of Madurai and has been ruled at various times by Later Pandyas, Vijayanagar Empire, Madurai Nayaks, Chanda Sahib, Carnatic kingdom and the British. A major riot during the British Raj took place in 1899.
    tivals constitute the major festivals of the city. AJ and Hatsun Indoor Stadium has a coaching center for badminton and is the major sporting venue of the city. Sivakasi is a part of Sivakasi constituency and elects its member of legislative assembly every five years, and a part of the Virudhunagar constituency that elects its member of parliament. Sivakasi is locally administered by a municipal corporation which covers an area of 6.8 km2 (2.6 sq mi). Roadways is the major mode of transport to the city, while it has also got rail connectivity. As of 2021, Sivakasi has a population of 260,047.
    
    Sivakasi has a dry weather, making it suitable for dry crops like cotton, chillies and millets. Badhrkali Amman temple is the most prominent landmark of Sivakasi, and the temple fes
    
</font></p>
</body>
</html>

srivilliputhur.html
<html>
    <head>
        <title>My Home Town</title>
    </head>
<body bgcolor="blue">
    <h1 align="center">
        <font color="yellow"><b>VIRUDHUNAGAR</b></font>
    </h1>
<h3 align="center">
    <font color="white"><b>Krishankovil</b></font>
</h3>
<hr color="black" size="3">
<p align=""justify">
<font face="Georgia" size="5">
    The history of Srivilliputhur centres around the Srivilliputhur Temple, dedicated to Andal (8th century or earlier),[4] the only female Alvar of the 12 Alvar saints of South India. 
    She is credited with the Tamil works of Thirupavai and Nachiar Tirumozhi that are still recited by devotees during the Winter festival season of Margazhi. Andal is known for her unwavering devotion to god Vishnu, the God of the Srivaishnavas. Adopted by her father, the Alvar saint Periyalvar who found her as a baby, Andal avoided earthly marriage, the normal and expected path for women of her culture, to "marry" Vishnu, both spiritually and physically.
     In many places in India, particularly in Tamil Nadu, Andal is treated more than a saint and as a form of god herself and a shrine for Andal is dedicated in most Vishnu temples.
</font></p>
</body>
</html>

```

## OUTPUT
![Alt text](1.png)
![Alt text](2.png)
![Alt text](3.png)
![Alt text](4.png)
![Alt text](5.png)
![Alt text](6.png)

## RESULT
The program for implementing image maps using HTML is executed successfully.
