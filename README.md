<!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        
        <link href='https://unpkg.com/boxicons@2.0.7/css/boxicons.min.css' rel='stylesheet'>

        
        <link rel="stylesheet" href="style1.css">

        <title>Responsive landing page</title>
    </head>
    <body>
       
        <a href="#" class="scrolltop" id="scroll-top">
            <i class='bx bx-up-arrow-alt scrolltop__icon'></i>
        </a>
        
       
        <header class="l-header" id="header">
            <nav class="nav bd-container">
                <a href="#" class="nav__logo">Christmas Gift</a>

                <div class="nav__menu" id="nav-menu">
                    <ul class="nav__list">
                        <li class="nav__item"><a href="#home" class="nav__link active-link">Home</a></li>
                        <li class="nav__item"><a href="#share" class="nav__link">Share</a></li>
                        <li class="nav__item"><a href="#decoration" class="nav__link">Decorations</a></li>
                        <li class="nav__item"><a href="#accessory" class="nav__link">Accessory</a></li>

                        <li><i class='bx bx-toggle-left change-theme' id="theme-button"></i></li>
                    </ul>
                </div>

                <div class="nav__toggle" id="nav-toggle">
                    <i class='bx bx-grid-alt'></i>
                </div>
            </nav>
        </header>

        <main class="l-main">
           
            <section class="home" id="home">
                <div class="home__container bd-container bd-grid">
                    <div class="home__img">
                        <img src="assets/img/home.png" alt="">
                    </div>

                    <div class="home__data">
                        <h1 class="home__title">Send A Gift For Christmas</h1>
                        <p class="home__description">In these end of the year holidays send a gift to your loved one and share the happiness at Christmas.</p>
                        <a href="#" class="button">Get Started</a>
                    </div>   
                </div>
            </section>

           
            <section class="share section bd-container" id="share">
                <div class="share__container bd-grid">
                    <div class="share__data">
                        <h2 class="section-title-center">Sharing Is The Best Gift <br> You Can Give</h2>
                        <p class="share__description">Sharing these holidays is the best gift you can give, give a present or share your love with the people you love the most and celebrate with great happiness.</p>
                        <a href="#" class="button">Send a Gift</a>
                    </div>

                    <div class="share__img">
                        <img src="assets/img/shared.png" alt="">
                    </div>
                </div>
            </section>

            
            <section class="decoration section bd-container" id="decoration">
                <h2 class="section-title">Give Christmas Decorations <br> For Your Home</h2>
                <div class="decoration__container bd-grid">
                    <div class="decoration__data">
                        <img src="assets/img/decoration1.png" alt="" class="decoration__img">
                        <h3 class="decoration__title">Christmas Bells</h3>
                        <a href="#" class="button button-link">Go Shopping</a>
                    </div>

                    <div class="decoration__data">
                        <img src="assets/img/decoration2.png" alt="" class="decoration__img">
                        <h3 class="decoration__title">Christmas Candies</h3>
                        <a href="#" class="button button-link">Go Shopping</a>
                    </div>

                    <div class="decoration__data">
                        <img src="assets/img/decoration3.png" alt="" class="decoration__img">
                        <h3 class="decoration__title">Christmas Trees</h3>
                        <a href="#" class="button button-link">Go Shopping</a>
                    </div>
                </div>
            </section>

           
            <section class="accessory section bd-container" id="accessory">
                <h2 class="section-title">New Christmas <br> Accessories</h2>

                <div class="accessory__container bd-grid">
                    <div class="accessory__content">
                        <img src="assets/img/accessory1.png" alt="" class="accessory__img">
                        <h3 class="accessory__title">Snow Globe</h3>
                        <span class="accessory__category">Accessory</span>
                        <span class="accessory__preci">$9.45</span>
                        <a href="#" class="button accessory__button"><i class='bx bx-heart'></i></a>
                    </div>

                    <div class="accessory__content">
                        <img src="assets/img/accessory2.png" alt="" class="accessory__img">
                        <h3 class="accessory__title">Candy</h3>
                        <span class="accessory__category">Accessory</span>
                        <span class="accessory__preci">$2.52</span>
                        <a href="#" class="button accessory__button"><i class='bx bx-heart'></i></a>
                    </div>

                    <div class="accessory__content">
                        <img src="assets/img/accessory3.png" alt="" class="accessory__img">
                        <h3 class="accessory__title">Angel</h3>
                        <span class="accessory__category">Accessory</span>
                        <span class="accessory__preci">$13.15</span>
                        <a href="#" class="button accessory__button"><i class='bx bx-heart'></i></a>
                    </div>

                    <div class="accessory__content">
                        <img src="assets/img/accessory4.png" alt="" class="accessory__img">
                        <h3 class="accessory__title">Sphere</h3>
                        <span class="accessory__category">Accessory</span>
                        <span class="accessory__preci">$4.25</span>
                        <a href="#" class="button accessory__button"><i class='bx bx-heart'></i></a>
                    </div>

                    <div class="accessory__content">
                        <img src="assets/img/accessory5.png" alt="" class="accessory__img">
                        <h3 class="accessory__title">Surprise gift</h3>
                        <span class="accessory__category">Accessory</span>
                        <span class="accessory__preci">$7.99</span>
                        <a href="#" class="button accessory__button"><i class='bx bx-heart'></i></a>
                    </div>
                </div>
            </section>

            
            <section class="send section">
                <div class="send__container bd-container bd-grid">
                    <div class="send__content">
                        <h2 class="section-title-center send__title">Send Gift Now</h2>
                        <p class="send__description">Start giving away before the holidays are over. Write the home address of the person who will send the gift.</p>
                        <form action="">
                            <div class="send__direction">
                                <input type="text" placeholder="House address" class="send__input">
                                <a href="#" class="button">Send</a>
                            </div>
                        </form>
                    </div>

                    <div class="send__img">
                        <img src="assets/img/send.png" alt="">
                    </div>
                </div>
            </section>
        </main>

        <footer class="footer section">
            <div class="footer__container bd-container bd-grid">
                <div class="footer__content">
                    <h3 class="footer__title">
                        <a href="#" class="footer__logo">Christmas Gift</a>
                    </h3>
                    <p class="footer__description">I sent a gift and it gives <br> happiness</p>
                </div>

                <div class="footer__content">
                    <h3 class="footer__title">Our Services</h3>
                    <ul>
                        <li><a href="#" class="footer__link">Pricing </a></li>
                        <li><a href="#" class="footer__link">Discounts</a></li>
                        <li><a href="#" class="footer__link">Shipping mode</a></li>
                    </ul>
                </div>

                <div class="footer__content">
                    <h3 class="footer__title">Our Company</h3>
                    <ul>
                        <li><a href="#" class="footer__link">Blog</a></li>
                        <li><a href="#" class="footer__link">About us</a></li>
                        <li><a href="#" class="footer__link">Our mision</a></li>
                    </ul>
                </div>

                <div class="footer__content">
                    <h3 class="footer__title">Social</h3>
                    <a href="#" class="footer__social"><i class='bx bxl-facebook-circle '></i></a>
                    <a href="#" class="footer__social"><i class='bx bxl-twitter'></i></a>
                    <a href="#" class="footer__social"><i class='bx bxl-instagram-alt'></i></a>
                </div>
            </div>

            <p class="footer__copy">&#169; 2021 Bedimcode. All right reserved</p>
        </footer>

       
        <script src="https://unpkg.com/scrollreveal"></script>

        
        <script src="main.js"></script>
    </body>
</html>
