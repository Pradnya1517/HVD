# HVD
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Valentine's Week</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <h1>Happy Valentine's Day</h1>
    <h3>"The Best Thing To Hold Onto In Life Is Each Other"</h3>

    <div class="whole-heart">
        <div class="peace-of-heart"></div>
    </div>
</body>
</html>

style.css
body{
    background-color: #ee8c86;
    background-image: linear-gradient(45deg, #EE8c68, #E86B9D);
    overflow: hidden;
    width: 100%;
    height: 100vh;
    font-family: serif;
}

h1 {
    color: #8B0000;
    position: absolute;
    bottom: 10%;
    width: 100%;
    text-align: center;
    letter-spacing: 1px;
}

h3 {
    color: #660000;
    position: absolute;
    top: 10%;
    transform: translateY(-10%);
    width: 100%;
    text-align: center;
    font-size: 1.5em;
    letter-spacing: 2px;
}

.whole-heart {
    position: absolute;
    left: 50%;
    top: 50%;
    box-shadow: 0px 0 0 7px #FF160c, 18px 0 0 7px #FF160c, 
    36px 0 0 7px #FF160c, 108px 0 0 7px #FF160c,
    -18px 18px 0 7px #FF160c, 0px 18px 0 7px #FF160c,
    18px 18px 0 7px #FF160c, 36px 18px 0 7px #FF160c,
    54px 18px 0 7px #FF160c, 90px 18px 0 7px #FF160c,
    108px 18px 0 7px #FF160c, 126px 18px 0 7px #FF160c,
    162px 18px 0 7px #FF160c, -18px 36px 0 7px #FF160c,
    0px 36px 0 7px #FF160c, 18px 36px 0 7px #FF160c,
    36px 36px 0 7px #FF160c, 54px 36px 0 7px #FF160c,
    72px 36px 0 7px #FF160c, 90px 36px 0 7px #FF160c,
    108px 36px 0 7px #FF160c, 126px 36px 0 7px #FF160c,
    162px 36px 0 7px #FF160c, -18px 54px 0 7px #FF160c,
    0px 54px 0 7px #FF160c, 18px 54px 0 7px #FF160c,
    36px 54px 0 7px #FF160c, 54px 54px 0 7px #FF160c,
    72px 54px 0 7px #FF160c, 90px 54px 0 7px #FF160c,
    108px 54px 0 7px #FF160c, 126px 36px 0 7px #FF160c,
    144px 54px 0 7px #FF160c, 162px 54px 0 7px #FF160c,
    0px 72px 0 7px #FF160c, 18px 54px 0 7px #FF160c,
    36px 72px 0 7px #FF160c, 54px 72px 0 7px #FF160c,
    72px 72px 0 7px #FF160c, 90px 72px 0 7px #FF160c,
    108px 72px 0 7px #FF160c,126px 72px 0 7px #FF160c,
    144px 72px 0 7px #FF160c, 18px 90px 0 7px #FF160c,
    36px 90px 0 7px #FF160c, 54px 90px 0 7px #FF160c, 
    72px 90px 0 7px #FF160c, 90px 90px 0 7px #FF160c,
    108px 90px 0 7px #FF160c, 126px 90px 0 7px #FF160c,
    36px 108px 0 7px #FF160c, 54px 108px 0 7px #FF160c,
    72px 108px 0 7px #FF160c, 90px 108px 0 7px #FF160c,
    108px 108px 0 7px #FF160c,54px 126px 0 7px #FF160c,
    72px 126px 0 7px #FF160c, 90px 126px 0 7px #FF160c,
    72px 144px 0 7px #FF160c;
margin-left: -71px;
margin-top: -50;
animation: incompleteHeart 4s linear;
}

.whole-heart .peace-of-heart {
    position:absolute;
    left: 50%;
    top: 50%;
    box-shadow: 126px 0px 0 7px #FF160c, 144px 0px 0 7px #FF160c, 
        144px 18px 0 7px #FF160c, 144px 36px 0 7px #FF160c;
    animation: completeHeart 4s linear;
}

@keyframes incompleteHeart {
    0%,90% {
        box-shadow: 0px 0 0 7px #DDD, 18px 0 0 7px #DDD, 
            36px 0 0 7px #DDD, 108px 0 0 7px #DDD,
            -18px 18px 0 7px #DDD, 18px 0 7px #DDD,
            18px 18px 0 7px #DDD, 36px 18px 0 7px #DDD,
            54px 18px 0 7px #DDD, 90px 18px 0 7px #DDD,
            108px 18px 0 7px #DDD, 126px 18px 0 7px #DDD,
            162px 18px 0 7px #DDD, -18px 36px 0 7px #DDD,
            0px 36px 0 7px #DDD, 18px 36px 0 7px #DDD,
            36px 36px 0 7px #DDD, 54px 36px 0 7px #DDD,
            72px 36px 0 7px #DDD, 90px 36px 0 7px #DDD,
            108px 36px 0 7px #DDD, 126px 36px 0 7px #DDD,
            162px 36px 0 7px #DDD, -18px 54px 0 7px #DDD,
            0px 54px 0 7px #DDD, 18px 54px 0 7px #DDD,
            36px 54px 0 7px #DDD, 54px 54px 0 7px #DDD,
            72px 54px 0 7px #DDD, 90px 54px 0 7px #DDD,
            108px 54px 0 7px #DDD, 126px 36px 0 7px #DDD,
            144px 54px 0 7px #DDD, 162px 54px 0 7px #DDD,
            0px 72px 0 7px #DDD, 18px 54px 0 7px #DDD,
            36px 72px 0 7px #DDD, 54px 72px 0 7px #DDD,
            72px 72px 0 7px #DDD, 90px 72px 0 7px #DDD,
            108px 72px 0 7px #DDD,126px 72px 0 7px #DDD,
            144px 72px 0 7px #DDD, 18px 90px 0 7px #DDD,
            36px 90px 0 7px #DDD, 54px 90px 0 7px #DDD, 
            72px 90px 0 7px #DDD, 90px 90px 0 7px #DDD,
            108px 90px 0 7px #DDD, 126px 90px 0 7px #DDD,
            36px 108px 0 7px #DDD, 54px 108px 0 7px #DDD,
            72px 108px 0 7px #DDD, 90px 108px 0 7px #DDD,
            108px 108px 0 7px #DDD,54px 126px 0 7px #DDD,
            72px 126px 0 7px #DDD, 90px 126px 0 7px #DDD,
        72px 144px 0 7px #DDD;
    } 
}

@keyframes completeHeart {
    0%, 24% { 
        box-shadow: 126px -72px 0 7px #FF160c,
        144px -72px 0 7px #FF160c,
        144px -54px 0 7px #FF160c,
        144px -36px 0 7px #FF160c;
    }

    25%, 49% { 
        box-shadow: 126px -54px 0 7px #FF160c,
        144px -54px 0 7px #FF160c,
        144px -36px 0 7px #FF160c,
        144px -18px 0 7px #FF160c;
    }

    50%, 74% { 
        box-shadow: 126px -36px 0 7px #FF160c,
        144px -36px 0 7px #FF160c,
        144px -18px 0 7px #FF160c,
        144px 0px 0 7px #FF160c;
    }

    75%, 99% {
        box-shadow: 126px -18px 0 7px #FF160c,
        144px -18px 0 7px #FF160c,
        144px 0px 0 7px #FF160c,
        144px 18px 0 7px #FF160c;
    }

    100% {
        box-shadow: 126px 0px 0 7px #FF160c,
        144px 0px 0 7px #FF160c,
        144px 18px 0 7px #FF160c,
        144px 36px 0 7px #FF160c;
    }
}
