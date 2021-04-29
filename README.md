<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="Style.css">
    <!-- font awesome -->
    <link rel="stylesheet" type="text/css" href="css/font-awesome.css">
    <title>PERSONAL PORTFOLIO</title>
    <style>
        /*----------
fonts
........*/
        @import url('https://fonts.googleapis.com/css2?family=Raleway:wght@700&display=swap');


        /* css variables */
        @import url(partials/variables.css);



        /* start navigation */

        .header_area .main-menu .navbar .navbar-brand {
            padding: 0 2rem 0 5rem;
            color: black;
        }

        .header_area .main-menu .navbar {
            padding: 1rem 1rem;
        }

        .header_area .main-menu .nav-item .nav-link {
            color: black;
        }

        .header_area .main-menu .navbar-nav a:hover {
            color: #9400D3;
        }

        /* End navigation */

        /* Banner area */



        /* End curser */

        /* .site-main .site-banner{
    background: url(./img/background.jpg) no-repeat 0% 50%;
} */

        /* Button */
        :root {
            --skin-color: #fb839e;
            --bg-block-900: #000000;
            --bg-block-100: #dddddd;
            --bg-block-50: #eff0f4;
            --text-block-900: #000000;
            --text-block-700: #555555;
            --text-block-600: #666666;
            --text-block-300: #bbbbbb;
            --outer-shadow: 3px 3px 3px #d0d0d0, -3px -3px 3px #f8f8f8;
            --outer-shadow-0: 0 0 0 #d0d0d0, 0 0 0 #f8f8f8;
            --inner-shadow: inset 3px 3px 3px #d0d0d0, inset -3px -3px 3px #f8f8f8;
            --primary-color: #4458dc;
            --box-shadow: 0px 10px 30px rgbs(57, 56, 61, 0.0.205);
        }

        .btn-1 {
            padding: 9px 20px;
            font-size: 15px;
            font-weight: 600;
            /* color: var(--skin-color); */
            background-color: transparent;
            line-height: 1.5;
            cursor: pointer;
            border-radius: 30px;
            transition: all 0.3% ease;
            display: inline-block;
            color: #9400D3;
        }

        .btn-1:after {
            border-radius: 30px;
        }

        .outer-shadow {
            box-shadow: var(--outer-shadow);
        }

        .hover-in-shadow {
            position: relative;
            z-index: 1;
        }

        .hover-in-shadow:hover {
            box-shadow: var(--outer-shadow-0);
        }

        .hover-in-shadow:after {
            content: '';
            position: absolute;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            transform: all 0.3s ease;
        }

        .hover-in-shadow:hover:after {
            box-shadow: var(--inner-shadow);
        }

        /* END Button  */


        /* Abuut section */
        .site-main .about-area {
            padding: 8rem 5rem;
        }

        .site-main .about-area .about-title .paragraph>p {
            padding: 0.5rem 0;
        }

        p.para {
            color: var(--text-block-600);
        }

        /* End Abuut section */


        /* Skills Section */
        .site-main .skills-area {
            padding: 8rem 5rem;
        }

        /* End Skills Section */
    </style>
    <!-- Boostrap css file -->
    <link rel="stylesheet" href="css/bootstrap.min.css">

    <!-- font Awsome Icons -->
    <link rel="stylesheet" href="css/font-awesome.css">
</head>

<body>
    <!--=====================================================  Start header Area ===================================================== -->
    <header class="header_area">
        <div class="main-menu">
            <nav class="navbar navbar-expand-lg navbar-light mb-5">
                <div class="container-fluid">
                    <a class="navbar-brand" href="#">DINAKAR BIJILI</a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarNav">
                        <div class="navbar-nav me-auto mb-2 mb-lg-0"></div>
                        <ul class="navbar-nav">
                            <li class="nav-item">
                                <a class="nav-link active" style="color:#9400D3" aria-current="page" href="#">HOME</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">ABOUT</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">PROJECTS</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">PORTFOLIO</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">BLOG</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">CONTACT</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </nav>
        </div>
    </header>

    <!--=============================================== End header Area =============================================== -->

    <!--=============================================== Start Main Area =============================================== -->
    <main class="site-main">


        <!--============================================ Start Banner Area ============================================ -->
        <section class="site-banner">
            <div class="container">
                <div class="row">
                    <div class="col-lg-6 col-md-12 site-title">
                        <h3 class="title-text">Hey</h3>
                        <h1 class="title-text " style="font-size: 60px;">I am Dinakar <spap>_</span></h1>
                        <h4 class="title-text">Python Developer </h1>
                            <div class="site-buttons">
                                <div class="d-flex flex-row flex-wrap">
                                    <button type="button" class="btn-1 outer-shadow hover-in-shadow my-2 ">HIRE
                                        ME</button>
                                    <button type="button" class="btn-1 outer-shadow hover-in-shadow my-2 mx-2">GET
                                        CV</button>
                                    </button>
                                    <div class="col-lg-6 col-md-12">
                                    </div>
                                </div>
                            </div>
                    </div>
                    <div class="col-lg-6 col-md-12 banner-image">
                        <img src="./img/working.jpg" alt="" class="img-fluid">
                    </div>
                </div>
            </div>
        </section>


        <!--============================= End Banner Area ============================= -->
        <!-- ============================ About Area ==================================-->
        <div class="about-area">
            <div class="container-fluid">
                <div class="row">
                    <div class="col-lg-6 col-md-12 ">
                        <div class="about-image">
                            <img src="./img/banner.jpg" alt="About us" class="img-fluid">
                        </div>
                    </div>
                    <div class="col-lg-6 col-md-12 about-title">
                        <h2 class="pt-5">
                            <span>LET ME</span>
                            <span>INTRODUCE</span>
                            <span>MYSELF</span>
                        </h2>
                        <div class="paragraph py-4 w-75">
                            <p class="para">
                                Aspire to work in a dynamic organization where I would get an opportunity to take up
                                challenges and prove my skills that leads to the development of both the organization as
                                well as a person.

                            </p>
                            <p class="para">
                                Aspire to work in a dynamic organization where I would get an opportunity to take up
                                challenges and prove my skills that leads to the development of both the organization as
                                well as a person.
                            </p>
                            <button type="button" class="btn-1 outer-shadow hover-in-shadow my-2">Download CV</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- ============================ End About Area ==================================-->

        <!-- ============================  Skills Area ==================================-->
        <section class="skills-area ">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12 text-center skills-title">
                        <h1 class="title-text">Skills</h1>
                        <p class="para">
                            para
                        </p>
                    </div>
                </div>
                <div class="container services-list">
                    <div class="row">
                        <div class="col-lg-3 col-md-6 col-sm-12">
                            <div class="skills">
                                <div class="skills-img text-center py-4">
                                    <img src="./img/programming.png" alt="" class="img-fluid">

                                </div>
                                <div class="card-body text-center">
                                    <h5 class="card-title">Programming Languages</h5>
                                    <strong class="card-text text-secondary">
                                        Python
                                    </strong>

                                </div>
                            </div>

                        </div>
                        <div class="col-lg-3 col-md-6 col-sm-12">
                            <div class="skills">
                                <div class="skills-img text-center py-4">
                                    <img src="./img/data-complexity.png" alt="" class="img-fluid">

                                </div>
                                <div class="card-body text-center">
                                    <h5 class="card-title"> Frameworks</h5>
                                    <strong class="card-text text-secondary">
                                        Python
                                    </strong>

                                </div>
                            </div>

                        </div>
                        <div class="col-lg-3 col-md-6 col-sm-12">
                            <div class="skills">
                                <div class="skills-img text-center py-4">
                                    <img src="./img/settings.png" alt="" class="img-fluid">

                                </div>
                                <div class="card-body text-center">
                                    <h5 class="card-title">Tools</h5>
                                    <strong class="card-text text-secondary">
                                        Python
                                    </strong>

                                </div>
                            </div>

                        </div>
                    </div>

                </div>
            </div>
        </section>
        <!-- ============================ End Skills Area ==================================-->

        <!-- ============================ End Project Area ==================================-->
        <section class="project-area">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12 text-center skills-title">
                        <h1 class="title-text">NOTEWORTHY PROJECTS</h1>
                        <span> _ _ _ _ _ _ ____________/\________ _ _ _ _ _ _ _ __</span>
                    </div>
                </div>
                <div class="row row-cols-1 row-cols-md-3 g-4 my-4">
                    <div class="col">
                        <div class="card text-white bg-dark">
                            <img src="./img/AI.jpg" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title">Python-Virtual-Assistant</h5>
                                <p class="card-text">• A virtual assistant capable of conversation, following basic
                                    commands and used to automate your tasks.</p>
                                <a href="https://github.com/DinakarBijili/Jarvis-Virtual-Assistant"
                                    class="btn btn-primary">Link</a>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card text-white bg-dark">
                            <img src="./img/Flappy bird.png" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title">Flappy Bird</h5>
                                <p class="card-text">This is a longer card with supporting text below as a natural
                                    lead-in to additional content. This content is a little bit longer.</p>
                                <a href="https://github.com/DinakarBijili/Flappybird-by-Dinakar"
                                    class="btn btn-primary">Link</a>
                            </div>
                        </div>
                    </div>
                    <div class="col text-white bg-dark">
                        <div class="card">
                            <img src="..." class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title">Card title</h5>
                                <p class="card-text">This is a longer card with supporting text below as a natural
                                    lead-in to additional content.</p>
                                <a href="#" class="btn btn-primary">Link</a>
                            </div>
                        </div>
                    </div>
                    <div class="col text-white bg-dark">
                        <div class="card">
                            <img src="..." class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title">Card title</h5>
                                <p class="card-text">This is a longer card with supporting text below as a natural
                                    lead-in to additional content. This content is a little bit longer.</p>
                                <a href="#" class="btn btn-primary">Link</a>
                            </div>
                        </div>
                    </div>
                </div>
        </section>
        <!-- ============================ End Project Area ==================================-->

        <!-- ============================ PROJECT AREA ==================================-->

        <!-- ============================ END PROJECT AREA ==================================-->

    </main>
    <!--================================= End Main Area ================================= -->

    <!-- Jquery js file -->
    <script src="js/jquery3.6.0.js"></script>
    <!-- Boostrap js file -->
    <script src="js/bootstrap.min.js"></script>
</body>

</html>
