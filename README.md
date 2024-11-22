# Ex03 Time Table
## Date:15\11\2024

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
<body>
    <img src="\static\logo.png" height="150" width="900">
<table border="2" cellspacing="2" cellpadding="2">
    <caption>TimeTable Devika 24002534</caption>
    <tr bgcolor="yellow">
        <th>Date/Time</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
        <th>Saturday</th>
    </tr>
    <tr>
        <td bgcolor="yellow">8-10</td>
        <td>Free Slot</td>
        <td>Web</td>
        <td>Free Slot</td>
        <td>Free Slot</td>
        <td>Probability and quening models</td>
        <td>Communicative English</td>
    </tr>
    <tr>
        <td bgcolor="yellow">10-12</td>
        <td>Physics for quantum computing</td>
        <td>Digital Electronics</td>
        <td>Communicative English</td>
        <td>Fundamentals of C programming</td>
        <td>Digital Electronics</td>
        <td>Probability and quening models</td>
    </tr>
    <tr>
        <td bgcolor="yellow">12-1</td>
        <td colspan="6">Lunch Break</td> 
    </tr>
    <tr>
        <td bgcolor="yellow">1-3</td>
        <td>Career development</td>
        <td>Fundamentals of C programming</td>
        <td>Mentor meet</td>
        <td>Physics for quantum computing</td>
        <td colspan="2">Web</td>
     </tr>             
</table>
<br>
<table border="2" cellspacing="2" cellpadding="6">
     <caption>Course</caption>
     <tr bgcolor="purple"</tr>
         <th>S.no</th>
         <th>Course code</th>
         <th>Course Name</th>
     </tr>
     <tr> 
         <td>1</td>
         <td>19AI304</td>
         <td>Fundamentals of C programming</td>
     </tr>
     <tr>
         <td>2</td>
         <td>19AI414</td>
         <td>Fundamentals of Web Application Development</td>
     </tr>
     <tr>
         <td>3</td>
         <td>SH3214</td>
         <td>Physics for quantum computing</td>
     </tr>
     <tr> 
         <td>4</td>
         <td>19EN101</td>
         <td>Communicative English</td>
     </tr>
     <tr>
         <td>5</td>
         <td>19MA222</td>
         <td>Probability and quening models</td>
     </tr>
     <tr>
         <td>6</td>
         <td>19EE404</td>
         <td>Digital Eletronics</td>
     </tr>
     <tr> 
         <td>7</td>
         <td>SH7101</td>
         <td>Heritage of Tamils</td>
        </tr>
        <tr> 
            <td>8</td>
            <td>19EY708</td>
            <td>Career development</td>
     </tr>
     <tr> 
         <td>9</td>
         <td>ECA-M-SCOFT</td>
         <td>Mentor Meet</td>
     </tr>
</table>
</body>
</html>     

```
##OUTPUT
![alt text](<Screenshot (22).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
