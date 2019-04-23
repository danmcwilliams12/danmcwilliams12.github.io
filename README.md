<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

    <!-- Font Awesome-->
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous">

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css?family=Lalezar" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Faster+One" rel="stylesheet">

    <!-- Custom CSS -->
    <link rel="stylesheet" href="./css/portfolio_style.css">

    <title>Dan McWilliams</title>
  </head>
  <body>
    <!-- Navbar (Include Name) -->
    <nav class="invisible navbar fixed-top navbar-expand-lg navbar-light bg-light">
      <a class="visible navbar-brand" href="#">Dan McWilliams</a>
      <button class="visible navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="visible navbar-toggler-icon"></span>
      </button>
      <div class="visible collapse navbar-collapse font-weight-bolder" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item active">
            <a class="nav-link" href="#home">Home<span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#skills">Skills</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#portfolio">Portfolio</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </nav>


    <!-- Home -->

    <section id="home">
      <div class="container">
        <Header class="text_center">
          <span class="home_main">Code. Create. Communicate.</span>
        </Header>
      </div>
    </section>

    <!-- About -->

    <section id="about">
      <div class="section_head_container center">
        <div class="text_center">
          <H1 class="about_head">About Dan</H1>
        </div>
      </div>
      <br>
      <div class="container">
        <div class="text_left">
          <p class="summary">From a very early age,&nbsp; I have been facinated with games,&nbsp; puzzles and problem solving.&nbsp; 
            I have a deep interest in working with systems and figuring out how they function.&nbsp; 
            I appreciate that software development requires a great amount of perserverance,&nbsp; attention to detail and mental energy,&nbsp; 
            but I believe that I am more than fit for the task.  My greatest strength lies in a devotion to daily incremental improvement.&nbsp; 
            Rome was not buit in a day,&nbsp; neither will my skillset,&nbsp; nor a robust software application.&nbsp; I look forward to the prospect of working 
            with you and your company in the future.&nbsp;  Please check out my skills and projects below!
          </p>
        </div>
      </div>
    </section>

    <!-- Technical Skills -->

    <section id="skills">
      <div class="section_head_container center text-center">
        <H1 class="skills_head">Skills</H1>
      </div>
      <h2 class="skill_type_head text-center">Web Development</h2>
      <div class="skills_container">
       <div class="icon-container">
        <i class="fab fa-html5"></i>
        <br><br><br><br><br><br><br>
        <h4 class="icon-text text-center">HTML5</h4>
        <p class="text-center">Bootstrap 4</p>
       </div>
       <div class="icon-container">
        <i class="fab fa-css3-alt"></i>
        <br><br><br><br><br><br><br>
        <h4 class="icon-text text-center">CSS3</h4>
       </div>
       <div class="icon-container">
        <i class="fab fa-js-square"></i>
        <br><br><br><br><br><br><br>
        <h4 class="icon-text text-center">JavaScript</h4>
        <p>JQuery</p>
        <p>ReactJS</p>
       </div>
      </div>
      <br><br><br><br>
      <h2 class="skill_type_head text-center">IDEs</h2>
      <div class="skills_container">
        <div class="icon-container">
            <i class="fas fa-atom"></i>
            <br><br><br><br><br><br><br>
          <h4 class="icon-text text-center">Atom</h4>
        </div>
        <div class="icon-container">
            <i class="fas fa-code"></i>
            <br><br><br><br><br><br><br>
          <h4 class="icon-text text-center">Visual Studio<br>Code</h4>
        </div>
      </div>
      <br><br><br><br>

    </section>

    <!-- Portfolio -->

    <section id="portfolio">
      <Header class="section_head_container center text-center">
        <H1 class="portfolio_head">Portfolio</H1>
      </Header>
      <div class="project_container">
        <div class="card text-center" style="width: 18rem;">
          <img src="./img/personal_webpage.jpg" class="card-img-top" height="150" alt="...">
          <div class="card-body">
            <p class="card-text text-center">Personal Website</p>
            <a class="btn btn-outline-dark" target="_new" href="https://danmcwilliams12.github.io/" role="button">Go To Project</a>
            <button type="button" class="btn btn-outline-dark" data-toggle="modal" data-target="#detail1">Details</button>
          </div>
        </div>
        <div class="card text-center" style="width: 18rem;">
          <img src="./img/pizza_order.jpg" class="card-img-top" height="150" alt="...">
          <div class="card-body">
            <p class="card-text text-center">Pizza Receipt Generator</p>
            <a class="btn btn-outline-dark" target="_new" href="./Pizza Order/pizza_order.html" role="button">Go To Project</a>
            <button type="button" class="btn btn-outline-dark" data-toggle="modal" data-target="#detail2">Details</button>
          </div>
        </div>
      </div>
      <!-- Modal Descriptions -->
      <div class="modal" id="detail1" tabindex="-1" role="dialog">
        <div class="modal-dialog" role="document">
          <div class="modal-content">
            <div class="modal-header">
              <h5 class="modal-title">Personal Website</h5>
              <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                <span aria-hidden="true">&times;</span>
              </button>
            </div>
            <div class="modal-body">
              <p>I created this website to showcase my technical skills in front end web design.  I am constantly updating it with new content and features.  Make sure to check back regularly for new updates and additions.</p>
            </div>
            <div class="modal-footer">
              <button type="button" class="btn btn-primary" data-dismiss="modal">Close</button>
            </div>
          </div>
        </div>
      </div>
      <div class="modal" id="detail2" tabindex="-1" role="dialog">
      <div class="modal-dialog" role="document">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title">Pizza Receipt Generator</h5>
            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
              <span aria-hidden="true">&times;</span>
            </button>
          </div>
          <div class="modal-body">
            <p>This project is my first formal application of JavaScript in conjunction with HTML and CSS. The objective was to create a recipt that contained the selected items, their subtotals and a grand total.</p>
          </div>
          <div class="modal-footer">
            <button type="button" class="btn btn-primary" data-dismiss="modal">Close</button>
          </div>
        </div>
      </div>
    </div>
    </section>

    <!-- Contact -->

    <section id="contact">
        <Header class="section_head_container center text-center">
          <H1 class="contact_head">Contact</H1>
        </Header>
        <br><Br>
        <div class="container">
          <h2>Phone: (330)-209-7678</h2>
          <br><br>
          <h2>Email: daniel.mcwilliams12@yahoo.com</h2>
        </div>
        <div class="portrait_container">
            <img src="./img/self_portrait.jpg" alt="">
          </div>
      </section>
      

    <!-- Footer (with Linkedin and GitHub buttons) -->

    <section id="footer">
      <div class= "btn_container">
        <a class="btn color_linkedin" target="_new" href="https://www.linkedin.com/in/danielmcwilliams12/" role="button">Linkedin</a>
        <a class="btn color_facebook" target="_new" href="https://www.facebook.com/daniel.mcwilliams.52" role="button">Facebook</a>
        <a class="btn color_github" target="_new" href="https://github.com/danmcwilliams12" role="button">GitHub</a>
      </div>
    </section>
    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
  </body>
</html>
