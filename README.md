# GYM-WEBSITE
My First Website just as a frontend...

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Babbar Gym</title>
</head>
<link rel="stylesheet" href="css/style.css">
<!-- <link rel="preconnect" href="https://fonts.googleapis.com"> -->
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2:wght@500&display=swap" rel="stylesheet">
<style>
    /* CSS reset */
    body{
        font-family: 'Baloo Bhai 2', cursive;
        color: white;
        margin: 0px;
        padding: 0px;
        background: url('projects/katie-deadlift.jpg');
        height: 4544px;
    }
    .left{
        display: inline-block;
        /* border: 2px groove white; */
        position: absolute;
        top: 20px;
        left: 30px;
        

    }
    .mid{
        /* border: 2px groove yellow; */
display: block;
width: 33%;
margin: 20px auto;
top: 20px;

    }
    .right{
        display: inline-block;
        /* border: 2px groove lightpink; */
        position: absolute;
        right: 34px;
        top:20px;

    }
    .navbar{
        display: inline-block;
    }
    .navbar li{
        display: inline-block;
        font-size: 16px;
        
    }
    .navbar li a{
        color:white;
        text-decoration: none;
        padding: 10px  ;
    }
    .navbar li a:hover,.navbar li a.active{
        text-decoration: underline;
        color: grey;
    }
    .left img{
        width: 90px;
        filter: invert(100%);
    }
    .left div{
        line-height: 19px;
        font-size: 20px;
        text-align: center;
    }
    .btn{
        font-family: 'Baloo Bhai 2', cursive;
        margin: 0px 9px;
        background-color: black;
        color: white;
        padding: 4px 14px;
        border: 2px groove cyan;
        border-radius: 10px;
        font-size: 15px;
        cursor: pointer;

    }
    .btn:hover{
         background-color: grey;
    }
    .container{
        border: 2px groove yellow;
        margin: 100px 80px;
        padding: 75px;
        width: 33%;
        border-radius: 30px;
    }
    .form-group input{
        text-align: center;
        display: block;
        width: 344px;
        padding:6px;
        border: 2px solid white;
        margin: 8px auto;
        border-radius: 28px;
        font-size: 25px;
        font-family: 'Baloo Bhai 2', cursive;


    }
    .container h1{
        text-align: center;
    }
    .container button{
        display: block;
        width: 80px;
        margin: 2px auto;
    }
    
</style>
<body>
    <header class="header">
        <div class="left">
            <img src="projects/babbar.jfif" alt="">
            <div>babbar GYM</div>
       </div>
       <div class="mid">
        <ul class="navbar">
            <li> <a href="#" class="active">Home</a></li>
            <li> <a href="#">About us</a></li>
            <li><a href="#" >Fitness calculator</a></li>
            <li><a href="#" >Contact us</a></li>
        </ul>
               
       </div>
       <div class="right">
<button class="btn">call us</button>
<button class="btn">Email us</button>
       </div>
    </header>
    <div class="container">
        <h1>Join The Best Gym Now</h1>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" name="" placeholder="enter your name">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="enter your Age">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="enter your gender">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="enter your Mobile No.">
            </div>
            <button class="btn">Submit</button>
        </form>
    </div>
</body>
</html>
