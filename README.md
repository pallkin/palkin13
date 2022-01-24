<!DOCTYPE html>
<style>
    *{
  user-select: none;
 padding: 0;
 margin: 0; 
 border: 0;
 outline: 0;
 font-size: 100%;
 background: transparent;
 vertical-align: baseline;
 overflow-x: 0;
}
html{
  scroll-behavior: smooth;
}
.main{
  display: block;
}
#pro > h1{
  text-align: center;
  margin-top: 20px;
}

/* *{
  background: black;
} */
/* navigation bar */
.nav{
  background: black;
  height: 80px;
  width: 100vw;
  max-width: 100%;
  position: fixed;
  /* position: relative; */
  top: 0%;
  z-index: 999;
}

/*nav links */
.abcdefu{
  position: absolute;
  right: 10%;
  top: 30%;
  /* left: 60%; */
  word-spacing:94px;
  display: inline;
  font-size: 130%;
}

/* img in nav */
.img{
  
  position: absolute;
  top: 30%;
  left: 10%;
  right:90%
}

/* link  */
.abcdefu a{
  color:rgba(175, 175, 175, 1);
  font-style: none;
}

.abcdefu a:hover{
  color: white;
  text-decoration-line:underline;
  text-decoration-style:solid;
  text-underline-offset: 15px;
  text-decoration-color:rgb(255, 255, 255) ;
  text-decoration-thickness: 5px;
}

/* page */
section{
  height: 100vh;
  width: 100vw;
  max-width:100%;
  max-height: 100%;
  scroll-margin-top: 80px;
}

#home{
  background-image: url("https://s3-alpha-sig.figma.com/img/8333/d065/6e5a89f378faefa7e2b7c2b74c9bdf94?Expires=1643587200&Signature=bbTa9oPdkOxJKEA~B-Bsno49Fmm~h5dTkgQ9-tVAjOmIUtgU4cqnmIdg7LMyl1qAJrvcQoFMdcVg67pvN4pz0rlaP3ak7GZRh5FVMm4VleUusoM45wQB12TWQbNNaXHtdb-Jx7-e-KD7aUfpkezwQIIaY~cmxxzEyYycSeUUoGfXD-e8dXXgB6LDRjBMH5JC1AR1ABsGLxQwJqzQb~SREEg1GDJDDWU0ptdJmMty-E-mtKdc7y9vjSTtstsks67qSkd7QpOEEAW85-XMMs-nmLbgOHS9oVPqXDbskqE2cA2Lj7-MAePjLjOhYC~~NmrXo8JeUrBnZtk5p6xDIkph9A__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA");
  background-size: 55%;
  background-repeat: no-repeat;
  background-position: 50% 50%;



}

.home{
  position: relative;
  z-index:1;
  color: rgb(255, 255, 255);
  text-align: center;
  position: relative;
  top:30%;
  /* font-size: 4.4vw;  */
}

.home h1{
  font-size: 8vh;
  margin: .5%;
}

.home h6{
  font-size: 200%;    
}
.home button{
  font-size: 150%;
  font-weight: 900;
  background: #E59B05;
  color: white;
  padding: 19px 40px 19px 40px;
  border-radius: 8px;
  margin-top: 20px;
}
.black{

  /* background-color: rgba(0,0, 0,.5); */
  background: radial-gradient(50% 50% at 50% 50%, rgba(0, 0, 0, 0.72) 0%, rgba(0, 0, 0, 0.81) 100%);
  height: 100vh;
  width: 100vw;
  max-width: 100%;
  position: absolute;
  z-index: 0;

}
.carousel{
  height: calc(100vh - 80px);
  /* height: 100vh; */
  width: 100vw;
  max-width: 100%;
}
.text-center{
  top: 0;
  height: calc(100vh - 80px);
  max-width: 100%!important;
  overflow: hidden!important;

}
.carousel-inner{
  overflow: visible!important;
  transform: translate(0px, 80%);

  top: 0;
  max-width: 100%!important;

}
.carousel-inner img{

  width: 300px;
  aspect-ratio: 1/1;
  transition: all linear 50ms;
  /* display: block; */
  background-image: url("task2 img/Ellipse1.png");
  /* position: relative; */
  /* background-size:80%; */
  background-repeat: no-repeat;
  background-position:center;
  /* background-position: bottom; */
  /* background-position-x: center; */
  /* background-position-y: top; */
}

#mainimg{
  position: relative;
  margin: auto;
}
#im12{
  position: absolute;
  margin-left: -30%;
}
#im11{
  position: absolute;
  margin-right: 45%;

}

.carousel-indicators {
  position: relative;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 15;
  display: -ms-flexbox;
  display: flex;
  -ms-flex-pack: center;
  justify-content: center;
  padding-left: 0;
  margin-right: 15%;
  margin-left: 15%;
  list-style: none;
}



#fea{
  background: rgba(238, 238, 238, 1);

}

#fea h1{
  position: absolute;
  margin-top: 20px;
  /* top: 5%; */
  /* right: 40%;
  left: 40%; */
  text-align:center;
  width: 100%;

}


#carouselExampleIndicators{
  position: relative;
  /* top: 100px; */
}

.box {
  /* display: flex; */
  /* justify-content: center; */
  position: relative;
  left: 50%;
  transform: translate(-50%, 130px);
  width: 90vw;
  padding: 10px;
  border-radius: 18px;
  background: radial-gradient(50% 50% at 50% 50%, #FAA700 0%, #E48D00 100%);
  text-align: left;
  text-align: left;

}
.text{
  text-align: left;
  margin-right: 440px;

}
.picbox {
  position: absolute;
  right: 2%;
  top: -10vh;
}




.box2 {
  position: relative;
  left: 50%;
  padding: 10px;
  transform: translate(-50%, 205px);
  top: 50px;
  width: 90vw;
  border-radius: 18px;
  text-align: left;
  margin-bottom:50px;

  background: radial-gradient(50% 50% at 50% 50%, #6DD5ED 0%, #2193B0 100%);
}
.text2 {
  text-align: left;
  margin-left: 441px;
}

.picbox2 {
  position: absolute;
   
  top: -10vh;
}




/* nav bar(small) */
#menuToggle{
  display: none;
}
@media only screen and (max-width:779px){
  #navA{
      display: none!important;
      
  }
  .img{
      /* float:right; */
      width: 100%;
      display: flex;
      justify-content: center;
      left: 0;
      /*position: absolute;
      left:0;
      transform:translate(50%,0%); */
      /* right: 50%;*/
  }
  .nav{
      display: flex;
      place-items: center;
  }
  #menuToggle
  {
    margin-left: 25px;  
    display: block;
    position: relative;
    /* top: 50px;
    left: 50px; */
    transform:scale(1.3) ;
    
    z-index: 1;
    
    -webkit-user-select: none;
    user-select: none;
  }
  
  #menuToggle a
  {
    text-decoration: none;
    color: #232323;
    
    transition: color 0.3s ease;
  }
  
  #menuToggle a:hover
  {
    color: tomato;
  }
  
  
  #menuToggle input
  {
    display: block;
    width: 40px;
    height: 32px;
    position: absolute;
    top: -7px;
    left: -5px;
    
    cursor: pointer;
    
    opacity: 0; /* hide this */
    z-index: 2; /* and place it over the hamburger */
    
    -webkit-touch-callout: none;
  }
  
 
  #menuToggle span
  {
    display: block;
    width: 33px;
    height: 3px;
    margin-bottom: 5px;
    position: relative;
    margin-left: 2vw;
    background: #cdcdcd;
    border-radius: 3px;
    
    z-index: 1;
    
    transform-origin: 4px 0px;
    
    transition: transform 0.5s cubic-bezier(0.77,0.2,0.05,1.0),
                background 0.5s cubic-bezier(0.77,0.2,0.05,1.0),
                opacity 0.55s ease;
  }
  
  #menuToggle span:first-child
  {
    transform-origin: 0% 0%;
  }
  
  #menuToggle span:nth-last-child(2)
  {
    transform-origin: 0% 100%;
  }
  

#menuToggle input:checked ~ span
  {
    opacity: 1;
    transform: rotate(45deg) translate(-2px, -1px);
    /* background: #232323; */
  }
  

  #menuToggle input:checked ~ span:nth-last-child(3)
  {
    opacity: 0;
    transform: rotate(0deg) scale(0.2, 0.2);
  }
  
 
  #menuToggle input:checked ~ span:nth-last-child(2)
  {
    transform: rotate(-45deg) translate(0, -1px);
  }

  #nav2
  {
      display: flex;
      place-items: center;
      justify-content: center;
      /* place-content: center; */
    position: absolute;
    width: 100vw;
    height: 100vh;
    /* max-width: 100%; */
    margin: -100px 0 0 -50px;
    /* padding-left: 0!important; */
    /* padding: 50px; */
    /* padding-top: 125px; */
    
    background: #474747b2;
    list-style-type: none;
    -webkit-font-smoothing: antialiased;
    /* to stop flickering of text in safari */
    
    transform-origin: 0% 0%;
    transform: translate(-100%, 0);
    
    transition: transform 0.5s cubic-bezier(0.77,0.2,0.05,1.0);
    backdrop-filter: blur(10px);
  }
  #nav2 a{
      /* flex: none; */
      display: block;
  }
  
  #nav2 li
  {
    padding: 10px 0;
    font-size: 40px;
    color: white;
  }
  #nav2::before{
      content:"";
      left: 0;
      position: absolute;
      display: block;
      background: black;
      height: 100vh;
      width:110px;
  }
  .nav211{
      margin-top: -50px;
  }
  /*
   * And let's slide it in from the left
   */
  #menuToggle input:checked ~ ul
  {
    transform: none;
  }

  #menuToggle a{
      color: black!important;
  }

  #nav2 li:active{
      color: black!important;
  }

  #nav2 li:active + #nav2{
      transform: translate(-100%, 0)!important;
  }


  .picbox >img ,.picbox2 > img{
      width: 200px;
  }
  .picbox {
      position: absolute;
      right: 10vw;
      top: -11vh;
      
  }
  .text {
      /* vertical-align: middle; */
      text-align: center;
      margin-right: 0;
      margin-top: 15vh;
  }
  .box {
      /* display: flex; */
      /* justify-content: center; */
      position: relative;
      left: 50%;
      transform: translate(-50%, 130px);
      width: 81vw;
      height: 55vh;
      padding: 10px;
      border-radius: 18px;
      background: radial-gradient(50% 50% at 50% 50%, #FAA700 0%, #E48D00 100%);
      text-align: left;
      text-align: left;
  }
  .box2 {
      position: relative;
      left: 50%;
      padding: 10px;
      transform: translate(-50%, 205px);
      top: 50px;
      width: 82vw;
      height: 52vh;
      border-radius: 18px;
      /* text-align: center; */
      /* vertical-align: middle; */
      background: radial-gradient(50% 50% at 50% 50%, #6DD5ED 0%, #2193B0 100%);
  }
  .picbox2 {
      position: absolute;
      right: 13vh;
      top: -11vh;
  }

   .text2 {
      margin-top: 13vh;
      text-align: center;
      margin-left: 0px;
      /* vertical-align: middle; */
  }
  .p {
      margin-top: 0;
      margin-bottom: 0;
  }
}

@media only screen and (max-width:376px) and (max-height:741px) {
  p {
      margin-top: 0;
      margin-bottom: 0!important;

  }
  .text2 {
      margin-top: 9vh;
      text-align: center;
      margin-left: 0px;
      /* vertical-align: middle; */
  }
  .text {
      /* vertical-align: middle; */
      text-align: center;
      margin-right: 0;
      margin-top: 11vh;
  }
}

#home1{
  font-style: italic;
}


.slide>h1{
  color:rgba(23, 53, 61, 1);
  font-style:oblique;
}
.abcdefu>a:active{
  color: chartreuse;
  /* outline: black; */
}
/* .picbox:hover,.picbox2:hover{
  transform: scale(1);
} */
#mainimg:hover{
  transform: scale3d(1.25,1.25,2);
  /* outline: rgba(21, 255, 0, 0.466) solid 4px; */
}
#im12:hover,#im11:hover{
  transform: scale(1.05);
}
#mainimg{
  position: relative;
  
  margin: auto;
}
#im12{
  position: absolute;
  margin-left: -30%;
  transform: scale(.75);
}
#im11{
  position: absolute;
  margin-left: 15%;
  transform: scale(.75);
}

.carousel-item {
  position: relative;
  top: -150px;
  display: none;
  float: left;
  width: 100%;
  margin-right: -100%;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
  transition: -webkit-transform .6s ease-in-out;
  transition: transform .6s ease-in-out;
  transition: transform .6s ease-in-out,-webkit-transform .6s ease-in-out;}
  
  
  
  
  
  
  
  
  
@media only screen and (max-width: 1210px) {
  
  #im12,#im11{
          display: none!important;
  }}


</style>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Amazon</title>
    <link rel="stylesheet" href="styles.css">

    <!-- Bootstrap css -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
        integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

    <!-- Bootstrap Js -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
        integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
        crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"
        integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1"
        crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"
        integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"
        crossorigin="anonymous"></script>

</head>

<body>

    <nav class="nav">
        <div class="img">
            <a href="#"><img src="https://s3-alpha-sig.figma.com/img/c6c3/4581/826c887c1bac3bb7c09edd19624a5919?Expires=1643587200&Signature=fA-Cz~hy4h39WK0WrCP-h22PI76CDbL~L1I64vxFXV1iBnhbKMnA3wE5eJaAIrB8hFyFBakICRrWD7jQ8AtZFy4FYGdQ~-qYD48WxN-8moSzxPugnU0JSt3cKvZCbA2K0kmYb~5uQ5YjReP5aclcogoYbkZlIrvVJdcFuEQr1zz-5-Y7j0BvNAk7kW2kPHWEl6GyBUCUMb553KssS0lACH7fsEzFaGiQRTNoBoGreZdQdFH8y1dp1x0z-sFM6d3peQEoe5JUIav2UntgAkm868xUyww7p3yLJYfH-KSxK5biB4MzW5y4PjRD7BuQpWpVuZ6LYkQcPcXBAO5IQ6lSRg__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA" style="width: 10VW;" alt="logo Amazon"> </a>
        </div>
        <div class="abcdefu" id="navA">
            <a href="#home" id="hmoe1">Home</a>
            <a href="#fea" id="fea1">Featured</a>
            <a href="#pro" id="pro1">Products</a>
        </div>
        <div id="menuToggle">

            <input id="hbc" type="checkbox" />

            <span></span>
            <span></span>
            <span></span>
            <ul id="nav2">
                <div id="nav211" class="nav211">
                    <a onclick="hbc()" href="#">
                        <li class="navRes">Home</li>
                    </a>
                    <a onclick="hbc()" href="#fea">
                        <li class="navRes">Featured</li>
                    </a>
                    <a onclick="hbc()" href="#pro">
                        <li class="navRes">Products</li>
                    </a>
                    <!-- <a href="#"><li>Contact</li></a> -->
                </div>
            </ul>
        </div>
    </nav>
    <section id="home">
        <div class="black">

        </div>
        <div class="home">

            <h1 id="home1">
                <b> AMAZING SHOES AT AN <br> AMAZING PRICE</b>
            </h1>
            <h6>Your Perfect Shoe Mate</h6>
            <a href="#fea"><button type="button">SEE WHAT WE HAVE</button></a>
        </div>
    </section>

    <section id="fea">
        <div class="fea">
            <!-- <header> -->
            <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
                <h1>Featured Products</h1>
                <!-- slider button -->
                <ol class="carousel-indicators">
                    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
                </ol>
                <!-- imgage -->
                <div class="text-center">
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <!-- <div class="circle" ></div> -->
                            <img src="https://s3-alpha-sig.figma.com/img/9e06/5c5a/a3c17d4bf3d4ccfa8eaab41533f982c6?Expires=1643587200&Signature=WPx5x33oYzDjxWZaHI14-3xekwushIcnmUUbephx4bGT28X3FF6rKXvS9nIdPablKMoHnwogPJJVVTzia~gLDD27tse5i~v3PxoT91Vmrwq2lfQrb8ptSAwWzRJiNMsuoaAHMGK-fyohKpMcTS3rA1PSk7e3jRS9JW2gim0rJirMnTdMc2szWFVjtaThRbeRalqdB4nRLF0PKo55CXXyKZbQtQ6spBW4U-jFGuU7uI8glJtHJin8WI~jK8OTacTwyNsgFsaeNQarqslCQy~VSlOm6log74PVFuy0BjRd9QpZ25GUyR~44yMRmt7sRJh~nh6oyFZUynDXUZmogESu5w__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA" class="img-fluid" id="im12">
                            <img src="https://s3-alpha-sig.figma.com/img/a7b0/4fc7/8860f9d2e644b5c2e8559733f8e43169?Expires=1643587200&Signature=dtBRXm3WI4pdVZWxxS9NNx9jZSDzs6Td~f-deXLK~LVuhi3-sI1-RH4M1xV21AZcZYFYsK49or1uBmEnm6ZyNGEMh-Ii0v0kS2g4Ph27RWQbTihP-ZPLFsA551lnY2pt2dZwZyBXN4HNk08COmnly5SprNo6caQPo967om2hpnNKv49pMUZitsYw7p6RTSs7ZQS0bBq6flwHThif5KNigIe6z2gE~pF3wrh5mcyhvY89yAoCISqQ68umku1FgRurf6-9Wldn~udpq2aFvwqp~zjBiqHkaob77-t13qa8Nb1YdBq~Gi6~vlvo35Gz48DFXYRTKdWu0Gn6emjf~AJeuw__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA" class="img-fluid" id="mainimg">
                            <img src="https://s3-alpha-sig.figma.com/img/6659/dec6/4c1a4ac118472e7026cbf7abd6eadc4a?Expires=1643587200&Signature=VyIyXDp6DXJkPEyt6dNnh2nMx1-BNzle-fvwvj9u650hOnOco1xGyd8P-Uk5nuIIOv96m9B2osgTVYa33EcEfIipoBsdHI178uU~evkSIQxKWGFQnfcYSlXC6WrcYyOEtMVvkWJ0-jpMiELExSd-SLmSaxROIcmW1CmAumSirJs59tHUF~lJu-jPNCMbfV72inT4RyNSsZMyLk3cci7wY2awMw2dJ02007Pi7WZyhWLqOU~~05fv0oZKQoFnHzHyGZL5H98kcNHoKmFftbefdZRLbXEsJMekNAcJeGEY3pcmQFEC1V5U1str9eDEfkX1MOduJkOKYj5BweYv5gqzmA__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA" class="img-fluid" id="im11">
                            <h2 class="discost">₹4999</h2>
                            <p class="disname">ADIDAS</p>
                        </div>

                        <div class="carousel-item">
                            <!-- <div class="circle" ></div> -->
                            <img src="https://s3-alpha-sig.figma.com/img/6659/dec6/4c1a4ac118472e7026cbf7abd6eadc4a?Expires=1643587200&Signature=VyIyXDp6DXJkPEyt6dNnh2nMx1-BNzle-fvwvj9u650hOnOco1xGyd8P-Uk5nuIIOv96m9B2osgTVYa33EcEfIipoBsdHI178uU~evkSIQxKWGFQnfcYSlXC6WrcYyOEtMVvkWJ0-jpMiELExSd-SLmSaxROIcmW1CmAumSirJs59tHUF~lJu-jPNCMbfV72inT4RyNSsZMyLk3cci7wY2awMw2dJ02007Pi7WZyhWLqOU~~05fv0oZKQoFnHzHyGZL5H98kcNHoKmFftbefdZRLbXEsJMekNAcJeGEY3pcmQFEC1V5U1str9eDEfkX1MOduJkOKYj5BweYv5gqzmA__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA" class="img-fluid" id="im12">
                            <img src="https://s3-alpha-sig.figma.com/img/9e06/5c5a/a3c17d4bf3d4ccfa8eaab41533f982c6?Expires=1643587200&Signature=WPx5x33oYzDjxWZaHI14-3xekwushIcnmUUbephx4bGT28X3FF6rKXvS9nIdPablKMoHnwogPJJVVTzia~gLDD27tse5i~v3PxoT91Vmrwq2lfQrb8ptSAwWzRJiNMsuoaAHMGK-fyohKpMcTS3rA1PSk7e3jRS9JW2gim0rJirMnTdMc2szWFVjtaThRbeRalqdB4nRLF0PKo55CXXyKZbQtQ6spBW4U-jFGuU7uI8glJtHJin8WI~jK8OTacTwyNsgFsaeNQarqslCQy~VSlOm6log74PVFuy0BjRd9QpZ25GUyR~44yMRmt7sRJh~nh6oyFZUynDXUZmogESu5w__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA" class="img-fluid" id="mainimg">
                            <img src="https://s3-alpha-sig.figma.com/img/a7b0/4fc7/8860f9d2e644b5c2e8559733f8e43169?Expires=1643587200&Signature=dtBRXm3WI4pdVZWxxS9NNx9jZSDzs6Td~f-deXLK~LVuhi3-sI1-RH4M1xV21AZcZYFYsK49or1uBmEnm6ZyNGEMh-Ii0v0kS2g4Ph27RWQbTihP-ZPLFsA551lnY2pt2dZwZyBXN4HNk08COmnly5SprNo6caQPo967om2hpnNKv49pMUZitsYw7p6RTSs7ZQS0bBq6flwHThif5KNigIe6z2gE~pF3wrh5mcyhvY89yAoCISqQ68umku1FgRurf6-9Wldn~udpq2aFvwqp~zjBiqHkaob77-t13qa8Nb1YdBq~Gi6~vlvo35Gz48DFXYRTKdWu0Gn6emjf~AJeuw__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA" class="img-fluid" id="im11">

                            <h2 class="discost">₹3599</h2>
                            <p class="disname">SKECHERS</p>
                        </div>
                        <div class="carousel-item">
                            <!-- <div class="circle" ></div> -->
                            <img src="https://s3-alpha-sig.figma.com/img/a7b0/4fc7/8860f9d2e644b5c2e8559733f8e43169?Expires=1643587200&Signature=dtBRXm3WI4pdVZWxxS9NNx9jZSDzs6Td~f-deXLK~LVuhi3-sI1-RH4M1xV21AZcZYFYsK49or1uBmEnm6ZyNGEMh-Ii0v0kS2g4Ph27RWQbTihP-ZPLFsA551lnY2pt2dZwZyBXN4HNk08COmnly5SprNo6caQPo967om2hpnNKv49pMUZitsYw7p6RTSs7ZQS0bBq6flwHThif5KNigIe6z2gE~pF3wrh5mcyhvY89yAoCISqQ68umku1FgRurf6-9Wldn~udpq2aFvwqp~zjBiqHkaob77-t13qa8Nb1YdBq~Gi6~vlvo35Gz48DFXYRTKdWu0Gn6emjf~AJeuw__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA" class="img-fluid" id="im12">
                            <img src="https://s3-alpha-sig.figma.com/img/6659/dec6/4c1a4ac118472e7026cbf7abd6eadc4a?Expires=1643587200&Signature=VyIyXDp6DXJkPEyt6dNnh2nMx1-BNzle-fvwvj9u650hOnOco1xGyd8P-Uk5nuIIOv96m9B2osgTVYa33EcEfIipoBsdHI178uU~evkSIQxKWGFQnfcYSlXC6WrcYyOEtMVvkWJ0-jpMiELExSd-SLmSaxROIcmW1CmAumSirJs59tHUF~lJu-jPNCMbfV72inT4RyNSsZMyLk3cci7wY2awMw2dJ02007Pi7WZyhWLqOU~~05fv0oZKQoFnHzHyGZL5H98kcNHoKmFftbefdZRLbXEsJMekNAcJeGEY3pcmQFEC1V5U1str9eDEfkX1MOduJkOKYj5BweYv5gqzmA__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA" class="img-fluid" id="mainimg">
                            <img src="https://s3-alpha-sig.figma.com/img/9e06/5c5a/a3c17d4bf3d4ccfa8eaab41533f982c6?Expires=1643587200&Signature=WPx5x33oYzDjxWZaHI14-3xekwushIcnmUUbephx4bGT28X3FF6rKXvS9nIdPablKMoHnwogPJJVVTzia~gLDD27tse5i~v3PxoT91Vmrwq2lfQrb8ptSAwWzRJiNMsuoaAHMGK-fyohKpMcTS3rA1PSk7e3jRS9JW2gim0rJirMnTdMc2szWFVjtaThRbeRalqdB4nRLF0PKo55CXXyKZbQtQ6spBW4U-jFGuU7uI8glJtHJin8WI~jK8OTacTwyNsgFsaeNQarqslCQy~VSlOm6log74PVFuy0BjRd9QpZ25GUyR~44yMRmt7sRJh~nh6oyFZUynDXUZmogESu5w__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA" class="img-fluid" id="im11">
                            <h2 class="discost">₹6999</h2>
                            <p class="disname">NIKE AIR</p>
                        </div>

                    </div>
                </div>
                <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="sr-only">Previous</span>
                </a>
                <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="sr-only">Next</span>
                </a>
            </div>

            <!-- </header> -->

        </div>
    </section>

    <section id="pro">
        <h1>OUR PRODUCTS</h1>
        <div class="box">
            <span class="picbox">
                <img src="https://s3-alpha-sig.figma.com/img/8333/d065/6e5a89f378faefa7e2b7c2b74c9bdf94?Expires=1643587200&Signature=bbTa9oPdkOxJKEA~B-Bsno49Fmm~h5dTkgQ9-tVAjOmIUtgU4cqnmIdg7LMyl1qAJrvcQoFMdcVg67pvN4pz0rlaP3ak7GZRh5FVMm4VleUusoM45wQB12TWQbNNaXHtdb-Jx7-e-KD7aUfpkezwQIIaY~cmxxzEyYycSeUUoGfXD-e8dXXgB6LDRjBMH5JC1AR1ABsGLxQwJqzQb~SREEg1GDJDDWU0ptdJmMty-E-mtKdc7y9vjSTtstsks67qSkd7QpOEEAW85-XMMs-nmLbgOHS9oVPqXDbskqE2cA2Lj7-MAePjLjOhYC~~NmrXo8JeUrBnZtk5p6xDIkph9A__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA" alt="Vans shoe" width="400px">

            </span>



            <div class="text">
                <h1>Vans Men's<br>Classic Trainers</h1>
                <p>Inspired by Vans classic old skool, the ward is a low top,
                    vulcanized lace up style with Vans signature side stripe.
                    along with vulcanized construction, offer increased comfort.
                    </p>
                <h2>₹4999</h2>
            </div>
        </div>
        <div class="box2">
            <span class="picbox2">
                <img src="https://s3-alpha-sig.figma.com/img/ecfc/1e1d/211180e4cadb175fb739a54501559927?Expires=1643587200&Signature=Aruof9kUiBm-2Pxft3xjdt8qQXuNrNsw7ANsno49UNXAtx5VCwssjTakv3USiVcEohvANt9lE5fEKtwF7~WhEng90IAAvNT01wiQphOeBv6iOGik710g5SZx5OpjNm3YzZYskDUj3b2TDI5zcqScZwskUc-yoJC-82xUsHqFR~-ueerkvpLr6im~dM6a5QsyJZtLkYdCqJeUjR54jXPoh-g3VGN~CeOUl~10rljlH2caBDQ31tJlDVXRfhxnbyvQopKQ8~NvQvPpXPIzzn4z4~zCPS~D1XX7xSx2xPA2YDUwggWcj1urxr8qQE4JIrUW61Wgyfya08HVCPP6iOAlSg__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA" width="400px">

            </span>
            <div class="text2">

                <h1>New Balance<br>Sneakers</h1>
                <p> Our shoes are lightweight, comfortable, sturdy and extremely sporty. 
                    The sole of all Labbin shoes is designed to provide an increased amount of comfort and the material is 
                    good enough to provide an improved fit. 
                    </p>
                <h2>₹3999</h2>
            </div>
        </div>

    </section>
    <script>
        function hbc() { document.getElementById('hbc').checked = false; }
    </script>

    <script type="module">
        // Import the functions you need from the SDKs you need
        import { initializeApp } from "https://www.gstatic.com/firebasejs/9.6.3/firebase-app.js";
        import { getAnalytics } from "https://www.gstatic.com/firebasejs/9.6.3/firebase-analytics.js";
        // TODO: Add SDKs for Firebase products that you want to use
        // https://firebase.google.com/docs/web/setup#available-libraries

        // Your web app's Firebase configuration
        // For Firebase JS SDK v7.20.0 and later, measurementId is optional
        const firebaseConfig = {
            apiKey: "AIzaSyBEkIdcIpz1ih6IGaKilW6jg_-GD5Cr0d0",
            authDomain: "replica-bae3a.firebaseapp.com",
            projectId: "replica-bae3a",
            storageBucket: "replica-bae3a.appspot.com",
            messagingSenderId: "437977473297",
            appId: "1:437977473297:web:99fa2ef21f7ba06dd82cb0",
            measurementId: "G-M625GWC2SE"
        };

        // Initialize Firebase
        const app = initializeApp(firebaseConfig);
        const analytics = getAnalytics(app);
    </script>

    <!-- Insert these scripts at the bottom of the HTML, but before you use any Firebase services -->
    <!-- Firebase App (the core Firebase SDK) is always required and must be listed first -->
    <script src="/__/firebase/8.10.0/firebase-app.js"></script>

    <!-- Add Firebase products that you want to use -->
    <script src="/__/firebase/8.10.0/firebase-auth.js"></script>
    <script src="/__/firebase/8.10.0/firebase-firestore.js"></script>
    <script src="/__/firebase/8.10.0/firebase-app.js"></script>
    <script src="/__/firebase/8.10.0/firebase-analytics.js"></script>


</body>

</html>
