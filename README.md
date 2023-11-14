# Ex03 Time Table
# DATE:07/10/2023

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
            background-color: whitesmoke;
            border-color: blue;
            text-align: center;
            width: px;
            height: 250px;
        }
        .table2{
            border-color: blue;
            text-align: center;
            width: 800px;
            height: 250px; 
        }
        .name{
            padding-left: 185px;
        }
        .row1{
            background-color:whitesmoke;
        }
        .c1{
            background-color: whitesmoke;
        }
    </style>
</head>
<body>
    <img src = "http://training.saveetha.in/pluginfile.php/1/core_admin/logo/0x150/1623542614/logo_1.png" width = "800" height="150">
    <h3 class = "name">SLOT TIMETABLE - S KIRUTHIKA (212221040085)</h3>
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
            <td>GP</td>
            <td>CNS</td>
            <td>CD</td>
            <td>FWAD</td>
            <td>MPMC</td>
            <td>TRAINING</td>
        </tr>
        <tr>
            <td class="c1">10-12</td>
            <th colspan="2">FS</th>
            <td>FS</td>
            <td>CD</td>
            <td>FS</td>
            <td>CNS</td>
        </tr>
        <tr>
            <td class="c1">12-1</td>
            <th colspan="6">LUNCH BREAK</th>
        </tr>
        <tr>
            <td class="c1">1-3</td>
            <td>CD</td>
            <td>FS</td>
            <td>GP</td>
            <td>FS</td>
            <th colspan="2">FS</th>
            
        </tr>
        <tr>
            <td class="c1">3-5</td>
            <td>MPMC</td>
            <td>FWAD</td>
            <th colspan="2">FS</th>
            <td>TRAINING</td>
            <td>CD</td>
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
            <td>19AI513</td>
            <td>Game Programming (GP)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19CS412</td>
            <td>Cryptography and Network Security (CNS)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19CS409</td>
            <td>Compiler Design (CD)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19AI414</td>
            <td>Fundamentals Of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19EC408</td>
            <td>Microprocessor and Microcontroller (MPMC)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19EY704</td>
            <td>Advance Quantitative and Logical Reasoning (TRAINING)</td>
        </tr>
    </table>
</body>
</html>
```


## OUTPUT
![exp3](https://github.com/skiruthika648/slot/assets/128348968/c31f4d6a-d619-4b98-9029-f7d52f7b8d3d)




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
