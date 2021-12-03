# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
~~~
<!DOCTYPE html>
<html>

   <head>
      <title>TIME TABLE</title>
   </head>
  
   <body>
      <table border = "8" cellspacing="3" bordercolor="BLUE" bgcolor="GREY">
        <img src="logo.png">
         <tr>
            <th colspan="8">TIME TABLE</th>
         </tr>
         <tr>
                <th colspan="2">Reference number:</th>
                <th colspan="2" align="left">21005806</th>
                <th colspan="2">Name:<th>
                <th colspan="2" align="left">G Jayanth</th>
        <tr>
            <th>DAYS</th>
            <th>1</th>
            <th>2</th>
            <th>3</th>
            <th>4</th>
            <th>5</th>
            <th>6</th>
            <th>7</th>
        </tr>  
      <tr>
             <td>MONDAY</td>
             <td colspan="2">Web Technology Laboratory(19AI402)G.Karthi</td>
             <td colspan="2">Mathematics for Artificial Intelligence(19MA220)Akila.P</td>
	        <th rowspan="1">LUNCH BREAK</th>
             <td colspan="2">Linear Algebra Laboratory(19MA221)Akila.P</td>
         </tr>
             <td>TUESDAY</td>
             <td colspan="2">Free Period</td>
             <td colspan="2">Engineering Mechanics and Product Development(19A1302)S.Sella kumar</td>
             <th rowspan="1">LUNCH BREAK</th>
             <td colspan="2">Engineering Mechanics and Product Development(19A1302)S.Sella kumar</td>
        </tr>
  
  	     <td>WEDNESDAY</td>
             <td colspan="2">Free Period</td>
             <td colspan="2">Mathematics for Artificial Intelligence(19MA220)Akila.P</td>
             <th rowspan="1">LUNCH BREAK</th>
             <td colspan="2">Web Technology Laboratory(19AI402)G.Karthi</td>
         </tr>
	     <td>THURSDAY</td>
             <td colspan="2">Engineering Mechanics and Product Development(19A1302)S.Sella Kumar</td>
             <td colspan="2">Python Programming(19MA301)Akila.P</td>
             <td colspan="1">Mentoring(ECA051-AD)S.Karthik</td>
             <td colspan="2">Engineering mechanics and product devolpment(19A1302)S.Sella kumar</td>
         </tr>  
	     <td>FRIDAY</td>
             <td colspan="2">Soft Skill(19EY701)Siji Joshep</td>
             <td colspan="2">Python Programming(19MA301)Akila.P</td>
             <th rowspan="1">LUNCH BREAK</th>
             <td colspan="2">Web Technology Laboratory(19AI402)G.Karthi</td>
          </tr>  
	     <td>SATURDAY</td>
             <td colspan="7" align="center">HOLIDAY</td> 
          </tr>  
	     <td>SUNDAY</td>
             <td colspan="7" align = "center">HOLIDAY</td>           
      </table>
   </body>
</html>
</html>
~~~
# OUPUT:
![OUTPUT](/IMAGES/IMG.png)
# RESULT:
Thus the program to create a timetable using HTML is completed sucessfully.
