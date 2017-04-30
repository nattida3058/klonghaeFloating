<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>

body, html {
    height: 100%;
    color: #777;
    line-height: 1.8;
}

/* Create a Parallax Effect */
.bgimg-1, .bgimg-2, .bgimg-3, .bgimg-4{
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

/* First image (Logo. Full height) */
.bgimg-1 {
    background-image: url('1.jpg');
    min-height: 100%;
}

/* Second image (Portfolio) */
.bgimg-2 {
    background-image: url("2.jpg");
    min-height: 400px;
}

/* Third image (Contact) */
.bgimg-3 {
    background-image: url("3.jpg");
    min-height: 400px;
}

/* fourth image (Contact) */
.bgimg-4 {
    background-image: url("4.jpg");
    min-height: 400px;
}

.w3-wide {letter-spacing: 10px;}
.w3-hover-opacity {cursor: pointer;}

/* Turn off parallax scrolling for tablets and phones */
@media only screen and (max-device-width: 1024px) {
    .bgimg-1, .bgimg-2, .bgimg-3, .bgimg-4 {
        background-attachment: scroll;
    }
}
</style>
<body>

<!-- logo desktop -->
<header class="w3-top w3-light-grey col-md-2 logo col-sm-2 col-xs-2  logo-mobile-show " id="header">
<a href="https://wanisa39.github.io/market/"> <img src="25.png" alt="betagro logo"></a>


<!-- Right-sided navbar links -->
<div class="w3-top ">
<div class="current_page_item  overlay"></div>
<ol class=" hiddenhome"></ol>
  <div class="w3-row w3-padding w3-hide-small w3-center   ">
	<div class="w3-col s2 ">
	  <a class="w3-bar-item w3-button"></a> 
	</div>
	 <div class="w3-col s2 ">
	  <a href="#home" class="w3-bar-item w3-button"><i class="fa fa-home"></i> Home</a> 
	</div>
	<div class="w3-col s2">
      <a href="#Story" class="w3-bar-item w3-button"><i class="fa fa-book"></i> Story</a>
	</div>
	<div class="w3-col s2">
      <a href="#Point" class="w3-bar-item w3-button "><i class="fa fa-star"></i> Point</a>
	</div>
	<div class="w3-col s2">
      <a href="#Gallery" class="w3-bar-item w3-button "><i class="fa fa-photo"></i> Gallery</a>
	</div>
	<div class="w3-col s2">
      <a href="#Map" class="w3-bar-item w3-button "><i class="fa fa-map-pin"></i> Map</a>
	  
	</div> 
  </div>      
</div>

    <!-- Hide right-floated links on small screens and replace them with a menu icon -->
    
    <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium w3-right" onclick="w3_open()">
      <i class="fa fa-bars"></i>
    </a>
  </div>
</div>

<!-- Sidebar on small screens when clicking the menu icon -->
<nav class="w3-sidebar w3-bar-block w3-black w3-card-2 w3-animate-left w3-hide-medium w3-hide-large" style="display:none" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-large w3-padding-16">Close ×</a>
  <a href="#Story" onclick="w3_close()" class="w3-bar-item w3-button">Story</a>
  <a href="#Point" onclick="w3_close()" class="w3-bar-item w3-button">Point</a>
  <a href="#Gallery" onclick="w3_close()" class="w3-bar-item w3-button">Gallery</a>
  <a href="#Map" onclick="w3_close()" class="w3-bar-item w3-button">Map</a>
  
</nav>
</header>

<!-- First Parallax Image with Logo Text -->
<div class="bgimg-1 w3-display-container" id="home">
  <div class="w3-display-middle" style="white-space:nowrap;">
    <span class="w3-center w3-padding-large w3-black w3-xlarge w3-wide w3-animate-opacity">MY <span class="w3-hide-small">WEBSITE</span> LOGO</span>
  </div>
</div>

<!-- Story Section -->
  <div class="w3-padding-64 w3-container"id="Story">
    <div class="w3-col m6 w3-padding-large w3-hide-small">
     <img src="5.jpg" class="w3-round w3-image" alt="Table Setting" width="600" height="750">
    </div>

    <div class="w3-col m6 w3-padding-large w3-container w3-card-2">
      <h1 class="w3-center"> About Catering</h1><br>
      <h5 class="w3-center">Tradition since 1889</h5>
      <p class="w3-large">The Catering was founded in blabla by Mr. Smith in lorem ipsum dolor sit amet, consectetur adipiscing elit consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute iruredolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.We only use <span class="w3-tag w3-light-grey">seasonal</span> ingredients.</p>
      <p class="w3-large w3-text-grey w3-hide-medium">Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod temporincididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    </div>
  </div>
  
  <hr>
  
<!-- Menu Section -->
  <div class="w3-padding-64 w3-container" id="menu">
    <div class="w3-col l6 w3-padding-large w3-container w3-card-2  ">
      <h1 class="w3-center">Our Menu</h1><br>
      <h4>Bread Basket</h4>
      <p class="w3-text-grey">Assortment of fresh baked fruit breads and muffins 5.50</p><br>
    
      <h4>Honey Almond Granola with Fruits</h4>
      <p class="w3-text-grey">Natural cereal of honey toasted oats, raisins, almonds and dates 7.00</p><br>
    
      <h4>Belgian Waffle</h4>
      <p class="w3-text-grey">Vanilla flavored batter with malted flour 7.50</p><br>
    
      <h4>Scrambled eggs</h4>
      <p class="w3-text-grey">Scrambled eggs, roasted red pepper and garlic, with green onions 7.50</p><br>
    
      <h4>Blueberry Pancakes</h4>
      <p class="w3-text-grey">With syrup, butter and lots of berries 8.50</p>    
    </div>
    
    <div class="w3-col l6 w3-padding-large">
      <img src="7.jpg" class="w3-round w3-image" alt="Menu" width="500" height="750">
    </div>
  </div>

  <hr>
 
 <!-- Second Parallax Image with Portfolio Text -->
<div class="bgimg-2 w3-display-container" id="Point">
  <div class="w3-display-middle">
     <span class="w3-xxlarge w3-text-white w3-wide">POINT</span>
  </div>
</div>


<!-- Container (Point  Section) -->
<div class=" w3-padding-64">
  <h3 class="w3-center w3-text-black">ระดับความพึงพอใจ</h3>
 <div class="w3-padding-64 w3-container w3-center" >
   <i class="fa fa-star" style="font-size:36px"></i>
   <i class="fa fa-star" style="font-size:36px"></i>
   <i class="fa fa-star" style="font-size:36px"></i>
   <i class="fa fa-star-o" style="font-size:36px"></i>
   <i class="fa fa-star-o" style="font-size:36px"></i>
  <p class="w3-center w3-text-black"><em>Here are some of my latest lorem work ipsum tipsum.<br> Click on the images to make them bigger</em></p><br>
  </div>
</div>
<!-- Third  Parallax Image with Portfolio Text -->
<div class="bgimg-3 w3-display-container" id="Gallery">
  <div class="w3-display-middle  ">
    <span class="w3-xxlarge w3-text-white w3-wide">GALLERY</span>
  </div>
</div>

<!-- Container (Gallery Section) -->
<div class=" w3-padding-64">
  <h3 class="w3-center">MY WORK</h3>
  <p class="w3-center"><em>Here are some of my latest lorem work ipsum tipsum.<br> Click on the images to make them bigger</em></p><br>
  
 <!-- Responsive Grid. Four columns on tablets, laptops and desktops. Will stack on mobile devices/small screens (100% width) -->
  <div class="w3-row-padding w3-center">
    <div class="w3-col m3">
      <img src="8.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="The mist over the mountains">
    </div>

    <div class="w3-col m3">
      <img src="9.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Coffee beans">
    </div>

    <div class="w3-col m3">
      <img src="10.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Bear closeup">
    </div>

    <div class="w3-col m3">
      <img src="12.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Quiet ocean">
    </div>
  </div>

  <div class="w3-row-padding w3-center w3-section">
    <div class="w3-col m3">
      <img src="13.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="The mist">
    </div>

    <div class="w3-col m3">
      <img src="14.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="My beloved typewriter">
    </div>

    <div class="w3-col m3">
      <img src="15.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Empty ghost train">
    </div>

    <div class="w3-col m3">
      <img src="16.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Sailing">
    </div>
   
  </div>
</div>

  <!-- Modal for full size images on click-->
<div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
  <span class="w3-button w3-large w3-black w3-display-topright" title="Close Modal Image"><i class="fa fa-remove"></i></span>
  <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
    <img id="img01" class="w3-image">
    <p id="caption" class="w3-opacity w3-large"></p>
  </div>
</div>

<!-- fourth Parallax Image with Portfolio Text -->
<div class="bgimg-4 w3-display-container" id="Map">
  <div class="w3-display-middle">
     <span class="w3-xxlarge w3-text-white w3-wide">MAP</span>
  </div>
</div>
<!-- Container (MAP Section) -->
  <div class="w3-row w3-padding-32 w3-section">
    <div class="w3-col m4 w3-container">
      <!-- Add Google Maps -->
      <div id="googleMap" class="w3-round-large w3-greyscale" style="width:100%;height:400px;"></div>
    </div>
    <div class="w3-col m8 w3-panel">
      <div class="w3-large w3-margin-bottom">
        <i class="fa fa-map-marker fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Hat Yat,THA<br>
      </div>
    
      <p>Swing by for a cup of <i class="fa fa-coffee"></i>, or leave me a note:</p>
	  
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-64 w3-opacity w3-hover-opacity-off">
  <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
  <div class="w3-xlarge w3-section">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
  </div>
  <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green">w3.css</a></p>
</footer>
 
<!-- Add Google Maps -->
<script>
function myMap()
{
  myCenter=new google.maps.LatLng(7.007112, 100.46982300000002);
  var mapOptions= {
    center:myCenter,
    zoom:12, scrollwheel: false, draggable: false,
    mapTypeId:google.maps.MapTypeId.ROADMAP
  };
  var map=new google.maps.Map(document.getElementById("googleMap"),mapOptions);

  var marker = new google.maps.Marker({
    position: myCenter,
  });
  marker.setMap(map);
}

// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}

// Change style of navbar on scroll
window.onscroll = function() {myFunction()};
function myFunction() {
    var navbar = document.getElementById("myNavbar");
    if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
        navbar.className = "w3-bar" + " w3-card-2" + " w3-animate-top" + " w3-white";
    } else {
        navbar.className = navbar.className.replace(" w3-card-2 w3-animate-top w3-white", "");
    }
}

// Used to toggle the menu on small screens when clicking on the menu button
function toggleFunction() {
    var x = document.getElementById("navDemo");
    if (x.className.indexOf("w3-show") == -1) {
        x.className += " w3-show";
    } else {
        x.className = x.className.replace(" w3-show", "");
    }
}
</script>
<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyBu-916DdpKAjTmJNIgngS6HL_kDIKU0aU&callback=myMap"></script>
<!--
To use this code on your website, get a free API key from Google.
Read more at: https://www.w3schools.com/graphics/google_maps_basic.asp
-->



</body>
</html>
