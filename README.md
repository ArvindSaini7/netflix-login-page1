# netflix-login-page1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix</title>
    <style>
        * {
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
}

.container {
    height: 200vh;
    width: 100%;
    border: 9px solid black;
    background-image: url("https://assets.nflxext.com/ffe/siteui/vlv3/9d3533b2-0e2b-40b2-95e0-ecd7979cc88b/a3873901-5b7c-46eb-b9fa-12fea5197bd3/IN-en-20240311-popsignuptwoweeks-perspective_alpha_website_large.jpg");

}
.netflix{
    height: 50px;
    width: 50%; 
    color: red;
    font-size: 25px;
     font-family: Arial, Helvetica, sans-serif;
    margin-left: 10%;
    margin-top: 10px;
    letter-spacing: 7px;

}
.first{
    height: 60%;
    width: 35%;
    border-radius: 2px;
    /* border: 5px solid black; */
    margin-left: 32%;
    margin-top: 3%;
    border-radius: 6px;
    background-color: rgba(0,0,0,0.75);
}
.sing-up{
     height: 100px;
     width: 100%;
     display: flex;
     align-items: center;
     /* border: 1px solid red; */
     color: white;

h1{
    color: white;
    padding-top: 20px;
    padding-left: 50px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}
}
.second{
    height: 28%;
    /* border: 1px solid red; */
}
input{
    height: 55px;
    width: 70%;
    background-color: white;
    margin-left: 50px;
    margin-top: 15px;
    border-radius: 2px;
    background-color: #465A7E70;
    border:  2px solid red;
    border-radius: 6px;
    color: white;
}
 button{
    height: 45px;
    width: 70%;
    margin-left: 50px;
    margin-top: 10px;
    background-color: red;
    border-radius: 5px;
    border: none;
    color: white;
 }
 .or{
    height: 40px;
    width: 100%;
    /* text-align: center; */
    /* border: 1px solid red; */
    /* padding-top: 10px; */
    padding-left: 44%;
    color: white;
    font-family: Arial, Helvetica, sans-serif;
 }
 .button button{
    height: 40px;
    width: 70%;
    margin-left: 54px;
    background-color: #465A7E70;
}
.forgot{
    height: 40px;
    width: 70%;
    margin-left: 54px;
    /* background-color: #465A7E70; */
    /* border: 2px solid gold; */
    font-family: Arial, Helvetica, sans-serif;
    text-align: center;
    color: white;
}

.remember{
    color: white;
    /* border: 2px solid red; */
    height: 60px;
    display: flex;

}
.remember input{
    height: 20px;
    width: 20px;
    margin-left: 13.5%;
    border: none;
    border-radius: 2%;
}
.remember label{
    padding-left: 5%;
    padding-top: 3%;

}
.Sign-on{
 /* border: 2px solid red; */
 height: 50px;
 color: white;
 font-family: Arial, Helvetica, sans-serif;
 display: flex;
 h4{
    margin-left: 13.5%;
 }
 h3{
    margin-left:1%;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 18px;
 }
}
.learn-more{
    height: 50px;
    color: white;
    font-family: Arial, Helvetica, sans-serif;
    margin-left: 13.5%;
    font-size: 13px;
    /* border: 2px solid red; */
    width: 70%;
    a{
        color: blue;
    }

}
.three{
    height: 25%;
    /* border: 2px solid red; */
    margin-top: 100px;
    background-color: rgba(0,0,0,0.75);

}
.A-container{
    height: 70%;
    width: 60%;
    margin-left: 10%;
    /* border: 2px dashed red; */
    margin-top: 70px;
}
.A1{
    height: 30%;
    /* border: 2px dashed red; */
}
.A1  {
       padding-top: 20px;
       padding-left: 20px;
       color: white;
       font-size: large;
       font-family: Arial, Helvetica, sans-serif;
    a{

        color: white;
  }
}

.A2{
    /* border: 2px dashed red; */
    height: 30%;
}
 .A2,ul{
    display: flex;
    color: white;
    list-style: none;
    font-family: Arial, Helvetica, sans-serif;
    
 } 
 ul li{
    padding: 30px 100px 20px 25px;

 }
 .A3{
    /* border: 2px dashed red; */
    height: 40%;
 }
 .A3.ul{
    display: flex;
    color: white;
    list-style: none;
    font-family: Arial, Helvetica, sans-serif;
  
 }
 .A3   li{
    padding: 20px 3px 20px 25px;
}
.section{
    margin-left: 30px;
    color: blue;
    box-sizing: 20px;
   

}
select{
    padding: 10px;
    border-radius: 4px;
    border: none;
    background-color: transparent;
    color: white;
    border: 2px solid white;
    width: 120px;
}
    </style>

</head>
<body>
    <div class="container">
     
        <div class="netflix">
            <h1>Netflix</h1>
        </div>

        <div class="first">

        <div class="sing-up">
            <h1>Sing in</h1>
        </div>
      
          <div class="second">
            <input type="text" placeholder="Enter your mail or phone number">
            <input type="password" placeholder="Password">
            <button>Sign in</button>
          </div>

          <div class="or">
            <h4>OR</h4>
          </div>

          <div class="button">
          <button>Use a Sign-in Code</button>
        </div>
      </br>
        <div class="forgot">
          <h4>Forgot Password?</h4>
        </div>
        

        <div class="remember">
           <input type="checkbox" id="remember_me">
           <label for="remember-me">Remember me</label>
        </div>

        <div class="Sign-on">
                <h4>New to Netflix?</h4>
                <h3>Sign-up now</h3>
        </div>

        <div class="learn-more">
           <p>This page is protected by Google reCAPTCHA to ensure you're not a bot.
            <a href=""> learn more.</a></p>
        </div>
        </div>

        <div class="three">

          <div class="A-container">
          <div class="A1">
            <div class="a1">Questions? Call <a href="">000-800-919-1694</a>
            </div>
          </div>

          <div class="A2">

            <ul>
              <li>FAQ</li>
              <li>Help Center</li>
              <li>Term of us</li>
              <li>Privacy</li>
            </ul>
          </div>

          <div class="A3">

            <ul>

              <li>cookire perfernces</li>
              <li>Corporate information</li>
            </ul>
          </div>

          <div class="section">
            <select name="" id="">
              <option value="english">English</option>
              <option value="hindi">Hindi</option>
            </select>
          </div>
          </div>

        </div>
    </div>
</body>
</html>
