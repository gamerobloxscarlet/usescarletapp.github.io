<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Server</title>

  <!-- 
    - favicon
  -->
  <link rel="shortcut icon" href="./favicon.svg" type="image/svg+xml">

  <!-- 
    - custom css link
  -->
  <link rel="stylesheet" href="./assets/css/style.css">


  <!-- 
    - google font link
  -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=League+Spartan:wght@400;500;600;700;900&display=swap"
    rel="stylesheet">

  <!-- 
    - preload image
  -->
  <link rel="preload" as="image" href="./assets/images/hero-banner.png">
</head>

<body id="top">

  <!-- 
    - #HEADER
  -->

  <header class="header" data-header>
    <div class="container">

      <h1>
        <a href="#" class="logo">Your Server</a>
      </h1>

      <nav class="navbar container" data-navbar>
        <ul class="navbar-list">

          <li class="navbar-item">
            <a href="#home" class="navbar-link" data-nav-link>Home</a>
          </li>

          <li class="navbar-item">
            <a href="#services" class="navbar-link" data-nav-link>Services</a>
          </li>

          <li class="navbar-item">
            <a href="#features" class="navbar-link" data-nav-link>Features</a>
          </li>

          <li class="navbar-item">
            <a href="#about" class="navbar-link" data-nav-link>About</a>
          </li>

          <li class="navbar-item">
            <a href="#stats" class="navbar-link" data-nav-link>Stats</a>
          </li>

          <li class="navbar-item">
            <a href="#contact" class="navbar-link" data-nav-link>Contact Us</a>
          </li>

        </ul>
      </nav>
<form action="/discord">
      <button class="btn btn-secondary">Join</button>
</form>
      <button class="nav-toggle-btn" aria-label="Toggle menu" data-nav-toggle-btn>
        <ion-icon name="menu-outline" class="menu-icon"></ion-icon>
        <ion-icon name="close-outline" class="close-icon"></ion-icon>
      </button>

    </div>
  </header>





  <main>
    <article>

      <!-- 
        - #HERO
      -->

      <section class="section hero" id="home">
        <div class="container">

          <figure class="hero-banner">
            <img src="./assets/images/logo.png"  loading="lazy" alt="hero banner"
              class="w-100">
          </figure>

          <div class="hero-content">

            <h2 class="h1 hero-title">Your Server Community</h2>

            <p class="section-text">
              A community of developers and students where you can interact and make the team. Explore the science-tech related projects and works.
            </p>
<br>
<!--             <form action="/discord" class="hero-form">
          
              <button type="submit" class="btn btn-primary">Join Now</button>
            </form> -->

            <ul class="hero-list">

              <li class="hero-item">
                <img src="./assets/images/check-circle.svg" width="16" height="16" loading="lazy" alt="Checkmark icon">

                <span class="span">Active Chat</span>
              </li>

              <li class="hero-item">
                <img src="./assets/images/check-circle.svg" width="16" height="16" loading="lazy" alt="Checkmark icon">

                <span class="span">Ticketing</span>
              </li>

              <li class="hero-item">
                <img src="./assets/images/check-circle.svg" width="16" height="16" loading="lazy" alt="Checkmark icon">

                <span class="span">Funny Bots</span>
              </li>

              <li class="hero-item">
                <img src="./assets/images/check-circle.svg" width="16" height="16" loading="lazy" alt="Checkmark icon">

                <span class="span">Advertisement</span>
              </li>

              <li class="hero-item">
                <img src="./assets/images/check-circle.svg" width="16" height="16" loading="lazy" alt="Checkmark icon">

                <span class="span">Giveaways</span>
              </li>

            </ul>

          </div>

        </div>
      </section>





      <!-- 
        - #SERVICE
      -->

      <section class="section service" id="services">
        <div class="container">

          <h2 class="h2 section-title">Services</h2>

          <p class="section-text">
           We provide you different services to you like
          </p>

          <ul class="service-list">

            <li>
              <div class="service-card">

                <figure class="card-banner">
                  <img src="./assets/images/service-1.gif" width="728" height="344" loading="lazy" alt="support"
                    class="w-100">
                </figure>

                <div class="card-content">

                  <h3 class="h3">
                    <a href="#" class="card-title">Support</a>
                  </h3>

                  <p class="card-text">
                    We give 24/7 active support to you. You may ask any kind of help realted codings or any others. You can  also report members.
                  </p>

<!--                   <a href="#" class="btn-link">
                    <span class="span">Learn More</span>

                    <ion-icon name="arrow-forward" aria-hidden="true"></ion-icon>
                  </a> -->

                </div>

              </div>
            </li>

            <li>
              <div class="service-card">

                <figure class="card-banner">
                  <img src="./assets/images/service-2.gif" width="728" height="344" loading="lazy" alt="Engagement"
                    class="w-100">
                </figure>

                <div class="card-content">

                  <h3 class="h3">
                    <a href="#" class="card-title">Engagement</a>
                  </h3>

                  <p class="card-text">
                   We have active chats & you can enjoy chating with our members. You can make friends and work together.
                  </p>

<!--                   <a href="#" class="btn-link">
                    <span class="span">Learn More</span>

                    <ion-icon name="arrow-forward" aria-hidden="true"></ion-icon>
                  </a> -->

                </div>

              </div>
            </li>

            <li>
              <div class="service-card">

                <figure class="card-banner">
                  <img src="./assets/images/service-3.gif" width="728" height="344" loading="lazy" alt="Marketing"
                    class="w-100">
                </figure>

                <div class="card-content">

                  <h3 class="h3">
                    <a href="#" class="card-title">Games & Events</a>
                  </h3>

                  <p class="card-text">
                    We organize differents events in stage channel. Also, we play many games together with our members. Winner will get awesome gift.
                  </p>

<!--                   <a href="#" class="btn-link">
                    <span class="span">Learn More</span>

                    <ion-icon name="arrow-forward" aria-hidden="true"></ion-icon>
                  </a> -->

                </div>

              </div>
            </li>

          </ul>

        </div>
      </section>





      <!-- 
        - #FEATURES
      -->

      <section class="section features" id="features">
        <div class="container">

          <div class="features-content">

            <h2 class="h2 section-title">Our Awesome Features To Serve You</h2>

            <p class="section-text">
              We make it easiest for you
              through the different facilities 
            </p>

            <ul class="features-list">

              <li class="features-item">
                <img src="./assets/images/features-icon-1.svg" width="26" height="26" loading="lazy" aria-hidden="true"
                  class="item-icon">

                <h3 class="item-title">Promote your social account</h3>
              </li>

              <li class="features-item">
                <img src="./assets/images/features-icon-2.svg" width="26" height="26" loading="lazy" aria-hidden="true"
                  class="item-icon">

                <h3 class="item-title">Accept your suggestions</h3>
              </li>

              <li class="features-item">
                <img src="./assets/images/features-icon-3.svg" width="26" height="26" loading="lazy" aria-hidden="true"
                  class="item-icon">

                <h3 class="item-title">Provide you free gifts</h3>
              </li>

              <li class="features-item">
                <img src="./assets/images/features-icon-4.svg" width="26" height="26" loading="lazy" aria-hidden="true"
                  class="item-icon">

                <h3 class="item-title">Open Source Code</h3>
              </li>

            </ul>

          </div>

          <div class="banner-wrapper">

            <figure class="features-banner one">
              <img src="./assets/images/dc.svg" width="600" height="500" loading="lazy"
                alt="features image" class="w-100">
            </figure>

            <figure class="features-banner two">
              <img src="./assets/images/dc-2.svg" width="436" height="311" loading="lazy"
                alt="features image" class="w-100">
            </figure>

          </div>

        </div>
      </section>





      <!-- 
        - #ABOUT
      -->

      <section class="section about" id="about">
        <div class="container">

          <h2 class="h2 section-title">What We Do</h2>

          <p class="section-text">
           Many peoples are bored staying home and doing nothing. Our goal is to create an interactive community where you can create and build ideas in the science and technology sectors. 
          </p>

          <ul class="about-list">

            <li>
              <div class="about-card about-card-1">

                <figure class="card-banner">
                  <img src="./assets/images/about-img-1.svg" width="94" height="94" loading="lazy"
                    alt="Automated Ticket Routing">
                </figure>

                <div class="card-content">

                  <h3 class="h3">
                    <a href="#" class="card-title">Ticket System</a>
                  </h3>

                  <p class="card-text">
                    We accept all the ticket you have opened and review it.
                  </p>

<!--                   <a href="#" class="btn-link">
                    <span class="span">Learn More</span>

                    <ion-icon name="arrow-forward" aria-hidden="true"></ion-icon>
                  </a> -->

                </div>

              </div>
            </li>

            <li>
              <div class="about-card about-card-2">

                <figure class="card-banner">
                  <img src="./assets/images/about-img-2.svg" width="94" height="94" loading="lazy"
                    alt="Workflow Automation">
                </figure>

                <div class="card-content">

                  <h3 class="h3">
                    <a href="#" class="card-title">Workflow</a>
                  </h3>

                  <p class="card-text">
                  We will help you to complete your project and solve your errors.
                  </p>

<!--                   <a href="#" class="btn-link">
                    <span class="span">Learn More</span>

                    <ion-icon name="arrow-forward" aria-hidden="true"></ion-icon>
                  </a> -->

                </div>

              </div>
            </li>

            <li>
              <div class="about-card about-card-3">

                <figure class="card-banner">
                  <img src="./assets/images/about-img-3.svg" width="94" height="94" loading="lazy"
                    alt="Automated Callback">
                </figure>

                <div class="card-content">

                  <h3 class="h3">
                    <a href="#" class="card-title">Youtube Video</a>
                  </h3>

                  <p class="card-text">
                    We will make installization tutorial of open source code. 
                  </p>

<!--                   <a href="#" class="btn-link">
                    <span class="span">Learn More</span>

                    <ion-icon name="arrow-forward" aria-hidden="true"></ion-icon>
                  </a> -->

                </div>

              </div>
            </li>

            <li>
              <div class="about-card about-card-4">

                <figure class="card-banner">
                  <img src="./assets/images/about-img-4.svg" width="94" height="94" loading="lazy"
                    alt="Customer Feedback Surveys">
                </figure>

                <div class="card-content">

                  <h3 class="h3">
                    <a href="#" class="card-title">Customer Feedback Surveys</a>
                  </h3>

                  <p class="card-text">
                    We will review and make our community better by seeing feedback
                  </p>

<!--                   <a href="#" class="btn-link">
                    <span class="span">Learn More</span>

                    <ion-icon name="arrow-forward" aria-hidden="true"></ion-icon>
                  </a> -->

                </div>

              </div>
            </li>

          </ul>

          <p class="section-text">
            We do lots of new things make sure to
            <a href="/discord" class="btn-link">
              <span class="span">join our server</span>

              <ion-icon name="arrow-forward" aria-hidden="true"></ion-icon>
            </a>
          </p>

        </div>
      </section>





      <!-- 
        - #STATS
      -->

      <section class="section stats" id="stats">
        <div class="container">

          <figure class="stats-banner">
            <img src="./assets/images/stats-banner.png" width="619" height="482" loading="lazy" alt="stats"
              class="w-100">
          </figure>

          <ul class="stats-list">

            <li class="stats-item purple">
              <h3 class="item-title">
                2000
                <span class="span">members</span>
              </h3>

              <p class="stats-text">Active Members</p>
            </li>

            <li class="stats-item red">
              <h3 class="item-title">
                3060
                <span class="span">members</span>
              </h3>

              <p class="stats-text">Total member of our server</p>
            </li>

            <li class="stats-item green">
              <h3 class="item-title">
                20+
                <span class="span">channels</span>
              </h3>

              <p class="stats-text">Text & Voice Chat</p>
            </li>

            <li class="stats-item yellow">
              <h3 class="item-title">
                50+
                <span class="span">roles</span>
              </h3>

              <p class="stats-text">with colors</p>
            </li>

          </ul>

        </div>
      </section>









      <!-- 
        - #SUPPORT
      -->

      <section class="section support" id="contact">
        <div class="container">

          <div class="support-content">
            <h2 class="h2 section-title">24/7 Customer Support</h2>

            <p class="section-text">
              Our team is here to provide you with personalized and outstanding service. We also offer a range of
              self-learning tools
              in our support center:
            </p>
          </div>

          <a href="/discord" class="btn btn-primary">Join Us</a>

        </div>
      </section>

    </article>
  </main>





  <!-- 
    - #FOOTER
  -->

  <footer class="footer">

    

    <div class="footer-bottom">
      <div class="container">

        <p class="copyright">
          &copy; 2022 <span class="span">Your Server</span>. All rights reserved by <a href="#"
            class="copyright-link">Your Server</a>
        </p>

        <ul class="footer-bottom-list">

          <li>
            <a href="#" class="footer-bottom-link">Privacy Policy</a>
          </li>

          <li>
            <a href="#" class="footer-bottom-link">Security</a>
          </li>

          <li>
            <a href="#" class="footer-bottom-link">Terms & Conditions</a>
          </li>

        </ul>

      </div>
    </div>

  </footer>





  <!-- 
    - #BACK TO TOP
  -->

  <a href="#top" class="back-top-btn" aria-label="Back to top" data-back-top-btn>
    <ion-icon name="chevron-up"></ion-icon>
  </a>





  <!-- 
    - custom js link
  -->
  <script src="./assets/js/script.js" defer></script>

  <!-- 
    - ionicon link
  -->
  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>

</body>

</html>
