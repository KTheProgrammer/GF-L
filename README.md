<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="">

    <!-- Bootstrap core CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.1/js/bootstrap.min.js" integrity="sha384-XEerZL0cuoUbHE4nZReLT7nx9gQrQreJekYhJD9WNWhH8nEW+0c5qq7aIo2Wl30J" crossorigin="anonymous"></script>

    <style>
      .bd-placeholder-img {
        font-size: 1.125rem;
        text-anchor: middle;
        -webkit-user-select: none;
        -moz-user-select: none;
        -ms-user-select: none;
        user-select: none;
      }

      .fit-picture {
        width: 50%;
      }

      .icon {
        height: 40px;
      }
      .tableIcon{
        margin-left: auto;
        margin-right: auto;
      }

      body {
        background: url(photos/background.png);
        text-align: center;
      }

      .flyer-picture {
        width: 80%;
        margin: 20px;
      }

      .flyer-title {
        font-family: cursive;
        color: green;
      }

      @media (min-width: 768px) {
        .bd-placeholder-img-lg {
          font-size: 3.5rem;
        }
      }
    </style>
  </head>
<body>
<!-- <div class="d-flex flex-column flex-md-row align-items-center p-3 px-md-4 mb-3 bg-white border-bottom shadow-sm">
  <h5 class="my-0 mr-md-auto font-weight-normal">Geraldine Flyers & Logos</h5>
  <nav class="my-2 my-md-0 mr-md-3">
    <a class="p-2 text-dark" href="#">Features</a>
    <a class="p-2 text-dark" href="#">Enterprise</a>
    <a class="p-2 text-dark" href="#">Support</a>
    <a class="p-2 text-dark" href="#">Pricing</a>
  </nav>
</div> -->

<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <a class="navbar-brand" href="">Geraldine Flyers & Logos</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo02" aria-controls="navbarTogglerDemo02" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarTogglerDemo02">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item">
        <a class="nav-link" href="">Features</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="">Enterprise</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="">Support</a>
      </li>
      <li class="nav-item">
          <a class="nav-link" href="">Pricing</a>
      </li>
    </ul>
  </div>
</nav>

<img class="fit-picture" src=photos/geraldine.png>
<div class="pricing-header px-3 py-3 pt-md-5 pb-md-4 mx-auto text-center">
  <h1 class="display-4">Flyers & Logos</h1>
  <p class="lead">Bringing beautiful Logos and Flyers from your thought to everyone eyes.</p>
</div>

<div class="container">
  <div class="card-deck mb-3 text-center">
    <div class="card mb-4 shadow-sm">
      <div class="card-header">
        <h4 class="my-0 font-weight-normal">Logo</h4>
      </div>
      <div class="card-body">
        <h1 class="card-title pricing-card-title">$15 <small class="text-muted"></small></h1>
        <ul class="list-unstyled mt-3 mb-4">
          <li>10 users included</li>
          <li>2 GB of storage</li>
          <li>Email support</li>
          <li>Help center access</li>
        </ul>
        <button type="button" class="btn btn-lg btn-block btn-primary">Let's Begin</button>
      </div>
    </div>
    <div class="card mb-4 shadow-sm">
      <div class="card-header">
        <h4 class="my-0 font-weight-normal">Flyer</h4>
      </div>
      <div class="card-body">
        <h1 class="card-title pricing-card-title">$25 <small class="text-muted"></small></h1>
        <ul class="list-unstyled mt-3 mb-4">
          <li>20 users included</li>
          <li>10 GB of storage</li>
          <li>Priority email support</li>
          <li>Help center access</li>
        </ul>
        <button type="button" class="btn btn-lg btn-block btn-primary">Get started</button>
      </div>
    </div>
    <div class="card mb-4 shadow-sm">
      <div class="card-header">
        <h4 class="my-0 font-weight-normal">Logo & Flyer</h4>
      </div>
      <div class="card-body">
        <h1 class="card-title pricing-card-title">$40 <small class="text-muted"></small></h1>
        <ul class="list-unstyled mt-3 mb-4">
          <li>30 users included</li>
          <li>15 GB of storage</li>
          <li>Phone and email support</li>
          <li>Help center access</li>
        </ul>
        <button type="button" class="btn btn-lg btn-block btn-primary">Let's Start</button>
      </div>
    </div>
  </div>
  <hr>
  <h2 class="flyer-title">Flyers by Geraldine</h2>
  <section id="projects">

    <div id="projects-carousel" class="carousel slide" data-ride="false">
      <div class="carousel-inner">
        <div class="carousel-item">
          <img class="flyer-picture" src="projects/flyer.jpeg" alt="project">
        </div>
        <div class="carousel-item">
          <img class="flyer-picture" src="projects/flyer2.jpeg" alt="project2">
        </div>
        <div class="carousel-item">
          <img class="flyer-picture" src="projects/flyer3.jpeg" alt="project3">
        </div>
        <div class="carousel-item">
          <img class="flyer-picture" src="projects/flyer4.jpeg" alt="project4">
        </div>
        <div class="carousel-item">
          <img class="flyer-picture" src="projects/flyer5.jpeg" alt="project5">
        </div>
        <div class="carousel-item">
          <img class="flyer-picture" src="projects/flyer6.jpeg" alt="project6">
        </div>
        <div class="carousel-item">
          <img class="flyer-picture" src="projects/flyer7.jpeg" alt="project">
        </div>
        <div class="carousel-item">
          <img class="flyer-picture" src="projects/flyer8.jpeg" alt="project2">
        </div>
        <div class="carousel-item">
          <img class="flyer-picture" src="projects/flyer9.jpeg" alt="project3">
        </div>
        <div class="carousel-item">
          <img class="flyer-picture" src="projects/flyer10.jpeg" alt="project4">
        </div>
        <div class="carousel-item">
          <img class="flyer-picture" src="projects/flyer11.jpeg" alt="project5">
        </div>
        <div class="carousel-item">
          <img class="flyer-picture" src="projects/flyer12.jpeg" alt="project6">
        </div>
        <div class="carousel-item">
          <img class="flyer-picture" src="projects/flyer13.jpeg" alt="project2">
        </div>
        <div class="carousel-item">
          <img class="flyer-picture" src="projects/flyer14.jpeg" alt="project3">
        </div>
        <div class="carousel-item">
          <img class="flyer-picture" src="projects/flyer15.jpeg" alt="project4">
        </div>
        <div class="carousel-item active">
          <img class="flyer-picture" src="projects/flyer16.jpeg" alt="project5">
        </div>
        <div class="carousel-item">
          <img class="flyer-picture" src="projects/flyer17.jpeg" alt="project6">
        </div>
      </div>
    <a class="carousel-control-prev" href="#projects-carousel" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon"></span>
    </a>
    <a class="carousel-control-next" href="#projects-carousel" role="button" data-slide="next">
      <span class="carousel-control-next-icon"></span>
    </a>
    </div>

  </section>

  <footer class="pt-4 my-md-5 pt-md-5 border-top">
    <div class="row">
      <div class="col-12 col-md">
        <small class="d-block mb-3 text-muted">&copy; 2021 K The Programmer</small>
      </div>
      <div class="col-6 col-md">
        <h5>Features</h5>
        <ul class="list-unstyled text-small">
          <li><a class="text-muted" href="#">Cool stuff</a></li>
          <li><a class="text-muted" href="#">Random feature</a></li>
        </ul>
      </div>
      <div class="col-6 col-md">
        <h5>Resources</h5>
        <ul class="list-unstyled text-small">
          <li><a class="text-muted" href="#">Resource</a></li>
          <li><a class="text-muted" href="#">Resource name</a></li>
          <li><a class="text-muted" href="#">Another resource</a></li>
          <li><a class="text-muted" href="#">Final resource</a></li>
        </ul>
      </div>
      <div class="col-6 col-md">
        <h5>About</h5>
        <ul class="list-unstyled text-small">
          <li><a class="text-muted" href="#">Locations</a></li>
          <li><a class="text-muted" href="#">Privacy</a></li>
          <li><a class="text-muted" href="#">Terms</a></li>
        </ul>
      </div>
    </div>
    <hr id="iconspace">
    <table class="tableIcon">
        <tr>
            <td><a href="https://www.facebook.com/geraldinecox.atkins"><img class="icon" src="photos/facebook.png" alt="facebookLogo"></a></td>
            <td><a href="https://www.instagram.com/twink_atkins/"><img class="icon" src="photos/instagram.png" alt="instagramLogo"></a></td>
            <td><a href="https://www.pinterest.com/mrsgatkins/"><img class="icon" src="photos/pinterest.png" alt="pinterestLogo"></a></td>
            <td><a href="https://twitter.com/walkin_nfavor"><img class="icon" src="photos/twitter.png" alt="twitterLogo"></a></td>
        </tr>
    </table>  
  </footer>
</div>
</body>
</html>
