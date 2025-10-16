# Ex03 Time Table
## Date:09-10-2025

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

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>TIMETABLE</title>
        <link rel="icon" href="/static/time_table/newpro/timetable/static/sec-logo-01as.png">
        <style>
            body{
                background-repeat: no-repeat;
                background-size:cover;
                background-position: center;
            }
            span{
                writing-mode:vertical-lr;
                text-orientation:upright;
            }
        </style>
    </head>
     <body style="color:rgb(255, 255, 255);" background="c:\Users\admin\Downloads\natural.jpg">
        <center>
            <IMG SRC="/static/logo.png" width="600" height="100" border="4">
            <HR>
            <H1 STYLE="COLOR: WHITE; background-color: rgb(7, 222, 255);">
            <MARQUEE>TIMETABLE</MARQUEE></H1>
            <HR>
            <table BORDER="1" WIDTH="1500" HEIGHT="600" STYLE="background-color:rgb(255, 0, 111);">
                <tr bgcolor="AQUA">
                    <td >DAY/TIME</td>
                    <td>8AM-10AM</td>
                    <td>10AM-12PM</td>
                    <td>12PM-1PM</td>
                    <td >1PM-3PM</td>
                    <td>3PM-5PM</td> 
                </tr>
                <tr>
                    <td bgcolor="AQUA">MONDAY</td>
                    <td>FREE SLOT</td> <td>BEEE</td>
                    <td rowspan="6"><CENTER><H4><span>LUNCH</span></H4></CENTER></td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                </tr>
                <tr>
                    <td bgcolor="AQUA">TUESDAY</td>
                    <td>FREE SLOT</td>
                    <td>TOC</td>
                    <td>WEB</td>
                    <td>PYTHON AND LINEAR ALGEBRA</td> 
                </tr>
                <TR>
                    <TD bgcolor="AQUA">WEDNESDAY</TD>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                    <td>MEN</td>
                    <td>BEEE</td> 
                </TR>
                <TR>
                    <TD bgcolor="AQUA">THURSDAY</TD>
                    <td>PYTHON AND LINEAR ALGEBRA</td>
                    <td>PROBABILITY</td>
                    <td>PYTHON AND LINEAR ALGEBRA</td>
                    <td>TOC</td> 
                </TR>
                <TR>
                    <TD bgcolor="AQUA">FRIDAY</TD>
                    <td>FREE SLOT</td>
                    <td>PYTHON AND LINEAR ALGEBRA</td>
                    <td>WEB</td>
                    <td>FREE SLOT</td> 
                </TR>
                <TR>
                   <TD bgcolor="AQUA">SATURDAY</TD>
                    <td>FREE SLOT</td>
                    <td>PROBABILITY</td>
                    <td>REASONING ABILITY</td>
                    <td>EVS</td> 
                </TR>
            
            </table>
            <TABLE BORDER="1" style="background-color: rgb(255, 255, 255); color: rgb(0, 0, 0);">
                <TR>
                    <TH>S.NO:</TH><TH>COURSE CODE</TH> <TH>COURSE NAME</TH>
                </TR>
                <TR>
                    <TD>1.</TD> <TD>19AI301C</TD>
                    <TD>PYTHON AND LINEAR ALGEBRA</TD>
                </TR>
                <TR>
                    <TD>2.</TD> <TD>19CS407</TD>
                    <TD>TOC-THEORY OF COMPUTATION</TD>
                </TR>
                <TR>
                    <TD>3.</TD> <TD>19AI414</TD>
                    <TD>WEB-FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</TD>
                </TR>
                <TR>
                    <TD>4.</TD> <TD>19MA222</TD>
                    <TD>PROBABILITY-PROBABILITY AND QUEUEING MODELS</TD>
                </TR>
                <TR>
                    <TD>5.</TD> <TD>19EY709</TD>
                    <TD>REASONING ABILITY</TD>
                </TR>
                <TR>
                    <TD>6.</TD> <TD>19EE305</TD>
                    <TD>BEEE-BASIC ELECTRICAL ELECTRONIC AND MEASUREMENT ENGINEERING</TD>
                </TR>
                <TR>
                    <TD>6.</TD> <TD>19CY801</TD>
                    <TD>EVS-ENVIRONMENTAL SCIENCES AND SUSTAINABILITY</TD>
                </TR>
                <TR>
                    <TD>8.</TD> <TD>ECA-M-SCOFT</TD>
                    <TD>MEN-MENTOR MEET</TD>
                </TR>
            
            </TABLE>
        </CENTER>
        <h1 ALIGN="RIGHT"  STYLE="COLOR: BLACK ;background-color:wheat;">
        <MARQUEE>DONE BY:VUTUKURI SAI KUMAR REDDY(24010662)</MARQUEE></h1>
    </body>
</htmL>
```

## OUTPUT
![alt text](<Screenshot 2025-10-16 093710-1.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
