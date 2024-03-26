
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Gym website </title>
    <link href="https://fonts.googleapis.com/css?family=Baloo+Bhai&display=swap" rel="stylesheet">
    <style>
        body {
            padding: 0px;
            margin: 0px;
            background-image: url(sushil-ghimire-5UbIqV58CW8-unsplash.jpg);
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
            width: 100%;
            height: 100vh;
            color: white;
            font-family: 'Baloo Bhai', cursive;
        }

        .left {
            /* border: 2px solid red; */
            width: 100px;
            height: 50px;
            display: inline-block;
            position: absolute;
            top: 15px;
            left: 60px;
            text-align: center;


        }

        .mid {
            /* border: 2px solid green; */
            width: 650px;
            height: 50px;
            display: block;
            margin: 10px auto;
            margin-left: 220px;
        }

        .right {
            /* border: 2px solid yellow; */
            width: 200px;
            height: 50px;
            display: inline-block;
            position: absolute;
            top: 20px;
            right: 30px;
        }

        .logogym {
            height: 70px;
            width: 100px;
            filter: invert(100%);
        }

        .navbar {
            display: inline-block;
            width: 639px;
        }

        .navbar li {
            display: inline-block;
            font-size: 25px;
        }

        .navbar li a {
            margin: 12px;
            text-decoration: none;
            color: rgb(158, 156, 156);
        }

        .navbar li a:hover,
        .navbar li .active {
            color: white;
            text-decoration: underline;
            font-family: '';
        }

        .btn {
            width: 98px;
            height: 45px;
            border-radius: 20px;
            cursor: pointer;
            background-color: black;
            color: white;
            border: 2px solid grey;
            font-family: 'Baloo Bhai', cursive;
            transition: ease 1s;
        }

        .btn:hover {
            background-color: grey;
            transform: scale(1.2);
        }

        .container {
            /* border:1px solid white; */
            width: 400px;
            position: absolute;
            top: 190px;
            left: 35px;
            text-align: center;

        }

        .form-group input {
            width: 350px;
            margin: 5px auto;
            text-align: center;
            border-radius: 8px;
            border: 1px solid white;
            padding: 5px;
            font-family: 'Baloo Bhai', cursive;
            transition: ease 3s;
            cursor: pointer;

        }
        .form-group input:hover{
            transform: scale(0.8);
        }

        .container h1 {
            text-align: center;
            transition: ease 3s;
        }

        .container h1:hover {
            transform: scale(0.8);
          
        }

        .container button {
            width: 350px;

        }
    </style>
</head>

<body>
    <header class="header">
        <div class="left">
            <img src="dumbbell.png" class="logogym">
            <div>SUMIT GYM</div>

        </div>
        <div class="mid">
            <div class="navbar">
                <ul>
                    <li><a href="#" class="active">Home</a></li>
                    <li><a href="#">About Us</a> </li>
                    <li><a href="#">Fitness Calculator </a> </li>
                    <li> <a href="#"> Contact Us</a></li>
                </ul>
            </div>

        </div>
        <div class="right">

            <button class="btn"> Call us Now</button>
            <button class="btn"> Email Us</button>

        </div>

    </header>

    <div class="container">
        <h1> Join The Best Gym In Delhi</h1>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" placeholder="Enter Your Name">
            </div>
            <div class="form-group">
                <input type="text" placeholder="Enter Your Age">
            </div>
            <div class="form-group">
                <input type="text" placeholder="Enter Your Gender">
            </div>
            <div class="form-group">
                <input type="text" placeholder="Enter Your Locality">
            </div>
            <div class="form-group">
                <input type="text" placeholder="Enter Your Email Id">
            </div>
            <div class="form-group">
                <input type="text" placeholder="Enter Your Phone No.">
            </div>

            <button class="btn"> Submit Now</button>

        </form>

    </div>

</body>

</html>
