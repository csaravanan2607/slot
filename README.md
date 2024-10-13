# Ex03 Time Table
# Date : 13/10/24

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

## CODE
```

<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src ="http://training.saveetha.in/pluginfile.php/1/core_admin/logo/0x150/1623542614/logo_1.png" width="800" Height="150">
</center>
<br>
<table align="center" width="750" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><i><b><h3>SLOT TIME TABLE - Saravanan C (212222110041)</h3><b></i></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
</tr>

<tr align="center">
<th bgcolor="yellow">8-10</th>
<td></td>
<td>FWAD</td>
<td>C Programming</td>
<td colspan="5,6">FREE SLOT</td>
</tr>

<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>Transforms</td>
<td>Probability</td>
<td>Probability</td>
<td></td>
<td>PMC</td>
</tr>

<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>

<tr align="center">
<th bgcolor="yellow">1-3</th>
<td colspan="1"> OS </td>
<td>C Programming</td>
<td>Transforms</td>
<td>EDM</td>
<td></td>
</tr>

<tr align="center">
<th bgcolor="yellow">3-5</th>
<td colspan="1">EDM</td>
<td>PMC</td>
<td></td>
<td>FWAD</td>
<td></td>
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
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>

<tr>
<td align="center">2.</td>
<td align="center">19CS405</td>
<td>OS</td>
</tr>

<tr>
<td align="center">3.</td>
<td align="center">19AI302</td>
<td>EDM</td>
</tr>

<tr>
<td align="center">4.</td>
<td align="center">19EE309</td>
<td>Microcontroller(PMC)</td>
</tr>

<tr>
<td align="center">5.</td>
<td align="center">19AI304</td>
<td>C Programming</td>
</tr>

<tr>
<td align="center">6.</td>
<td align="center">19MA219</td>
<td>Transforms</td>
</tr>

<tr>
<td align="center">7.</td>
<td align="center">19MA222</td>
<td>Probability</td>
</table>
</body>
</html>
```

## OUTPUT
![Slot html - slot - Visual Studio Code 20-10-2023 09_06_48](https://github.com/saravanan2607/slot/assets/121395849/28166cee-f96a-43e8-8bc3-925c741d9bb9)
![Slot html - slot - Visual Studio Code 20-10-2023 09_06_57](https://github.com/saravanan2607/slot/assets/121395849/c655197e-1b7d-4df4-abfb-826260a60519)
![Slot html - slot - Visual Studio Code 20-10-2023 09_07_12](https://github.com/saravanan2607/slot/assets/121395849/fda08109-d54f-4784-9858-1c3152a5d906)

![Screenshot (15)](https://github.com/saravanan2607/slot/assets/121395849/98dfd734-f125-487e-b858-7ce594b25bdb)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
