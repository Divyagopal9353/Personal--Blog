# Personal--Blog html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>responsive personal portfolio website design tutorail</title>

    <!-- font awesome cdn link  -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css">

    <!-- custom css file link  -->
    <link rel="stylesheet" href="styles.css">

</head>
<body>
    
<!-- header section starts  -->

<header>
    <div class="user img">
        <img src="https://pbs.twimg.com/profile_images/1390657670974033923/BqdrIykR.jpg" alt="">
    </div>
    <div class="user">
        <h3 class="name">Dudekula Dastagiri</h3>
        <p class="post">Engineering student</p>
    </div>

    <nav class="navbar">
        <ul>
            <li><a href="#home">home</a></li>
            <li><a href="#about">about</a></li>
            <li><a href="#education">education</a></li>
            <li><a href="#contact">contact</a></li>
        </ul>
    </nav>

</header>

<!-- header section ends -->

<div id="menu" class="fas fa-bars"></div>

<!-- home section starts  -->

<section class="home" id="home">

    <h3>HI THERE !</h3>
    <h1>I'M <span>D.dastagiri</span></h1>
    </p>
    <a href="#about"><button class="btn">about me <i class="fas fa-user"></i></button></a>

</section>

<!-- home section ends -->

<!-- about section starts  -->

<section class="about" id="about">

<h1 class="heading"> <span>about</span> me </h1>

<div class="row">

    <div class="info">
        <h3> <span> name : </span> Dudekula Dastagiri </h3>
        <h3> <span> age : </span> 21 </h3>
        <h3> <span> qualification : </span> B.tech </h3>
        <h3> <span> language : </span> telugu </h3>
        <a href="#"><button class="btn"> download CV <i class="fas fa-download"></i> </button></a>
    </div>

    <div class="counter">

        <div class="box">
            <span>70%</span>
            <h3>In B.tech</h3>
        </div>

        <div class="box">
            <span>95%</span>
            <h3>In class 12 </h3>
        </div>

        <div class="box">
            <span>85%</span>
            <h3>In class 10</h3>
        </div>

        <div class="box">
            <span>great</span>
            <h3>Learner</h3>
        </div>

    </div>

</div>

</section>

<!-- about section ends -->

<!-- education section starts  -->

<section class="education" id="education">

<h1 class="heading"> my <span>education</span> </h1>

<div class="box-container">

    <div class="box">
        <i class="fas fa-graduation-cap"></i>
        <span>2K16-17</span>
        <h3>class 10</h3>
        <p> Azim's Brillient High School</p>
    </div>

    <div class="box">
        <i class="fas fa-graduation-cap"></i>
        <span>2K17-19</span>
        <h3>class 12</h3>
        <p>Narayana Juniour Collage</p>
    </div>

    <div class="box">
        <i class="fas fa-graduation-cap"></i>
        <span>2K19-23</span>
        <h3>B.tech</h3>
        <p>Cambridge Institute Of Technology</p>
    </div>

</div>

</section>

<!-- education section ends -->

<!-- contact section starts  -->

<section class="contact" id="contact">

<h1 class="heading"> <span>contact</span> me </h1>

<div class="row">

    <div class="content">

        <h3 class="title">contact info</h3>

        <div class="info">
            <h3> <i class="fas fa-envelope"></i> dudekuladastagiri3711@gmail.com</h3>
            <h3> <i class="fas fa-phone"></i> +91 6305581836</h3>
            <h3> <i class="fas fa-phone"></i> +91 8660956863 </h3>
            <h3> <i class="fas fa-map-marker-alt"></i> kurnool,AP ,562157  </h3>
        </div>

    </div>

    <form action="">

        <input type="text" placeholder="name" class="box">
        <input type="email" placeholder="email" class="box">
        <input type="text" placeholder="project" class="box">
        <textarea name="" id="" cols="30" rows="10" class="box message" placeholder="message"></textarea>
        <button type="submit" class="btn"> send <i class="fas fa-paper-plane"></i> </button>

    </form>

</div>

</section>

<!-- contact section ends -->


<!-- scroll top button  -->

<a href="#home" class="top">
    <img src="images/scroll-top-img.png" alt="">
</a>


</body>
</html>
