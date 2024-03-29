# Ex03 Time Table
## Date: 29-03-2024
## Name: Suriya Pravin M
## Reg.no: 212223230223
## Dept: AIDS

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
    <title>slot timetable</title>
</head>
<body>
    <center> 
        <img src="/static/logo.png" height="100" width="500">
        <br>
        <table align="center" width="500" cellsapacing="2" cellpadding="5" border="5">
            <caption><b>SLOT TIME TABLE - Suriya Pravin M (212223230223)</b></caption>
            <tr align="center">
                <th bgcolor="green">DAY/TIME</th>
                <th bgcolor="green">MONDAY</th>
                <th bgcolor="green">TUESDAY</th>
                <th bgcolor="green">WEDNESDAY</th>
                <th bgcolor="green">THURSDAY</th>
                <th bgcolor="green">FRIDAY</th>
                <th bgcolor="green">SATURDAY</th>
            </tr>
            <tr align="center">
                <th bgcolor="Red">8-10</th>
                <td bgcolor="blue">Fundamental of Web Application Development</td>
                <td bgcolor="blue">Digital Electronics</td>
                <td bgcolor="blue">Chemistry</td>
                <td bgcolor="blue">Digital Electronics</td>
                <td bgcolor="yellow">Free slot</td>
                <td bgcolor="blue">Creative Skill</td>
            </tr>
            <tr align="center">
                <th bgcolor="Red">10-12</th>
                <td bgcolor="blue">Operating System</td>
                <td bgcolor="blue">Computer Network</td>
                <td bgcolor="blue">Free slot</td>
                <td bgcolor="blue">Computer Network</td>
                <td bgcolor="blue">Python Programming</td>   
                <td bgcolor="blue">Algebra and Number Theory</td> 
            </tr>
            <tr align="center">
                <th bgcolor="Red">1-3</th>
                <td bgcolor="blue">Algebra and Number Theory</td>
                <td bgcolor="blue">Chemistry</td>
                <td bgcolor="blue">Operating System</td>
                <td bgcolor="blue">Fundamental of Web Application Development</td>
                <td bgcolor="blue">Fundamental of Web Application Development</td>   
                <td bgcolor="blue">Algebra and Number Theory</td> 
            </tr>
            <tr align="center">
                <th bgcolor="Red">3-5</th>
                <td bgcolor="yellow">Free slot</td>
                <td bgcolor="yellow">Free slot</td>
                <td bgcolor="yellow">Free slot</td>
                <td bgcolor="blue">Python Programming</td>
                <td bgcolor="yellow">Free slot</td>   
                <td bgcolor="yellow">Free slot</td> 
            </tr>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="5" border="5">
            <tr align="center">
                <th>s. No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td>Fundamental of Web Application Development</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19AI301</td>
                <td>Python Programming</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19CS405</td>
                <td>Operating System</td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">19CS406</td>
                <td>Computer Network</td>
            </tr>
            <tr>
                <td align="center">5.</td>
                <td align="center">19CY205</td>
                <td>Principles of Chemistry in Engineering</td>
            </tr>
            <tr>
                <td align="center">6.</td>
                <td align="center">19EE404</td>
                <td>Digital Electronics</td>
            </tr>
            <tr>
                <td align="center">7.</td>
                <td align="center">19EY702</td>
                <td>Creative Skill for Communication</td>
            </tr>
            <tr>
                <td align="center">8.</td>
                <td align="center">19MA212</td>
                <td>Algebra and Number Theory</td>
            </tr>
        </table>
    </center>
</body>
</html>
```

## OUTPUT
![Alt text](<Screenshot 2024-03-29 141526.png>)


![Alt text](<Screenshot 2024-03-29 143707.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
