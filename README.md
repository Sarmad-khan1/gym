<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fitness Hub</title>
    <link rel="stylesheet" href="css/style.css">
    <style>
        body {
            margin: 0px;
            padding: 0px;
            background: url('images/bg.png');
            color: white;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;

        }

        .left {
            display: inline-block;
            position: absolute;
            left: 60px;
            top: 20px;

            text-align: center;
        }

        .left img {
            width: 70px;
            filter: invert(100%);
            background-repeat: no-repeat;
        }

        .left div {
            text-align: center;
            font-size: 27px;
            line-height: 30px;
        }

        .mid {
            display: block;
            width: 53%;
            margin: 20px auto;

        }

        .right {
            position: absolute;
            right: 33px;
            top: 34px;
            display: inline-block;
        }

        .navbar {
            display: inline-block;
        }

        .navbar li {
            display: inline-block;
            font-size: 25px;
        }

        .navbar li a {
            color: rgb(248, 224, 6);
            text-decoration: none;
            padding: 34px 23px;
        }

        .navbar li a:hover,
        .navbar a.active {
            text-decoration: underline;
            color: rgb(1, 248, 166);
        }

        .btn {
            margin: 0px 9px;
            color: white;
            background-color: rgb(255, 209, 5);
            padding: 4px 14px;
            border-radius: 4px;
            font-size: 20px;
            cursor: pointer;
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;

        }

        .btn:hover {
            background-color: gray;
        }

        .container {
            margin: 70px 2px;
            border-right:4px solid yellow;
            padding: 70px 90px;
            width: 33%;
            display: inline-block;
            border-radius: 24px;
            font-size: 18px;
            font-family:Verdana, Geneva, Tahoma, sans-serif;

        }

        .form-group input {
            text-align: center;
            width: 460px;
            margin: 11px auto;
            padding: 1px;
            font-size: 25px;
            display: block;
            border-radius: 12px;
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;

        }

        .container h1 {
            text-align: center;
            color:yellow;
            background-color:red;
        }

        .container button {
            display: block;
            width: 94%;
            margin: 20px auto;
            border-radius: 15px;
        }
    </style>
</head>

<body>
    <header class="header">
        <div class="left">
            <img src="images/logo.png">
            <div>Fitness Club</div>
        </div>





        <div class="mid">
            <ul class="navbar">
                <li><a href="#">Home</a><!--class="active"!--></li>
                <li><a href="#">About us </a></li>
                <li><a href="#"> Fitness Calculator</a></li>
                <li><a href="#"> Contact us</a></li>
            </ul>
        </div>




        <div class="right">
            <button class="btn">Call us</button>
            <button class="btn">Email us</button>


        </div>

    </header>
    <div class="container">
        <h1>Join the best gym of Lahore now</h1>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Name">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Age">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Gender">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Locality">
            </div>
            <button class="btn">Submit</button>
        </form>

    </div>
</body>

</html>
