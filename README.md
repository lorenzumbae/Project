<!DOCTYPE HTML>
<html>
<head>
<title>Lorenz Portfolio</title>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" type="text/css" href="assets/css/style.css">
<link rel="stylesheet" type="text/css" href="assets/css/boot.css">
<link rel="stylesheet" type="text/css" href="assets/css/font-awesome.min.css">
<link rel="stylesheet" type="text/css" href="assets/css/bootstrap.min.css">
<link rel="stylesheet" type="text/css" href="assets/css/bootstrap.css">
<link rel="stylesheet" type="text/css" href="assets/css/style_common.css">
<link rel="stylesheet" type="text/css" href="assets/css/style1.css">
<link rel='stylesheet' type='text/css' href='http://fonts.googleapis.com/css?family=Open+Sans+Condensed:700,300,300italic'>
<script src="assets/js/modernizr.custom.69142.js"></script>
<script src="assets/js/jquery-1.10.1.min.js"></script>
<script src="assets/js/bootstrap.min.js" ></script>
<style type="text/css">
.carousel{
    background: #2f4357;
    margin-top: 20px;
}
.carousel .item{
    min-height: 280px; /* Prevent carousel from being distorted if for some reason image doesn't load */
}
.carousel .item img{
    margin: 0 auto; /* Align slide image horizontally center */
}
.bs-example{
	margin: 20px;
}
</style>
</head>
<body>
<div id="page-top" class="index">
  <nav class="navbar navbar-inverse navbar-fixed-top">
    <div class="container-fluid">
      <div class="navbar-header">
        <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false"><span class="sr-only">Toggle navigation</span><span class="icon-bar"></span><span class="icon-bar"></span><span class="icon-bar"></span></button>
        <a class="navbar-brand page-scroll" href="#page-top">Lorenz Umbae Production</a></div>
      <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
        <ul class="nav navbar-nav navbar-right">
          <li><a class="page-scroll" href="#page-top">Home</a></li>
          <li><a class="page-scroll" href="#thanks">Special Thanks</a></li>
          <li><a class="page-scroll" href="#port">Portfolio</a></li>
          <li><a class="page-scroll" href="#about">About</a></li>
          <li><a class="page-scroll" href="#team">Creator</a></li>
          <li><a class="page-scroll" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div><!-- /.container-fluid -->
  </nav>
  <!-- Header -->
  <header style="background-image:url(assets/img/3218_Computer-power-abstract-binary-code.jpg)">
    <div class="container">
      <div class="intro-text">
        <div class="intro-lead-in" style="color:black ">Welcome To My Portfolio!</div>
        <div class="intro-heading" style="color:black ">It's Nice To Meet You</div>
        <a href="#thanks" class="page-scroll btn btn-success">Special Thanks to</a></div>
    </div>
  </header>
</div>
<!-- ===== services ===== -->
<section id="thanks">
  <div class="container">
    <div class="row">
      <div class="col-lg-12 text-center">
        <h2 class="section-heading" style="color:#3680C1">Making things with these...</h2>
      </div>
    </div>
    	<div class="col-md-12">
        		<center><img src="assets/img/html.jpg"></center>
		</div>	
    </div>
  </div>
</section>
<!-- ===== Team Section ===== -->
<section id="port" class="bg-danger">
  <div class="container">
    <div class="row">
      <div class="col-lg-12 text-center">
        <h2 class="section-heading" style="color:#3680C1">My Portfolio</h2>
        <h3 class="section-subheading text-muted">Sample of my pictures</h3>
      </div>
    </div>

    

<div class="bs-example">
    <div id="myCarousel" class="carousel slide" data-ride="carousel">
        <!-- Carousel indicators -->
        <ol class="carousel-indicators">
            <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
            <li data-target="#myCarousel" data-slide-to="1"></li>
            <li data-target="#myCarousel" data-slide-to="2"></li>
        </ol>   
        <!-- Wrapper for carousel items -->
        <div class="carousel-inner">
            <div class="item active">
                <img src="assets/img/lorenz2.jpg" alt="First Slide">
            </div>
            <div class="item">
                <img src="assets/img/lorenz4.jpg" alt="Second Slide">
            </div>
            <div class="item">
                <img src="assets/img/lorenz5.jpg" alt="Third Slide">
            </div>
        </div>
        <!-- Carousel controls -->
        <a class="carousel-control left" href="#myCarousel" data-slide="prev">
            <span class="glyphicon glyphicon-chevron-left"></span>
        </a>
        <a class="carousel-control right" href="#myCarousel" data-slide="next">
            <span class="glyphicon glyphicon-chevron-right"></span>
        </a>
    </div>
</div>





  </div>

</section>
<script>	
Modernizr.load({
    test: Modernizr.csstransforms3d && Modernizr.csstransitions,
    yep: ['assets/js/jquery-1.10.1.min.js', 'assets/js/jquery.hoverfold.js'],
    nope: '',
    callback: function(url, result, key) {
        if (url === 'assets/js/jquery.hoverfold.js') {
            $('#grid').hoverfold();
        }
    }
});
</script> 
<!-- About Section -->
<section id="about">
  <div class="container">
    <div class="row">
      <div class="col-lg-12 text-center">
        <h2 class="section-heading" style="color:#3680C1">About</h2>
        <h3 class="section-subheading text-muted">Some Of My Hobbies and Favorites</h3>
      </div>
    </div>
    <div class="row">
      <div class="col-lg-12">
        <ul class="timeline">

          <li>
            <div class="timeline-image"><img class="img-responsive" src="assets/img/dota.jpg" alt=""></div>
            <div class="timeline-panel">
              <div class="timeline-heading">
                <h4 style="color:#3680C1">Dota Maniac</h4>
                <h4 class="subheading" style="color:#3680C1">Dota2 ID:376314597</h4>
              </div>
              <div class="timeline-body">
                <p class="text-muted">Dota is my life <3</p>
              </div>
            </div>
          </li>

          <li class="timeline-inverted">
           <div class="timeline-image"><img class="img-responsive" src="assets/img/ball.jpg" alt=""></div>
            <div class="timeline-panel">
              <div class="timeline-heading">
                <h4 style="color:#3680C1">Basketball</h4>
                <h4 class="subheading" style="color:#3680C1">Position : Pointguard</h4>
              </div>
              <div class="timeline-body">
                <p class="text-muted">Im playing basketball since birth HAHA</p>
              </div>

            </div>
          </li>

          <li>
            <div class="timeline-image"><img class="img-responsive" src="assets/img/cong.jpg" alt=""></div>
            <div class="timeline-panel">
              <div class="timeline-heading">
                <h4 style="color:#3680C1">CONG TV</h4>
                <h4 class="subheading" style="color:#3680C1">He is my Lodi</h4>
              </div>
              <div class="timeline-body">
                <p class="text-muted">Cong is a Youtube blogger and His real name is Lincoln Velasquez and he is from the Philippines. He has a brother who's known as Junnie Boy; he's also a vlogger on YouTube.</p>
              </div>
            </div>
          </li>

       
         
        </ul>
      </div>
    </div>
  </div>
</section>
<!-- ===== Team Section ===== -->
<section id="team" class="bg-success">
  <div class="container">
    <div class="row">
      <div class="col-lg-12 text-center">
        <h2 class="section-heading" style="color:#3680C1">Web Developer</h2>
        <h3 class="section-subheading text-muted">Hes Currently Taking a Bachelors Degree of Computer Science at Cavite State University Silang Campus</h3>
      </div>
    </div>
    <div class="row">
      <div class="col-sm-12">
        <div class="team-member"><img src="assets/img/lorenzdp.jpg" class="img-responsive img-rounded" alt="" >
          <h4 style="color:#3680C1" class="text-center">Lorenz Umbay</h4>
          <p class="text-muted">BSCS-3B</p>
          <ul class="list-inline social-buttons">
            <li><a href="https://twitter.com/UmbayLorenz"><i class="fa fa-twitter"></i></a></li>
            <li><a href="https://www.facebook.com/UmbaeLrnz"><i class="fa fa-facebook"></i></a></li>
            <li><a href="https://www.instagram.com/umbaeeeee"><i class="fa fa-instagram"></i></a></li>
          </ul>
        </div>
      </div>
      

     

    </div>
  </div>
</section>
<!-- ===== Contact Us ===== -->
<section id="contact">
  <div class="container">
    <div class="row">
      <div class="col-lg-12 text-center">
        <h2 class="section-heading" style="color:#3680C1">Contact Us</h2>
        <h3 class="section-subheading text-muted">Just leave a message and tell everything about my portfolio thank you.</h3>
      </div>
    </div>
    <div class="row">
      <div class="col-lg-12">
        <form action="#" method="post" name="sentMessage" id="contactForm" novalidate>
          <div class="row">
            <div class="col-md-6">
              <div class="form-group">
                <input type="text" class="form-control" placeholder="Your Name *" id="name" required>
                <p class="help-block text-danger"></p>
              </div>
              <div class="form-group">
                <input type="email" class="form-control" placeholder="Your Email *" id="email" required>
                <p class="help-block text-danger"></p>
              </div>
              <div class="form-group">
                <input type="tel" class="form-control" placeholder="Your Phone *" id="phone" required>
                <p class="help-block text-danger"></p>
              </div>
            </div>
            <div class="col-md-6">
              <div class="form-group">
                <textarea class="form-control" placeholder="Your Message *" id="message" required></textarea>
                <p class="help-block text-danger"></p>
              </div>
            </div>
            <div class="clearfix"></div>
            <div class="col-lg-12 text-center">
              <div id="success"></div>
              <button type="submit" class="btn btn-primary">Send Message</button>
            </div>
          </div>
        </form>
      </div>
    </div>
  </div>
</section>
<footer>
  <div class="container">
    <div class="row">
      <div class="col-md-4"></div>
      <div class="col-md-4 col-md-offset-">
        <ul class="list-inline social-buttons">
          <li><a href="https://twitter.com/UmbayLorenz"><i class="fa fa-twitter"></i></a></li>
          <li><a href="https://www.facebook.com/UmbaeLrnz"><i class="fa fa-facebook"></i></a></li>
          <li><a href="https://www.instagram.com/umbaeeeee"><i class="fa fa-instagram"></i></a></li>
        </ul>
      </div>
      <div class="col-md-4"></div>
    </div>
  </div>
  <br>
  <div class="container">
    <div class="row">
      <div class="col-md-3"></div>
      <div class="col-md-6">
        <h3 style="color:#3680C1">Thank You For Visiting To My Portfolio Pawer !!!!</h3>
        <h3 style="color:#3680C1">Copyright &copy; 2017 All Rights Reserved</h3>
      </div>
      <div class="col-md-3"></div>
    </div>
  </div>
</footer>
</body>
</html>
