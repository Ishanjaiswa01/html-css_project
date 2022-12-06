# html-css_project
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Document</title>
<link rel="stylesheet" href="style.css">
</head>

<body>
<div class="head">
<header>
<div class="navlink"></div>
<img src="C:\Users\HP\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\9161AB7A1B61012C4C303F10B4C16B2C\loho.png" alt="logo" style="height:200px">
<a href="">For Home</a>
<a href="">For Business</a>
<a href="">For Industries</a>
<a href="">About Us</a>

</div>
</header>
</div>
<section style="height: fit-content;">
<div class="grid-container">
<div class="grid-item" id="item1">
<div class="login-form">
<form action="">
<input type="text" name="username" id="username" placeholder="Username / Email-Id">
<br>
<input type="password" name="password" placeholder="Password">
<input type="checkbox" name="check" id="checkbox">
<label for="checkbox">Remember me</label>
<a href="#" id="forgot-password">Forgot Password</a>
<input type="submit" value="Login">
<a href="#" class="newuser">New User / Register</a>
<h4>Or</h4>
<div class="socialmedia">
<div class="links" style="background-color: #CF473C;">
<a href="http://www.google.com" target="_blank">Google</a>
</div>
</div>
<p style="font-size: 12px; text-align: center;">By creating this account,you agree to our <a
href="#" style="text-decoration: none; color:#08830a;">Privacy
Policy</a> &amp; <a href="#" style="text-decoration: none; color:#08830a;">Cookie
Policy.</a> </p>
</form>
</div>
</div>

<div class="grid-item" id="item2">
    <h1 style="color:black">How to save Electricity?</h1>
    <br>
    <p style="font-size: 22px;">
    1. Watch out for energy-draining appliances.</p>
    <p style="font-size: 22px;">          
    2.Switch off when not in use to save electricity & conserve energy.</p>
    <p style="font-size: 22px;">
    3. Smart power strips help to manage usage the smart way.</p>
    <p style="font-size: 22px;">
    4. Use large appliances together to reduce energy use.</p>
    <p style="font-size: 22px;">
    5. Dry your clothes and dishes naturally.</p>
    <p style="font-size: 22px;">
    6. Reduce usage during peak hours..</p>
   
<img src="" alt="" height="210px">
</div>
<div class="grid-item" id="item3">
<h2 style="padding: 10px; margin-bottom: 50px;">Quick Links</h2>
<div class="qlinks">
<a href="">1. Pay your Bills.</a><br>
<a href="">2. Consumption History </a><br>
<a href="">3. Nearest Service</a><br>
<a href="">4. Next Connection</a><br>
<a href="">5. Maintainance Service</a><br>
</div>
</div>


<div class="grid-item" id="item5" >
<h4>High Consumption States</h4>
<ul style="font-size: 20px; text-align: left;">
<li>Gujarat</li>
<li>Andhra Pradesh</li>
<Li>Maharashtra</Li>
<li>Tamil Nadu</li>
<li>Punjab</li>
<li>Haryana</li>
<li>Rajasthan</li>
<li>Uttar Pradesh</li>
</ul>
</div>

<div class="grid-item" id="item7">
<!-- <h4 style="display: inline;margin: 3px;padding: 2px;">FAQs</h4> -->
 <h1>FAQS</h1>  
<details>
    <summary><h4>1. How to find the electricity bill consumer number? </h4></summary>
    <p><h6>Consumer number, K Number, CA Number, CON ID etc. are the unique identification numbers that are
        used to identify every unique user.To help you find this number, we have uploaded the sample bills on every board electricity
        payment page.Go to your respective electricity board bill payment page on Paytm and click on ‘View Sample
        Bill’.See where is the unique identification number is on your electricity bill. </h6></p>
</details>
        <details>
            <summary><h4>2. What is arrear in electricity bill?</h4></summary>
            <p><h6>An arrear is financial and a legal term which is associated with the overdue payment.
                It generally means that the user hasn’t made the payment before the due date.
                So when you miss your electricity bill payment before the due date, your account will be in
                arrear. </h6></p>
        </details>

    <details>
        <summary><h4> 3.How To Calculate electricity bill from meter reading ?</h4></summary>
        <p class="fon"><h6>To calculate your bill from your meter reading, you need to follow these steps- 
            Check and note down the meter reading. This value is in kWh (KiloWatt Hour). Check the last month’s reading on the last month’s 
            bill Subtract the last month’s reading from current month’s reading. This is the energy used by you since last month. 
            Now multiply the number obtained to charges per kWh. This will indicate your Total Energy Charge Now add Total Energy 
            Bill to the Fixed Monthly Charge. This will be your total bill.</h6></p>
    </details>
</div>

</div>
</section>
<section class="second">
<div class="custom-shape-divider-top-1669678223">
<svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120"
preserveAspectRatio="none">
<path
d="M321.39,56.44c58-10.79,114.16-30.13,172-41.86,82.39-16.72,168.19-17.73,250.45-.39C823.78,31,906.67,72,985.66,92.83c70.05,18.48,146.53,26.09,214.34,3V0H0V27.35A600.21,600.21,0,0,0,321.39,56.44Z"
class="shape-fill"></path>
</svg>
</div>
<center> <h1> INDIAN ELECTRICITY</h1></center>





<script src="C:\Users\Victus\OneDrive\Desktop\INT\style1.css"></script>


</section>

</body>
</html>
###css coding


 * {
    margin: 0px;

 }
    header {
    background-color: #ff7722;
    width: 98%;
    height: 200px;
    box-shadow: 16px 10px 18px black;
    position: sticky;
    border-radius: 10px;
    margin-left: 8px;
    margin-top: 5px;
    }
    
    .navlink {
    display: flex;
    flex-direction: row;
    
    }
    
    
    header a {
    box-sizing: content-box;
    text-decoration: none;
    padding: 20px;
    border-radius: 4px;
    background-color: white;
    color: #1b02fa;
    margin-left: 50px;
    text-align: center;
    box-shadow: inset 0px 1px 10px black;
    }
    
    #searchbar1 {
    margin-left: 120px;
    padding: 15px;
    box-shadow: inset 0px 1px 10px black;
    }
    
    .grid-container {
    display: grid;
    grid-template-columns: auto auto auto;
    
    padding: 10px;
    margin-top: 60px;
    grid-gap: 9px;
    height: 800px;
    }
    
    .grid-item {
    background-color: rgba(255, 255, 255, 0.8);
    padding: 20px;
    font-size: 30px;
    text-align: center;
    }
    
    
    #item1 {
    grid-row-start: 1;
    grid-row-end: 3;
    height: 500px;
    width: 500px;
    background-image: url(https://images.unsplash.com/photo-1507668077129-56e32842fceb?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=774&q=80);
    background-repeat: no-repeat;
    background-size: cover;
    box-shadow: 11px 5px 20px 0px #5c5b5b;
    }
    
    #item7 {
    grid-row-start: 3;
    grid-row-end: 10;
    width: 500px;
    box-shadow: 11px 5px 20px 0px #5c5b5b;
    z-index: 1;
    }
    
    #item2 {
    grid-row-start: 1;
    grid-row-end: 11;
    height: 720px;
    width: 400px;
    box-shadow: 11px 5px 20px 0px #5c5b5b;
    }
    
    #item3 {
    width: 376px;
    height: 400px;
    display: flex;
    flex-direction: column;
    box-shadow: 11px 5px 20px 0px #5c5b5b;
    background-image: url(45.png);
    background-repeat: no-repeat;
    background-size: cover;
    }
    
    #item5 {
    box-shadow: 11px 5px 20px 0px #5c5b5b;
    }
    
    .login-form {
    width: 400px;
    height: 410px;
    border-radius: 5px;
    margin: auto;
    margin-top: 20px;
    padding: 15px;
    background-color: rgba(255, 254, 255, 0.728);
    }
    
    input[type="text"],
    input[type="password"] {
    width: 90%;
    padding: 7px;
    margin: auto;
    display: block;
    border: 1px solid black;
    text-align: center;
    font-size: 15px;
    }
    
    input[type="checkbox"] {
    margin-left: 12px;
    margin-top: 20px;
    }
    
    label {
    font-size: 16px;
    }
    
    #forgot-password {
    text-decoration: none;
    margin-left: 130px;
    color: #100088;
    font-size: 16px;
    }
    
    input[type="submit"] {
    width: 95%;
    margin: auto;
    display: block;
    padding: 10px;
    font-size: 15px;
    margin-top: 15px;
    border: none;
    border-radius: 3px;
    background-color: #08830a;
    color: white;
    margin-bottom: 7px;
    }
    
    .login-form h4 {
    text-align: center;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-weight: 100;
    
    }
    
    .newuser {
    text-decoration: none;
    margin-left: 37%;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 13px;
    color: #0e0458;
    }
    
    .socialmedia {
    display: flex;
    width: 100%;
    height: 50px;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
    }
    
    .socialmedia2 {
    display: inline-flex;
    width: 100%;
    height: 50px;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
    }
    
    .links {
    width: 110px;
    height: 35px;
    border-radius: 5px;
    text-align: center;
    font-size: 25px;
    box-shadow: 0px 0px 8px rgb(0, 0, 0);
    }
    
    .links a {
    text-decoration: none;
    color: white;
    margin-top: 10px;
    font-size: 16px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    
    }
    .qlinks a {
    text-decoration: none;
    font-size: 25px;
    color: #000000;
    text-align: center;
    padding: 9px;
    }
    
    .second {
    height: 300px;
    background-color:green;
    }
    
    .custom-shape-divider-top-1669678223 {
    position: absolute;
    top: 1085px;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
    }
    
    .custom-shape-divider-top-1669678223 svg {
    position: relative;
    display: block;
    width: calc(148% + 1.3px);
    height: 205px;
    }
    
    .custom-shape-divider-top-1669678223 .shape-fill {
    fill: #ffffff;
    }
    .fon{
        font-family: Arial, Helvetica, sans-serif;
    }
    .ptp{
        background-image: url("electric image.jpg");
        height: fit-content;
    }



