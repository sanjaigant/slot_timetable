# Ex03 Time Table
## Date:22/04/2025

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
<title> TIME TABLE </title>   
</head>
<body>
<center>
<img src="/static/logo.png"height="100"width="540">
</center>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<caption> SLOT TIME TABLE - sanjai ganth(212224230244) </caption>

<tr bgcolor="CornflowerBlue">
     <th > Day/Time </th>
     <th> Monday </th>
     <th> Tuesday </th>
     <th> Wednesday </th>
     <th> Thursday </th>
     <th> Friday </th> 
     <th> Saturday </th>
</tr>
<tr align="center">
   <th bgcolor="CornflowerBlue"> 8-10 </th>
   <td> free slot</td>
   <td> free slot </td>
   <td> free slot</td>
   <td> Free Slot </td>
   <td> Free Slot </td>
   <td> Free Slot </td>
</tr>
<tr align="center">
    <th bgcolor="CornflowerBlue"> 10-12 </th>
    <td> b.eee</td>
    <td> ess </td>
    <td> h.v</td>
    <td> c.n </td>
    <td> web </td>
    <td> chem </td>
</tr>
<tr align ="center">
    <th bgcolor="CornflowerBlue"> 12-1 </th>
    <td colspan="6" align="center"> LUNCH </td>
</tr>
<tr align ="center">
    <th bgcolor="CornflowerBlue"> 1-3 </th>
    <td > fund of c</td>
    <td> r.a</td>
    <td>  m.m </td>
    <td> chem </td>
    <td> fund of c </td>
    <td> free slot </td>
</tr>
<tr align ="center">
    <th bgcolor="CornflowerBlue"> 3-5 </th>
    <td> cn </td>
    <td> free slot </td>
    <td> free slot</td>
    <td> web </td>
    <td> b.eee </td>
    <td> Free Slot </td>
</tr>
</tr>
</table>
<br>
<table align="center" border="7" cellspacing="10" cellpadding="10">
<tr align="center">
<th> S.NO. </th>
<th> Subject Code</th>
<th> Subject Name </th>
</tr>
<tr align="center">
<td> 1. </td>
<td> 19AI304 </td>
<td> Fundamentals of C Programming </td>
</tr>
<tr align="center">
<td> 2. </td>
<td> 19AI414 </td>
<td> Fundamentals of Web Application Development </td>
</tr>
<tr align="center">
<td> 3. </td>
<td>19CS406 </td>
<td> Computer Networks </td>
</tr>
<tr align="center">
<td> 4. </td>
<td> 19CY205 </td>
<td> Principles of Chemistry in Engineering </td>
</tr>
<tr align="center">
<td> 5. </td>
<td> 19CY801 </td>
<td> Environmental Sciences and Sustainability </td>
</tr>
<tr align="center">
<td> 6. </td>
<td> 19EE305 </td>
<td> Basic Electrical, Electronics and Measurement Engineering  </td>
</tr>
<tr align="center">
<td> 7. </td>
<td> 19EY709 </td>
<td> Reasoning Ability </td>
</tr>
<tr align="center">
<td> 8. </td>
<td> 19HS801  </td>
<td> Human Values and Professional Ethics </td>
</html>
```


## OUTPUT
![alt text](image.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
