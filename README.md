# Ex03 Time Table
## Date: 01/05/2025

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
    <title>Time Table</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', sans-serif;
            background: linear-gradient(to right, #e0f7fa, #e1bee7);
            color: #333;
        }
        h1 {
            color: #222;
        }
        table {
            border-collapse: collapse;
            margin: 20px auto;
            width: 95%;
            max-width: 1000px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            overflow: hidden;
        }
        th, td {
            padding: 12px;
            border: 1px solid #ccc;
        }
        th {
            background-color: #673ab7;
            color: white;
        }
        td {
            background-color: #fffde7;
        }
        tr:hover td {
            background-color: #f1f8e9;
        }
        img {
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <center>
        <img src="/static/logo.png" height="100" width="540">
        <h1>Weekly Time Table: Sujith A (221224230278)</h1>
    </center>

    <table>
        <thead>
            <tr>
                <th>Day</th>
                <th>9:00 - 10:00</th>
                <th>10:00 - 11:00</th>
                <th>11:00 - 12:00</th>
                <th>12:00 - 1:00</th>
                <th>1:00 - 2:00</th>
                <th>2:00 - 3:00</th>
                <th>3:00 - 4:00</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Monday</td>
                <td>Free period</td>
                <td>Maths</td>
                <td>Data Science</td>
                <td rowspan="5">Lunch</td>
                <td>Free Period</td>
                <td>Web Development</td>
                <td>Artificial Intelligence</td>
            </tr>
            <tr>
                <td>Tuesday</td>
                <td>DSA</td>
                <td>Java</td>
                <td>Data Science</td>
                <td>Web Development</td>
                <td>Artificial Intelligence</td>
                <td>Free period</td>
            </tr>
            <tr>
                <td>Wednesday</td>
                <td>OS</td>
                <td>Computer Network</td>
                <td>Free Period</td>
                <td>Java</td>
                <td>OOPs</td>
                <td>Free Period</td>
            </tr>
            <tr>
                <td>Thursday</td>
                <td>DSA</td>
                <td>Machine Learning</td>
                <td>Digital Electronics</td>
                <td>Data Science</td>
                <td>Computer Network</td>
                <td>Python</td>
            </tr>
            <tr>
                <td>Friday</td>
                <td>Python</td>
                <td>C Programming</td>
                <td>Machine Learning</td>
                <td>Digital Electronics</td>
                <td>Data Science</td>
                <td>Computer Network</td>
            </tr>
        </tbody>
    </table>

    <table>
        <thead>
            <tr>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
        </thead>
        <tbody>
            <tr><td>19AL109</td><td>Mathematics</td></tr>
            <tr><td>19AI120</td><td>Data Science</td></tr>
            <tr><td>19EE102</td><td>Digital Electronics</td></tr>
            <tr><td>19CS129</td><td>Data Structures and Algorithms (DSA)</td></tr>
            <tr><td>19CS109</td><td>Java Programming</td></tr>
            <tr><td>19CS102</td><td>Web Development</td></tr>
            <tr><td>19AL219</td><td>Operating Systems</td></tr>
            <tr><td>19AL101</td><td>Object-Oriented Programming (OOP)</td></tr>
            <tr><td>19CY119</td><td>Artificial Intelligence</td></tr>
            <tr><td>19MA101</td><td>Mathematics II</td></tr>
            <tr><td>19AL111</td><td>Computer Networks</td></tr>
            <tr><td>19AI107</td><td>Machine Learning</td></tr>
            <tr><td>19AL130</td><td>Python Programming</td></tr>
        </tbody>
    </table>

</body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2025-05-02 091022.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
