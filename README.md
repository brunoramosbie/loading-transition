<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <link rel="stylesheet" href="style.css">
    
</head>

<body>
    <div class="container loader">
        <span>L</span>
        <span>O</span>
        <span>A</span>
        <span>D</span>
        <span>I</span>
        <span>N</span>
        <span>G</span>
    </div>
</body>
body {
    background: #2b2b2b;
    margin: 0;
    padding: 0;
}

.loader {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translateX(-50%) translateY(-50%);
}

.loader span {
    color: rgba(255, 255, 255, 0.1);
    font-family: Arial, Helvetica, sans-serif;
    font-size: 24px;
    display: inline-block;
    transition: all .5s;
    animation: animate 2s infinite;
}

.loader span:nth-child(1) {
    animation-delay: .1s;
}

.loader span:nth-child(2) {
    animation-delay: .2s;
}

.loader span:nth-child(3) {
    animation-delay: .3s;
}

.loader span:nth-child(4) {
    animation-delay: .4s;
}

.loader span:nth-child(5) {
    animation-delay: .5s;
}

.loader span:nth-child(6) {
    animation-delay: .6s;
}

.loader span:nth-child(7) {
    animation-delay: .7s;
}

@keyframes animate {
    0% {
        color: rgba(255, 255, 255, 0.1);
        transform: translateY(0);
        margin-left: 0;
    }
    25% {
        color: yellow;
        transform: translateY(-15px);
        margin-left: 10px;
        text-shadow: 0 15px 5px rgba(0, 0, 0, 1);
    }
    100% {
        color: rgba(255, 255, 255, 0.1);
        transform: translateY(0);
    }
}

</html>
