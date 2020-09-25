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

# Navigation bar

    Navigation bar used from Bootstrap "Navs" 
    When adding class= "Navbar", to add my own class name, the navigation items jumped from center to left side. After checking Bootstrap I noticed that Bootstrap is using this for its "Navbar's".
    Removed the class in total.

    Can't get space inbetwen nav-items
    Tried with different class path but nothing works.
    Wrote a message on Slack, suggestion was made to target .nav-item which I already tried which was not working.
    Jim Morel, Slack username: JimLynx_lead, and I had a call via Slack.
    
