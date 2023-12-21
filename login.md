---
title: Login
layout: template
filename: login
--- 
<html>
  <head><title>Chlor | Login</title></head>
  <style>
    body{
      }
    .loginbox {
border-style: solid black;
      border-width:2px;
      text-align: center;
        justify-content: center;
      }
   #text {
border-style: solid;
border-width: 2px;
border-color: #846c6b;
     width:200px;
     height:25px;
    }
    
  </style>
<body>
  <div class="loginbox">
  <center>Log in to Chlor!</center><br>
<input type="text" id="text" placeholder="Username or Email"><br><br>
<input type="password" id="text" placeholder="Password"><br><br>
  
  <input type="submit" id="button" value="Log In"><br>
  <hr width="30%">
 <div> <em>Not signed up?</em></div>
  <div><a href="signup">Sign up for Chlor now!</a></div>
  </div>
</body>
  
</html>
