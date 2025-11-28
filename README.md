# Ex02 Time Table
## Date:28-11-2025

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
        <title>Timetable</title>
    </head>
    <body>
        <br>
        <br>
        <img src="logo.png" width="1000" height="100" style="display:block; margin:auto;">
        <table style="width: 65%;" border="2" cellspacing="2"cellpadding="2" align="center">
            <caption><b>SLOT TIMETABLE-Induja R (25001726)</b></caption>
            <tr>
                <td bgcolor="orange" align="center"><b>Day/Time</b></td>
                <td bgcolor="green" align="center"><b>Monday</b></td>
                <td bgcolor="green" align="center"><b>Tuesday</td>
                <td bgcolor="green" align="center"><b>Wednesday</b></td>
                <td bgcolor="green" align="center"><b>Thursday </b></td>
                <td bgcolor="green" align="center"><b>Friday</b></td>
                <td bgcolor="green" align="center"><b>Saturday</b></td>
            </tr>
            <tr>
                <td bgcolor="yellow" align="center">8-10</td>
                <td bgcolor="pink" colspan="2" align="center">Eng</td>
                <td bgcolor="pink" align="center">FWAD</td>
                <td bgcolor="pink" align="center">Python</td>
                <td bgcolor="pink" align="center">Free Slot</td>
                <td bgcolor="pink" align="center">FWAD</td>
            </tr>
            <tr>
                <td bgcolor="yellow" align="center">10-12</td>
                <td bgcolor="pink" colspan="3" align="center" align="center">FWAD</td>
                <td colspan="2" bgcolor="pink" align="center">Free Slot</td>
                <td bgcolor="pink" align="center">Eng</td>
            </tr>
            <tr>
                <td bgcolor="yellow" align="center">12-1</td>
                <td bgcolor="pink" colspan="6" align="center" align="center"><b>Lunch</b></td>
            </tr>
            <tr>
                <td bgcolor="yellow" align="center">1-3</td>
                <td bgcolor="pink" rowspan="2" align="center">Python</td>
                <td bgcolor="pink"align="center">Free Slot</td>
                <td bgcolor="pink" align="center">Mentor Meet</td>
                <td bgcolor="pink" align="center">Eng</td>
                <td bgcolor="pink" align="center">Free Slot</td>
                <td bgcolor="pink" align="center">Python</td>
            </tr>
            <tr>
                <td bgcolor="yellow" align="center">3-5</td>
                <td bgcolor="pink" colspan="3" align="center">Free Slot</td>
                <td bgcolor="pink" align="center">Python</td>
                <td bgcolor="pink" align="center">Free Slot</td>  
            </tr>
        </table>
        <br>
        <br>
        <table style="width: 65%;" border="2" cellspacing="2"cellpadding="2" align="center">
            <tr>
                <td align="center">S.NO</td>
                <td align="center">Subject Code</td>
                <td align="center">Subject Name</td>   
            </tr>
            <tr>
                <td align="center">1</td>
                <td align="center">19AI414</td>
                <td align="center">Fundamental Of Web Application Development(FWAD)</td>
            <tr>
                <td align="center">2</td>
                <td align="center">19EN101</td>
                <td align="center">Communicative English</td>
            </tr>
            <tr>    
                <td align="center">3</td>
                <td align="center">19AI301</td>
                <td align="center">Python Programming</td>
            </tr>
        </table>
    </body>
</html>
```


## OUTPUT

<img width="1920" height="1080" alt="Screenshot (19)" src="https://github.com/user-attachments/assets/f753f467-1d0e-45ed-a146-2551eaaa28a7" />

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
