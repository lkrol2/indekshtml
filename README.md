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
