# Ex03 Time Table
## Date: 16/11/2024

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
    <title>SLOT TIMETABLE</title>
    <center>
    <img src="logo.png" height="100" width="540"></center>

    <table border="5" cellpadding="15" align="center" bgcolor="cyan">
        <caption align="center">VISHAL(24900214)</caption>
        <font color="white">
        <th bgcolor="yellow">Time\Day</th><th bgcolor="yellow">Monday</th> <th bgcolor="yellow">Tuesday</th> <th bgcolor="yellow">Wednesday</th> <th bgcolor="yellow">Thursday</th> <th bgcolor="yellow">Friday</th> <th bgcolor="yellow">Saturday</th>
        <tr >
            <td bgcolor="yellow">8.00-10.00</td>
            <td>-</td>
            <td>-</td>
            <TD>-</TD>
            <td>French</td>
            <td>-</td>
            <td>French</td>
        </tr>
        <tr><td bgcolor="yellow">10.00-12.00</td><td>C programming</td><td>Calculus</td><td>CDS</td><td>BEEE</td><td>C programming</td><td>FWAD</td>
        </tr>
        <tr>
            <td bgcolor="yellow">1.00-3.00</td><td>French</td><td>FWAD</td><td>-</td><td>FWAD</td><td>BEEE</td><td>Calculus</td>
               </tr>
               <tr>
               </tr>
    </font>


    </table>
    

<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19A1414</td>
<td>Fundamentals of Web Application Development</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19A1304</td>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">SH5601</td>
<td>FRENCH LANGUAGE A1</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19EE305</td>
<td> BASICS OF ELECTRICALS ELECTRONICS AND MEASUREMENT ENGINEERING</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA201</td>
<td>CALCULUS AND MATRIX ALGEBRA</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EY708</td>
<td>CAREER DEVELOPEMENT SKILLS</td>
</tr>
</table>
</body>
</html>
```


## OUTPUT
![alt text](<Screenshot 2024-11-16 112628.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
