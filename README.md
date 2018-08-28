# loginPage
my first login page trial project
<html>

<head>
    <title> Registration Form </title>
</head>

<body>
    <link href="registration.css" type="text/css" rel="stylesheet" />
    <h2> Sign Up</h2>
    <!--==========form start here================-->
    <form name="form1" action="modified.php" method="post" enctype="multipart/form-data">

        <div class="container">
            <!--the above div will contain its ending tag before ending form tag-->


            <div class="form_group">
                <label> First Name: </label >
 <input type = "text" name = "fname" value = "" required/>
</div>


 <div class = "form_group" >
 <label > Middle Name: </label >
 <input type = "text" name = "mname" value = "" required />
 </div>


 <div class = "form_group" >
 <label > Last Name: </label >
 <input type = "text" name = "lname" value = "" required/>
 </div>


 
<div class="form_group">
    <label>Confirm Password: </label>
                <input type="password" name="pwd" value="" required/>
            </div>

            <div class="form_group">
                <label>Email: </label>
                <input type="text" name="email" value="" required/>
            </div>

            <div class="form_group">
                <label>Contact No: </label>
                <input type="text" name="contact" value="" required/>
            </div>

            <div class="form_group">
                <label for=""> Gender :</label>
                <input type="radio" name="gender" value="male"> Male
                <input type="radio" name="gender" value="female"> Female
                <input type="radio" name="gender" value="other"> Other
            </div>

            <div class="form_group">
                <label for="">Address :</label>
                <textarea name="" id="" cols="30" rows="10"></textarea>
            </div>

            <div class="form_group">
                <label> Pin code: </label>
                <input type="text" name="contact" value="" required/>
            </div>

            <div class="form_group">
                <label for="">City:</label>
                <select name="" id="">
                        <option value="Nairobi">Nairobi</option>
                        <option value="Kampala">Kampala</option>
                        <option value="Kigali">Kigali</option>
                        <option value="Cairo">Cairo</option>
                        <option value="Casablanca">Casablanca</option>
               </select>

            </div>
            <div class="form_group">
                <label for="">Country:</label>
                <select name="" id="">
                        <option value="Kenya">Kenya</option>
                        <option value="Uganda">Kampala</option>
                        <option value="Rwanda">Rwanda</option>
                        <option value="Burundi">Burundi</option>
                        <option value="Morocco">Morocco</option>
            
                  </select>
            </div>

            <div class="form_group">
                <label for="">Skills :</label>
                <input type="radio" name="php" value=""> Php
                <input type="radio" name="java" value="">Java
                <input type="radio" name="ajax" value="">Jquery
                <input type="radio" name="net" value="">.NET
            </div>

            <div class="form_group">


                <input type="file" name="myFile" multiple>

            </div>

            <div class="form_group">
                <input type="radio" name="php" value="">I have read items and conditions
            </div>

            <div class="form_group">
                <input type="submit" name="submit">
            </div>

        </div>
    </form>
</body>

</html>
