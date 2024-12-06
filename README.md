# Ex04 Places Around Me
## Date: 06-12-2024

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
<html>
    <head>
        <title>VILLUPURAM</title>
    </head>
    <body>
        <div style="text-align: center;">
        <h1> Explore My Neighbourhood</h1>
        <h2> Please click any of the pictures in the middle to know more about it</h2>
        
            <div style="text-align: center;">
            <img src="C:\Users\admin\NearMe\myarea\mapapp\static\vpm map.png" alt=""  usemap="#Landmark" style="width: fit-content;">
            </div>
         <map name="Landmark">
            <area shape="circle" coords="640,155,9" title="JANAS cinemas" href="C:\Users\admin\NearMe\myarea\mapapp\static\janas.html">
            <area shape="circle" coords="1197,64,2" title="Arignar Anna Government arts college " href="C:\Users\admin\NearMe\myarea\mapapp\static\govtcollege.html">
            <area shape="circle" coords="168,802,8" title="Theivanai Ammal College for Women(Autonomous)" href="C:\Users\admin\NearMe\myarea\mapapp\static\autonomouscollege.html">
            <area shape="circle" coords="835,104,4" title="Villupuram Railway Junction" href="C:\Users\admin\NearMe\myarea\mapapp\static\railway.html">
            <area shape="circle" coords="216,506,8" title="Villupuram New Bus Stand" href="C:\Users\admin\NearMe\myarea\mapapp\static\busstand.html">
         </map>
        </div>
    </body>
</html>



janas.html

<html>
    <title>JANAS CINEMAS</title>
    <body style="background-color: rgb(223, 104, 201);">
        <div style="text-align: center;">
            <h1 style="font-style: oblique;">JANAS CINEMAS</h1><br><br>
    <img src="C:\Users\admin\NearMe\myarea\mapapp\static\janas.img.png">
    
        <center>
            Janas Cinemas is a popular movie theater located in Villupuram, Tamil Nadu, offering an excellent cinematic experience for local residents and visitors. Known for its modern infrastructure, the theater features advanced projection and sound systems, ensuring a high-quality viewing experience for its audience. It screens the latest Tamil, Telugu, Hindi, and occasionally English movies, catering to diverse preferences.<br><br>

            The theater is designed with comfortable seating, air-conditioned halls, and ample legroom to provide a pleasant experience for moviegoers. It also has an efficient online and offline ticket booking system, making it convenient for customers to secure their seats. The premises include a snack counter offering a variety of refreshments, adding to the overall entertainment experience.<br><br>

            Located in a prime area of Villupuram, Janas Cinemas is easily accessible and has sufficient parking facilities. The theater is well-regarded for maintaining cleanliness and adhering to safety standards. Its commitment to providing affordable entertainment combined with top-notch amenities has made it a favorite destination for cinema enthusiasts in and around Villupuram.<br><br>
        <h1>Jana’s Cinemas – 7D Entertainment</h1>
        Jana’s Cinemas – 7D Entertainment in Villupuram

        <h1>Phone No</h1>
        +91 82207 56789<br><br>

        <h1>Email</h1>
        info@maghalakshmiplaazaa.in<br><br>

        <h1>Address</h1>
        716, 2nd Floor, Nehruji Road, Mandhakarai, Viluppuram, Tamil Nadu 605602<br><br>
        </center>
    </div>
    </body>
</html>


railway.html

<html>
    <title>RAIMWAY JUNCTION</title>
    <body style="background-color:rgb(171, 126, 126);">
        <div style="text-align: center;">
            <H1 style="font-style: oblique;"> VILLUPURAM RAILWAY JUNCTION </H1><br><br>
    <img src="C:\Users\admin\NearMe\myarea\mapapp\static\VPM JUNCTION 1.png" width="49%">
    <img src="C:\Users\admin\NearMe\myarea\mapapp\static\VPM JUNCTION 2.png" width="50%">
        <center>
        <body>Villupuram Railway Junction, located in Tamil Nadu, India, is one of the oldest and most prominent railway stations in the state. It serves as a vital hub connecting the southern railway network, linking major cities like Chennai, Tiruchirappalli, Madurai, and Salem. The station falls under the jurisdiction of the Southern Railway zone and has a rich history, being operational since the late 19th century.<br><br>

            The junction has six platforms and is equipped with modern amenities such as waiting rooms, a ticketing office, refreshment stalls, and digital information boards. It is also an important stop for numerous express and passenger trains, playing a critical role in facilitating transportation for commuters and goods alike.<br><br>
            
            Villupuram Junction is strategically significant as it connects key rail lines leading to the southern, western, and northern parts of Tamil Nadu and neighboring states. The station is well-maintained, with clean premises and good passenger facilities, making it a preferred transit point for travelers. Its proximity to the cultural and historical landmarks of Tamil Nadu further enhances its importance as a gateway for tourism.<br><br>
        </body>
    </center>
    </div>
    </body>
</html>


govtcollege.html

<html>
    <title>Arignar Anna Government Arts College</title>
    <body style="background-color: rgba(22, 128, 92, 0.821);">
        <div style="text-align: center;">
            <h1 style="font-style: inherit; ">Arignar Anna Government Arts College</h1><br><br>
    <img src="C:\Users\admin\NearMe\myarea\mapapp\static\govt college.png">
    
        <center>
            Arignar Anna Government Arts College, located in Villupuram, Tamil Nadu, is a renowned institution named after Arignar Anna, a prominent leader and former Chief Minister of Tamil Nadu. Established in 1968, the college serves as a hub for higher education in the region, offering a variety of undergraduate and postgraduate programs in arts, science, and commerce. The institution is affiliated with Thiruvalluvar University and adheres to the principles of inclusive and affordable education.<br><br>

            The campus is well-equipped with essential facilities, including spacious classrooms, a library with a diverse collection of books and journals, laboratories for practical learning, and sports facilities to encourage physical activities. It provides an ideal environment for students to excel academically and personally.<br><br>
            
            Arignar Anna Government Arts College emphasizes academic excellence, cultural development, and community service. The faculty members are highly qualified and dedicated to nurturing students’ talents and preparing them for the competitive world. The college also conducts seminars, workshops, and extracurricular activities to enhance students' overall development.<br><br>
            
            Over the years, the college has contributed significantly to the educational and socio-economic upliftment of the local community. It continues to uphold its mission of providing quality education, fostering innovation, and instilling values among its students<br><br>
    </center>
    </div>
    </body>
</html>


autonomouscollege.html

<html>
    <title>Theivanai Ammal College for Women</title>
    <body style="background-color:rgb(69, 148, 29);">
        <div style="text-align: center;">
            <h1 style="font-style: normal;">Theivanai Ammal College for Women(Autonomous)</h1><br><br>
    <img src="C:\Users\admin\NearMe\myarea\mapapp\static\tacw 1.png" width="50%">
    <img src="C:\Users\admin\NearMe\myarea\mapapp\static\tawc 2.png" width="50%" >
    
        <center>
            Theivanai Ammal College for Women, located in Villupuram, Tamil Nadu, is a prominent institution dedicated to empowering women through quality education. Established in 1989 by the E. S. Educational Charities, the college aims to provide higher education opportunities to women, particularly those from rural and underprivileged backgrounds. The institution is affiliated with Annamalai University and offers a wide range of undergraduate, postgraduate, and diploma courses in arts, science, commerce, and management.<br><br>

            The college is known for its serene campus equipped with state-of-the-art infrastructure. Facilities include modern classrooms, well-equipped laboratories, a comprehensive library, computer centers, and hostel accommodations. Additionally, the institution fosters extracurricular and co-curricular activities, providing platforms for students to explore their talents in sports, cultural events, and academic competitions.<br><br>
            
            Theivanai Ammal College focuses on holistic development, blending academic rigor with value-based education. The faculty is highly qualified and committed to nurturing students' intellectual, emotional, and social growth. The college organizes seminars, workshops, and guest lectures to keep students updated with contemporary knowledge and skills.<br><br>
            
            With a strong emphasis on women's empowerment, the institution encourages leadership, self-reliance, and community engagement among its students. Over the years, Theivanai Ammal College has played a vital role in transforming the lives of countless women, equipping them with the skills and confidence to excel in various fields and contribute to society effectively.<br><br>
    </center>
    </div>
    <h1>FOR FURTHER DETAILS</h1>
    <a href="https://www.tacw.in/">visit</a>
    </body>
</html>


busstand.html

<html>
    <title>Villupuram Bus Stand</title>
    <body style="background-color: rgb(14, 120, 152);">
        <div style="text-align: center;">
            <h1 style="font-style: italic;">Villupuram New Bus Stand</h1>

    <img src="C:\Users\admin\NearMe\myarea\mapapp\static\vpm bus stand.png">
    
        <center>
             Villupuram New Bus Stand, located in the heart of Villupuram town in Tamil Nadu, is a major transportation hub connecting various cities and towns across the state and neighboring states. It is one of the busiest bus terminals in the region, catering to thousands of passengers daily. The bus stand operates under the Tamil Nadu State Transport Corporation (TNSTC) and serves as a vital link for commuters traveling to Chennai, Puducherry, Trichy, Madurai, and other key destinations.<br><br>

            The facility is well-organized, with multiple bays for buses, a spacious waiting area, ticket counters, and essential amenities such as restrooms, food stalls, and shops. It operates both government and private bus services, including regular, express, and deluxe buses.<br><br>
            
            Villupuram New Bus Stand is known for its strategic location, as Villupuram serves as a major junction connecting the northern, southern, and western parts of Tamil Nadu. Its efficient operation and connectivity make it a critical part of the town’s infrastructure, supporting the daily commute and economic activities of the region.<br><br>
            
            The Villupuram New Bus Stand also provides seamless connectivity to nearby tourist attractions such as Gingee Fort, Thiruvakkarai Fossil Park, and Auroville in Puducherry, making it a key transit point for travelers. The terminal is well-maintained, ensuring cleanliness and safety for passengers. It has digital boards displaying bus schedules and routes for better convenience. Additionally, the bus stand plays a significant role in supporting local businesses, as many vendors and shops thrive on the bustling passenger traffic. With ongoing improvements and upgrades, Villupuram Bus Stand continues to be a reliable and essential hub for public transportation in the region.<br><br>
    </center>
    </div>
    </body>
</html>

```


## OUTPUT
![alt text](<myarea/imgmap map.png>)

![alt text](<myarea/imgmap janas.png>)

![alt text](<myarea/imgmap junction.png>)

![alt text](<myarea/imgmap govt.png>)

![alt text](<myarea/imgmap auto college.png>)

![alt text](<myarea/imgmap bus.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
