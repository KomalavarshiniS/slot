# Ex03 Time Table
## Date:21.11.2024

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
    
    <body>
        <img src="logo.png" width="700" height="100">
        <table border="2" cellspacing="15" cellpadding="5">
    <caption>SLOT TIMETABLE-KOMALAVARSHINI.S(24900909)</caption>
<tr bgcolor="blue">
    <th> DAY/TIME</th>
    <th>MONDAY</th>
    <th>TUESDAY</th>
    <th>WEDNESDAY</th>
    <th>THURSDAY</th>
    <th>FRIDAY</th>
    <th>SATURDAY</th>
</tr>
<tr>
    <td>8-10</td>
    <td>FREE SLOT</td>
    <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
    <td>FREE SLOT</td>
    <td>FREE SLOT</td>
    <td>PROBABILITY AND QUEUEING MODELS</td>
    <td>COMMUNICATIVE ENGLISH</td>
</tr> 
<tr>
    <td>10-12</td>
    <td>CARRER DEVELOPMENT SKILLS</td>
    <td>DIGITAL ELECTRONICS</td>
    <td>COMMUNICATIVE ENGLISH</td>
    <td>FUNDAMENTALS OF C PROGRAMMING</td>
    <td>DIGITAL ELECTRONICS</td>
    <td>PROBABILITY AND QUEUEING MODELS</td>
</tr>        
<tr>
    <td>12-1</td>
    <td colspan="6">LUNCH BREAK</td>
</tr>   
<tr>
    <td>1-3</td>
    <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
    <td>FUNDAMENTALS OF C PROGRAMMING</td>
    <td>MENTOR MEET</td>
    <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
    <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
    <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
</tr>
<tr>
    <td>3-5</td>
    <td colspan="6">FREE SLOT</td>
</tr>
</table>


        <table border="2" cellspacing="15" cellpadding="5">
        <caption COURSES >
            <tr bgcolor="cyan">
                <th>S.NO</th>
                <th>COURSE CODE</th>
                <th>COURSE NAME</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION AND DEVELOPMENT</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI304</td>
                <td>FUNDAMENTALS OF C PROGRAMMING</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19EN101</td>
                <td>COMMUNICATIVE ENGLISH</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19CY205</td>
                <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19EY708</td>
                <td>CAREER DEVELOPMENT SKILLS</td>
            </tr>
            <tr>
                <td>6</td>
                <td>19MA222</td>
                <td>PROBABILITY ND QUEUEING MODELS</td>
            </tr>
            <tr>
                <td>7</td>
                <td>19EE404</td>
                <td>DIGITAL ELECTRONIC</td>
            </tr>
            <tr>
                <td>8</td>
                <td>ECA-M-SCOFT</td>
                <td>MENTOR MEET</td>
            </tr>
        </caption>   
        </table>
    </body>
</tr>    

        </table>
       </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (32).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
