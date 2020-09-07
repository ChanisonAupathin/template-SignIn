<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
     <!-- Required meta tags -->
     <meta charset="utf-8">
     <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
 
     <!-- Bootstrap CSS -->
     <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">

     <title>Template-Signup</title>
    <link href="../css/bootstrap.min.css" rel="stylesheet">
	<script src="../js/jquery.min.js"></script>
	<script src="../js/popper.min.js"></script>
	<script src="../js/bootstrap.min.js"></script>
    
</head>

<style>
   html , body{
       height: 100%;
   }

   body{
       background-color: #F5F5F5;
   }

   .form-signup{
       width: 100%;
       max-width: 50%;
       padding:50px;
       margin: auto;
   }

   .form-signup .form-group .form-control{
        position: relative;
        height: auto;
        padding:10px;
        font-size: 16px;
   }
   
   .form-signup:focus{
       z-index: 2;
   }

   #input{
    border-bottom-left-radius:1 ;
    border-bottom-right-radius: 1;
    margin-bottom: -1;
   
   }
  
   img{
       padding:auto;
       margin: auto;
   }

   #txtlogo{
       font-weight: bold;
       text-align: center;
       font-family:monospace;
       color: #e0a38b;
       
       
   }

</style>
    
    <body class="d-flxe align-self-center">
        <form action="#" class="form-signup form-row">
            <img src="img/register.svg" class="mt-4" alt="" width="80px" height="80px">

            <div class="col-md-12 mt-4 display-4 " id="txtlogo">Sign Up</div>

            <div class="form-group col-md-12 mt-4">
                <label for="fullname">FullName</label>
                <input type="text" name="" id="inputfullname" class="form-control" placeholder="Fullname" required>
            </div>
            <div class="form-group col-md-4">
                <label for="Username">Username</label>
                <input type="text" name="" id="inputUsername" class="form-control" placeholder="Username" required>
            </div>
            <div class="form-group col-md-4">
                <label for="Password">Password</label>
                <input type="password" name="" id="inputPassword" class="form-control" placeholder="Password" required>
            </div>
            <div class="form-group col-md-4">
                <label for="Password">Confirm Password</label>
                <input type="password" name="" id="inputRepeatpass" class="form-control" placeholder="Confirm Password" required>
            </div>
            <div class="form-group col-md-12">
                <label for="Address">address</label>
                <input type="text" name="" id="inputaddress" class="form-control" placeholder="123/4 M.4" required>
            </div>
            <div class="form-group col-md-12">
                <label for="Gmail" >Gmail</label>
                <input type="email" name="" id="inputgmail" class="form-control" placeholder="abc@gmail.com" required>
            </div>
            <div class="form-group col-md-4">
                <label for="City">City</label>
                <input type="text" name="" id="inputCity" class="form-control " placeholder="Bangkok" required>
            </div>
            <div class="form-group col-md-4">
               <label for="State" required>State</label>
               <select name="" id="State" class="form-control" >
                   <option selected class="form-control">Choose...</option>
               </select>
            </div>  
            <div class="form-group col-md-4">
                <label for="zip">Zip</label>
                <input type="text" name="" id="zip" class="form-control" placeholder="10230" required>
            </div> 
            <div class="form-group col-md-4 mt-4">
                 <button class="btn btn-block btn-lg btn-outline-primary">CREATE ACCOUNT</button> 
            </div>
            <div class="form-group col-md-4 mt-4">
                <button type="reset" class="btn btn-block btn-lg btn-outline-warning">Reset</button>
            </div>
            <div class="form-group col-md-4 mt-4">
                <button type="button" class="btn btn-block btn-lg btn-outline-danger">Cancel</button>
            </div>
        </form>
    </body>    
</html>
