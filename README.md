# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Clone the github repository into Theia IDE.

### Step 2:
Create a new Django project

### Step 3:
Write the needed HTML code.

### Step 4:
Run the Django server and execute the HTML files.

## Code:
```map.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Neyveli Township</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Sakthi Priya D (22008838)</b></font>
</h3>
<center>
<img src="/static/images/map.png" usemap="#MyCity" height="420" width="1100">
<map name="MyCity">
<area shape="circle" coords="200,60,30" href="/static/html/jhss.html" title="Jawahar Higher Secondary School,CBSE">
<area shape="rectangle" coords="250,67,260,60" href="/static/html/nlchospital.html" title="NLC General Hospital">
<area shape="circle" coords="400,350,50" href="/static/html/stadium.html" title="Bharathi Stadium">
<area shape="circle" coords="400,200,75" href="/static/html/theatre.html" title="Sri Ranga Theatre">
<area shape="rectangle" coords="460,150,870,320" href="/static/html/jb.html" title="Golden Jubilee Park">
</map>
</center>
</body>
</html>

stadium.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>RTO Office</title>
</head>
<body bgcolor="violet">
<h1 align="center">
<font color="red"><b>Neyveli Township</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Bharathi Stadium</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
Bharathi stadium in neyveli is the place where all the cultural
events take place.events for Republic day and independence day usually 
takes place here. students from various schools participate in the 
events like parade,drill,also some sports events. Prices will be given 
to the students for their active participation in variours activities.
Its a huge ground and a clean and green one.
</b>
</font>
</p>
</body>
</html>

theatre.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>RTO Office</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Neyveli Township</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Sri Ranga Theatre</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
Theatre Advertising in Sri Ranga Theatre, Thanthai Periyar Rd, Neyveli, Tamil Nadu offers a variety of both Onscreen Cinema Advertising and Off-screen Cinema Advertising, both of which are executed in a highly seamless manner. Having a total of 1 Screens in India, Sri Ranga Theatre, Thanthai Periyar Rd, Neyveli, Tamil Nadu caters to an audience of 714+ people per show. Present in a very suitable location, in majorIndia States, Sri Ranga Theatre, Thanthai Periyar Rd, Neyveli, Tamil Nadu is the preferred cinema for a majority of the population there, and attracts a wide recurring audience.Clubbed with the impressive execution of on-screen advertisement through, Cinema Advertising in Sri Ranga Theatre, Thanthai Periyar Rd, Neyveli, Tamil Nadu will ensure an Adv…
</b>
</font>
</p>
</body>
</html>

nlchospital.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>NLC general hospital</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Neyveli Township</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>NLC general hospital</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
<b>
NLC general hospital is a cleand and a hygienious hospital in neyveli.
The employees in the hospital treats the patients in a very good and humble manner.
The doctors are also very notable ones in the hospital.Well experienced doctors are 
taking care of the patients. For emergency there is 24 hours available casuality with 
doactors and nurses.Also 24 hrs ambulances are available.The management maintain the 
hospital in a good way. 
</b>
</font>
</p>
</body>
</html>

jhss.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Jawahar Hr. Sec. School</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Neyveli Township</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Jawahar Higher Secondary School,CBSE</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The main objectives of Jawahar Higher Secondary School ,CBSE are 
<ul>
<li>To impart proper and qualified training to teachers and give them an attractive salary and incentives so that they are not tempted to quit and look elsewhere for jobs.</li>
<li>To provide financial aids and grants wisely and judiciously.</li>
<li>To Frame of syllabus and curriculum.</li>
<li>To set aims and objectives of education.</li>
</ul>
</font>
</p>
</body>
</html>

park.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>Eco-Park</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Neyveli Township</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Golden Jubilee Park</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
A very nice park near Main Bazzar in Neyveli . It is located surrounding the bazzar. 
Very superb calm place in Neyveli. Best for walking. Nice playing place for kids.
Well maintained with jogging track. Source of ground water.
Good place play with children.Children enjoy playing in this park. 
Good sound and Air. Fountains in the park looks awesome.
Very nice place at Neyveli.
Simple and relax with play area.
</font>
</p>
</body>
</html>
```

## Output:
![Output](./screenshots/out1.png)

![Output](./screenshots/out2.png)

![Output](./screenshots/out3.png)

![Output](./screenshots/out4.png)

![Output](./screenshots/out5.png)

![Output](./screenshots/out6.png)

## HTML Validator
![HTML Validator](./screenshots/validate.png)



## Result:
THe program for implementing image map is executed successfully