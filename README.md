<!DOCTYPE html>
<html>
<head>
    <title>Kevin Domingo Portfolio</title>

    <meta charset="UTF-8">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <!-- CS File -->
    <link rel="stylesheet" href="myportfolio.css">

    <!-- Bootstrap -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>

    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css">

    <!-- JS File -->
    <script src="myportfolio.js"></script>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

</head>
<body>

    <nav id="navbar" class="nav">
        <a class="nav-link" href="file:///C:/Users/Kevin%20Domingo/Documents/Kevin%20Domingo%20-%20Resume.pdf" target="_blank">Resume</a>
        <a class="nav-link" href="https://github.com/kevDomingo" target="_blank">GitHub</a>
      </nav>

    <div class="waveWrapper waveAnimation">
        <div class="waveWrapperInner bgTop">
          <div class="wave waveTop" style="background-image: url('http://front-end-noobs.com/jecko/img/wave-top.png')">
        
            <section id="homePage">
                <div id="contactMe">
                    <h6><b>Contact Me At: (775) 846 - 4042 / kevdomingo10@gmail.com</b></h6>
                </div>
    
                <div id="introduction">
                    <h1 id="welcome"><b>Welcome</b></h1>
                    <h4><b>I'm Kevin Domingo</b></h4>
                    <h4><b>Thank you for having interest in me</b></h4>
                    <h4>-Click the icon to view my projects-</h4>
                    <a href="#portfolio"><i id="arrow" class="fas fa-arrow-down"></i></a>
                </div>
            </section>

        </div>
        </div>

        <div class="waveWrapperInner bgMiddle">
          <div class="wave waveMiddle" style="background-image: url('http://front-end-noobs.com/jecko/img/wave-mid.png')"></div>
        </div>
        <div class="waveWrapperInner bgBottom">
          <div class="wave waveBottom" style="background-image: url('http://front-end-noobs.com/jecko/img/wave-bot.png')"></div>
        </div>
      </div>

      <section id="portfolio" class="container-fluid px-0">
          <div class="container">
          <div class="row justify-content-center">
          <div id="stack" class="col-md-6">
              <h2><u>Technologies & Frameworks/Libraries</u></h2>
              <img id="html" src="https://i.imgur.com/Tcadzom.png" alt="html">
              <img src="https://i.imgur.com/51qcDv8.png" alt="JavaScript">
              <img src="https://i.imgur.com/36V1T07.png" alt="css">
              <br>
              <img id="bootstrap" src="https://i.imgur.com/uL3TL9D.png" alt="Bootstrap">
              <img src="https://i.imgur.com/GyUhQQJ.png" alt="Jquery">
          </div>
          <div id="extra" class="col-md-6">
              <h2><u>Tools & Extra Skills</u></h2>
              <h1>-Photography-</h1>
              <img id="lightroom" src="https://i.imgur.com/fKEgziX.png" alt="Lightroom">
              <img id="visualStudio" src="https://i.imgur.com/u8PSZk9.png" alt="VS Code">
          </div>
          </div>
          </div>

          <hr>

          <div class="row align-items-center content">
            <div id="projects" class="col-md-6 order-2 order-md-1">
                    <a href="houseoffashion.html" target="_blank"><img src="https://i.imgur.com/Dc03XSF.jpg" alt="House of Fashion" class="img-fluid"></a>
            </div>
                <div class="col-md-6 text-center order-1 order-md-2">
                    <div class="row justify-content-center">
                        <div id="description" class="col-10 col-lg-8 blurb mb-5 mb-md-0">
                            <a href="houseoffashion.html" target="_blank"><h2>House Of Fashion</h2></a>
                            <h6>Your virtual mall. Discover what's trending in the world of fashion and style, and be directed straight to the clothing stores.</h6>
                            <a href="houseoffashion.html" target="_blank" data-lightbox="" id="button" class="btn btn-primary mr-lg-3 d-none d-lg-inline-block">Site</a>
                            <a href="https://github.com/kevDomingo/HouseOfFashion.git" target="_blank" data-lightbox="" id="buttonTwo" class="btn btn-primary mr-lg-3 d-none d-lg-inline-block">GitHub</a>
                        </div>
                    </div>
                </div>
          </div>

          <hr>

          <div class="row align-items-center content">
            <div id="projects" class="col-md-6 order-2 order-md-1">
                <a href="colorgame.html" target="_blank"><img src="https://i.imgur.com/PihJ2Db.png" alt="ColorGame"></a>
            </div>
            <div class="col-md-6 text-center order-1 order-md-2">
                <div class="row justify-content-center">
                    <div id="description" class="col-10 col-lg-8 blurb mb-5 mb-md-0">
                        <a href="colorgame.html" target="_blank"><h2>ColorGame</h2></a>
                        <h6>Guess the correct color based off the random RGB code given to you.</h6>
                        <a href="colorgame.html" target="_blank" data-lightbox="" id="button" class="btn btn-primary mr-lg-3 d-none d-lg-inline-block">Site</a>
                        <a href="https://github.com/kevDomingo/ColorGame.git" target="_blank" data-lightbox="" id="buttonTwo" class="btn btn-primary mr-lg-3 d-none d-lg-inline-block">GitHub</a>
                    </div>
                </div>
            </div>
          </div>

          <hr>

          <div class="row align-items-center content">
            <div id="projects" class="col-md-6 order-2 order-md-1">
                <a href="photoGrid.html" target="_blank"><img src="https://i.imgur.com/ToyBJM5.png" alt="Photography Portfolio"></a>
            </div>
            <div class="col-md-6 text-center order-1 order-md-2">
                <div class="row justify-content-center">
                    <div id="description" class="col-10 col-lg-8 blurb mb-5 mb-md-0">
                        <a href="photoGrid.html" target="_blank"><h2>Photography Portfolio</h2></a>
                        <h6>A showcase of my photography skills.</h6>
                        <a href="photoGrid.html" target="_blank" data-lightbox="" id="button" class="btn btn-primary mr-lg-3 d-none d-lg-inline-block">Site</a>
                        <a href="https://github.com/kevDomingo/PhotographyPortfolio.git" target="_blank" data-lightbox="" id="buttonTwo" class="btn btn-primary mr-lg-3 d-none d-lg-inline-block">GitHub</a>
                    </div>
                </div>
            </div>
          </div>

          <hr>

          <div class="row align-items-center content">
            <div id="projects" class="col-md-6 order-2 order-md-1">
                <a href="technicolor.html" target="_blank"><img src="https://i.imgur.com/D2HfmJU.png" alt="Technicolor"></a>
            </div>
            <div class="col-md-6 text-center order-1 order-md-2">
                <div class="row justify-content-center">
                    <div id="description" class="col-10 col-lg-8 blurb mb-5 mb-md-0">
                        <a href="technicolor.html" target="_blank"><h2>TechniColor</h2></a>
                        <h6>Hover the mouse over the squares to get a cool color show.</h6>
                        <a href="technicolor.html" target="_blank" data-lightbox="" id="button" class="btn btn-primary mr-lg-3 d-none d-lg-inline-block">Site</a>
                        <a href="https://github.com/kevDomingo/TechniColor.git" target="_blank" data-lightbox="" id="buttonTwo" class="btn btn-primary mr-lg-3 d-none d-lg-inline-block">GitHub</a>
                    </div>
                </div>
            </div>
          </div>

          <hr>

          <div class="row align-items-center content">
            <div id="projects" class="col-md-6 order-2 order-md-1">
                <a href="secretmessage.html" target="_blank"><img src="https://i.imgur.com/AqU3buA.png" alt="Secret Message"></a>
            </div>
            <div class="col-md-6 text-center order-1 order-md-2">
                <div class="row justify-content-center">
                    <div id="description" class="col-10 col-lg-8 blurb mb-5 mb-md-0">
                        <a href="secretmessage.html" target="_blank"><h2>Secret Message</h2></a>
                        <h6>Reveal a secret message as you scroll down through the page.</h6>
                        <a href="secretmessage.html" target="_blank" data-lightbox="" id="button" class="btn btn-primary mr-lg-3 d-none d-lg-inline-block">Site</a>
                        <a href="https://github.com/kevDomingo/SecretMessage.git" target="_blank" data-lightbox="" id="buttonTwo" class="btn btn-primary mr-lg-3 d-none d-lg-inline-block">GitHub</a>
                    </div>
                </div>
            </div>
          </div>

          <hr>

          <div class="row align-items-center content">
            <div id="projects" class="col-md-6 order-2 order-md-1">
                <a href="todolistproject.html" target="_blank"><img src="https://i.imgur.com/uE7Uq5c.jpg" alt="ToDoList Tool"></a>
            </div>
            <div class="col-md-6 text-center order-1 order-md-2">
                <div class="row justify-content-center">
                    <div id="description" class="col-10 col-lg-8 blurb mb-5 mb-md-0">
                        <a href="todolistproject.html" target="_blank"><h2>ToDoList Tool</h2></a>
                        <h6>Use this ToDoList Tool to better organize your day.</h6>
                        <a href="todolistproject.html" target="_blank" data-lightbox="" id="button" class="btn btn-primary mr-lg-3 d-none d-lg-inline-block">Site</a>
                        <a href="https://github.com/kevDomingo/ToDoList.git" target="_blank" data-lightbox="" id="buttonTwo" class="btn btn-primary mr-lg-3 d-none d-lg-inline-block">GitHub</a>
                    </div>
                </div>
            </div>
          </div>

          <hr>

          <div class="row align-items-center content">
            <div id="projects" class="col-md-6 order-2 order-md-1">
                <a href="randomcolor.html" target="_blank"><img src="https://i.imgur.com/7SjkNtV.png" alt="RandoColor"></a>
            </div>
            <div class="col-md-6 text-center order-1 order-md-2">
                <div class="row justify-content-center">
                    <div id="description" class="col-10 col-lg-8 blurb mb-5 mb-md-0">
                        <a href="randomcolor.html" target="_blank"><h2>RandoColor</h2></a>
                        <h6>Click on the button to get random colors.</h6>
                        <a href="randomcolor.html" target="_blank" data-lightbox="" id="button" class="btn btn-primary mr-lg-3 d-none d-lg-inline-block">Site</a>
                        <a href="https://github.com/kevDomingo/RandoColor.git" target="_blank" data-lightbox="" id="buttonTwo" class="btn btn-primary mr-lg-3 d-none d-lg-inline-block">GitHub</a>
                    </div>
                </div>
            </div>
          </div>

          <hr>

      </section>

</body>
</html>
