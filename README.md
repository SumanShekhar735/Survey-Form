<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SURVEY FORM by suman shekhar</title>
  
</head>

<body>
  <center>
    <B>
      <h1>Survey Form</h1>
      <form action="mailto:sumanshekharsingh735@gmail.com" method="post" enctype="text/plain">
        <label>Your Name</label>
        <input type="text" name="Your name" value=" "></br> </br>
        <label> Phone_number</label>
        <input type="phonenumber" name="Your Phone_number" size=10 maxlength=11 value=" "></br> </br>
        <label>Enter your email_id</label>
        <input type="email" name="Your email_id" value=" "></br> </br>
        Do you exercise at home?
        <input type="radio" name="exe" value=1>yes
        <input type="radio" name="exe" value=0>no
        </br></br>
        How do you like to read about your favourite topics
        <p>
          <input type="checkbox" name="book">Books
          <input type="checkbox" name="online">Online resources
          <input type="checkbox" name="Phone app">Phone app
          <input type="checkbox" name="magazines">Magzanine
        </p>
        Which genra of movie do you like?
        <select name="moviepref">
          <option>
          <option value=1 selected="true">comedy
          <option value=2>romance
          <option value=3>thriller
          <option value=4>horror
          <option value=5>biopic
        </select>
        <br><br>
        <label>Tell us about yourself: </label>
        <textarea name="name" rows=4 cols=40></textarea></br> </br>
        <input type=submit value="Submit form">
      </form>
  </center>

</body>

</html>
