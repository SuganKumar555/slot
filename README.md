# Ex04 Time Table
## Date:17/11/2016

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
<html>
<head>
    <title>Time Table</title>
</head>
<body bgcolor="yellow">
    <img src="/static/logo.png"  height="104" width="634" hspace="374">
<caption><h2 align="center">slot timetable - SUGANKUMAR(26017521)</h2></caption>


<table border="4" align="center" cellpadding="4" cellspacing="1" height="234" width="776">

    <tr bgcolor="blue">

        <th>DAY/TIME</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
        <th>Saturday</th>

    </tr>

    <tr bgcolor="cyan">

        <th bgcolor="purple">8.00 TO 9.30</th>
        <td align="center">FCC</td>
        <td align="center">PY</td>
        <td align="center">FWAD</td>
        <td align="center"bgcolor="red">-</td>
        <td align="center">PY</td>
        <td align="center">CA</td>
        


    </tr>

    <tr bgcolor="cyan">

        <th bgcolor="purple">9.45 TO 11.15</th>
        <td align="center">FWAD</td>
        <td align="center"bgcolor="red">-</td>
        <td align="center"bgcolor="red">-</td>
        <td align="center">FCC</td>
        <td align="center"bgcolor="red">-</td>
        <td align="center">CDS</td>

    </tr>

    <tr bgcolor="cyan">

        <th bgcolor="purple">11.30 TO 1.00</th>
        <td colspan="6" align="center" bgcolor="lightgray">LUNCH/ ECA-SCOFT-M</td>

    </tr>

    <tr bgcolor="cyan">

        <th bgcolor="purple">1.15 TO 2.45</th>
        <td align="center">PY</td>
        <td align="center">FWAD</td>
        <td align="center"bgcolor="red">-</td>
        <td align="center">MAT</td>
        <td align="center"bgcolor="red">-</td>
        <td align="center">DE</td>

    </tr>

    <tr bgcolor="cyan">

        <th bgcolor="purple">3.00 TO 4.30</th>
        <td align="center"bgcolor="red">-</td>
        <td align="center"bgcolor="red">-</td>
        <td align="center">MAT</td>
        <td align="center">DE</td>
        <td align="center">CA</td>
        <td align="center"bgcolor="red">-</td>

    </tr>

</table>

<br><br><br>



<table border="4"  cellspacing="1" align="center" cellpadding="4"  height="246" width="607">

    <tr bgcolor="blue">

        <th>S. No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>

    </tr>

    <tr bgcolor="cyan">

        <td align="center" bgcolor="yellow">1.</td>
        <td align="center">19AI414</td>
        <td bgcolor="lightgray">Fundamentals of Web Application Development (FWAD)</td>

    </tr>

    <tr bgcolor="cyan">

        <td align="center" bgcolor="yellow">2.</td>
        <td align="center">19CS305</td>
        <td bgcolor="lightgray">Computer architecture (CA)</td>

    </tr>

    <tr bgcolor="cyan">

        <td align="center" bgcolor="yellow">3.</td>
        <td align="center">19MA201</td>
        <td bgcolor="lightgray">Calculus and Matrix Algebra (MAT)</td>

    </tr>

    <tr bgcolor="cyan">

        <td align="center" bgcolor="yellow">4.</td>
        <td align="center">19CS547</td>
        <td bgcolor="lightgray">Fundamentals of Cryptocurrency (FCC)</td>

    </tr>

    <tr bgcolor="cyan">

        <td align="center" bgcolor="yellow">5.</td>
        <td align="center">19AI301</td>
        <td bgcolor="lightgray">Python Programming (PY)</td>

    </tr>

    <tr bgcolor="cyan">

        <td align="center" bgcolor="yellow">6.</td>
        <td align="center">19EY708</td>
        <td bgcolor="lightgray">Career Development Skills (CDS)</td>

    </tr>

    <tr bgcolor="cyan">

        <td align="center" bgcolor="yellow">7.</td>
        <td align="center">19EE404</td>
        <td bgcolor="lightgray">Digital Electronics (DE)</td>

    </tr>

    <tr bgcolor="cyan">

        <td align="center" bgcolor="yellow">8.</td>
        <td align="center">ECA-SCOFT-M</td>
        <td bgcolor="lightgray">SCOFT Mentor Meeting</td>

    </tr>

</table>

</body>
</html>
```


## OUTPUT

![alt text](<Screenshot (15).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
