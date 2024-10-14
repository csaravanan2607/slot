# Time Table
# EXP - 3
# Date : 13/10/24

## AIM :
To write a html webpage page to display your slot timetable.

## ALGORITHM :
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

## CODE :
```


<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src ="/static/logo.png" width="800" Height="150">
</center>
<br>
<table align="center" width="750" cellspacing="2" cellpadding="4" border="5" bgcolor="grey">
<caption><i><b><h3>SLOT TIME TABLE - Saravanan C (212222110041)</h3><b></i></caption>
<tr align="center">
<th bgcolor="red">Day/Time</th>
<th bgcolor="green">Monday</th>
<th bgcolor="green">Tuesday</th>
<th bgcolor="green">Wednesday</th>
<th bgcolor="green">Thursday</th>
<th bgcolor="green">Friday</th>
<th bgcolor="green">Saturday</th>
</tr>

<tr align="center">
<th bgcolor="red">8-10</th>
<td>PMC</td>
<td>PLA</td>
<td>C Programming</td>
<td>DBMS</td>
<td></td>
<td>FWAD</td>
</tr>

<tr align="center">
<th bgcolor="red">10-12</th>
<td>FOC</td>
<td></td>
<td>PMC</td>
<td>FWAD</td>
<td>OS</td>
<td></td>
</tr>

<tr>
<th bgcolor="red">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>

<tr align="center">
<th bgcolor="red">1-3</th>
<td colspan="1">EES</td>
<td></td>
<td>MM</td>
<td></td>
<td></td>
<td>PLA</td>
</tr>

<tr align="center">
<th bgcolor="red">3-5</th>
<td colspan="1">FWAD</td>
<td>PLA</td>
<td>PLA</td>
<td>OS</td>
<td></td>
<td>DBMS</td>
</tr>

</table>
<br>
<table align="center" width="750" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>

<tr>
<td align="center">1.</td>
<td align="center">19AI301</td>
<td>PLA</td>
</tr>

<tr>
<td align="center">2.</td>
<td align="center">19AI414</td>
<td>FWAD</td>
</tr>

<tr>
<td align="center">3.</td>
<td align="center">19AI304</td>
<td>FOC</td>
</tr>

<tr>
<td align="center">4.</td>
<td align="center">19CS405</td>
<td>OS</td>
</tr>

<tr>
<td align="center">5.</td>
<td align="center">19CS404</td>
<td>DBMS</td>
</tr>

<tr>
<td align="center">6.</td>
<td align="center">19EY712</td>
<td>EES</td>
</tr>

<tr>
<td align="center">7.</td>
<td align="center">19EE309</td>
<td>PMC</td>
</table>
</body>
</html>
```

## OUTPUT :
![Slot Timetable](https://github.com/user-attachments/assets/5886a742-7f8e-45ad-99ee-f7599e20349e)
## RESULT :
The program for creating slot timetable using basic HTML tags is executed successfully.
