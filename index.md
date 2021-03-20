<!DOCTYPE html>
<html lang = "en">

<head>
       <meta charset = "utf-8">
       <title>loopstudios - Landing page</title>
	   <link rel="icon" type="image/png" href="./images/favicon-32x32.png">
	   <link rel = "stylesheet" type = "text/css" href = "loopstudios.css">
	   <meta name="viewport" content="width=device-width, initial-scale=1.0">
	   
	   <link rel="preconnect" href="https://fonts.gstatic.com">
       <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300&display=swap" rel="stylesheet">
       <link href="https://fonts.googleapis.com/css2?family=Alata&display=swap" rel="stylesheet">
	   <script src="https://kit.fontawesome.com/d69fe3d682.js" crossorigin="anonymous"></script> 
</head>
  <body>
  <header>
   <img class="desktop-header" src="images/desktop/image-hero.jpg" width="100%" height="auto">
   <!--HEADER IMAGE FOR MOBILE PHONES-->
   <img class="mobile-header" src="images/mobile/image-hero.jpg" width="100%" height="auto"> 
   
   <h1 class="logo">loopstudios</h1>
   
   <div class="top-nav">
	<a href="#">About</a>
	<a href="#">Careers</a>
	<a href="#">Events</a>
	<a href="#">Products</a>
	<a href="#">Support</a>
   </div>
   <!--TOP HAMBURGER NAVIGATION FOR MOBILES-->
   <span id="bars" onclick="openClose()" class="fas fa-bars"></span>
   <div class="mobile-overlay">
    <img id="x" onclick="openClose()" src="images/icon-close.svg">
	<h1 class="logo">loopstudios</h1>
	<div class="top-nav-mobile">
	 <a href="#">About</a>
	 <a href="#">Careers</a>
	 <a href="#">Events</a>
	 <a href="#">Products</a>
	 <a href="#">Support</a>
	</div>
   </div>
   
   <div class="sign">IMMERSIVE EXPIRIENCES THAT DELIVER</div>
  </header>
  
  <div class="main">
   <div class="I-content">
    <img src="./images/desktop/image-interactive.jpg" width="65%" height="auto" class="interactive-desktop">
	<!--IMAGE FOR MOBILES-->
	<img src="images/mobile/image-interactive.jpg" width="100%" height="auto" class="interactive-mobile">
    <div class="text-box">
     <h1>THE LEADER IN INTERACTIVE VR</h1>
	 <p>Founded in 2011, Loopstudios has been producing world-class virtual reality 
        projects for some of the best companies around the globe. Our award-winning 
        creations have transformed businesses through digital experiences that bind 
        to their brand.
	 </p>
    </div>
   </div>
   
   <a href="#" class="see-all">SEE ALL</a>
   <h1 class="our-creations">Our creations</h1>
   
   <div class="flex-contain">
   
     <div class="flex-item">
      <img src="images/desktop/image-deep-earth.jpg">
	  <!--MOBILE IMAGE-->
	  <img src="images/mobile/image-deep-earth.jpg">
	  <div class="text">DEEP EARTH</div>
	 </div>
	 
	 <div class="flex-item">
      <img src="images/desktop/image-night-arcade.jpg">
	  <!--MOBILE IMAGE-->
	  <img src="images/mobile/image-night-arcade.jpg">
	  <div class="text">NIGHT ARCADE</div>
	 </div>
	
	 <div class="flex-item">
	  <img src="images/desktop/image-soccer-team.jpg">
	  <!--MOBILE IMAGE-->
	  <img src="images/mobile/image-soccer-team.jpg">
	  <div class="text">SOCCER TEAM VR</div>
	 </div>
	 
	 <div class="flex-item"> 
	  <img src="images/desktop/image-grid.jpg">
	  <!--MOBILE IMAGE-->
	  <img src="images/mobile/image-grid.jpg">
	  <div class="text">THE<br>GRID</div>
	 </div>
	
	 <div class="flex-item"> 
	  <img src="images/desktop/image-from-above.jpg">
	  <!--MOBILE IMAGE-->
	  <img src="images/mobile/image-from-above.jpg">
	  <div class="text">FROM UP ABOVE VR</div>
	 </div>
	 
	 <div class="flex-item">
	  <img src="images/desktop/image-pocket-borealis.jpg">
	  <!--MOBILE IMAGE-->
	  <img src="images/mobile/image-pocket-borealis.jpg">
	  <div class="text">POCKET BOREALIS</div>
	 </div>
	
	 <div class="flex-item">
	  <img src="images/desktop/image-curiosity.jpg">
	  <!--MOBILE IMAGE-->
	  <img src="images/mobile/image-curiosity.jpg">
	  <div class="text">THE CURIOSITY</div>
	 </div>
	 
	 <div class="flex-item">
	  <img src="images/desktop/image-fisheye.jpg">
	  <!--MOBILE IMAGE-->
	  <img src="images/mobile/image-fisheye.jpg">
	  <div class="text">MAKE IT FISH EYE</div>
	 </div>
   </div>
  
  </div>
  
  <a href="#" class="see-all-mobile">SEE ALL</a>
  
  <footer>
   <div class="footer-left">
    <h1>loopstudios</h1>
	<div class="bottom-nav A">
	 <a href="#">About</a>
	 <a href="#">Careers</a>
	 <a href="#">Events</a>
	 <a href="#">Products</a>
	 <a href="#">Support</a>
	</div>
   </div>
   <div class="footer-right">
    <div class="bottom-nav">
     <a href="#"><img src="images/icon-facebook.svg"></a>
	 <a href="#"><img src="images/icon-twitter.svg"></a>
	 <a href="#"><img src="images/icon-pinterest.svg"></a>
	 <a href="#"><img src="images/icon-instagram.svg"></a><br>
	</div>
	<h4>&copy; 2021 loopstudios.All rights reserved.</h4>
   </div>
  </footer>
  
  <script>
   function openClose(){
     var x = document.querySelector(".mobile-overlay");
	 var y = document.querySelector("body");
	 if (x.style.display === "block"){
	   x.style.display = "none";
	   y.style.overflow = "auto";
	   }
	 else {
	   x.style.display = "block";
	   y.style.overflow = "hidden";
	   }
   }
  </script>
      
 </body>   
</html>
