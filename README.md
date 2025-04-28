# Ex03 Time Table
## Date:

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
    <meta name="viewport" content="width=
    , initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <center>
    <table border="1" width="505">
        <h3>SLOT TIME TABLE - NARESH S (24901201)</h3>
           <tr>
               <td style="background-color: yellow;">Day/Time</td> <td style="background-color: yellow;"><center>Monday</center></td> <td style="background-color: yellow;"><center>Tuesday</center></td> <td style="background-color: yellow;"><center>Wednesday</center></td> <td style="background-color: yellow;"><center>Thursday</center></td> <td><center style="background-color: yellow;">Friday</center></td>
           </tr>
           <tr>
               <td style="background-color: yellow;"><center>8-10</center></td> <td colspan="3" style="background-color:aqua ;"><center>FREE SLOT</center></td> <td style="background-color:aqua ;"><center>PHY</center></td> <td style="background-color:aqua ;"><center>CHE</center></td>
           </tr>
           <tr>
               <td style="background-color: yellow;"><center>10-12</center></td> <td style="background-color:aqua ;"><center>GER</center></td> <td style="background-color:aqua ;"><center>FREE SLOT</center></td> <td style="background-color:aqua ;"><center>FWAD</center></td> <td style="background-color:aqua ;"><center>FWAD</center></td> <td style="background-color:aqua ;"><center>PHY</center></td>
           </tr>
           <tr>
               <td style="background-color: yellow;"><center>12-1</center></td> <td colspan="5" style="background-color:aqua ;"><center>L U N C H</center></td>
           </tr>
           <tr>
               <td style="background-color: yellow;"><center>1-3</center></td> <td colspan="2" style="background-color:aqua ;"><center>FREE SLOT</center></td> <td style="background-color:aqua ;"><center>MAT</center></td> <td style="background-color:aqua ;"><center>MAT</center></td> <td style="background-color:aqua ;"><center>SS</center></td>
           </tr>
           <tr>
               <td style="background-color: yellow;"><center>3-5</center></td> <td colspan="2" style="background-color:aqua ;"><center>FREE SLOT</center></td> <td style="background-color:aqua ;"><center>GER</center></td> <td style="background-color:aqua ;"><center>CHE</center></td> <td style="background-color:aqua ;"><center>FWAD</center></td>
           </tr>
    
       </table>
    
<br>
        <table border="1" >
            <tr>
                <td>S.No.</td> <td>Subject Code</td> <td><center>Subject Name</center></td>
            </tr>
            <tr>
                <td><center>1.</center></td> <td><center>19AI414</center></td> <td>Fundamentals of Web Application Development(FWAD)</td>
            </tr>
            <tr>
                <td><center>2.</center></td> <td><center>19EN612</center></td> <td>German Basic(GER)</td>
            </tr>
            <tr>
                <td><center>3.</center></td> <td><center>19PH206</center></td> <td>Physics for information Technology(PHY)</td>
            </tr>
            <tr>
                <td><center>4.</center></td> <td><center>19CY205</center></td> <td>Principles of Chemistry in Engineering(CHE)</td>
            </tr>
            <tr>
                <td><center>5.</center></td> <td><center>19MA201</center></td> <td>Calculus and Matrix Algebra(MAT)</td>
            </tr>
            <tr>
                <td><center>6.</center></td> <td><center>19EY701</center></td> <td>Soft Skills(SS)</td>
            </tr>
        </table>

        </center>
</body>
</html>
```
## OUTPUT
![exp-3](https://github.com/user-attachments/assets/7303d098-9e86-4f96-9709-34f2714e5357)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
