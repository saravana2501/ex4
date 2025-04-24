# Ex04 Places Around Me
## Date: 24.04.2025

NAME : SARAVANA KUMAR S 

REG NO : 212224220090

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

map.htmal
<!Doctype html>
 <html>
    <body>
<img src="map.png" usemap="#image-map">
<map name="image-map">
    <area shape="rect" target="_self" alt="my home" title="my home" href="home.html" coords="937,458,1064,575" >
    <area target="_self" alt="ashokpillar" title="ashokpillar" href="ashokpillar.html" coords="1005,890,40" shape="circle">
    <area target="_self" alt="santhome church" title="santhome church" href="santhome.html" coords="1514,890,43" shape="circle">
    <area target="_self" alt="marina beach" title="marina beach" href="marinabeach.html" coords="1541,768,37" shape="circle">
    <area target="_self" alt="kaalikambal temple" title="kaalikambal temple" href="kaalikambal.html" coords="1597,406,46" shape="circle">
    <area target="_self" alt="semozhipoonga" title="semozhipoonga" href="semozhipoonga.html" coords="1301,757,33" shape="circle">
    <area target="_self" alt="koyambedu" title="koyambedu" href="koyambedu.html" coords="874,636,35" shape="circle">
    <area target="_self" alt="egmore" title="egmore" href="egmore.html" coords="1386,565,41" shape="circle">
    <area target="_self" alt="n4 beach" title="n4 beach" href="n4beach.html" coords="1714,131,33" shape="circle">
</map>
</body>
</html>


marinabeach.html
<html>
<head><title>Marina Beach</title></head>
<body bgcolor="LightBlue">
<h1 align="center"><font color="DarkBlue"><b>CHENNAI</b></font></h1>
<h3 align="center"><font color="DarkBlue"><b>Marina Beach</b></font></h3>
<hr size="3" color="White">
<p align="justify"><font face="Georgia" size="3">
    Marina Beach is one of the most iconic landmarks of Chennai and holds the title of being the longest natural urban beach in India, stretching over 13 kilometers along the Bay of Bengal. It is not only a scenic coastal attraction but also a cultural and historical symbol of the city. Every morning and evening, thousands of locals and tourists gather here to enjoy the sea breeze, golden sands, and breathtaking sunrises and sunsets. The beach is lined with historical statues, memorials, and food stalls selling local treats like sundal and murukku. Marina Beach also hosts many public events and festivals, adding to its vibrant atmosphere. Nearby attractions include the famous Anna Memorial, MGR Memorial, and the Chennai Lighthouse. Whether for a quiet walk, a family outing, or a lively local experience, Marina Beach is a must-visit spot in Chennai.
</font></p>
</body>
</html>


n4beach.html
<center>
    <h2><font face="Georgia" color="#003366">N4 Beach</font></h2>
    <p><font face="Georgia" size="3">
      N4 Beach, located in the northern part of Chennai near Kasimedu, is a serene and lesser-known coastal spot. Unlike the bustling Marina Beach, N4 Beach offers a peaceful environment, mostly visited by local fishermen and residents. It provides beautiful views of the sunrise and is a perfect place for early morning walks. The beach is close to the fishing harbor, giving visitors a chance to see traditional fishing boats and daily fish markets in action. N4 Beach is also known for its scenic beauty and proximity to local seafood stalls. It may not be a tourist hotspot, but its simplicity and charm attract those who enjoy quiet coastal experiences. The beach plays a key role in the lives of nearby fishing communities and reflects the hardworking spirit of Chennai’s coastal culture.
    </font></p>
  </center>


egmore.html
<center>
    <h2><font face="Georgia" color="#003366">Egmore Government Museum</font></h2>
    <p><font face="Georgia" size="3">
      The Egmore Government Museum is the second oldest museum in India, established in 1851. It is located in the heart of Chennai and is known for its Indo-Saracenic style buildings. The museum has various sections such as archaeology, anthropology, numismatics, and natural history. Its bronze gallery has a world-famous collection of Chola bronzes. The museum complex also houses the National Art Gallery, showcasing classical paintings and sculptures. The children’s museum is a fun and educational spot for kids. Visitors can learn about ancient Tamil culture, tools, pottery, and fossils. The museum is surrounded by a peaceful garden with statues and shady paths. It is a favorite destination for students, researchers, and history lovers. Egmore Museum is a treasure chest of India’s cultural and historical wealth.
    </font></p>
  </center>


koyambedu.html
<center>
    <h2><font face="Georgia" color="#003366">Koyambedu</font></h2>
    <p><font face="Georgia" size="3">
      Koyambedu is a major commercial and transportation hub in Chennai, best known for housing one of Asia’s largest wholesale markets. The Koyambedu Market is famous for its vast supply of fruits, vegetables, and flowers, catering to vendors and businesses across Tamil Nadu. It is always buzzing with activity, especially in the early morning hours. Koyambedu is also home to the Chennai Mofussil Bus Terminus (CMBT), one of the largest bus stations in South Asia. This makes it a key point for travelers commuting to various parts of Tamil Nadu and neighboring states. The area is surrounded by shopping complexes, hotels, and residential buildings. With its excellent connectivity and commercial significance, Koyambedu plays a vital role in the daily life of Chennai’s citizens. It represents the city's fast-paced, dynamic character and economic strength.
    </font></p>
  </center>
  

```

## OUTPUT

![Screenshot 2025-04-22 122908](https://github.com/user-attachments/assets/d32083b5-1a04-4700-91f7-964a447af27a)


![Screenshot 2025-04-22 123004](https://github.com/user-attachments/assets/efbd9447-e88b-407e-90c0-1be50d1456d1)


![Screenshot 2025-04-22 123317](https://github.com/user-attachments/assets/a2d8b8e6-dd69-47a0-9420-6348a59451dc)


![Screenshot 2025-04-22 122941](https://github.com/user-attachments/assets/9cb10834-4058-461d-b094-09759816d126)


![Screenshot 2025-04-22 122929](https://github.com/user-attachments/assets/95ffef3a-b42e-4f3a-b79f-57be4a5fea17)

## RESULT
The program for implementing image maps using HTML is executed successfully.
