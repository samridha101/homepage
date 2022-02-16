<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" type="text/css" href="style.css" />
    <link
      rel="stylesheet"
      href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
      integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm"
      crossorigin="anonymous"
      -
    />
    <!-- <link rel="stylesheet" href="../public/stylesheets/logindashbord.css" /> -->
    <title>home</title>
  </head>

  <body>
    <header>
      <nav class="navbar navbar-expand-lg navbar-light">
        <div class="nav-logo">
          <div class="row text-white">
            <img
              src="logo.png"
              class="image-logo mr-3"
              alt="" height="300" width="100"
            />
            <h2 class="heading text-white">Leaders Academy</h2>
            <button
              class="navbar-toggler ml-auto"
              type="button"
              data-toggle="collapse"
              data-target="#navbarNav"
              aria-controls="navbarNav"
              aria-expanded="false"
              aria-label="Toggle navigation"
            >
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse nav-end" id="navbarNav">
              <div class="navbar-nav">
                <a class="nav-item nav-link active text-white" href="#">LDP </a>
                <a class="nav-item nav-link text-white" href="#">Resource</a>
                <a class="nav-item nav-link text-white" href="#">Achievement</a>
                <a class="nav-item nav-link text-white" href="#">Admission</a>
                <a class="nav-item nav-link text-white" href="#">About Us</a>
              </div>
            </div>
          </div>
        </div>
      </nav>
    </header>
    <main>
    
        <div class="container-fluid">
          <div class="row mt-2">
            <div class="col">
              
                    <h1><b>LEADERS</b><br>ACADEMY</h1>
                    <button type="button" class="btn btn-primary" data-toggle="modal" data-target="#exampleModal" data-whatever="@getbootstrap">Login</button>
            </div>
            
              
                <div class="col">
                    <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
                        <div class="carousel-inner">
                          <div class="carousel-item active">
                            <img class="d-block w-100" src="Samridha.jpeg" alt="First slide" height="400" width="50">
                          </div>
                          <div class="carousel-item">
                            <img class="d-block w-100" src="Nawaf.jpeg" alt="Second slide" height="400" width="50">
                          </div>
                          <div class="carousel-item">
                            <img class="d-block w-100" src="Hadi.jpeg" alt="Third slide" height="400" width="50">
                          </div>
                        </div>
                        <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
                          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                          <span class="sr-only">Previous</span>
                        </a>
                        <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
                          <span class="carousel-control-next-icon" aria-hidden="true"></span>
                          <span class="sr-only">Next</span>
                        </a>
                    </div>
                  
            
            </div>
        </div>
      </div>
<div class="modal fade" id="exampleModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog" role="document">
    <div class="modal-content text-white">
      <div class="modal-header">
        <h1 class="modal-title mx-auto " id="exampleModalLabel">Login</h1>
        <button type="button" class="close text-white" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body mx-auto">
        <form>
          <div class="form-group ">
            <label for="recipient-name" class="col-form-label">Username:</label>
            <input type="text" class="form-control" id="recipient-name">
          </div>
          <div class="form-group ">
            <label for="message-text" class="col-form-label">Password:</label>
            <input class="form-control" id="message-text" type="password"></input>
          </div>
        </form>
      </div>
      <div class="modal-footer">
        <button type="submit" class="btn mx-auto "> <b> submit</b></button>
      </div>
    </div>
  </div>
</div>
    
</main>
<footer>
  <div class="container">
    <div class="row mt-4">
      <div class="col">
        <h2 class="head-leagel"><u> LEGAL</u></h2>
        <ul>
            <li>Terms & conditions</li>
            <li>Privacy policy</li>
            <li>Cookies policy</li>
            <li>Cookies settings</li>
        </ul>

      </div>
      <div class="col">
        <h2 class="head-leagel"><u>HELP</u></h2>
        <ul>
            <li>Support</li>
            <li>Contact</li>
        </ul>
      </div>
      <div class="col">

      </div>
      <div class="col">
        <h2 class="head-leagel"><u>SOCIAL MEDIA</u></h2>
        <div class="row mt-4">
            <i class="fab fa-facebook"></i>
            <i class="fab fa-instagram"></i>
            <i class="fab fa-linkedin"></i>
            <i class="fab fa-twitter-square"></i>
            <i class="fab fa-youtube"></i>
        </div>

      </div>

    </div>
  </div>
</footer>
    
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" integrity="sha512-Fo3rlrZj/k7ujTnHg4CGR2D7kSs0v4LLanw2qksYuRlEzO+tcaEPQogQ0KaoGN26/zrn20ImR1DfuLWnOo7aBA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
</body>
</html>




.container-fluid{
   background-color: rgb(228, 243, 255); 
   margin-bottom: -20px;
   margin-top: -8px;
}

.navbar {
    background-color: #63808c;
  }
  .image-logo {
    max-width: 3%;
    height: 40px;
  }
  .nav-logo {
    margin-left: 20px;
  }
  .nav-end {
    margin-left: 680px;
  }
  

@media screen and (max-width:980px) {
  .nav-end {
  margin-left: 95px;
  }
}


@media screen and (max-width: 768px) {
    .image-logo {
      max-width: 9%;
      height: 45px;
    }
  }

    .heading {
      font-size: 24px;
      line-height: revert;
      margin-right: 24px;
    }

  .modal-header .close {
    margin: 0rem;
  }
  .modal-body{
    background-color: #63808C;
  }
  .modal-header{
    background-color: #63808C;
  }
  .modal-footer{
    background-color: #63808C;
  }

  
  .carousel{
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
    margin: 10px 0;
    padding: 5px;
    transition: 3%;
  }

 .footer {
  background-color: #63808c;
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  color: #63808c;
  text-align: center;
 
  
}
.ul {
    text-align: left;
    list-style-type: none;
    font-size: 18px;
    padding: 0;
    
    
}
.head-leagel{
    color: #A2B9C2;
    text-align: left;
}
.fab{
    margin-left: 15px;
    font-size: 33px;
}

.container{
  background-color: #63808c ;
}

@media screen and (max-width:980px) {
  .col .carousel {
  margin-bottom: 5px;
  flex-basis: 40%;
  }
}
