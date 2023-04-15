<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Kavya Corporate</title>
    <!-- Css File Link -->
    <link rel="stylesheet" href="New folder (3)/style.css" />
    <!-- Font Awesome Link -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css"
      integrity="sha512-xh6O/CkQoPOWDdYTDqeRdPCVd1SpvCA9XXcUnZS2FmJNp1coAFzvtCN9BmamE+4aHK8yyUHUSCcJHgXloTyT2A=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"/>
  </head>
  <body>
    <!-- Start Header -->
    <header>
      <div id="menu-bar" class="fa-solid fa-bars"></div>
      <a href="https://www.google.com/maps/place/Kavya+Corporate/@21.2286407,72.8976496,15z/data=!4m6!3m5!1s0x3be04f6015cd43a9:0x8e4a3824004212dc!8m2!3d21.2286407!4d72.8976496!16s%2Fg%2F11gffhtnrn" class="header__logo">
        <img src="New folder (3)\images\logo.png" width="250" height="50" alt=""/>
      </a>
      <nav class="navbar">
        <div class="navbar__links">
          <a href="#">Home</a>
          <a href="New folder (3)\About Us.html">About us</a>
          <a href="https://documentcloud.wondershare.com/clientShare/review/bpcFVoayn8Msp0rtjRcN4WokAUXRE-2NX4QiyyHuH4ZA43ovnMdl2Qh6BInvqmV1CNclYhneKk8Q0UYuSMFQEg">Contact</a>
          <a href="https://documentcloud.wondershare.com/clientShare/review/bpcFVoayn8Msp0rtjRcN4bptw_kOGuIIXBcI0nJqNZsX4Ok14K89PRSwYLvsHu2A7_yXFN01NbTfwVNejfiwug">For More Information</a>
        </div>
      </nav>
      
      <form action="" class="search-bar-container">
        <input type="search" id="search-bar" placeholder="Search here ..." />
        <img src="images/search-icon-search.svg" alt="" />
      </form>
    </header>
    <!-- End Header -->
    <!-- Start Login Form Container -->
    <div class="login-form-container container">
      <i class="fa-solid fa-xmark" id="form-close"> </i>
      <form action="" id="form">
        <h3>LOGIN</h3>
        <input type="email" class="box" placeholder="enter your email" />
        <input type="password" class="box" placeholder="enter your password" />
        <input type="submit" class="btn" value="login now" />
        <input type="checkbox" id="remember" />
        <label for="remember">Remember Me</label>
        <p>Forget Password? <a href="#">Click Here</a></p>
        <p>Don't Have An Account <a href="#">Register Now</a></p>
      </form>
    </div>
    <!-- End Login Form Container -->
    <!-- Start Home Section -->
    <section class="home container" id="home">
      <div class="home__content">
        <h1 class="home__title">
          Kavya Corporate

        </h1>
        <p class="home__text">Simplified Accounting Solution</p>
        <a href="https://documentcloud.wondershare.com/clientShare/review/bpcFVoayn8Msp0rtjRcN4WokAUXRE-2NX4QiyyHuH4ZA43ovnMdl2Qh6BInvqmV1CNclYhneKk8Q0UYuSMFQEg" class="btn">Contact me</a>
      </div>
      <div class="home__controls">
        <svg
          class="prev"
          data-id="video"
          xmlns="http://www.w3.org/2000/svg"
          width="86.742"
          height="73.216"
          viewBox="0 0 86.742 73.216"
        >
          <path
            d="M22.897 73.216L0 48.158 44.032 0v6.983L27.159 25.498l17.248 18.94L84.897 0v6.985L68.533 24.942l18.209 19.961v7.01L65.35 28.435 47.593 47.931l16.681 18.304v6.981l-40.299-44.22L6.468 48.207l16.429 18.028z"
          ></path>
        </svg>
        <div class="big-text">GST, Income Tax & Accounting</div>
        <svg
          class="next"
          data-id="video"
          xmlns="http://www.w3.org/2000/svg"
          width="86.742"
          height="73.216"
          viewBox="0 0 86.742 73.216"
        >
          <path
            d="M63.845 73.216l22.897-25.058L42.71 0v6.983l16.873 18.515-17.248 18.94L1.845 0v6.985l16.364 17.957L0 44.903v7.01l21.392-23.478 17.757 19.496-16.681 18.304v6.981l40.299-44.22 17.507 19.211-16.429 18.028z"
          ></path>
        </svg>
      </div>
      <div class="home__videos">
        <video
          src="pexels-olia-danilevich-5466767-1920x1080-25fps.mp4"
          class="video live"
          id="video1"
          autoplay
          muted
        ></video>
        <video
          src="New folder (3)\images\pexels-tima-miroshnichenko-6693625-3840x2160-25fps.mp4"
          class="video"
          id="video2"
          autoplay
          muted
        ></video>
        <video
          src="New folder (3)\images\pexels-kampus-production-8348732-3840x2160-25fps.mp4"
          class="video"
          id="video3"
          autoplay
          muted
        ></video>
        <video
          src="New folder (3)\images\pexels-monstera-7429357-4096x2160-30fps.mp4"
          class="video"
          id="video4"
          autoplay
          muted
        ></video>
        <video
          src="New folder (3)\images\pexels-tima-miroshnichenko-7579657-4096x2160-25fps.mp4"
          class="video"
          id="video5"
          autoplay
          muted
        ></video>
      </div>
    </section>

    <!-- End Home Section -->

    <!-- Js File Link -->
    <script src="New folder (3)/main.js"></script>
  </body>
</html>
<!-- <svg
xmlns="http://www.w3.org/2000/svg"
width="86.742"
height="73.216"
viewBox="0 0 86.742 73.216"
>
<path
  d="M22.897 73.216L0 48.158 44.032 0v6.983L27.159 25.498l17.248 18.94L84.897 0v6.985L68.533 24.942l18.209 19.961v7.01L65.35 28.435 47.593 47.931l16.681 18.304v6.981l-40.299-44.22L6.468 48.207l16.429 18.028z"
></path>
</svg>
<svg
xmlns="http://www.w3.org/2000/svg"
width="86.742"
height="73.216"
viewBox="0 0 86.742 73.216"
>
<path
  d="M63.845 73.216l22.897-25.058L42.71 0v6.983l16.873 18.515-17.248 18.94L1.845 0v6.985l16.364 17.957L0 44.903v7.01l21.392-23.478 17.757 19.496-16.681 18.304v6.981l40.299-44.22 17.507 19.211-16.429 18.028z"
></path>
</svg> -->
