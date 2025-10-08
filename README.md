# Ex03 Time Table
## Date: 08/10/2025
## NAME : RAMYA L
## REGISTOR NO : 25018000
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
<!DOCTYPE html>
<html>
<head>
    <title>Slot Time Table - Jeeva Nivas</title>
</head>
<body>
    <IMG SRC="c:\Users\jeeva\Pictures\Screenshots\Screenshot 2025-10-08 110813.png" ALT="Saveetha Engineering College" WIDTH="500" HEIGHT="100">
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - Jeeva Nivas M</h3>

    <table border="1">
        <tr BGCOLOR="RED">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">8-10</td>
            <td>English</td>
            <td>WEB</td>
            <td>Python</td>
            <td>Enlish</td>
            <td>web</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">10-12</td>
            <td></td>
            <td></td>
            <td>WEB</td>
            <td>Python</td>
            <td>Python</td>
        </tr>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">12-1</td>
            <td COLSPAN=5 ALIGN="CENTER">LUNCH BREAK</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">1-3</td>
            <td>English</td>
            <td>English</td>
            <td></td>
            <td>English</td>
            <td>Python</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">3-5</td>
            <td>WEB</td>
            <td>WEB</td>
            <td>Python</td>
            <td></td>
            <td>English</td>
        </tr>
    </table>

    <h3>Subjects</h3>
    <table border="1">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19EN612</td>
            <td>Communicative English</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19AI301</td>
            <td>Fundamentals of Python programming language</td>
        </tr>
    </table>
</body>
</html>

## OUTPUT

<img width="1537" height="952" alt="Screenshot 2025-10-08 111558" src="https://github.com/user-attachments/assets/cd8840f5-2b3b-4e2e-8cd5-290cad1ed1bf" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
