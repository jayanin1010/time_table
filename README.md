# Ex03 Time Table
# Date:21-10-2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using <table> tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Time Table</title>
        <style>
            body {
                font-family: Arial, sans-serif;
                margin: 20px;
                background-color: #f5f5f5;
            }
            table {
                border-collapse: collapse;
                width: 80%;
                margin: 0 auto;
                background-color: #f0f8ff;
            }
            th, td {
                border: 1px solid #000;
                padding: 10px;
                text-align: center;
            }
            th {
                background-color: #ffcc00;
                color: #000;
            }
            td {
                background-color: #e0ffff;
            }
            .time-slot {
                background-color: #00ffff;
                font-weight: bold;
            }
            .free-slot {
                background-color: #99ffff;
            }
            .subject-table {
                margin-top: 20px;
                width: 60%;
            }
            .subject-table th {
                background-color: #87ceeb;
            }
            h1 {
                text-align: center;
                margin-bottom: 20px;
            }
        </style>
    </head>
    <body>
        <CENTER>
    <img src="image.png" alt="logo" >
    </CENTER>
        <h1>Slot Time Table - JAYANI N (24900024)</h1>

        <table>
            <tr>
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <TH>Saturday</TH>
            </tr>
            <tr>
                <td class="time-slot">8-10</td>
                <td class="free-slot">---</td>
                <td >BEEE</td>
                <td class="free-slot">---</td>
                <td>CE</td>
                <td class="free-slot">---</td>
                <td class="free-slot">---</td>
            </tr>
            <tr>
                <td class="time-slot">10-12</td>
                <td>CE</td>
                <td class="free-slot">---</td>
                <td>BEEE</td>
                <td>PYTHON</td>
                <td>WEB</td>
                <td>WEB</td>
            </tr>
            <tr>
                <td class="time-slot">12-1</td>
                <td colspan="6">LUNCH</td>
            </tr>
            <tr>
                <td class="time-slot">1-3</td>
                <td >WEB</td>
                <td>PYTHON</td>
                <td>MENTOR MEET</td>
                <td>CDS</td>
                <td>PYTHON</td>
                <td>PYTHON</td>

            </tr>

        </table>

        <table class="subject-table">
            <tr>
                <th>S. No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI301C</td>
                <td>Python and linear algebra</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19EE305</td>
                <td>Basics of Electrical and Electronics Engineering</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19EY708</td>
                <td>Career Development Skills</td>
            </tr>

        </table>

    </body>
    </html>

# OUTPUT

![alt text](<Screenshot 2024-11-21 182339.png>)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
