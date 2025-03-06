<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <title>Hello World</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <nav class="navbar navbar-expand-lg navbar-light">
            <div class="container-fluid">
                <a id="logo" class="navbar-brand" href="#">
                    <img src="web-development.png" class="img-fluid"/>
                </a>
                <button class="navbar-toggler" type="button"
                data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent"
                aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Product</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Contact</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>

        <div id="banner">
            <img src="banner1.jpg" class="img-fluid rounded-3"/>
        </div>

        <div id="highlight" class="row mt-3">
            <div class="col">
                <img src="thor.jpg" class="img-fluid rounded-3"/>
            </div>
            <div class="col">
                <img src="wick.jpg" class="img-fluid rounded-3"/>
            </div>
            <div class="col">
                <img src="ironman.jpg" class="img-fluid rounded-3"/>
            </div>
            <div id="box2">
                <div id="box21">
                    <img src="banner2.jpg" />
                </div>
                <div id="box22">
                    <h1>Subtitle Here</h1>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nesciunt, error nobis! Minima, nam doloribus maxime architecto id quis aut tenetur est a accusantium sequi exercitationem ipsum explicabo minus veritatis nesciunt?</p>
                </div>
            </div>
        </div>
        <hr>
        <section class="clients">
            <h3>Our Client</h3>
            <div class="client-list">
                <img src="0.jpg" alt="Client 1">
                <img src="1.jpg" alt="Client 2">
                <img src="2.jpg" alt="Client 3">
                <img src="3.jpg" alt="Client 4">
                <img src="4.jpg" alt="Client 5">
                <img src="5.jpg" alt="Cient 6">
            </div>
        </section>
        <hr>
        <section class="testimonials container">
            <h3 class="text-center">Testimonial</h3>
            <div class="row justify-content-center align-items-stretch">
                <div class="col-12 col-md-6 d-flex">
                    <div class="testimonial text-center p-3 flex-fill">
                        <img src="6.jpg" alt="John Thor" class="rounded-circle mb-2">
                        <h4>John Thor</h4>
                        <p>Setelah menggunakan jasa perusahaan ini, saya menjadi seorang super hero yang memiliki kekuatan untuk mengendalikan petir. Keren banget kan.</p>
                    </div>
                </div>
                <div class="col-12 col-md-6 d-flex">
                    <div class="testimonial text-center p-3 flex-fill">
                        <img src="7.jpg" alt="Tony Stark" class="rounded-circle mb-2">
                        <h4>Tony Stark</h4>
                        <p>Setelah saya kuliah di UMN, saya jadi jenius banget dan bisa bikin Iron Man, saya jadi super hero paling tajir di jagad raya.</p>
                    </div>
                </div>
            </div>
        </section>
        <div class="kontainer">
            <section class="newsletter">
                <h3>Subscribe to our newsletter to get the latest info</h3>
                <input type="email" placeholder="Enter your email here...">
                <div> 
                    <button>Subscribe</button>
                </div>
            </section>
                </div>
                <footer>
                    <div class="footer-left">
                        <h3>PT. Tajir Mampus Corporation Inc.</h3>
                        <p>Dark Science Boulevard <br>
                        Blok A1 No. 45 <br>
                        Gading Serpong, Tangerang</p>
                        <h4>Tel : (021) 123456789</h4>
                    </div> 
                    <div class="footer-right">
                        <div class="social-media">
                            <a href="#"><img src="facebook.png" alt="Facebook"></a>
                            <a href="#"><img src="instagram.png" alt="Instagram"></a>
                            <a href="#"><img src="youtube.png" alt="YouTube"></a>
                        </div>
                        <p class="copyright">Copyright © 2022 | All rights reserved.</p>
                    </div>
                </footer>
                
        </div>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
        </div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>
