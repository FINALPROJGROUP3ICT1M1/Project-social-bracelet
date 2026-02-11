# Project-social-bracelet
<!DOCTYPE html>
<html>
<head>
    <title>Gabriel Angelo Torejas</title>

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-image: url("background.jpg"); /* your purple sky image */
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            color: black;
        }

        .container {
            display: flex;
            justify-content: space-between;
            padding: 60px;
        }

        .left {
            width: 50%;
        }

        .right {
            width: 40%;
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .right img {
            width: 200px;
            height: 200px;
            object-fit: cover;
        }

        h1 {
            text-align: center;
            margin-top: 40px;
            font-size: 40px;
        }

        h2 {
            font-size: 32px;
            margin-top: 30px;
        }

        p {
            font-size: 28px;
        }

        .social a {
            display: flex;
            align-items: center;
            font-size: 28px;
            text-decoration: none;
            color: black;
            margin: 15px 0;
        }

        .social i {
            font-size: 40px;
            margin-right: 15px;
        }

        .facebook {
            color: #1877F2;
        }

        .instagram {
            color: #E1306C;
        }
    </style>
</head>

<body>

    <h1>Hello I am Gabriel Angelo Torejas</h1>

    <div class="container">

        <!-- LEFT SIDE -->
        <div class="left">

            <h2><b>Hobby</b></h2>
            <p>- playing chess</p>

            <h2><b>Social Media</b></h2>

            <div class="social">
                <a href="https://www.facebook.com/gabriel.torejas.2024" target="_blank" class="facebook">
                    <i class="fab fa-facebook"></i> VIEW PROFILE
                </a>

                <a href="https://www.instagram.com/gab_real284/" target="_blank" class="instagram">
                    <i class="fab fa-instagram"></i> VIEW PROFILE
                </a>
            </div>

            <h2><b>Favorite Music</b></h2>
            <p>- Pajama Party by 1096 Gang</p>

        </div>

        <!-- RIGHT SIDE (IMAGES) -->
        <div class="right">
            <img src="monkey.jpg" alt="Image">
            <img src="monkey.jpg" alt="Image">
            <img src="monkey.jpg" alt="Image">
        </div>

    </div>

</body>
</html>
