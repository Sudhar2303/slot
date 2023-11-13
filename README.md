# Ex03 Time Table
## DATE : 12/10/2023

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Timetable</title>
    <style>
        .table1{
            background-color: cyan;
            border-color: gray;
            text-align: center;
            width: 800px;
            height: 250px;
        }
        .table2{
            border-color: gray;
            text-align: center;
            width: 800px;
            height: 250px; 
        }
        .name{
            padding-left: 185px;
        }
        .row1{
            background-color: yellow;
        }
        .c1{
            background-color: yellow;
        }
    </style>
</head>
<body>
    <img src = "http://training.saveetha.in/pluginfile.php/1/core_admin/logo/0x150/1623542614/logo_1.png" width = "800" height="150">
    <h3 class = "name">SLOT TIMETABLE - SUDHARSANAN(212221040165)</h3>
    <table border="1" class = "table1">
        <tr class = "row1">
            <th class="c1">Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <td class="c1">8-10</td>
            <td>DAA</td>
            <td>WEB</td>
            <td>MPMC</td>
            <th colspan="1">Free Hour</th>
            <td>MPMC</td>
            <td>DS</td>
        </tr>
        <tr>
            <td class="c1">10-12</td>
            <th colspan="2">Free Hour</th>
            <td>GER</td>
            <th colspan="1">Free Hour</th>
            <td>DW</td>
            <th colspan="1">Free Hour</th>
            
        </tr>
        <tr>
            <td class="c1">12-1</td>
            <th colspan="6">LUNCH BREAK</th>
        </tr>
        <tr>
            <td class="c1">1-3</td>
            <td>MPMC</td>
            <th colspan="1">Free Hour</th>
            <td>DW</td>
            <td>PP</td>
            <td>GER</td>
            <td>PP</td>
            
        </tr>
        <tr>
            <td class="c1">3-5</td>
            <td>GER</td>
            <th colspan="1">Free Hour</th>
            <td>DS</td>
            <td>WEB</td>
            <th colspan="1">Free Hour</th>
            <td>WEB</td>
        </tr>
    </table>
    <br>
    <br>
    <table border="1" class="table2">
        <tr>
            <th>S.No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Applications Development (WEB)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19CS402</td>
            <td>Programming Paradigm(PP)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19CS403</td>
            <td>Design Analysis Algorithm(DAA)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19CS521</td>
            <td>Data Warehouse (DW)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19AI403</td>
            <td>Introduction to Data Science(DS)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19CS412</td>
            <td>MICROPROCESSOR AND MICROCONTROLLER(MPMC)</td>
        </tr>
    </table>
</body>
</html>
```
## OUTPUT

![Alt text](<sudhar/new1/static/Screenshot (287).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
