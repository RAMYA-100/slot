# Ex03 Time Table
## Date:08/10/2025

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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Time Table</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        table, th, td {
            border: 1px solid black;
        }
        th, td {
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #f2f2f2;
        }
        .header {
            font-size: 1.5em;
            text-align: center;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540"
</center>

    <div class="header">
        <h3>SLOT TIME TABLE - KAYALVIZHI.V.M(25018055)</h3>
    </div>

    <table>
        <tr>
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr>
            <td>8-10</td>
            <td>Communicative english</td>
            <td>Fwad</td>
            <td>Python</td>
            <td>Communicative english</td>
            <td>Fwad</td>
        </tr>
        <tr>
            <td>10-12</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>Python</td>
            <td>Python</td>
            
        </tr>
        <tr>
            <td>1-3</td>
            <td>Communicative english</td>
            <td>Communicative english</td>
            <td>mentor meet</td>
            <td>Communicative english</td>
            <td>Python</td>
            
        </tr>
        <tr>
            <td>3-5</td>
            <td>Fwad</td>
            <td>Fwad</td>
            <td>Python</td>
            <td>FREE SLOT</td>
            <td>Communicative english</td>
            
        </tr>
    </table>

    <h3>Subjects:</h3>
    <table>
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2</td>
            <td>SH1101</td>
            <td>Communicative English(Communicative english)</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19AI301</td>
            <td>Python programming(Python) </td>
        </tr
    </table>

</body>
</html>

```
## OUTPUT

<img width="1281" height="688" alt="Screenshot 2025-10-08 193050" src="https://github.com/user-attachments/assets/36fb1795-6809-4ac2-8709-3276d1875051" />

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
