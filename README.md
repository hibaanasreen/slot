# Ex03 Time Table
## Date:16/11/24

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
        <table border="1" cellspacing="15"cellpadding="2">
        <caption>SLOT TIMETABLE HIBA NASREEN.M (24900188)</caption>
        </caption>
        <tr bgcolor="orange">
            <th>DAYS/TIME</th>
            <th>MONDAY</th>
            <th>TUESDAY</th>
            <th>WEDENESDAY</th>
            <th>THURSDAY</th>
            <th>FRIDAY</th>
            <th>SATURDAY</th>
        </tr>
        <tr bgcolor="skyblue">
        <th bgcolor="orange">8:00-10:00</th>
        <th>FREE SLOT</th>
        <th>CDS</th>
        <th>FREE SLOT</th>
        <th>PYHSICS</th>
        <th>WEB</th>
        <th>EDM</th>
       </tr>
        <tr bgcolor="skyblue">
        <th bgcolor="orange">10:00-12:00</th>
        <th>EDM</th>
        <th>MATHS</th>
        <th>C+</th>
        <th>FREE SLOT</th>
        <th>C+</th>
        <th>PHYSICS</th>
        </tr>
        <tr bgcolor="skyblue">
        <th bgcolor="orange">12:00-1:00</th>
        <th>LUNCH</th>
        <th>LUNCH</th>
        <th>LUNCH</th>
        <th>LUNCH</th>
        <th>LUNCH</th>
        <th>LUNCH</th>
        
        </tr>

        <tr bgcolor="skyblue">
        <th bgcolor="orange">1:00-3:00</th> 
        <th>WEB</th>
        <th>WEB</th>
        <th>MM</th>
        <th>DE</th>
        <th>FREE SLOT</th>
        <th>MATHS</th>
        

        
       </tr>
        <tr bgcolor="skyblue">
        <th bgcolor="orange">3:00-5:00</th> 
        <th>FREE SLOT</th>
        <th>DE</th>
        <th>FREE SLOT</th>
        <th>FREE SLOT</th>
        <th>FREE SLOT</th>
        <th>FREE SLOT</th>
        </tr>
   
   
    </table>
    <table border="1"cellspacing="15"cellpadding="2">
    <tr bgcolor="beige">
    <th>S.NO</th>
    <th>COURSE CODE</th>
    <th>COURCE NAME</th>
    </tr>
    <tr bgcolor="palegreen">
   <th> 1</th>
   <th>19AI302</th>
   <th>ENGINEERING DESIGN AND MODELLING</th>
    </tr>
    <tr bgcolor="palegreen">
    <th>2</th>
    <th>19AI304</th>
    <th>FUNDAMENTALS OF C PROGRAMMING</th>
    </tr>
   <tr bgcolor="palegreen">
    <th>3</th>
    <th>19AI414</th>
    <th>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</th>
    </tr>
    <tr bgcolor="palegreen">
        <th>4</th>
        <th>19EEE304</th>
        <th>DIGITAL ELECTRONICS</th>
    </tr>
    <tr bgcolor="palegreen">
        <th>5</th>
        <th>19EY708</th>
        <th>CAREER DEVELOPMENT SKILLS</th>
    </tr>
    <tr bgcolor="palegreen">
    <th>6</th>
    <th>ECA-M-SCOFT</th>
    <th>MENTOR MEET</th>
    </tr>
    <tr bgcolor="palegreen">
   <th>7</th>
   <th>SH3214</th>
   <th>PYSICS OF QUANTUM COMPUTING</th>
    </tr>
    <tr bgcolor="palegreen">
   <th>8</th>
   <th>19MAA201</th>
   <th>CALCULUS AND MATRIX ALGEBRA</th>
    </tr>
    </table>
    </body>
</html>
```


## OUTPUT
![alt text](<Screenshot 2024-11-16 215112.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
