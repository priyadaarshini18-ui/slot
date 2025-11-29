# Ex02 Time Table
## Date:26-11-2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<<html>
    <head>
        <title>slot Timetable</title>
    </head>
    <body>
        <center>
        <img src="/static/logo.png" height="100" width="600">
        </center>
        <br>
        <table align="center" width="600" cellspacing="2" cellpadding="4" border="6" bgcolor="pink">            
    <caption><b>SLOT TIME TABLE - PRIYADAARSHINI V(25013541)</b></caption>
        <tr align="center">
            <th bgcolor="purple">Date/Time</th>
            <th bgcolor="purple">Monday</th>
            <th bgcolor="purple">Tuesday</th>
            <th bgcolor="purple">Wednesday</th>
            <th bgcolor="purple">Thursday</th>
            <th bgcolor="purple">Friday</th>
            <th bgcolor="purple">saturday</th>
        </tr>
     <tr align="center">
            <td bgcolor="purple">8-10</td>
            <td>Free slot</td>
            <td>cp</td>
            <td>Free slot</td>
            <td>Free slot</td>
            <td>web</td>
            <td>ps</td>
        </tr>
        <tr align="center" >
            <td bgcolor="purple">10-12</td>
            <td>cp</td>
            <td>Free slot</td>
            <td>ps</td>
            <td>Free slot</td>
            <td>web</td>
            <td>web</td>
        </tr>
        <tr  align="center">
            <td bgcolor="purple">12-1</td>
            <td colspan="6" align="center">L U N C H</td>
        </tr>
        <tr align="center">
            <td bgcolor="purple">1-3</td>
            <td>web</td>
            <td>web</td>
            <td>MM</td>
            <td>ps</td>
            <td>Free slot</td>
            <td>ps</td>
        </tr>
        <tr align="center">
            <td bgcolor="purple">3-5</td>
            <td>Free slot</td>
            <td>cp</td>
            <td>cp</td>
            <td>cp</td>
            <td>Free slot</td>
            <td>Free slot</td> 
        </tr>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="6">
            <tr align="center">
                <th>s.no</th>
                <th>Subject Code</th>
                <th>Subject Name </th>
            </tr>
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI304</td>
                <td align="center">Fundamentals of c programming(cp)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19AI414</td>
                <td align="center">Fundamentals of web application development(web)</td>  
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19EN105</td>
                <td align="center">Public Speaking(ps)</td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">ECA-M</td>
                <td align="center">Mentor Meet(MM)</td>
            </tr>
            </table>
        </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (14).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
