# Ex03 Time Table
## Date:18.03.2024

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <head>
        <title>My Time Table</title>
    </head>
    <body>
        <img src="logo.png" height="200" width="1200"
        <table border="4" cellspacing="9" cellpadding="6" width="540" height="100">
        <caption><b> SLOT TIME TABLE-SANTHA RAMANATH M (212223220097)</b></caption>
        <tr>
            <th bgcolor="green">DAY/TIME</th>
            <th bgcolor="green">MONDAY</th>
            <th bgcolor="green">TUESDAY</th>
            <th bgcolor="green">WEDNESDAY</th> 
            <th bgcolor="green">THURSDAY</th>
            <th bgcolor="green">FRIDAY</th>
            <th bgcolor="green">SATURDAY</th>      
        </tr>
        <tr>
            <td bgcolor="green">8-10</td>
            <td bgcolor="pink">DE</td>
            <td bgcolor="pink">ML</td>
            <td bgcolor="pink">FREE</td>
            <td bgcolor="pink">FREE</td>
            <td bgcolor="pink">FWAD</td>
            <td bgcolor="pink">ML</td>
        </tr>
        <tr>
            <td bgcolor="green">10-12</td>
            <td bgcolor="pink">FREE</td>
            <td bgcolor="pink">FREE</td>
            <td bgcolor="pink">PQM</td>
            <td bgcolor="pink">CS</td>
            <td bgcolor="pink">PYTHON</td>
            <td bgcolor="pink">OS</td>
        </tr>
        <tr>
            <td bgcolor="green">12-01</td>
            <td rowspan="6" bgcolor="pink" align="center">LUNCH</td>
        </tr>
        <tr>
            <td bgcolor="green">01-03</td>
            <td bgcolor="pink">CHEM</td>
            <td bgcolor="pink">FWAD</td>
            <td bgcolor="pink">FREE</td>
            <td bgcolor="pink">FWAD</td>
            <td bgcolor="pink">DE</td>
            <td bgcolor="pink">PQM</td>
        </tr>
        <tr>
            <td bgcolor="green">03-05</td>
            <td bgcolor="pink">OS</td>
            <td bgcolor="pink">FREE</td>
            <td bgcolor="pink">FREE</td>
            <td bgcolor="pink">PYTHON</td>
            <td bgcolor="pink">FREE</td>
            <td bgcolor="pink">CHEM</td>
        </tr>
        </table>
        <table align="left" border="2" cellspacing="2" cellpadding="4">
            <tr>
                <td>S.NO</td>
                <td>SUBJECT CODE</td>
                <td>SUBJECT NAME</td>
            </tr>
            <tr>
                <td>01.</td>
                <td>22HS102</td>
                <td>TAMILS AND TECHNOLOGY</td>
            </tr>
            <tr>
                <td>02.</td>
                <td>19MA222</td>
                <td>PROBABILITY AND QUEUEING MODELS</td>
            </tr>
            <tr>
                <td>03.</td>
                <td>19EY702</td>
                <td>CREATIVE SKILL FOR COMMUNICATION</td>
            </tr>
            <tr>
                <td>04.</td>
                <td>19EE404</td>
                <td>DIGITAL ELECTRONICS</td>
            </tr>
            <tr>
                <td>05.</td>
                <td>19CY205</td>
                <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
            </tr>
            <tr>
                <td>06.</td>
                <td>19CS405</td>
                <td>OPERATING SYSTEM</td>
            </tr>    
            <tr>
                <td>07.</td>
                <td>19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            </tr>
            <tr>
                <td>08.</td>
                <td>19AI410</td>
                <td>INTRODUCTION TO MACHINE LEARNING</td>
            </tr>
            <tr>
                <td>09.</td>
                <td>19AI301</td>
                <td>PYTHON PROGRAMMING</td>
            </tr>
        </table>

    </body>

```

## OUTPUT
![alt text](<Screenshot 2024-03-19 150639.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
