# logo-img
    Position not centered

    valkommen.html
    <div>
        <a href="valkommen.html">
            <img class="logo-img" src="./image/logo.png" alt="Hofra B&B Breakfast">
        </a>
    </div>

    stylesheet.css
    .logo-img {
        heigth: 150px;
        position: center;
    }


    Result after research thru old repositories, Google and testing

    valkommen.html
    <div class="logo-img">&nbsp;
        <a href="valkommen.html"></a>
    </div>

    stylesheet.css
    .logo-img {
        background: url("../images/logo.png") no-repeat;
        background-size: contain;
        background-position: center;
        height: 8vh;
    }