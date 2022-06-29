
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>David Chu's China Bistro</title>

    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>
    <link rel="stylesheet" href="bootstrap-5.2.0-beta1-dist.zip">
    <link rel="stylesheet" href="CSS2.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <script src="https://kit.fontawesome.com/yourcode.js" crossorigin="anonymous"></script>
    
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href='https://fonts.googleapis.com/css?family=Oxygen:400,300,700' rel='stylesheet' type='text/css'>
<link href='https://fonts.googleapis.com/css?family=Lora' rel='stylesheet' type='text/css'>
</head>
<body>
    <header>
        <nav id="header-nav" class="navbar navbar-default">
          <div class="container">
            <div class="navbar-header">
                <a href="index.html" class="pull-left visible-md visible-lg">
                  <div id="logo-img" alt="Logo image"></div>
                </a>

                <div class="navbar-brand">
                    <a href="index.html"><h1>David Chu's China Bistro</h1></a>
                    <p>
                      <img src="images/star-k-logo.png" alt="Kosher certification">
                      <span>Kosher Certified</span>
                    </p>
                </div>

                <button id="navbarToggle" type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#collapsable-nav" aria-expanded="false">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                  </button>
                </div>
                
                <div id="collapsable-nav" class="collapse navbar-collapse">
                  <ul id="nav-list" class="nav navbar-nav navbar-right">
                   <li id="navHomeButton" class="visible-xs active">
                     <a href="index.html">
                       <span class="glyphicon glyphicon-home"></span> Home</a>
                   </li>
                   <li id="navMenuButton">
                     <a href="menu-categories.html" onclick="$dc.loadMenuCategories();">
                       <span class="glyphicon glyphicon-cutlery"></span><br class="hidden-xs"> Menu</a>
                   </li>
                   <li>
                     <a href="#">
                       <span class="glyphicon glyphicon-info-sign"></span><br class="hidden-xs"> About</a>
                   </li>
                   <li>
                     <a href="#">
                       <span class="glyphicon glyphicon-certificate"></span><br class="hidden-xs"> Awards</a>
                   </li>
                   <li id="phone" class="hidden-xs">
                     <a href="tel:410-602-5008">
                       <span>410-602-5008</span></a><div>* We Deliver</div>
                   </li>
                  </ul><!-- #nav-list -->
                </div><!-- .collapse .navbar-collapse -->
          </div>
        </nav>
    </header>

    <div id="call-btn" class="visible-xs">
      <a class="btn" href="tel:410-602-5008">
      <span class="glyphicon glyphicon-earphone"></span>
      410-602-5008
      </a>
    </div>
    <div id="xs-deliver" class="text-center visible-xs">* We Deliver</div>

   
  
    <div id="main-content" class="container">
      <div class="jumbotron">
        <img src="D:\IMAGES\jumbotron_768.jpg" alt="picture of restarunt" class="img-responsive visible-xs">
      </div>
        <div id="home-tiles" class="row">
          <div class="col-md-4 col-sm-6 col-xs-12">
            <a href="menu-categories.html"><div id="menu-tile"><span>menu</span></div></a>
            </div>
            <div class="col-md-4 col-sm-6 col-xs-12">
              <a href="single-categories.html"><div id="specials-tile"><span>specials</span></div></a>
              </div>
              <div class="col-md-4 col-sm-12 col-xs-12">
                  <a href="https://goo.gl/maps/DsSgRPt3gSG53Vpb9" target="_blank">
                    <div id="map-tile">
                      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3084.6752464097885!2d-76.71388214998836!3d39.36359027940089!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89c81a14e7817803%3A0xab20a0e99daa17ea!2sDavid%20Chu&#39;s%20China%20Bistro!5e0!3m2!1sen!2sin!4v1656171700875!5m2!1sen!2sin" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                      <span>map</span>
                    </div>
                  </a>
              </div>
              </div>
    </div>
  
    <footer class="panel-footer">
      <div class="container">
        <div class="row">
          <section id="hours" class="col-sm-4">
            <span>Hours:</span><br>
            Sun-Thurs: 11:15am - 10:00pm<br>
            Fri: 11:15am - 2:30pm<br>
            Saturday Closed
            <hr class="visible-xs">
          </section>
          <section id="address" class="col-sm-4">
            <span>Address:</span><br>
            7105 Reisterstown Road<br>
            Baltimore, MD 21215
            <p>* Delivery area within 3-4 miles, with minimum order of $20 plus $3 charge for all deliveries.</p>
            <hr class="visible-xs">
          </section>
          <section id="testimonials" class="col-sm-4">
            <p>"The best Chinese restaurant I've been to! And that's saying a lot, since I've been to many!"</p>
            <p>"Amazing food! Great service! Couldn't ask for more! I'll be back again and again!"</p>
          </section>
        </div>
        <div class="text-center">&copy; Copyright David Chu's China Bistro 2016</div>
      </div>
    </footer>
  



    <!-- jQuery (Bootstrap JS plugins depend on it) -->
   <script src="js/jquery-3.6.0.js"></script>
   <script src="js/bootstrap.min.js"></script>
   <script src="js/ajax-utils.js"></script>
   <script src="js/script.js"></script>
</body>
</html>
![Uploading jumbotron_768.jpg…]()
![jumbotron_768](https://user-images.githubusercontent.com/107862323/176472041-400db446-7434-46fe-9324-033dea1184a2.jpg)

