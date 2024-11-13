# Ex03 Time Table
## Date: 25/09/2005

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
              <title> web </title>
     </head>
     <body bgcolor="black" TEXT="white">

          
          <table border= "4" cellspacing="0px" cellpadding="10px" bgcolor=green" align="center" >
          <CAPTION align=“top”> SLOT TIME TABLE - SURJITH(212223043006) </CAPTION>
          <br>
          <br>
               <tr> 
               <th bgcolor="gray">   DAY/TIME </th>
               <th bgcolor="purple">   MONDAY </th>
               <th bgcolor="purple">   TUESDAY </th>
               <th bgcolor="purple">   WEDNESDAY </th>
               <th bgcolor="purple">   THURSDAY </th>
               <th bgcolor="purple">   FRIDAY </th>
               <th bgcolor="purple>">  SATURDAY</th>
               </tr>
               <tr>
                <th bgcolor="purple"> 8-10 </th>
                <td> Quantitative Ability </td>
                <td> Computer Architecture </td>
                  <td> -- </td>
                <td> -- </td>
                <td> Fundamental of Web Application development </td>
                <td> -- </td>
               </tr>
               <tr>
                <th bgcolor="purple"> 10-12 </th>
                <td> -- </td>
                <td> --  </td>
                <td> Fundamental of Web Application development </td>
                <td> -- </td>
                <td> Computer Architecture </td>
                <td> -- </td>
               </tr>
               <tr>
                <th bgcolor="purple"> 12-1 </th>
                 <td colspan="5" align="center">LUNCH TIME</td>
               </tr>
               <tr>
                <th bgcolor="purple"> 1-3 </th>
                <td> -- </td>
                <td> -- </td>
                <td> Mentor Meets </td>
                <td> -- </td>
                <td> Computer Networks </td>
                <td>Probability and Queueing Models</td>
               </tr>
               
              
              <tr>
               <th bgcolor="purple"> 3-5 </th>
               <td> Computer Networks </td>
               <td> Fundamental of Web Application development </td>
               <td> Probability and Queueing Models </td> 
               <td> -- </td> 
               <td> Career development skills </td>
               <td> -- </td>
              </tr>
           </table>
            <table border= "4" cellspacing="0px" cellpadding="10px"  align="center" >
           <tr>
           <th> S.No </th>
             <th> SUBJECT CODE </th>
           <th> SUBJECT NAME </th>
           </tr>
           <tr> 
           <td> 1. </td>
           <td> 19AI414 </td>
           <td> Fundamental of web application and development </td>
           </tr>
           <tr>
           <td> 2. </td>
           <td> 19MA22 </td>
           <td> Probability and Queueing Models </td>
           </tr>
           <tr>
           <td> 3. </td>
           <td> 19CS406 </td> 
           <td> Computer Networks </td>
           </tr>
           <tr>
           <td> 4. </td>
           <td> ECA-M </td>
           <td> Mentor Meets </td>
           </tr>
           <tr>
           <td> 5. </td>
           <td> 19EY708 </td>
           <td> Quantitative Ability </td>
           </tr>
           <tr>
           <td> 6. </td>
           <td> 19CS305 </td>
           <td> Computer Architecture </td>
           </tr>
           </table>
              
        </body>
</html>
```


## OUTPUT

![Screenshot 2024-11-13 223612](https://github.com/user-attachments/assets/a08b03f2-2e46-4688-9dcf-ca3b6cf56631)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
