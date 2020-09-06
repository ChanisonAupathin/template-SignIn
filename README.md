# template-signin
Template-signin whith Bootstrap v.4

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

     <title>Template-Signin</title>
    <link href="../css/bootstrap.min.css" rel="stylesheet">
	<script src="../js/jquery.min.js"></script>
	<script src="../js/popper.min.js"></script>
	<script src="../js/bootstrap.min.js"></script>
    
</head>

<style>
    <.form-signin>
        html , body {
            height: 100%;
        }
        body{
            background-color: #F5F5F5;
        }
        .form-signin{
            widows: 100%;
            max-width: 330px;
            padding:15px;
            margin:auto;
        }
        .form-signin .form-control{
            position: relative;
            height: auto;
            padding:10px;
            font-size: 16px;
        }
        .form-signin:focus{
            z-index: 2;
        }
        #inputEmail{
            border-bottom-left-radius: 1;  /*radius: 0; = ไม่โค้ง  */
            border-bottom-right-radius: 1;
            margin-bottom: -1px;
        }
        #inputPassword{
            border-top-left-radius: 1;
            border-top-right-radius: 1;
        }
    </style>
    <body   class="d-flex  align-self-center text-center" >
        <form action="#" class="form-signin">
            <img src="img/login.svg" alt="LOGIN" class="mt-3" width="72" height="72">
            <h1 class="h3 mb-3 mt-3 font-weight-normal">Please Sign</h1>
            <input type="email" name="" id="inputEmail" class="form-control" placeholder="Email address" required autofocus>
            <input type="password" name="" id="inputPassword" class="form-control" placeholder="Password" required>


            <div class="custom-control custom-checkbox m-3 ">
                <input type="checkbox" name="" id="check1" class="custom-control-input" value="remember-me" checked>
                <label for="check1" class="custom-control-label">Remember me</label>
            </div>

            <button type="submit" class="btn btn-lg btn-primary btn-block">Sign In</button>
            <p class="mt-3 mb-3 text-muted">&copy;2020 - 2030 </p>

        </form>

        
      
        

        
    </body>



    
          
    
</html>
