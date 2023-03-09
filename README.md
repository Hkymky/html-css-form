#html/css form 
<!doctype html>
<html> 
    <title> html form </title>
 <head> 
     <style> 
         h2 { 
             color:yellow;    background-color:blue;
         }
         form{ 
             color:green;
         }
  table,tr,th,td{
      border:1px solid black;
          color:red;
  }
     </style>
   
      
      </head> 
 <body>
     <h2> Html form </h2>
     <form>
        <label for="name" >enter name:</label><br>
                <input type ="text  name="name" /> <br/>
                emal:<br>
     <input type="email" name="email"><br>
     enter password:<br>
     <input type="password" name="password"><br> 
     gender:<br> 
     <input type="radio" name="gender" id="male" value="male"> male</input>
     <input type="radio" id="gender" name="gender"> female<br>
     hobby:<br> 
     <input type="checkbox" id="hobby" name="hobby">cricket
     <input type="checkbox" id="hobby" name="hobby">hocky<br>
                enter add:<br>
                <textarea length="20"  width="10">  </textarea><br>
     <select name="language"> 
         <option value="hindi"> Hindi</option>
         <option value="english">English</option>
         <option value ="Bengali">Bengali</option>
         
     </select><br>
    <input class="sub" type="submit" value="submit"><br>
    <a href="https://www.google.coom"> google</a>
    <a href="facebook.com">facebook</a>
    
     </form>
     <table> 
        <tr><th>name</th><th>id</th><th>salary</th><th>proffesion</th></tr></tr>
   <tr><td>sah</td><td>334</td><td>20000</td><td>web developer</td></tr>
   <tr><td>komal</td><td>tyt34</td><td>3000</td><td>software developer</td></tr>
    </table>
 
    
       
       </body> 
       
 </html>
