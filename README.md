# Ex03 Time Table
## Date:29/04/2024

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
        <title>
            Rohan's page  
        </title>
      
    </head>
    <body>
        <center>
        <img src="https://github.com/Rohanjeyachandiran/slot/blob/main/logo.png?raw=true" width="600" height="100">
        <h2> SLOT TIME TABLE ROHAN(212223040171)</h2>

        <table border="5" bgcolor="BLUE" >
            <tr bgcolor="red">
                <th>day/time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>saturday</th>
            </tr>
            <tr>
                <td bgcolor="red">8-10</td>
                <td bgcolor="yellow">FWAD</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                <td>os</td>
            </tr>
            <tr>
                <td bgcolor="red">10-12</td>
                <td>-</td>
                <td>computer networks</td>
                <td>soft skills</td>
                <td>computer networks</td>
                <td>FWAD</td>
                <td>-</td>
            </tr>
            <tr>
                <td bgcolor="red">1-3</td>
                <td>logics and combinatorics</td>
                <td>-</td>
                <td>-</td>
                <td bgcolor="yellow">FWAD</td>
                <td bgcolor="yellow">FWAD</td>
                <td>-</td>
            </tr>
            <tr>
                <td bgcolor="red" >3-5</td>
                <td>c programming</td>
                <td>-</td>
                <td>-</td>
                <td>os</td>
                <td>logics and combinatorics</td>
                <td>-</td>
            </tr>
           
           
        </table>
        <br>
        <br>
        <table border="5" bgcolor="88ffcc">
            <tr>
                <th>S.No.</th>
                <th>Subject code</th>
                <th>Subject name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td><font color="b1a7b1">Fundamental of Web Applications Development(FWAD)</font></td>
            </tr>
            <tr>
                <td>2</td>
                <td>19CS405</td>
                <td>operating system(os)</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19CS406</td>
                <td>computer networks(cn)</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19EY702</td>
                <td>creative skills for communication(cs)</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19MA206</td>
                <td>logics and combinatroics(maths)</td>
            </tr>
            <tr>
                <td>6</td>
                <td>19AI304</td>
                <td>Fundamentals of C programming</td>
            </tr>
            <tr>
                <td>7</td>
                <td>19MC802</td>
                <td>Environment Science</td>
            </tr>
            <tr>
                <td>8</td>
                <td>ECA-M</td>
                <td>Mentor Meeting</td>
            </tr>
            <tr>
                <td>09</td>
                <td>19HS102</td>
                <td>tamil and technology</td>
            </tr>
        </table>
    </center>
    </body>
</html>
```


## OUTPUT
![WhatsApp Image 2024-04-29 at 09 11 43_7c71d26d](https://github.com/Rohanjeyachandiran/slot/assets/161102491/6756f8d9-fd23-45be-9d45-60c5c45b287c)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
