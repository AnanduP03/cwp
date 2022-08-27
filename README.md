# College-Website-Project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amrita Webpage</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">
    <link href="css\file.css" rel="stylesheet" type="text/css">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js" integrity="sha384-pprn3073KE6tl6bjs2QrFaJGz5/SUsLqktiwsUTF55Jfv3qYSDhgCecCxMW52nD2" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.1/jquery.min.js"></script>
</head>
<body>
  <div class="preloader"></div>
  <div class="content">
    <div class="container-fluid">
        <div class="row">
          <div class="col-12 col-sm-12 col-md-12 col-lg-12 col-xl-12 col-xxl-12">
                <nav class="navbar navbar-expand-lg fixed-top">
                    <div class="container-fluid">
                      <a class="navbar-brand" href="index.html">
                        <img src="images\logo.png" alt="amrita logo" class="image-fluid" width="150" height="auto">
                      </a>
                      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                      </button>
                      <div class="collapse navbar-collapse" id="navbarSupportedContent">
                        <ul class="navbar-nav ms-auto mb-2 mb-lg-0 main-menu">
                          <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="home.html">Home</a>
                          </li>
                          <li class="nav-item">
                            <a class="nav-link" href="about.html">About</a>
                          </li>
                          <li class="nav-item">
                            <a class="nav-link" href="campus.html">Campus</a>
                          </li>
                          <li class="nav-item">
                            <a class="nav-link" href="contact.html">Contact us</a>
                          </li>
                        </ul>
                      </div>
                    </div>
                  </nav>
            </div>
        </div>
    </div>
    <section class="section main-banner" id="top">
        <video autoplay muted loop id="bg-video">
            <source src="https://dt19wmazj2dns.cloudfront.net/wp-content/uploads/2019/08/vdonew01.mp4" type="video/mp4"/>
        </video>

        <div class="video-overlay header-text">
            <div class="caption">   
                <h2> LEARN FROM INDIA'S<br><span class="text-warning">TOP RANKED</span><br>UNIVERSITY</h2>
                <h6>Ranked 5th best university in India by NIRF 2021, Amrita is a NAAC A++ grade university spread across 7 campuses in 4 states.</h6>      
            </div>
        </div>
    </section>

<div class="container-fluid">
    <div class="row bg-dark">   
        <div class="col-12 col-sm-12 col-md-12 col-lg-12 col-xl-12 col-xxl-12">
            <p class="text-light text-center">
                University Website©
            </p>
        </div>
    </div>
</div>
</div>
<script>
  $(window).on('load',function(){
    $(".preloader").fadeOut(1000);
    $(".content").fadeIn(1000);
  });
</script>
</body>
</html>
