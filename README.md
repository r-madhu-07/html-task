# html-task

## AIM

   ``To Create a Daily Schedule Using a Table. Use <table>, <tr>, <td> to display tasks for each day of the week.``

## html

```
      <!DOCTYPE html>
<html>
<head>
    <title>Weekly Schedule</title>
    <style>
        table {
            width: 80%;
            border-collapse: collapse;
            margin: 20px auto;
        }
        th, td {
            border: 1px solid #444;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #f2f2f2;
        }
        caption {
            font-size: 1.5em;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

<table>
    <caption>Weekly Task Schedule</caption>
    <tr>
        <th>Day</th>
        <th>Task</th>
        <th>Status</th>
    </tr>
    <tr>
        <td>Monday</td>
        <td>Team Meeting</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>Tuesday</td>
        <td>Project Work</td>
        <td>Incomplete</td>
    </tr>
    <tr>
        <td>Wednesday</td>
        <td>Client Call</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>Thursday</td>
        <td>Documentation</td>
        <td>Not Done</td>
    </tr>
    <tr>
        <td>Friday</td>
        <td>Review</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>Saturday</td>
        <td>Workshop</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>Sunday</td>
        <td>Rest Day</td>
        <td>N/A</td>
    </tr>
</table>

</body>
</html>
```
## output
![Screenshot 2025-07-01 122643](https://github.com/user-attachments/assets/9e11efd4-415d-4a21-83a9-e4676ce387e6)
