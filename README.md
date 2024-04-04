# Ex03 Time Table
## Date:

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
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/images/logo.png"height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="4" border="5" bgcolor="green">
<caption><b>SLOT TIMETABLE - JAYASEELAN U(212223220039)</b></caption>
<tr align="center">
	<th bgcolor="purple">Day/Time</th>
	<th bgcolor="">Monday</th>
	<th bgcolor="purple">Tuesday</th>
	<th bgcolor="">Wednesday</th>
	<th bgcolor="purple">Thursday</th>
	<th bgcolor="">Friday</th>
</tr>
<tr align="center">
	<th bgcolor="">8-10</th>
	<td>FREE</td>
	<td>DIGITAL ELECTRONICS</td>
	<td> WEB</td>
	<td>DIGITAL ELECTRONICS</td>
	<td>FREE</td>
</tr>
<tr align="center">
	<th bgcolor="purple">10-12</th>
	<td>FREE</td>
	<td>OPERATION SYSTEM</td>
	<td>CHEMISTRY</td>
	<td>OPERATION SYSTEM</td>
	<td>PYTHON PROGRAMING</td>
</tr>
<tr>
	<th bgcolor="">12-1</th>
	<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
	<th bgcolor="purple">1-3</th>
	<td>CREATIVE SKILLS</td>
	<td>FREE</td>
	<td>FREE</td>
	<td>FREE</td>
	<td>COMPUTER NETWORKS</td>
</tr>
<tr align="center">
	<th bgcolor="">3-5</th>
	<td>WEB</td>
	<td>CHEMISTRY</td>
	<td>COMPUTER NETWORKS</td>
	<td>PYTHON PROGRAMING</td>
	<td>FREE</td>
</tr>
</table>
</br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19CS406</td>
<td>OPERATION SYSTEM</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI414</td>
<td>WEB DEVELOPMENT</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI301</td>
<td>PYTHON PROGRAMMING</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS405</td>
<td>COMPUTER NETWORKS</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EY702</td>
<td>CREATIVE SKILLS</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19CY205</td>
<td>CHEMISTRY</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19EE404</td>
<td>DIGITAL ELECTRONICS</td>
</tr>


</table>
</body>
</html>

## OUTPUT
![output](./img1.png)
![output](./img2.png)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
