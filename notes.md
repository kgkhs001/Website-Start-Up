Boiler Plate
<!-- <!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>replit</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    Hello world
    <script src="script.js"></script>
  </body>
</html> -->

The Navbar 
<!-- <header>
      <a href="index.html" class="logo"> < / Garg Web Development > </a>
      <ul>
        <div class="dropdown">
          <button class="dropbtn"><li><a href="#">Products</a></li></button>
          <div class="dropdown-content">
            <a href="#">Templates</a>
            <a href="#">Customize</a>
            <a href="#">Update</a>
          </div>
        </div>
        <li><a href="#">Pricing</a></li>
        <li><a href="#">Contact Us</a></li>
        <li><a href="#">About Us</a></li>
      </ul>
    </header>
    <script type="text/javascript">
      window.addEventListener("scroll", function(){
        var header = document.querySelector("header");
        header.classList.toggle("sticky", window.scrollY > 0);
      })
    </script> -->

    <!-- .parallax-effect {
        background-image: url("https://p0.pxfuel.com/preview/697/898/445/cloud-computing-illustration-technology.jpg");
        height: 100%;
        width: 100%;
        background-attachment: fixed;
        background-position: center;
        background-repeat: repeat-y;
        background-size: cover;
      } -->


      Footer Template
      <div class="fourthsection">
        <div class="fifth">
          <div class="mainline-three"><h1>Contact Us</h1></div>
      </div>
    </div> 

    Css footer

  .fourthsection{
    background: black;
    color: white;
    text-align: center;
    height: 135%;
    width: 100%;
  }
  .mainline-three{
    padding-top: 2.5%;
    text-decoration: underline;
    text-align: center;
  }





  CARDS HTML

  <div class="cardholder">
      <div class="card">
        <a href="http://sacoriverlodgeandsuites.com/MtWashington.htm"><img src="http://sacoriverlodgeandsuites.com/images/mtwashington_001.png" alt="White Mountains"></a>
        <div class="container">
          <p><b>Mount Washington</b></p>
          <p></p>
        </div>
      </div>

      <div class="card">
        <a href="http://sacoriverlodgeandsuites.com/north-conway-canoe-kayak-lodge-specials.htm"><img src="http://sacoriverlodgeandsuites.com/saco_river_images/saco-river-canoe.jpg" alt="Saco River"></a>
        <div class="container">
          <p><b>Saco River</b></p>
          <p></p>
        </div>
      </div>

      <div class="card">
        <a href="http://sacoriverlodgeandsuites.com/HIKERS.htm"><img src="http://sacoriverlodgeandsuites.com/images/7405778508_4977b9aea7_m.jpg" alt="Trails"></a>
        <div class="container">
          <p><b>Hiking Trails</b></p>
          <p></p>
        </div>
      </div>

      <div class="card">
        <a href="http://sacoriverlodgeandsuites.com/SummerFun.htm"><img src="http://sacoriverlodgeandsuites.com/images/slides.jpg" alt="Foliage"></a>
        <div class="container">
          <p><b>Summer Fun</b></p>
          <p></p>
        </div>
      </div>

      <div class="card">
        <a href="http://sacoriverlodgeandsuites.com/FRYEBURGFAIR.htm"><img src="http://sacoriverlodgeandsuites.com/images/fryeburgfair.png" alt="Fryeburg Fair"></a>
        <div class="container">
          <p><b>Fryeburg Fair</b></p>
          <p></p>
        </div>
      </div>

      <div class="card">
        <a href="http://sacoriverlodgeandsuites.com/SNOWMOBILINGSKI.htm"><img src="http://sacoriverlodgeandsuites.com/images/cranmore.jpg" alt="Skiing"></a>
        <div class="container">
          <p><b>Winter Fun</b></p>
          <p></p>
        </div>
      </div>
    </div>


    CARDS CSS
    .cardholder{
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
}

.card {
  /* Add shadows to create the "card" effect */
  width: 16.667%;
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
  transition: 0.6s;
  margin-top: 10px;
}
.card img{
  height: 100%;
  width: 100%;
  padding: 10px ;
}
.card p{
  text-align: center;
  font-size: 110%;
}
/* On mouse-over, add a deeper shadow */
.card:hover {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,1);
}

/* Add some padding inside the card container */
.container {
  padding: 2px 16px;
}
