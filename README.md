<!DOCTYPE html>
<html lang="pl">
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="Statystyki Komunikacji GDAŃSK">
        <meta name="author" content="CELOFYZ DEV">
        <meta name="keywords" content="komunikacja, gdańsk, ztm, autobusy">
        <link rel="stylesheet" href="aga_pliki/resetcss.css">
        <link rel="stylesheet" href="css/style.css">
        <link href='https://fonts.googleapis.com/css?family=Poiret+One&subset=latin,latin-ext' rel='stylesheet' type='text/css'>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css">
        <link rel="shortcut icon" href="images/favicon.ico" type="image/x-icon" />
        <link rel="http://www.vectorhq.com/psd/vector-cavemen-illustrations-394204" rel="stylesheet" type="text/css">
        <title>Statystyki komunikacji ZTM Gdańsk</title>
    </head>
    <body>

            <header class="naglowek-strony">
                <div class="section">
                    <a href="#home">
                        <div class="logo-strony left">

                        </div>
                    </a>
                    <nav>
        <!--kamila-->
                        <ul id="menu" class="menu-glowne">
                            <li><a href="">menu</a></li>

                            <li><a href="#home">o nas</a></li>
                            <li><a href="#features">funkcje</a></li>
                            <li><a href="#form">wyślij zapytanie</a></li>
                            <li><a href="#social">polub nas</a></li>
                        </ul>
                    </nav>
                </div>
            </header>
        <main>

            <article id="home" class="welcome">
                <div class="section">
                    <div class="logo">
                        <img src="images/logo-autobus.png" alt="logo">
                    </div>
                    <div class="slogan">
                        <h1>Autobusem po Gdańsku</h1>
                        <p>Dbaj o środowisko! Jedź autobusem!
                            <br>Mniejsza emisja zanieczyszczeń,do tego większe oszczędności oraz krótszy czas dojazdu bez nerwowego stania w korkach - to tylko niektóre zalety korzystania z komunikacji miejskiej.</p>
                    </div>
                </div>
            </article>
            <!--sekcja funkcje agnieszka-->
            <!--http://www.bihapi.pl/media/uploads/dokumentacja-api-bihapi/gdansk/gdansk_komunikacja_publiczna_statystyki.pdf-->
            <article id="features" class="features-container ">
                <h2>Poznaj korzyści z jazdy autobusem</h2>
                <div class= "feature left">
                    <a href="" target="_blank">
                        <div class="feature-image feature-image-1"></div>
                        <h3>Rozkład jazdy</h3>
                    </a>
                    <p>W tym miejscu znajdziesz niezbędne informacje na temat linii autobusowych, przystanków i rozkładów jazdy.</p>
                </div>
                <div class= "feature left">
                    <a href="" target="_blank">
                        <div class="feature-image feature-image-2"></div>
                        <h3>Wirtualny przystanek </h3>
                    </a>
                    <p>Bez wychodzenia z domu sprawdzisz ile masz czasu do odjazdu wybranego autobusu.</p>
                </div>
                <div class= "feature left">
                    <a href="" target="_blank">
                        <div class="feature-image feature-image-3"></div>
                        <h3> Mobilnie</h3>
                    </a>
                    <p>Wystarczy telefon a każdy rozkład masz w zasięgu ręki - spróbuj jakie to proste!</p>
                <!--<div style="clear:both;"></div>-->
                </div>
            </article>

                <!--sekcja frmularz marcin - marcin dodalam id form do article, zeby sie ladnie formatowalo-->
            <div class="clear"></div>

            <article class ="small-icons-container" >

                <div class="small-icons "title="Lista linii autobusowych"> <i class="fa fa-table"></i></div>
                <div class="small-icons " title="Trasy"> <i class="fa fa-map" ></i></div>
                <div class="small-icons " title="Lista przystanków"> <i class="fa fa-map-marker" ></i></div>
                <div class="small-icons " title="Czas przyjazdu"> <i class="fa fa-clock-o" ></i></div>
                <div class="small-icons " title="Ceny biletów"> <i class="fa fa-ticket" ></i></div>
                <div class="small-icons " title="Kup mobilny bilet"> <i class="fa fa-mobile" ></i></div>


            </article>
            <article>

            <div class="O nas">
                <div class="small-icons" title="Agnieszka">
                <img src="http://images.vectorhq.com/images/previews/4f5/vector-travel-girl-character-71854.jpg">
</div>
            </div>
            </article>

            </div>

            <article id="form" class="formularz">

                <h2>Zapytaj nas o nasz produkt</h2>
                <form action="http://jfdd.infoshareaca.nazwa.pl/mailer.php" method="POST">
                    <div>
                        <input type="text" name="telefon" required pattern="^[0-9]*" placeholder="podaj numer telefonu" title="Podaj tylko liczby"><br>
                        <input type="text" name="email" required pattern="^\S+@\S+\.\S+$" title="Podaj prawidłowy email" placeholder="podaj email">
                    </div>
                    <div class="zgoda">
                        <input type="checkbox" required title="Musisz wyrazić zgodę">Wyrażam zgodę na działania marketingowe
                    </div>

                    <div id="moveM" class="mousemove">


                        <p>Poruszaj myszką żeby odblokować formularz</p>
                        <span id="pole" >100</span>
                        <div class="mmwidth"></div>

                    </div>

                    <input type="hidden" name="receiver" value="wojciech.makurat@infoshareacademy.com">
                    <!--<input type="hidden" name="receiver" value="z@z.com">-->

                <button type="submit" value="Send" disabled id="przycisk">Wyślij Zapytanie</button>
                </form>




            </article>
            <article>
                <div class="about">

                </div>

            </article>
            <!--sekcja sm marcin-->
            <article id="social" class="social-media">
                <h2>Polub nas!</h2>
                    <div class="sm-ico fb"><a href="http://www.facebook.com" target="_blank"><i class="fa fa-facebook fa-2x"></i></a></div>
                    <div class="sm-ico gplus"><a href="http://plus.google.com"><i class="fa fa-google-plus fa-2x"></i></a></div>
                    <div class="sm-ico tw"><a href="http://www.twitter.com"><i class="fa fa-twitter fa-2x"></i></a></div>
                    <div class="clear"></div>
            </article>




        </main>
        <footer class="footer">
            &copy; infoshare academy 2016 / design celofyz <!-- agnieszka -->
        </footer>

<!-- Skrypty JS -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<script src="js/script.js"></script>

</body>
</html>




CSSSSS
/*@import url("https://fonts.googleapis.com/css?family=Poiret+One&subset=latin,latin-ext");*/

/*style głowne*/
body {
    color: #B30800;
    font-family: 'Poiret One', cursive;
    font-size: 20px;
    margin-left: auto;
    margin-right: auto;
}

/*h1 {*/
    /*font-size: 45px;*/
    /*font-weight: 600;*/
/*}*/

h2 {
    font-size: 40px;
    font-weight:900;
    margin-bottom: 25px;
}

h3 {
    font-size: 30px;
    font-weight:600;
    text-decoration: none;
    margin-bottom: 15px;
    margin-top: 15px;
}

h4 {
    font-size: 20px;
    font-weight:600;
}

/*style menu*/

.section {
    width: 1000px;
    margin-right: auto;
    margin-left: auto;
}

.naglowek-strony {
    position: fixed;
    z-index: 1000;
    top:0;
    width: 100%;
    height: 80px;
    border-bottom: 2px solid #B30800;
    background-color: white;
    margin-top: 0;
    box-shadow: 0 1px 2px 0 rgba(179,8,0,0.3);
}

.naglowek-strony .logo-strony{
    width: 60px;
    height:60px;
    background-image: url('../images/logo-autobus.png');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: contain;
    margin-left: 10px;
    margin-top: 10px;
}

.menu-glowne {
    /*list-style-type: none;*/
    font-size: 20px;
    font-weight: 600;
    text-align: right;
}

.menu-glowne > li {
    display: inline-block;
    margin-top: 25px;
    margin-left: 50px;
}

.menu-glowne > li > a {
    color: #A20700;
    font-size: 26px;
    text-decoration: none;
    font-weight: 600;
}

.menu-glowne > li > a:hover {
    color: #f02541;
}

/*style welcome*/

.welcome {
    height: 700px;
    align-items:center;
    display:flex;
    color: white;
    background-image: url("../images/public-transport-1920-03r.jpg");
    background-size: cover;
    border-bottom: 10px solid #B30800;
    background-color: #B30800;
    margin-top: 80px;
}


.welcome img {
    height: 250px;
    width: 250px;
    margin-right: 40px;
    float: left;
}

.slogan {
    margin-left: 20px;
    margin-top: 50px;
}

.slogan h1 {
    margin-top: 0;
    font-size: 45px;
    font-weight: 600;
    margin-bottom: 20px;
}

.slogan p {
    font-size: 25px;
    font-weight: 600;
}

/*style features*/
.features-container {
    background-color: white;
    color: #B30800;
    letter-spacing: normal;
    text-align: center;
    margin-left: auto;
    margin-right: auto;
    margin-bottom: 25px;
    margin-top: 25px;
}

.feature {
    width: 32%;
    font-size:20px;
    font-weight: 600;
    padding-bottom: 15px;

}

.feature a{
    display: block;
    text-decoration: none;
    color: #B30800;

}

.feature .feature-image {
    height: 250px;
    width: 250px;
    margin: 5px auto;
    border: 5px solid #B30800;
    background-color:#B30800;
    border-radius: 50%;
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center center;
}

.feature .feature-image:hover {
    opacity: .5;
    transition: 5s easy;
}

.feature-image-1 {background-image: url('../images/feature-chair-600.jpg');}
.feature-image-2 {background-image: url('../images/feature-hand-600.jpg');}
.feature-image-3 {background-image: url('../images/feature-woman-600.jpg');}

.feature p {
    padding-left:10px;
    padding-right:10px;
}
.small-icons-container {
    margin-top:20px ;
    margin-bottom: 20px;
    margin-left: auto;
    margin-right: auto;
    text-align: center;
    }

.small-icons  {
    display: inline-block;
    margin: 20px;
    margin-right: 10px;
    text-align: center;
    padding: 10px;
    font-size: 60px;
    height: 70px;
    width: 70px;
    background-color:#B30800 ;
    border-radius: 50%;
    color:white;
    }

.small-icons:hover {
    transition: 1s;
    transform:rotate(360deg);
}


.formularz {
    background-color: #B30800;
    background-image: url('../images/public-transport-1920-02r.jpg');
    color:white;
    padding: 50px;
    text-align: center;
}

.formularz input {
    font-size: 1.2em;
    padding: 5px;
    margin: 5px;
    border-radius: 5px;
    box-shadow: 0 1px 4px 0 rgba(0,0,0,0.2);
}

.formularz button {
    padding: 10px;
    border-radius: 5px;
    font-size: 1em;
    color:#B30800;
    margin: 10px;
    background-color: white;
    box-shadow: 0 1px 4px 0 rgba(0,0,0,0.2);
}

.formularz button:hover {
    background-color: #B30800;
    color:#fff;
    box-shadow: 0 1px 1px 0 rgba(0,0,0,0.2);
    transition: 1s;
}

.formularz button:disabled {
    color: #cecece;
}

.formularz .mousemove {
    padding: 10px;
    margin: 10px auto;
    height: 50px;
    width: 400px;
    border: 1px solid #fff;
    font-size: .8em;
    border-radius: 5px;
    text-align: center;
    display: block;
    line-height: 1.5em;
    position: relative;
    z-index: 2;
}

.formularz .mousemove p,
.formularz .mousemove span {
    position: relative;
    z-index: 1;
}

.mmwidth {

    position: relative;
    height: 50px;
    background-color: red;
    background: linear-gradient(to right, rgba(255,0,0,0.2), rgba(255,0,0,.9));
    box-shadow: 0 1px 1px 0 rgba(0,0,0,0.2);
    border-radius: 5px;
    top: -50px;
    z-index: 0;
    opacity: 0.5;
}

.formularz .zgoda {
    font-size: .8em;
}

.social-media {
    margin: auto;
    text-align: center;
    padding: 20px;
    background-color: #B30800;
    color: floralwhite;
    border-top: 2px solid floralwhite;
}

.social-media .sm-ico {
    text-align: center;
    margin: 10px;
    width: 40px;
    height: 40px;
    padding: 10px;
    display: inline-block;
    border-radius: 5px;
    box-shadow: 0 1px 4px 0 rgba(0,0,0,0.2);
}

.social-media .sm-ico a {color: #fff;}
.social-media .sm-ico a:hover {color: #fff;}

.social-media .fb { background-color: #4668b3; }
.social-media .fb:hover { background-color: #3557a2; }
.social-media .gplus { background-color: #d95333; }
.social-media .gplus:hover { background-color: #c84222; }
.social-media .tw { background-color: #3095d3; }
.social-media .tw:hover { background-color: #2084c2; }

.footer {
    background-color: #222222;
    color: white;
    padding: 15px;
    text-align: center;
    font-size: 0.8em;
}
.right{float: right;}
.left {float: left;}
.clear{clear:both;}


