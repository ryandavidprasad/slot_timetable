# Ex03 Time Table
## Date:29/9/2025

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
       <title > Time Table</title>
        <style>
            img.center{
                display:block;
                margin-left:auto;
                margin-right:auto;
                width: 100%;
            }
           marquee{
            font-size: larger;
            color:red;

           }
            table,tr,th,td{
                border:1px solid black;
                text-align: center;
            }
            table.center{
                margin-left:auto;
                margin-right:auto;
            }
            h1,h2{
                text-align:center;
            }
        </style>
    </head>
    <body>
        <p text-align="center">
        <img src="c:\Users\admin\Downloads\logo.png" alt="Not found" class="center" style="width:500px;height:100px;"></p>
        <h1><b1>Slot Time Table - Ryan David Prasad(212224040282)</b1></h1>
        <table width="50px" class="center">
        <tr>
            <th bgcolor="yellow">Time/Day</th>
            <th bgcolor="yellow">Monday</th>
            <th bgcolor="yellow">Tuesday</th>
            <th bgcolor="yellow">Wednesday</th>
            <th bgcolor="yellow">Thursday</th>
            <th bgcolor="yellow">Friday</th>
            <th bgcolor="yellow">Saturday</th>
            
        </tr>
        <tr>
            <th bgcolor="yellow">8-10</th>
            <td bgcolor="aqua">Free</td>
            <td bgcolor="aqua">Free</td>
            <td bgcolor="aqua">Calculus And Matrix</td>
            <td bgcolor="aqua">Free</td>
            <td bgcolor="aqua">Free</td>
            <td bgcolor="aqua">Free</td>
            
            
        </tr>
        <tr>
            <th bgcolor="yellow">10-12</th>
            <td bgcolor="aqua">Communicative English</td>
            <td bgcolor="aqua">Free</td>
            <td bgcolor="aqua">C Programming</td>
            <td bgcolor="aqua">Calculus And Matrix</td>
            <td bgcolor="aqua">Web application</td>
            <td bgcolor="aqua">Web application</td>
        </tr>
        <tr>
            <th bgcolor="yellow">12-1</th>
            <td colspan="6" bgcolor="aqua">Lunch</td>
           
        </tr>
        <tr>
            <th bgcolor="yellow">1-3</th>
            <td bgcolor="aqua">Web application</td>
            <td bgcolor="aqua">Communicative English</td>
            <td bgcolor="aqua">Free</td>
            <td bgcolor="aqua">Digital Electronics</td>
            <td bgcolor="aqua">Career Development</td>
            <td bgcolor="aqua">C programmimng</td>
        </tr>
        <tr>
            <th bgcolor="yellow">3-5</th>
            <td bgcolor="aqua">Free</td>
            <td bgcolor="aqua">Digital electronics</td>
            <td bgcolor="aqua">Free</td>
            <td bgcolor="aqua">Free</td>
            <td bgcolor="aqua">Free</td>
            <td bgcolor="aqua">Free</td>
        </tr>
        </table>
        <table class="center" >
            <h2>Subjects</h2>
            <tr>
                <th>S.No</th>
                <th>Subject Code</th>
                <th>Subject name</th>
            </tr>
            <tr>
                <th>1.</th>
                <td>19AI304</td>
                <td>Fundamentals of Cprogramming</td>
            </tr>
            <tr>
                <th>2.</th>
                <td>19EE404</td>
                <td>Fundamentals of Web Application Development</td>
            </tr>
            <tr>
                <th>3.</th>
                <td>19EE404</td>
                <td>Digital Electronics</td>
            </tr>
            <tr>
                <th>4.</th>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
            <tr>
                <th>5.</th>
                <td>19MA201</td>
                <td>Calculus and Matrix Algebra</td>
            </tr>
            <tr>
                <th>6.</th>
                <td>19EY708</td>
                <td>Career Development Skills</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT

![alt text](image-2.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
