<!DOCTYPE html>
<html>
  <head>
    
    <title>Registration Form template</title>

  </head>
  
  <body> 

  <h1>Register</h1>

  <!-- the tag <strong> is placed around the words that I wanted to be in bold -->

  <!-- below is my First name Last name inputs and the male / female / other, radio buttons -->
   
  	<form>
 <strong>First name:</strong> <input id="first" type="text" placeholder="John">
 <strong>Last Name:</strong>  <input id="last" type="text" placeholder="Doe">
  	</form>

<!-- below is my radio buttons for male and female options but you can make the options whatever you want -->

	<form>
<strong><label for="Male">Male</label></strong>
<input name= "Male" id="Male" type="radio" value="Male">

<strong><label for="female">female:</label></strong>
<input name="female" id="female" type="radio" value="female">

<strong><label for="other">other</label></strong>
<input name="other" id="other" type="radio" value="other">
	</form>

<!-- below is for the email and password entry. Dont forget to use the "id" selector with password so you get dots for hidden text, instead of actual text  -->

	<form>
  <strong>Email:</strong><input id="email" type="email" placeholder="Email">
  <strong>Password:</strong><input id="Password" type="Password" placeholder="Password">
  	</form>

  	<!-- below is for the drop down selections, i used birthday here, you can use them however you like -->

  	<!-- below is the first selector box -->

<strong>Birthday:</strong><select name="Birthday month">
	<option value="Jan">Jan</option>
	<option value="Feb">Feb</option>
	<option value="Mar">Mar</option>
	<option value="April">April</option>
</select>
 
 <!-- below is the second selector box -->

<select name="day">
	<option value="1">1</option>
	<option value="2">2</option>
	<option value="3">3</option>
	<option value="4">4</option>
</select>

<!--below is the third selector box -->

<select name="year">
	<option value="1999">1999</option>
	<option value="1989">1989</option>
	<option value="2009">2009</option>
	<option value="1902">1902</option>
</select>

<form>

<strong>I agree to the terms and conditions:</strong></label>
<input type="radio">

<button>Submit it now asshole!</button>
</form>





  </body>
</html>
