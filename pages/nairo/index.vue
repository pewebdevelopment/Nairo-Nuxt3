<template>
  <div>
    <div id="loading">
      <div class="load-circle"><span class="one"></span></div>
    </div>
    <!-- End -->
    <!-- Mobile Header -->
    <div class="mobile-header flex lg:hidden">
      <!-- Logo -->
      <div class="logo">
        <a href="#"
          ><img src="../../assets/Nairo_images/logo.svg" title="" alt=""
        /></a>
      </div>
      <!-- Mobile Toggle -->
      <button class="ml-auto mobile_toggle w-[40px] flex flex-col">
        <span
          class="w-[25px] h-[2px] bg-slate-900 dark:bg-white inline-block"
        ></span>
        <span
          class="w-[25px] h-[2px] bg-slate-900 dark:bg-white inline-block my-[5px]"
        ></span>
        <span
          class="w-[25px] h-[2px] bg-slate-900 dark:bg-white inline-block"
        ></span>
      </button>
    </div>
    <!-- End Mobile Header -->
    <!-- Header -->
    <header class="main-header one-page-nav">
      <!-- Logo -->
      <div class="logo bg-theme-500">
        <a href="#"
          ><img src="../../assets/Nairo_images/logo.svg" title="" alt=""
        /></a>
      </div>
      <div class="navbar-collapse">
        <ul class="nav nav-menu">
          <li>
            <a class="nav-link active" data-scroll-nav="0" href="#home">
              <span>HOME</span>
              <i>
                <font-awesome-icon icon="fas fa-house-chimney-crack" />
              </i>
            </a>
          </li>
          <li>
            <a class="nav-link" data-scroll-nav="1" href="#about">
              <span>ABOUT</span>
              <i><font-awesome-icon icon="fa-solid fa-address-card" /></i>
            </a>
          </li>
          <li>
            <a class="nav-link" data-scroll-nav="2" href="#resume">
              <span>RESUME</span>
              <i><font-awesome-icon icon="fa-solid fa-file" /></i>
            </a>
          </li>
          <li>
            <a class="nav-link" data-scroll-nav="3" href="#work">
              <span>WORK</span>
              <i><font-awesome-icon icon="fa-solid fa-briefcase" /></i>
            </a>
          </li>
          <li>
            <a class="nav-link" data-scroll-nav="4" href="#blog">
              <span>BLOG</span>
              <i><font-awesome-icon icon="fa-solid fa-blog" /></i>
            </a>
          </li>
          <li>
            <a class="nav-link" data-scroll-nav="5" href="#contactus">
              <span>CONTACT</span>
              <i><font-awesome-icon icon="fa-solid fa-id-card-clip" /></i>
            </a>
          </li>
        </ul>
      </div>
      <!-- Theme Color Switch -->
      <div class="theme-color mt-auto">
        <button id="theme-toggle" type="button">
          <svg
            id="theme-toggle-dark-icon"
            class="hidden w-5 h-5"
            fill="currentColor"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M17.293 13.293A8 8 0 016.707 2.707a8.001 8.001 0 1010.586 10.586z"
            ></path>
          </svg>
          <svg
            id="theme-toggle-light-icon"
            class="hidden w-5 h-5"
            fill="currentColor"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M10 2a1 1 0 011 1v1a1 1 0 11-2 0V3a1 1 0 011-1zm4 8a4 4 0 11-8 0 4 4 0 018 0zm-.464 4.95l.707.707a1 1 0 001.414-1.414l-.707-.707a1 1 0 00-1.414 1.414zm2.12-10.607a1 1 0 010 1.414l-.706.707a1 1 0 11-1.414-1.414l.707-.707a1 1 0 011.414 0zM17 11a1 1 0 100-2h-1a1 1 0 100 2h1zm-7 4a1 1 0 011 1v1a1 1 0 11-2 0v-1a1 1 0 011-1zM5.05 6.464A1 1 0 106.465 5.05l-.708-.707a1 1 0 00-1.414 1.414l.707.707zm1.414 8.486l-.707.707a1 1 0 01-1.414-1.414l.707-.707a1 1 0 011.414 1.414zM4 11a1 1 0 100-2H3a1 1 0 000 2h1z"
              fill-rule="evenodd"
              clip-rule="evenodd"
            ></path>
          </svg>
        </button>
      </div>
    </header>
    <!-- End Header -->
    <!-- Main -->
    <main class="wrapper main-left">
      <!-- Section -->
      <section id="home" data-scroll-index="0" class="home-banner">
        <div class="hb-top-fixed hidden lg:flex">
          <div class="hb-info">
            <label>+04 6545-9535-6515</label>
            <label>nairobi-designer@domain.com</label>
          </div>
          <div class="hb-lang">
            <ul class="flex list-none">
              <li class="active"><a href="#">EN</a></li>
              <li><a href="#">FR</a></li>
            </ul>
          </div>
        </div>
        <div class="container">
          <div class="grid grid-cols-12 min-h-screen items-center">
            <div class="col-span-12 lg:col-span-8">
              <div class="type-box">
                <h6>👋 Hello, My name is</h6>
                <h1 class="font-alt">Nairobi Gadot</h1>
                <h3>I'm a <span id="type-it"></span></h3>
                <p class="desc">
                  I design and develop services for customers of all sizes,
                  specializing in creating stylish, modern websites, web
                  services and online stores.
                </p>
                <div class="btn-bar">
                  <a class="font-alt" href="#">Donwload CV</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div>
          <img class="hb-me" src="../../assets/Nairo_images/home-banner.png" />
        </div>
      </section>
      <!-- End Section -->

      <!-- Home -->
      <section data-scroll-index="1" id="about" class="section bg-gray">
        <div class="container">
          <div class="grid grid-cols-12 gap-7 items-center justify-center">
            <div class="col-span-12 lg:col-span-4">
              <div class="about-me">
                <div class="img">
                  <div class="img-in">
                    <img
                      src="../../assets/Nairo_images/about-me.jpg"
                      title=""
                      alt=""
                    />
                  </div>
                  <div class="social-icons flex justify-center">
                    <a href="#"><i class="fab fa-facebook-f"></i></a>
                    <a href="#"><i class="fab fa-twitter"></i></a>
                    <a href="#"><i class="fab fa-instagram"></i></a>
                    <a href="#"><i class="fab fa-linkedin-in"></i></a>
                    <a href="#"><i class="fab fa-pinterest"></i></a>
                  </div>
                </div>
                <div class="info">
                  <p>Ux/Ui Designer</p>
                  <h3>Nairobi Gadot</h3>
                </div>
              </div>
            </div>
            <div class="col-span-12 lg:col-span-8">
              <div class="about-info">
                <div class="title">
                  <h3>Biography</h3>
                </div>
                <div class="about-text">
                  <p>
                    I'm a Freelancer Front-end Developer with over 3 years of
                    experience. I'm from San Francisco. I code and create web
                    elements for amazing people around the world. I like work
                    with new people. New people new Experiences.
                  </p>
                  <p>
                    I'm a Freelancer Front-end Developer with over 3 years of
                    experience. I'm from San Francisco. I code and create web
                    elements for amazing people around the world. I like work
                    with new people. New people new Experiences.
                  </p>
                </div>
                <div class="info-list">
                  <div class="grid sm:gap-7 grid-cols-12">
                    <div class="col-span-12 sm:col-span-6">
                      <ul>
                        <li>
                          <label>Name: </label>
                          <span>Nairobi Gadot</span>
                        </li>
                        <li>
                          <label>Birthday: </label>
                          <span>4th April 1994</span>
                        </li>
                        <li>
                          <label>Age: </label>
                          <span>26 years</span>
                        </li>
                        <li>
                          <label>Address: </label>
                          <span>San Francisco</span>
                        </li>
                      </ul>
                    </div>
                    <div class="col-span-12 sm:col-span-6">
                      <ul>
                        <li>
                          <label>Phone: </label>
                          <span>(+38) 469 2344 2364</span>
                        </li>
                        <li>
                          <label>Email: </label>
                          <span>info@domainname.com</span>
                        </li>
                        <li>
                          <label>Skype: </label>
                          <span>nairob.40</span>
                        </li>
                        <li>
                          <label>Freelance: </label>
                          <span>Available</span>
                        </li>
                      </ul>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- separated -->
          <div class="separated"></div>
          <!-- End separated -->
          <div class="title">
            <h3>What I do?</h3>
          </div>
          <div class="grid grid-cols-12 gap-7">
            <div class="col-span-12 lg:col-span-4">
              <div class="feature-box-01">
                <i class="icon theme-bg bi-phone"></i>
                <div class="feature-content">
                  <h5>Web Design</h5>
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit,
                    sed do eiusmod tempor incididunt ut labore et dolore magna
                    aliqua.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-span-12 lg:col-span-4">
              <div class="feature-box-01">
                <i class="icon theme-bg bi-laptop"></i>
                <div class="feature-content">
                  <h5>Web Development</h5>
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit,
                    sed do eiusmod tempor incididunt ut labore et dolore magna
                    aliqua.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-span-12 lg:col-span-4">
              <div class="feature-box-01">
                <i class="icon theme-bg bi-triangle"></i>
                <div class="feature-content">
                  <h5>SEO Marketing</h5>
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit,
                    sed do eiusmod tempor incididunt ut labore et dolore magna
                    aliqua.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <!-- separated -->
          <div class="separated"></div>
          <!-- End separated -->
          <div class="title">
            <h3>Awards.</h3>
          </div>
          <div class="grid grid-cols-12 gap-7">
            <div class="col-span-12 lg:col-span-4">
              <div class="feature-box-02 media align-items-center">
                <div class="icon">
                  <img src="../../assets/Nairo_images/a1.png" title="" alt="" />
                </div>
                <div class="media-body">
                  <h6>Honorable mension</h6>
                  <p>Site of the day</p>
                </div>
              </div>
            </div>
            <div class="col-span-12 lg:col-span-4">
              <div class="feature-box-02 media align-items-center">
                <div class="icon">
                  <img src="../../assets/Nairo_images/a2.png" title="" alt="" />
                </div>
                <div class="media-body">
                  <h6>Honorable mension</h6>
                  <p>Site of the day</p>
                </div>
              </div>
            </div>
            <div class="col-span-12 lg:col-span-4">
              <div class="feature-box-02 media align-items-center">
                <div class="icon">
                  <img src="../../assets/Nairo_images/a3.png" title="" alt="" />
                </div>
                <div class="media-body">
                  <h6>Honorable mension</h6>
                  <p>Site of the day</p>
                </div>
              </div>
            </div>
          </div>
          <!-- separated -->
          <div class="separated"></div>
          <!-- End separated -->
          <div class="title">
            <h3>Testimonials.</h3>
          </div>
          <div
            class="owl-carousel"
            data-items="2"
            data-nav-dots="true"
            data-lg-items="2"
            data-md-items="2"
            data-sm-items="1"
            data-xs-items="1"
            data-space="30"
            data-autoplay="true"
          >
            <div class="testimonial-01 media">
              <div class="avatar">
                <img src="../../assets/Nairo_images/team-1.jpg" title="" alt="" />
              </div>
              <div class="media-body">
                <p>
                  Lorem Ipsum is simply dummy text of the printing and
                  typesetting industry. Lorem Ipsum has been the industry's
                  standard dummy text ever since the 1500s.
                </p>
                <h6>Jennifer Lutheran</h6>
                <span>CEO at pxdraft</span>
              </div>
            </div>
            <div class="testimonial-01 media">
              <div class="avatar">
                <img src="../../assets/Nairo_images/team-2.jpg" title="" alt="" />
              </div>
              <div class="media-body">
                <p>
                  Lorem Ipsum is simply dummy text of the printing and
                  typesetting industry. Lorem Ipsum has been the industry's
                  standard dummy text ever since the 1500s.
                </p>
                <h6>Jennifer Lutheran</h6>
                <span>CEO at pxdraft</span>
              </div>
            </div>
            <div class="testimonial-01 media">
              <div class="avatar">
                <img src="../../assets/Nairo_images/team-3.jpg" title="" alt="" />
              </div>
              <div class="media-body">
                <p>
                  Lorem Ipsum is simply dummy text of the printing and
                  typesetting industry. Lorem Ipsum has been the industry's
                  standard dummy text ever since the 1500s.
                </p>
                <h6>Jennifer Lutheran</h6>
                <span>CEO at pxdraft</span>
              </div>
            </div>
            <div class="testimonial-01 media">
              <div class="avatar">
                <img src="../../assets/Nairo_images/team-1.jpg" title="" alt="" />
              </div>
              <div class="media-body">
                <p>
                  Lorem Ipsum is simply dummy text of the printing and
                  typesetting industry. Lorem Ipsum has been the industry's
                  standard dummy text ever since the 1500s.
                </p>
                <h6>Jennifer Lutheran</h6>
                <span>CEO at pxdraft</span>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- End Home -->

      <!-- Resume -->
      <section data-scroll-index="2" id="resume" class="section">
        <div class="container">
          <div class="title">
            <h3>Experience.</h3>
          </div>
          <div class="resume-box">
            <div class="resume-row">
              <div class="grid grid-cols-12 gap-7">
                <div class="col-span-12 md:col-span-4 xl:col-span-3">
                  <div class="rb-left">
                    <h6>Front-end Developer</h6>
                    <label>WeLab | Remote</label>
                    <p>Jan 2019 - Present</p>
                    <div class="rb-time">Full Time</div>
                  </div>
                </div>
                <div class="col-span-12 md:col-span-8 xl:col-span-9">
                  <div class="rb-right">
                    <h6>About Company</h6>
                    <p>
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit,
                      sed do eiusmod tempor incididunt ut labore et dolore magna
                      aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                      ullamco laboris nisi ut aliquip ex ea commodo consequat.
                      Duis aute irure dolor.
                    </p>
                  </div>
                </div>
              </div>
            </div>
            <div class="resume-row">
              <div class="grid grid-cols-12 gap-7">
                <div class="col-span-12 md:col-span-4 xl:col-span-3">
                  <div class="rb-left">
                    <h6>Front-end Developer</h6>
                    <label>WeLab | Remote</label>
                    <p>Jan 2019 - Present</p>
                    <div class="rb-time">Full Time</div>
                  </div>
                </div>
                <div class="col-span-12 md:col-span-8 xl:col-span-9">
                  <div class="rb-right">
                    <h6>About Company</h6>
                    <p>
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit,
                      sed do eiusmod tempor incididunt ut labore et dolore magna
                      aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                      ullamco laboris nisi ut aliquip ex ea commodo consequat.
                      Duis aute irure dolor.
                    </p>
                  </div>
                </div>
              </div>
            </div>
            <div class="resume-row">
              <div class="grid grid-cols-12 gap-7">
                <div class="col-span-12 md:col-span-4 xl:col-span-3">
                  <div class="rb-left">
                    <h6>Front-end Developer</h6>
                    <label>WeLab | Remote</label>
                    <p>Jan 2019 - Present</p>
                    <div class="rb-time">Full Time</div>
                  </div>
                </div>
                <div class="col-span-12 md:col-span-8 xl:col-span-9">
                  <div class="rb-right">
                    <h6>About Company</h6>
                    <p>
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit,
                      sed do eiusmod tempor incididunt ut labore et dolore magna
                      aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                      ullamco laboris nisi ut aliquip ex ea commodo consequat.
                      Duis aute irure dolor.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- separated -->
          <div class="separated">
            <!-- <img src="../../assets/Nairo_images/border-dark.png"/>   -->       
            </div> 
          <!-- End separated -->
          <div class="title">
            <h3>Education & Skills</h3>
          </div>
          <div class="grid grid-cols-12 gap-7">
            <div class="col-span-12 lg:col-span-4">
              <ul class="aducation-box">
                <li>
                  <span>2010-2012</span>
                  <h6>Graphic Designer</h6>
                  <p>International Design Institute</p>
                </li>
                <li>
                  <span>2010-2012</span>
                  <h6>Graphic Designer</h6>
                  <p>International Design Institute</p>
                </li>
                <li>
                  <span>2010-2012</span>
                  <h6>Graphic Designer</h6>
                  <p>International Design Institute</p>
                </li>
              </ul>
            </div>
            <div class="col-span-12 lg:col-span-8 lg:pl-16">
              <div class="skill-lt">
                <h6>HTML5</h6>
                <span>92%</span>
                <div class="skill-bar">
                  <div
                    class="skill-bar-in"
                    role="progressbar"
                    aria-valuenow="92"
                    aria-valuemin="0"
                    aria-valuemax="100"
                  ></div>
                </div>
              </div>
              <!-- /skill -->
              <div class="skill-lt">
                <h6>WordPress</h6>
                <span>75%</span>
                <div class="skill-bar">
                  <div
                    class="skill-bar-in"
                    role="progressbar"
                    aria-valuenow="72"
                    aria-valuemin="0"
                    aria-valuemax="100"
                  ></div>
                </div>
              </div>
              <!-- /skill -->
              <div class="skill-lt">
                <h6>Magento</h6>
                <span>86%</span>
                <div class="skill-bar">
                  <div
                    class="skill-bar-in"
                    role="progressbar"
                    aria-valuenow="86"
                    aria-valuemin="0"
                    aria-valuemax="100"
                  ></div>
                </div>
              </div>
              <!-- /skill -->
              <div class="skill-lt">
                <h6>UI/UX</h6>
                <span>88%</span>
                <div class="skill-bar">
                  <div
                    class="skill-bar-in"
                    role="progressbar"
                    aria-valuenow="88"
                    aria-valuemin="0"
                    aria-valuemax="100"
                  ></div>
                </div>
              </div>
              <!-- /skill -->
            </div>
          </div>
        </div>
      </section>
      <!-- Resume End -->

      <!-- Portfolio -->
      <section data-scroll-index="3" id="work" class="section bg-gray">
        <div class="container">
          <div class="title">
            <h3>My Portfolio.</h3>
          </div>
          <div class="portfolio-filter-01">
            <ul class="filter flex">
              <li class="active" data-filter="*">All</li>
              <li data-filter=".branding">Branding</li>
              <li data-filter=".photoshop">Photoshop</li>
              <li data-filter=".fashion">Fashion</li>
              <li data-filter=".product">Product</li>
            </ul>
          </div>
          <!-- Portfolio Filter -->
          <div
            class="portfolio-content grid-gutter-lg grid-col-3 lightbox-gallery"
          >
            <div class="grid-item product branding fashion">
              <div class="portfolio-box-01">
                <div class="portfolio-info">
                  <h5 class="white-color font-weight-bold">Momb ios App</h5>
                  <span>Broadcasting ios App</span>
                </div>
                <div class="portfolio-img">
                  <img
                    src="../../assets/Nairo_images/m-portfolio-1.jpg"
                    title=""
                    alt=""
                  />
                  <div class="portfolio-icon">
                    <a
                      href="assets/Nairo_images/m-portfolio-1.jpg"
                      class="gallery-link"
                    >
                      <span class="bi-plus"></span>
                    </a>
                  </div>
                </div>
              </div>
            </div>
            <!-- grid item -->
            <div class="grid-item photoshop">
              <div class="portfolio-box-01">
                <div class="portfolio-info">
                  <h5 class="white-color font-weight-bold">Momb ios App</h5>
                  <span>Broadcasting ios App</span>
                </div>
                <div class="portfolio-img">
                  <img
                    src="../../assets/Nairo_images/m-portfolio-2.jpg"
                    title=""
                    alt=""
                  />
                  <div class="portfolio-icon">
                    <a
                      href="assets/Nairo_images/m-portfolio-2.jpg"
                      class="gallery-link"
                    >
                      <span class="bi-plus"></span>
                    </a>
                  </div>
                </div>
              </div>
            </div>
            <!-- grid item -->
            <div class="grid-item product branding">
              <div class="portfolio-box-01">
                <div class="portfolio-info">
                  <h5 class="white-color font-weight-bold">Momb ios App</h5>
                  <span>Broadcasting ios App</span>
                </div>
                <div class="portfolio-img">
                  <img
                    src="../../assets/Nairo_images/m-portfolio-3.jpg"
                    title=""
                    alt=""
                  />
                  <div class="portfolio-icon">
                    <a
                      href="assets/Nairo_images/m-portfolio-3.jpg"
                      class="gallery-link"
                    >
                      <span class="bi-plus"></span>
                    </a>
                  </div>
                </div>
              </div>
            </div>
            <!-- grid item -->
            <div class="grid-item product photoshop">
              <div class="portfolio-box-01">
                <div class="portfolio-info">
                  <h5 class="white-color font-weight-bold">Momb ios App</h5>
                  <span>Broadcasting ios App</span>
                </div>
                <div class="portfolio-img">
                  <img
                    src="../../assets/Nairo_images/m-portfolio-5.jpg"
                    title=""
                    alt=""
                  />
                  <div class="portfolio-icon">
                    <a
                      href="assets/Nairo_images/m-portfolio-5.jpg"
                      class="gallery-link"
                    >
                      <span class="bi-plus"></span>
                    </a>
                  </div>
                </div>
              </div>
            </div>
            <!-- grid item -->
            <div class="grid-item branding">
              <div class="portfolio-box-01">
                <div class="portfolio-info">
                  <h5 class="white-color font-weight-bold">Momb ios App</h5>
                  <span>Broadcasting ios App</span>
                </div>
                <div class="portfolio-img">
                  <img
                    src="../../assets/Nairo_images/m-portfolio-4.jpg"
                    title=""
                    alt=""
                  />
                  <div class="portfolio-icon">
                    <a
                      href="assets/Nairo_images/m-portfolio-4.jpg"
                      class="gallery-link"
                    >
                      <span class="bi-plus"></span>
                    </a>
                  </div>
                </div>
              </div>
            </div>
            <!-- grid item -->
            <div class="grid-item product photoshop">
              <div class="portfolio-box-01">
                <div class="portfolio-info">
                  <h5 class="white-color font-weight-bold">Momb ios App</h5>
                  <span>Broadcasting ios App</span>
                </div>
                <div class="portfolio-img">
                  <img
                    src="../../assets/Nairo_images/m-portfolio-6.jpg"
                    title=""
                    alt=""
                  />
                  <div class="portfolio-icon">
                    <a
                      href="assets/Nairo_images/m-portfolio-6.jpg"
                      class="gallery-link"
                    >
                      <span class="bi-plus"></span>
                    </a>
                  </div>
                </div>
              </div>
            </div>
            <!-- grid item -->
            <div class="grid-item fashion">
              <div class="portfolio-box-01">
                <div class="portfolio-info">
                  <h5 class="white-color font-weight-bold">Momb ios App</h5>
                  <span>Broadcasting ios App</span>
                </div>
                <div class="portfolio-img">
                  <img
                    src="../../assets/Nairo_images/m-portfolio-7.jpg"
                    title=""
                    alt=""
                  />
                  <div class="portfolio-icon">
                    <a
                      href="assets/Nairo_images/m-portfolio-7.jpg"
                      class="gallery-link"
                    >
                      <span class="bi-plus"></span>
                    </a>
                  </div>
                </div>
              </div>
            </div>
            <!-- grid item -->
            <div class="grid-item product branding">
              <div class="portfolio-box-01">
                <div class="portfolio-info">
                  <h5 class="white-color font-weight-bold">Momb ios App</h5>
                  <span>Broadcasting ios App</span>
                </div>
                <div class="portfolio-img">
                  <img
                    src="../../assets/Nairo_images/m-portfolio-8.jpg"
                    title=""
                    alt=""
                  />
                  <div class="portfolio-icon">
                    <a
                      href="assets/Nairo_images/m-portfolio-8.jpg"
                      class="gallery-link"
                    >
                      <span class="bi-plus"></span>
                    </a>
                  </div>
                </div>
              </div>
            </div>
            <!-- grid item -->
            <div class="grid-item fashion">
              <div class="portfolio-box-01">
                <div class="portfolio-info">
                  <h5 class="white-color font-weight-bold">Momb ios App</h5>
                  <span>Broadcasting ios App</span>
                </div>
                <div class="portfolio-img">
                  <img
                    src="../../assets/Nairo_images/m-portfolio-9.jpg"
                    title=""
                    alt=""
                  />
                  <div class="portfolio-icon">
                    <a
                      href="assets/Nairo_images/m-portfolio-9.jpg"
                      class="gallery-link"
                    >
                      <span class="bi-plus"></span>
                    </a>
                  </div>
                </div>
              </div>
            </div>
            <!-- grid item -->
          </div>
        </div>
      </section>
      <!-- End Portfolio -->

      <!-- Blog -->
      <section data-scroll-index="4" id="blog" class="section">
        <div class="container">
          <div class="title">
            <h3>Latest Blog.</h3>
          </div>
          <div class="grid grid-cols-12 gap-7">
            <div class="col-span-12 md:col-span-6">
              <div class="blog-grid">
                <div class="blog-img">
                  <a class="px_modal" href="#blog_box_1">
                    <img src="../../assets/Nairo_images/blog-1.jpg" title="" alt="" />
                  </a>
                </div>
                <div class="blog-info">
                  <div class="meta">29/FEB/2020 - WEBSITE - 1 COMMENT</div>
                  <h6>
                    <a class="px_modal" href="#blog_box_1"
                      >Five Solid Evidences Attending Design Is Good For Your
                      Career Development.</a
                    >
                  </h6>
                </div>
              </div>
            </div>
            <div class="col-span-12 md:col-span-6">
              <div class="blog-grid">
                <div class="blog-img">
                  <a class="px_modal" href="#blog_box_2">
                    <img src="../../assets/Nairo_images/blog-2.jpg" title="" alt="" />
                  </a>
                </div>
                <div class="blog-info">
                  <div class="meta">29/FEB/2020 - WEBSITE - 1 COMMENT</div>
                  <h6>
                    <a class="px_modal" href="#blog_box_2"
                      >Ten Mind-Blowing Reasons Why Design Is Using This
                      Technique For Exposure.</a
                    >
                  </h6>
                </div>
              </div>
            </div>
            <div class="col-span-12 md:col-span-6">
              <div class="blog-grid">
                <div class="blog-img">
                  <a class="px_modal" href="#blog_box_3">
                    <img src="../../assets/Nairo_images/blog-3.jpg" title="" alt="" />
                  </a>
                </div>
                <div class="blog-info">
                  <div class="meta">29/FEB/2020 - WEBSITE - 1 COMMENT</div>
                  <h6>
                    <a class="px_modal" href="#blog_box_3"
                      >I Will Tell You The Truth About Design In The Next 60
                      Seconds.</a
                    >
                  </h6>
                </div>
              </div>
            </div>
            <div class="col-span-12 md:col-span-6">
              <div class="blog-grid">
                <div class="blog-img">
                  <a class="px_modal" href="#blog_box_4">
                    <img src="../../assets/Nairo_images/blog-4.jpg" title="" alt="" />
                  </a>
                </div>
                <div class="blog-info">
                  <div class="meta">29/FEB/2020 - WEBSITE - 1 COMMENT</div>
                  <h6>
                    <a class="px_modal" href="#blog_box_4"
                      >What You Know About Design And What You Don't Know About
                      Design.</a
                    >
                  </h6>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- End Blog -->

      <!-- Contact us -->
      <section data-scroll-index="5" id="contactus" class="section bg-gray">
        <div class="container">
          <div class="grid grid-cols-12 gap-7">
            <div class="col-span-12 lg:col-span-5 xl:col-span-4">
              <div class="contact-info">
                <h4>What’s your story? Get in touch</h4>
                <p>
                  Always available for freelancing if the right project comes
                  along, Feel free to contact me.
                </p>
                <ul>
                  <li class="media">
                    <i class="bi-map"></i>
                    <span class="media-body"
                      >123 Stree New York City , United States Of America
                      750065.</span
                    >
                  </li>
                  <li class="media">
                    <i class="bi-envelope"></i>
                    <span class="media-body">support@domain.com</span>
                  </li>
                  <li class="media">
                    <i class="bi-phone"></i>
                    <span class="media-body">+044 9696 9696 3636</span>
                  </li>
                </ul>
              </div>
            </div>
            <div class="col-span-12 lg:col-span-7 xl:col-span-8">
              <div class="contact-form">
                <h4>Say Something</h4>
                <form id="contact-form" method="POST" class="contactform">
                  <div class="grid grid-cols-12 gap-5">
                    <div class="col-span-12 md:col-span-6">
                      <div class="form-group">
                        <input
                          name="Name"
                          id="name"
                          placeholder="Name *"
                          class="form-control"
                          type="text"
                        />
                      </div>
                    </div>
                    <div class="col-span-12 md:col-span-6">
                      <div class="form-group">
                        <input
                          name="Email"
                          id="email"
                          placeholder="Email *"
                          class="form-control"
                          type="email"
                        />
                      </div>
                    </div>
                    <div class="col-span-12">
                      <div class="form-group">
                        <input
                          name="Subject"
                          id="subject"
                          placeholder="Subject *"
                          class="form-control"
                          type="text"
                        />
                      </div>
                    </div>
                    <div class="col-span-12">
                      <div class="form-group">
                        <textarea
                          name="message"
                          id="message"
                          placeholder="Your message *"
                          rows="3"
                          class="form-control"
                        ></textarea>
                      </div>
                    </div>
                    <div class="col-span-12">
                      <div class="send">
                        <button
                          class="px-btn px-btn-white"
                          onclick="send_mail()"
                          type="button"
                          value="Send"
                        >
                          Send Message
                        </button>
                        <span
                          id="suce_message"
                          class="text-success"
                          style="display: none"
                          >Message Sent Successfully</span
                        >
                        <span
                          id="err_message"
                          class="text-danger"
                          style="display: none"
                          >Message Sending Failed</span
                        >
                      </div>
                    </div>
                  </div>
                </form>
              </div>
            </div>
            <div class="col-span-12">
              <div class="google-map border-[5px] border-white shadow-md">
                <iframe
                  class="w-full aspect-[16/6]"
                  src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d3151.840107317064!2d144.955925!3d-37.817214!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xb6899234e561db11!2sEnvato!5e0!3m2!1sen!2sin!4v1520156366883"
                  allowfullscreen=""
                ></iframe>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- End Contact us -->

      <!-- All Snigle blog -->
      <!-- Snigle 1 -->
      <div id="blog_box_1" class="px-modal mfp-hide">
        <div class="single-blog-box">
          <div>
            <img
              class="w-full rounded-md"
              src="../../assets/Nairo_images/blog-1.jpg"
              title=""
              alt=""
            />
          </div>
          <article class="pt-5">
            <h6><a class="text-theme-500" href="#">Lifestyle</a></h6>
            <h2>They Now Bade Farewell To The Kind But Unseen People</h2>
            <p>
              Aenean eleifend ante maecenas pulvinar montes lorem et pede dis
              dolor pretium donec dictum. Vici consequat justo enim. Venenatis
              eget adipiscing luctus lorem. Adipiscing veni amet luctus enim sem
              libero tellus viverra venenatis aliquam. Commodo natoque quam
              pulvinar elit.
            </p>
            <p>
              Eget aenean tellus venenatis. Donec odio tempus. Felis arcu
              pretium metus nullam quam aenean sociis quis sem neque vici
              libero. Venenatis nullam fringilla pretium magnis aliquam nunc
              vulputate integer augue ultricies cras. Eget viverra feugiat cras
              ut. Sit natoque montes tempus ligula eget vitae pede rhoncus
              maecenas consectetuer commodo condimentum aenean.
            </p>
            <h4>What are my payment options?</h4>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </p>
            <blockquote>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam.
              </p>
              <p class="blockquote-footer">
                Someone famous in <cite title="Source Title">Dick Grayson</cite>
              </p>
            </blockquote>
          </article>
        </div>
      </div>
      <!-- End Snigle 1 -->
      <!-- Snigle 2 -->
      <div id="blog_box_2" class="px-modal mfp-hide">
        <div class="single-blog-box">
          <div>
            <img
              class="w-full rounded-md"
              src="../../assets/Nairo_images/blog-2.jpg"
              title=""
              alt=""
            />
          </div>
          <article class="pt-5">
            <h6><a class="text-theme-500" href="#">Lifestyle</a></h6>
            <h2>They Now Bade Farewell To The Kind But Unseen People</h2>
            <p>
              Aenean eleifend ante maecenas pulvinar montes lorem et pede dis
              dolor pretium donec dictum. Vici consequat justo enim. Venenatis
              eget adipiscing luctus lorem. Adipiscing veni amet luctus enim sem
              libero tellus viverra venenatis aliquam. Commodo natoque quam
              pulvinar elit.
            </p>
            <p>
              Eget aenean tellus venenatis. Donec odio tempus. Felis arcu
              pretium metus nullam quam aenean sociis quis sem neque vici
              libero. Venenatis nullam fringilla pretium magnis aliquam nunc
              vulputate integer augue ultricies cras. Eget viverra feugiat cras
              ut. Sit natoque montes tempus ligula eget vitae pede rhoncus
              maecenas consectetuer commodo condimentum aenean.
            </p>
            <h4>What are my payment options?</h4>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </p>
            <blockquote>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam.
              </p>
              <p class="blockquote-footer">
                Someone famous in <cite title="Source Title">Dick Grayson</cite>
              </p>
            </blockquote>
          </article>
        </div>
      </div>
      <!-- End Snigle 2 -->
      <!-- Snigle 3 -->
      <div id="blog_box_3" class="px-modal mfp-hide">
        <div class="single-blog-box">
          <div>
            <img
              class="w-full rounded-md"
              src="../../assets/Nairo_images/blog-3.jpg"
              title=""
              alt=""
            />
          </div>
          <article class="pt-5">
            <h6><a class="text-theme-500" href="#">Lifestyle</a></h6>
            <h2>They Now Bade Farewell To The Kind But Unseen People</h2>
            <p>
              Aenean eleifend ante maecenas pulvinar montes lorem et pede dis
              dolor pretium donec dictum. Vici consequat justo enim. Venenatis
              eget adipiscing luctus lorem. Adipiscing veni amet luctus enim sem
              libero tellus viverra venenatis aliquam. Commodo natoque quam
              pulvinar elit.
            </p>
            <p>
              Eget aenean tellus venenatis. Donec odio tempus. Felis arcu
              pretium metus nullam quam aenean sociis quis sem neque vici
              libero. Venenatis nullam fringilla pretium magnis aliquam nunc
              vulputate integer augue ultricies cras. Eget viverra feugiat cras
              ut. Sit natoque montes tempus ligula eget vitae pede rhoncus
              maecenas consectetuer commodo condimentum aenean.
            </p>
            <h4>What are my payment options?</h4>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </p>
            <blockquote>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam.
              </p>
              <p class="blockquote-footer">
                Someone famous in <cite title="Source Title">Dick Grayson</cite>
              </p>
            </blockquote>
          </article>
        </div>
      </div>
      <!-- End Snigle 3 -->
      <!-- Snigle 3 -->
      <div id="blog_box_4" class="px-modal mfp-hide">
        <div class="single-blog-box">
          <div>
            <img
              class="w-full rounded-md"
              src="../../assets/Nairo_images/blog-4.jpg"
              title=""
              alt=""
            />
          </div>
          <article class="pt-5">
            <h6><a class="text-theme-500" href="#">Lifestyle</a></h6>
            <h2>They Now Bade Farewell To The Kind But Unseen People</h2>
            <p>
              Aenean eleifend ante maecenas pulvinar montes lorem et pede dis
              dolor pretium donec dictum. Vici consequat justo enim. Venenatis
              eget adipiscing luctus lorem. Adipiscing veni amet luctus enim sem
              libero tellus viverra venenatis aliquam. Commodo natoque quam
              pulvinar elit.
            </p>
            <p>
              Eget aenean tellus venenatis. Donec odio tempus. Felis arcu
              pretium metus nullam quam aenean sociis quis sem neque vici
              libero. Venenatis nullam fringilla pretium magnis aliquam nunc
              vulputate integer augue ultricies cras. Eget viverra feugiat cras
              ut. Sit natoque montes tempus ligula eget vitae pede rhoncus
              maecenas consectetuer commodo condimentum aenean.
            </p>
            <h4>What are my payment options?</h4>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </p>
            <blockquote>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam.
              </p>
              <p class="blockquote-footer">
                Someone famous in <cite title="Source Title">Dick Grayson</cite>
              </p>
            </blockquote>
          </article>
        </div>
      </div>
      <!-- End Snigle 3 -->
      <!-- End All Snigle blog -->

      <!-- Footer -->
      <footer
        class="footer bg-white dark:bg-mode-300 border-t border-gray-100 dark:border-white dark:border-opacity-10 py-4"
      >
        <div class="container">
          <div class="grid grid-cols-12">
            <div class="col-span-12 md:col-span-6 flex pb-3 md:pb-0">
              <div class="flex justify-center md:justify-start w-full">
                <a
                  class="text-gray-700 dark:text-white text-opacity-90 hover:text-theme-500 mr-5 text-[16px]"
                  href="#"
                  ><i class="fab fa-facebook-f"></i
                ></a>
                <a
                  class="text-gray-700 dark:text-white text-opacity-90 hover:text-theme-500 mr-5 text-[16px]"
                  href="#"
                  ><i class="fab fa-twitter"></i
                ></a>
                <a
                  class="text-gray-700 dark:text-white text-opacity-90 hover:text-theme-500 mr-5 text-[16px]"
                  href="#"
                  ><i class="fab fa-instagram"></i
                ></a>
                <a
                  class="text-gray-700 dark:text-white text-opacity-90 hover:text-theme-500 mr-5 text-[16px]"
                  href="#"
                  ><i class="fab fa-linkedin-in"></i
                ></a>
                <a
                  class="text-gray-700 dark:text-white text-opacity-90 hover:text-theme-500 mr-5 text-[16px]"
                  href="#"
                  ><i class="fab fa-pinterest"></i
                ></a>
              </div>
            </div>
            <div class="col-span-12 md:col-span-6 text-center md:text-right">
              <p class="m-0 text-gray-700 dark:text-white text-opacity-75">
                © 2022 copyright all right reserved
              </p>
            </div>
          </div>
        </div>
      </footer>
      <!-- End Footer -->
    </main>
  </div>
</template>

<script>
export default {
  setup() {
    return {};
  },
};
</script>

<style scoped>
*,
::before,
::after {
  box-sizing: border-box;
  /* 1 */
  border-width: 0;
  /* 2 */
  border-style: solid;
  /* 2 */
  border-color: #e5e7eb;
  /* 2 */
}

::before,
::after {
  --tw-content: "";
}

html {
  line-height: 1.5;
  /* 1 */
  -webkit-text-size-adjust: 100%;
  /* 2 */
  -moz-tab-size: 4;
  /* 3 */
  -o-tab-size: 4;
  tab-size: 4;
  /* 3 */
  font-family: Rubik, Helvetica, Arial, sans-serif;
  /* 4 */
}
body {
  margin: 0;
  /* 1 */
  line-height: inherit;
  /* 2 */
}

hr {
  height: 0;
  /* 1 */
  color: inherit;
  /* 2 */
  border-top-width: 1px;
  /* 3 */
}

abbr:where([title]) {
  -webkit-text-decoration: underline dotted;
  text-decoration: underline dotted;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-size: inherit;
  font-weight: inherit;
}

a {
  color: inherit;
  text-decoration: inherit;
}

/*
Add the correct font weight in Edge and Safari.
*/

b,
strong {
  font-weight: bolder;
}

code,
kbd,
samp,
pre {
  font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas,
    "Liberation Mono", "Courier New", monospace;
  /* 1 */
  font-size: 1em;
  /* 2 */
}
small {
  font-size: 80%;
}

/*
Prevent `sub` and `sup` elements from affecting the line height in all browsers.
*/

sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}

sub {
  bottom: -0.25em;
}

sup {
  top: -0.5em;
}

/*
1. Remove text indentation from table contents in Chrome and Safari. (https://bugs.chromium.org/p/chromium/issues/detail?id=999088, https://bugs.webkit.org/show_bug.cgi?id=201297)
2. Correct table border color inheritance in all Chrome and Safari. (https://bugs.chromium.org/p/chromium/issues/detail?id=935729, https://bugs.webkit.org/show_bug.cgi?id=195016)
3. Remove gaps between table borders by default.
*/

table {
  text-indent: 0;
  /* 1 */
  border-color: inherit;
  /* 2 */
  border-collapse: collapse;
  /* 3 */
}

/*
1. Change the font styles in all browsers.
2. Remove the margin in Firefox and Safari.
3. Remove default padding in all browsers.
*/

button,
input,
optgroup,
select,
textarea {
  font-family: inherit;
  /* 1 */
  font-size: 100%;
  /* 1 */
  font-weight: inherit;
  /* 1 */
  line-height: inherit;
  /* 1 */
  color: inherit;
  /* 1 */
  margin: 0;
  /* 2 */
  padding: 0;
  /* 3 */
}

/*
Remove the inheritance of text transform in Edge and Firefox.
*/

button,
select {
  text-transform: none;
}

/*
1. Correct the inability to style clickable types in iOS and Safari.
2. Remove default button styles.
*/

button,
[type="button"],
[type="reset"],
[type="submit"] {
  -webkit-appearance: button;
  /* 1 */
  background-color: transparent;
  /* 2 */
  background-image: none;
  /* 2 */
}

/*
Use the modern Firefox focus style for all focusable elements.
*/

:-moz-focusring {
  outline: auto;
}

/*
Remove the additional `:invalid` styles in Firefox. (https://github.com/mozilla/gecko-dev/blob/2f9eacd9d3d995c937b4251a5557d95d494c9be1/layout/style/res/forms.css#L728-L737)
*/

:-moz-ui-invalid {
  box-shadow: none;
}

/*
Add the correct vertical alignment in Chrome and Firefox.
*/

progress {
  vertical-align: baseline;
}

/*
Correct the cursor style of increment and decrement buttons in Safari.
*/

::-webkit-inner-spin-button,
::-webkit-outer-spin-button {
  height: auto;
}

/*
1. Correct the odd appearance in Chrome and Safari.
2. Correct the outline style in Safari.
*/

[type="search"] {
  -webkit-appearance: textfield;
  /* 1 */
  outline-offset: -2px;
  /* 2 */
}

/*
Remove the inner padding in Chrome and Safari on macOS.
*/

::-webkit-search-decoration {
  -webkit-appearance: none;
}

/*
1. Correct the inability to style clickable types in iOS and Safari.
2. Change font properties to `inherit` in Safari.
*/

::-webkit-file-upload-button {
  -webkit-appearance: button;
  /* 1 */
  font: inherit;
  /* 2 */
}

/*
Add the correct display in Chrome and Safari.
*/

summary {
  display: list-item;
}

/*
Removes the default spacing and border for appropriate elements.
*/

blockquote,
dl,
dd,
h1,
h2,
h3,
h4,
h5,
h6,
hr,
figure,
p,
pre {
  margin: 0;
}

fieldset {
  margin: 0;
  padding: 0;
}

legend {
  padding: 0;
}

ol,
ul,
menu {
  list-style: none;
  margin: 0;
  padding: 0;
}

/*
Prevent resizing textareas horizontally by default.
*/

textarea {
  resize: vertical;
}

/*
1. Reset the default placeholder opacity in Firefox. (https://github.com/tailwindlabs/tailwindcss/issues/3300)
2. Set the default placeholder color to the user's configured gray 400 color.
*/

input::-moz-placeholder,
textarea::-moz-placeholder {
  opacity: 1;
  /* 1 */
  color: #9ca3af;
  /* 2 */
}

input::placeholder,
textarea::placeholder {
  opacity: 1;
  /* 1 */
  color: #9ca3af;
  /* 2 */
}

/*
Set the default cursor for buttons.
*/

button,
[role="button"] {
  cursor: pointer;
}

/*
Make sure disabled buttons don't get the pointer cursor.
*/

:disabled {
  cursor: default;
}

/*
1. Make replaced elements `display: block` by default. (https://github.com/mozdevs/cssremedy/issues/14)
2. Add `vertical-align: middle` to align replaced elements more sensibly by default. (https://github.com/jensimmons/cssremedy/issues/14#issuecomment-634934210)
   This can trigger a poorly considered lint error in some tools but is included by design.
*/

img,
svg,
video,
canvas,
audio,
iframe,
embed,
object {
  display: block;
  /* 1 */
  vertical-align: middle;
  /* 2 */
}

/*
Constrain images and videos to the parent width and preserve their intrinsic aspect ratio. (https://github.com/mozdevs/cssremedy/issues/14)
*/

img,
video {
  max-width: 100%;
  height: auto;
}

html {
  --tw-text-opacity: 1;
  color: rgb(85 85 85 / var(--tw-text-opacity));
}

*,
::before,
::after {
  --tw-border-spacing-x: 0;
  --tw-border-spacing-y: 0;
  --tw-translate-x: 0;
  --tw-translate-y: 0;
  --tw-rotate: 0;
  --tw-skew-x: 0;
  --tw-skew-y: 0;
  --tw-scale-x: 1;
  --tw-scale-y: 1;
  --tw-pan-x: ;
  --tw-pan-y: ;
  --tw-pinch-zoom: ;
  --tw-scroll-snap-strictness: proximity;
  --tw-ordinal: ;
  --tw-slashed-zero: ;
  --tw-numeric-figure: ;
  --tw-numeric-spacing: ;
  --tw-numeric-fraction: ;
  --tw-ring-inset: ;
  --tw-ring-offset-width: 0px;
  --tw-ring-offset-color: #fff;
  --tw-ring-color: rgb(59 130 246 / 0.5);
  --tw-ring-offset-shadow: 0 0 #0000;
  --tw-ring-shadow: 0 0 #0000;
  --tw-shadow: 0 0 #0000;
  --tw-shadow-colored: 0 0 #0000;
  --tw-blur: ;
  --tw-brightness: ;
  --tw-contrast: ;
  --tw-grayscale: ;
  --tw-hue-rotate: ;
  --tw-invert: ;
  --tw-saturate: ;
  --tw-sepia: ;
  --tw-drop-shadow: ;
  --tw-backdrop-blur: ;
  --tw-backdrop-brightness: ;
  --tw-backdrop-contrast: ;
  --tw-backdrop-grayscale: ;
  --tw-backdrop-hue-rotate: ;
  --tw-backdrop-invert: ;
  --tw-backdrop-opacity: ;
  --tw-backdrop-saturate: ;
  --tw-backdrop-sepia: ;
}

::-webkit-backdrop {
  --tw-border-spacing-x: 0;
  --tw-border-spacing-y: 0;
  --tw-translate-x: 0;
  --tw-translate-y: 0;
  --tw-rotate: 0;
  --tw-skew-x: 0;
  --tw-skew-y: 0;
  --tw-scale-x: 1;
  --tw-scale-y: 1;
  --tw-pan-x: ;
  --tw-pan-y: ;
  --tw-pinch-zoom: ;
  --tw-scroll-snap-strictness: proximity;
  --tw-ordinal: ;
  --tw-slashed-zero: ;
  --tw-numeric-figure: ;
  --tw-numeric-spacing: ;
  --tw-numeric-fraction: ;
  --tw-ring-inset: ;
  --tw-ring-offset-width: 0px;
  --tw-ring-offset-color: #fff;
  --tw-ring-color: rgb(59 130 246 / 0.5);
  --tw-ring-offset-shadow: 0 0 #0000;
  --tw-ring-shadow: 0 0 #0000;
  --tw-shadow: 0 0 #0000;
  --tw-shadow-colored: 0 0 #0000;
  --tw-blur: ;
  --tw-brightness: ;
  --tw-contrast: ;
  --tw-grayscale: ;
  --tw-hue-rotate: ;
  --tw-invert: ;
  --tw-saturate: ;
  --tw-sepia: ;
  --tw-drop-shadow: ;
  --tw-backdrop-blur: ;
  --tw-backdrop-brightness: ;
  --tw-backdrop-contrast: ;
  --tw-backdrop-grayscale: ;
  --tw-backdrop-hue-rotate: ;
  --tw-backdrop-invert: ;
  --tw-backdrop-opacity: ;
  --tw-backdrop-saturate: ;
  --tw-backdrop-sepia: ;
}

::backdrop {
  --tw-border-spacing-x: 0;
  --tw-border-spacing-y: 0;
  --tw-translate-x: 0;
  --tw-translate-y: 0;
  --tw-rotate: 0;
  --tw-skew-x: 0;
  --tw-skew-y: 0;
  --tw-scale-x: 1;
  --tw-scale-y: 1;
  --tw-pan-x: ;
  --tw-pan-y: ;
  --tw-pinch-zoom: ;
  --tw-scroll-snap-strictness: proximity;
  --tw-ordinal: ;
  --tw-slashed-zero: ;
  --tw-numeric-figure: ;
  --tw-numeric-spacing: ;
  --tw-numeric-fraction: ;
  --tw-ring-inset: ;
  --tw-ring-offset-width: 0px;
  --tw-ring-offset-color: #fff;
  --tw-ring-color: rgb(59 130 246 / 0.5);
  --tw-ring-offset-shadow: 0 0 #0000;
  --tw-ring-shadow: 0 0 #0000;
  --tw-shadow: 0 0 #0000;
  --tw-shadow-colored: 0 0 #0000;
  --tw-blur: ;
  --tw-brightness: ;
  --tw-contrast: ;
  --tw-grayscale: ;
  --tw-hue-rotate: ;
  --tw-invert: ;
  --tw-saturate: ;
  --tw-sepia: ;
  --tw-drop-shadow: ;
  --tw-backdrop-blur: ;
  --tw-backdrop-brightness: ;
  --tw-backdrop-contrast: ;
  --tw-backdrop-grayscale: ;
  --tw-backdrop-hue-rotate: ;
  --tw-backdrop-invert: ;
  --tw-backdrop-opacity: ;
  --tw-backdrop-saturate: ;
  --tw-backdrop-sepia: ;
}
.container {
  width: 100%;
  margin-right: auto;
  margin-left: auto;
  padding-right: 2rem;
  padding-left: 2rem;
}

@media (min-width: 640px) {
  .container {
    max-width: 640px;
  }
}

@media (min-width: 768px) {
  .container {
    max-width: 768px;
  }
}

@media (min-width: 1024px) {
  .container {
    max-width: 1024px;
  }
}

@media (min-width: 1280px) {
  .container {
    max-width: 1280px;
  }
}

@media (min-width: 1536px) {
  .container {
    max-width: 1536px;
  }
}

.sticky {
  position: -webkit-sticky;
  position: sticky;
}
.col-span-12 {
  grid-column: span 12 / span 12;
}

.m-0 {
  margin: 0px;
}

.my-\[5px\] {
  margin-top: 5px;
  margin-bottom: 5px;
}

.ml-auto {
  margin-left: auto;
}

.mt-auto {
  margin-top: auto;
}

.mr-5 {
  margin-right: 1.25rem;
}

.inline-block {
  display: inline-block;
}

.inline {
  display: inline;
}

.flex {
  display: flex;
}

.table {
  display: table;
}

.grid {
  display: grid;
}

.hidden {
  display: none;
}

.aspect-\[16\/6\] {
  aspect-ratio: 16/6;
}

.h-\[2px\] {
  height: 2px;
}

.h-5 {
  height: 1.25rem;
}

.min-h-screen {
  min-height: 100vh;
}

.w-\[40px\] {
  width: 40px;
}

.w-\[25px\] {
  width: 25px;
}

.w-5 {
  width: 1.25rem;
}

.w-full {
  width: 100%;
}

.cursor-text {
  cursor: text;
}

.list-none {
  list-style-type: none;
}

.grid-cols-12 {
  grid-template-columns: repeat(12, minmax(0, 1fr));
}

.flex-col {
  flex-direction: column;
}

.items-center {
  align-items: center;
}

.justify-center {
  justify-content: center;
}

.gap-7 {
  gap: 1.75rem;
}

.gap-5 {
  gap: 1.25rem;
}

.rounded-md {
  border-radius: 0.375rem;
}

.border-\[5px\] {
  border-width: 5px;
}

.border {
  border-width: 1px;
}

.border-t {
  border-top-width: 1px;
}

.border-white {
  --tw-border-opacity: 1;
  border-color: rgb(255 255 255 / var(--tw-border-opacity));
}

.border-gray-100 {
  --tw-border-opacity: 1;
  border-color: rgb(243 244 246 / var(--tw-border-opacity));
}

.bg-slate-900 {
  --tw-bg-opacity: 1;
  background-color: rgb(15 23 42 / var(--tw-bg-opacity));
}

.bg-theme-500 {
  --tw-bg-opacity: 1;
  background-color: rgb(255 147 1 / var(--tw-bg-opacity));
}

.bg-white {
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
}

.py-4 {
  padding-top: 1rem;
  padding-bottom: 1rem;
}

.pt-5 {
  padding-top: 1.25rem;
}

.pb-3 {
  padding-bottom: 0.75rem;
}

.text-left {
  text-align: left;
}

.text-center {
  text-align: center;
}

.text-right {
  text-align: right;
}

.align-top {
  vertical-align: top;
}

.align-middle {
  vertical-align: middle;
}

.align-bottom {
  vertical-align: bottom;
}

.text-\[16px\] {
  font-size: 16px;
}

.text-theme-500 {
  --tw-text-opacity: 1;
  color: rgb(255 147 1 / var(--tw-text-opacity));
}

.text-gray-700 {
  --tw-text-opacity: 1;
  color: rgb(55 65 81 / var(--tw-text-opacity));
}

.text-opacity-90 {
  --tw-text-opacity: 0.9;
}

.text-opacity-75 {
  --tw-text-opacity: 0.75;
}

.shadow-md {
  --tw-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
  --tw-shadow-colored: 0 4px 6px -1px var(--tw-shadow-color),
    0 2px 4px -2px var(--tw-shadow-color);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000),
    var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
}

.filter {
  filter: var(--tw-blur) var(--tw-brightness) var(--tw-contrast)
    var(--tw-grayscale) var(--tw-hue-rotate) var(--tw-invert) var(--tw-saturate)
    var(--tw-sepia) var(--tw-drop-shadow);
}

.container {
  padding-right: 15px;
  padding-left: 15px;
}

@media (min-width: 1200px) {
  .container {
    max-width: 1140px;
  }
}

/* #loading {
  position: fixed;
  top: 0px;
  left: 0px;
  right: 0px;
  bottom: 0px;
  z-index: 999;
  --tw-bg-opacity: 1;
  background-color: rgb(255 147 1 / var(--tw-bg-opacity));
} */

.load-circle {
  position: fixed;
  top: 0px;
  left: 0px;
  right: 0px;
  bottom: 0px;
  margin: auto;
  height: 50px;
  width: 50px;
}

.load-circle span {
  display: inline-block;
  height: 64px;
  width: 64px;
}

.load-circle span::after {
  content: var(--tw-content);
  position: absolute;
}

/* .load-circle span:after {
  margin: 1px;
  display: block;
  height: 46px;
  width: 46px;
  border-radius: 9999px;
  border-width: 4px;
  border-left-color: rgb(255 255 255 / var(--tw-border-opacity));
  border-bottom-color: rgb(255 255 255 / var(--tw-border-opacity));
  border-top-color: transparent;
  --tw-border-opacity: 1;
  border-right-color: rgb(255 255 255 / var(--tw-border-opacity));
  -webkit-animation: lds-dual-ring 1.2s linear infinite;
          animation: lds-dual-ring 1.2s linear infinite;
} */

@-webkit-keyframes lds-dual-ring {
  0% {
    transform: rotate(0deg);
  }

  100% {
    transform: rotate(360deg);
  }
}

@keyframes lds-dual-ring {
  0% {
    transform: rotate(0deg);
  }

  100% {
    transform: rotate(360deg);
  }
}

/* Body
------------------------------*/

body {
  overflow-x: hidden;
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
  font-size: 15px;
  font-weight: 400;
  line-height: 1.7;
  --tw-text-opacity: 1;
  color: rgb(85 85 85 / var(--tw-text-opacity));
}

.dark body {
  --tw-bg-opacity: 1;
  background-color: rgb(24 25 29 / var(--tw-bg-opacity));
  color: rgb(255 255 255 / var(--tw-text-opacity));
  --tw-text-opacity: 0.7;
}

@media (min-width: 1024px) {
  .main-left {
    padding-left: 80px;
  }
}

.bg-gray {
  --tw-bg-opacity: 1;
  background-color: rgb(247 247 255 / var(--tw-bg-opacity));
}
.dark .bg-gray {
  --tw-bg-opacity: 1;
  background-color: rgb(20 20 22 / var(--tw-bg-opacity));
}

/* Section
---------------------*/

.section {
  padding-top: 60px;
  padding-bottom: 60px;
}

@media (min-width: 768px) {
  .section {
    padding-top: 80px;
    padding-bottom: 80px;
  }
}

@media (min-width: 1024px) {
  .section {
    padding-top: 100px;
    padding-bottom: 100px;
  }
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-weight: 600;
  line-height: 1.3;
}

/* owl 
---------------------------*/

.owl-dots {
  text-align: center;
}

.owl-dots .owl-dot {
  margin-left: 0.25rem;
  margin-right: 0.25rem;
  display: inline-block;
  height: 10px;
  width: 10px;
  border-radius: 9999px;
  border-width: 1px;
  --tw-border-opacity: 1;
  border-color: rgb(24 25 29 / var(--tw-border-opacity));
  background-color: transparent;
  vertical-align: top;
  transition-duration: 300ms;
}

.dark .owl-dots .owl-dot {
  --tw-border-opacity: 1;
  border-color: rgb(255 255 255 / var(--tw-border-opacity));
}

.owl-dots .owl-dot.active {
  --tw-bg-opacity: 1;
  background-color: rgb(24 25 29 / var(--tw-bg-opacity));
}

.dark .owl-dots .owl-dot.active {
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
}

.owl-carousel .owl-item img {
  width: auto;
  max-width: 100%;
}

/* Buttons
------------------------------*/

.px-btn {
  position: relative;
  display: inline-flex;
  border-radius: 0.375rem;
  border-width: 2px;
  border-color: transparent;
  background-image: none;
  padding-left: 25px;
  padding-right: 25px;
  padding-top: 12px;
  padding-bottom: 12px;
  font-size: 1rem;
  line-height: 1.5rem;
  font-weight: 500;
  text-transform: capitalize;
  transition-duration: 300ms;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.px-btn.px-btn-white {
  --tw-border-opacity: 1;
  border-color: rgb(24 25 29 / var(--tw-border-opacity));
  --tw-bg-opacity: 1;
  background-color: rgb(24 25 29 / var(--tw-bg-opacity));
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.dark .px-btn.px-btn-white {
  --tw-border-opacity: 1;
  border-color: rgb(255 255 255 / var(--tw-border-opacity));
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.px-btn.px-btn-white:hover {
  background-color: transparent;
  --tw-text-opacity: 1;
  color: rgb(17 24 39 / var(--tw-text-opacity));
}

.dark .px-btn.px-btn-white:hover {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

/* theme color
------------------------------*/

.theme-color {
  padding-bottom: 1rem;
  text-align: center;
}

.theme-color button {
  margin-left: auto;
  margin-right: auto;
  display: flex;
  height: 40px;
  width: 40px;
  align-items: center;
  justify-content: center;
  border-radius: 9999px;
  --tw-bg-opacity: 1;
  background-color: rgb(24 25 29 / var(--tw-bg-opacity));
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
  outline: 2px solid transparent;
  outline-offset: 2px;
}

.dark .theme-color button {
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

/* Title
-----------------------------------*/

.title {
  margin-bottom: 25px;
}

@media (min-width: 1024px) {
  .title {
    margin-bottom: 35px;
  }
}

.title h3 {
  position: relative;
  z-index: 1;
  margin: 0px;
  display: inline-block;
  vertical-align: top;
  font-size: 30px;
  font-weight: 600;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.title h3::after {
  content: var(--tw-content);
  position: absolute;
}

.dark .title h3 {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.title h3:after {
  top: -4px;
  left: 0px;
  z-index: -1;
  height: 45px;
  width: 45px;
  border-radius: 9999px;
  background-color: rgb(255 147 1 / var(--tw-bg-opacity));
  --tw-bg-opacity: 0.5;
}

.dark .title h3:after {
  --tw-bg-opacity: 1;
}

@media (min-width: 1024px) {
  .title h3:after {
    top: -8px;
    left: -15px;
  }
}

.separated {
  background-image: url("`_nuxt/assets/Nairo_images/border-dark.png`");
  background-size: auto 6px;
  background-position: center;
  background-repeat: repeat-x;
  padding-top: 40px;
  padding-bottom: 40px;
}

.dark .separated {
  background-image: url("../img/border.png");
}

@media (min-width: 768px) {
  .separated {
    padding-top: 60px;
    padding-bottom: 60px;
  }
}

@media (min-width: 1024px) {
  .separated {
    padding-top: 80px;
    padding-bottom: 80px;
  }
}

/* Header
------------------------------*/

.main-header {
  position: fixed;
  left: -150px;
  top: 0px;
  bottom: 0px;
  z-index: 111;
  display: flex;
  width: 80px;
  flex-direction: column;
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
  --tw-shadow: 0 1px 3px 0 rgb(0 0 0 / 0.1), 0 1px 2px -1px rgb(0 0 0 / 0.1);
  --tw-shadow-colored: 0 1px 3px 0 var(--tw-shadow-color),
    0 1px 2px -1px var(--tw-shadow-color);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000),
    var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
  transition-property: left;
  transition-duration: 700ms;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.dark .main-header {
  border-right-width: 1px;
  border-color: rgb(255 255 255 / var(--tw-border-opacity));
  --tw-border-opacity: 0.05;
  --tw-bg-opacity: 1;
  background-color: rgb(35 38 47 / var(--tw-bg-opacity));
}

@media (min-width: 1024px) {
  .main-header {
    left: 0px;
  }
}

.main-header .logo img {
  margin-left: auto;
  margin-right: auto;
  max-width: 60px;
}

.main-header.menu-open {
  left: 0px;
}

.nav-menu {
  margin: 0px;
  display: flex;
  list-style-type: none;
  flex-direction: column;
  padding: 0px;
}

.nav-menu li {
  border-bottom-width: 1px;
  border-bottom-color: rgb(24 25 29 / var(--tw-border-opacity));
  --tw-border-opacity: 0.1;
}

.dark .nav-menu li {
  border-bottom-color: rgb(255 255 255 / var(--tw-border-opacity));
  --tw-border-opacity: 0.05;
}

.nav-menu a {
  margin: 0px;
  display: flex;
  align-items: center;
  justify-content: center;
  padding-top: 10px;
  padding-bottom: 10px;
  text-align: center;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
  transition-timing-function: linear;
}

.dark .nav-menu a {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.nav-menu a:hover,
.nav-menu a.active {
  --tw-text-opacity: 1;
  color: rgb(255 147 1 / var(--tw-text-opacity));
}

.nav-menu a i {
  display: flex;
  height: 40px;
  width: 40px;
  align-items: center;
  justify-content: center;
  font-size: 25px;
  line-height: 1;
}

.nav-menu a span {
  display: none;
}

.mobile-header {
  position: fixed;
  top: 0px;
  left: 0px;
  right: 0px;
  z-index: 40;
  align-items: center;
  border-bottom-width: 1px;
  --tw-border-opacity: 1;
  border-color: rgb(229 231 235 / var(--tw-border-opacity));
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
  padding: 0.5rem;
}

.dark .mobile-header {
  border-right-width: 1px;
  border-color: rgb(255 255 255 / var(--tw-border-opacity));
  --tw-border-opacity: 0.05;
  --tw-bg-opacity: 1;
  background-color: rgb(24 25 29 / var(--tw-bg-opacity));
}

.mobile-header .logo {
  max-width: 50px;
  --tw-bg-opacity: 1;
  background-color: rgb(35 38 47 / var(--tw-bg-opacity));
}
/* Home Banner
------------------------------*/

.home-banner {
  position: relative;
  overflow: hidden;
}

.home-banner::after {
  content: var(--tw-content);
  position: absolute;
  right: -20vh;
  bottom: -20vh;
  z-index: -1;
  height: 120vh;
  width: 120vh;
  border-radius: 9999px;
  --tw-bg-opacity: 1;
  background-color: rgb(248 250 252 / var(--tw-bg-opacity));
}

.dark .home-banner::after {
  background-color: rgb(0 0 0 / var(--tw-bg-opacity));
  --tw-bg-opacity: 0.1;
}

.home-banner .hb-top-fixed {
  position: absolute;
  top: 0px;
  left: 0px;
  right: 0px;
  z-index: 3;
  padding-left: 50px;
  padding-right: 50px;
  padding-top: 30px;
}

.home-banner .hb-info label {
  margin: 0px;
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 400;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.dark .home-banner .hb-info label {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.home-banner .hb-info label + label {
  margin-left: 2.5rem;
}

.home-banner .hb-lang {
  margin-left: auto;
}

.home-banner .hb-lang li a {
  margin-left: 0.5rem;
  padding-left: 8px;
  padding-right: 8px;
  padding-top: 5px;
  padding-bottom: 5px;
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 400;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.home-banner .hb-lang li a:hover {
  --tw-bg-opacity: 1;
  background-color: rgb(255 147 1 / var(--tw-bg-opacity));
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.dark .home-banner .hb-lang li a {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.home-banner .hb-lang li.active a {
  --tw-bg-opacity: 1;
  background-color: rgb(255 147 1 / var(--tw-bg-opacity));
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.home-banner .container {
  position: relative;
  z-index: 1;
}

.home-banner .hb-me {
  position: absolute;
  right: 0px;
  top: 0px;
  bottom: 0px;
  height: 100%;
  width: 100vw;
  background-size: contain;
  background-position: bottom;
  background-repeat: no-repeat;
  opacity: 0.4;
}

@media (min-width: 1024px) {
  .home-banner .hb-me {
    width: 90vw;
    opacity: 1;
  }
}

@media (min-width: 1280px) {
  .home-banner .hb-me {
    width: 50vw;
  }
}

.home-banner .type-box {
  padding-top: 120px;
  padding-bottom: 50px;
}

@media (min-width: 1024px) {
  .home-banner .type-box {
    padding-top: 90px;
  }
}

.home-banner .type-box h6 {
  margin-bottom: 20px;
  font-size: 1rem;
  line-height: 1.5rem;
  font-weight: 500;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.dark .home-banner .type-box h6 {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

@media (min-width: 1024px) {
  .home-banner .type-box h6 {
    font-size: 1.25rem;
    line-height: 1.75rem;
  }
}

.home-banner .type-box h1 {
  margin-bottom: 20px;
  font-size: 50px;
  font-weight: 700;
  line-height: 1;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.dark .home-banner .type-box h1 {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

@media (min-width: 768px) {
  .home-banner .type-box h1 {
    font-size: 60px;
  }
}

@media (min-width: 1024px) {
  .home-banner .type-box h1 {
    font-size: 80px;
  }
}

.home-banner .type-box h3 {
  margin-bottom: 15px;
  font-size: 1.125rem;
  line-height: 1.75rem;
  font-weight: 500;
  text-transform: uppercase;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.dark .home-banner .type-box h3 {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

@media (min-width: 768px) {
  .home-banner .type-box h3 {
    margin-bottom: 25px;
  }
}

.home-banner .type-box .desc {
  margin-bottom: 20px;
  max-width: 450px;
}

@media (min-width: 768px) {
  .home-banner .type-box .desc {
    margin-bottom: 30px;
  }
}

.home-banner .type-box .btn-bar a {
  position: relative;
  padding-left: 0px;
  font-size: 20px;
  font-weight: 400;
  line-height: 1;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
  transition-duration: 300ms;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.home-banner .type-box .btn-bar a::after {
  content: var(--tw-content);
  position: absolute;
}

.home-banner .type-box .btn-bar a:hover {
  padding-left: 45px;
}

.home-banner .type-box .btn-bar a:hover::after {
  content: var(--tw-content);
  width: 40px;
}

.dark .home-banner .type-box .btn-bar a {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

@media (min-width: 768px) {
  .home-banner .type-box .btn-bar a {
    font-size: 25px;
  }
}

.home-banner .type-box .btn-bar a::after {
  top: 0px;
  left: 0px;
  bottom: 0px;
  margin: auto;
  height: 2px;
  width: 0px;
  background-color: currentColor;
  transition-duration: 300ms;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

/* About
-----------------------------------*/

.about-me {
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 20px;
  max-width: 320px;
}

@media (min-width: 1024px) {
  .about-me {
    margin-bottom: 0px;
  }
}

.about-me .img-in {
  overflow: hidden;
  border-radius: 9999px;
  border-width: 5px;
  --tw-border-opacity: 1;
  border-color: rgb(255 147 1 / var(--tw-border-opacity));
}

.dark .about-me .img-in {
  --tw-border-opacity: 1;
  border-color: rgb(255 255 255 / var(--tw-border-opacity));
}

.about-me .img {
  position: relative;
}

.about-me .info {
  padding-top: 40px;
  text-align: center;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.dark .about-me .info {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.about-me .info h3 {
  font-size: 30px;
  font-weight: 500;
}

.about-me .info p {
  margin: 0px;
  font-size: 16px;
}

.about-me .social-icons {
  position: absolute;
  bottom: -15px;
  left: 0px;
  right: 0px;
}

.about-me .social-icons a {
  position: relative;
  margin-left: 0.25rem;
  margin-right: 0.25rem;
  display: inline-flex;
  height: 35px;
  width: 35px;
  --tw-scale-x: 1;
  --tw-scale-y: 1;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y))
    rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y))
    scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
  align-items: center;
  justify-content: center;
  border-radius: 9999px;
  border-width: 2px;
  --tw-border-opacity: 1;
  border-color: rgb(255 255 255 / var(--tw-border-opacity));
  --tw-bg-opacity: 1;
  background-color: rgb(24 25 29 / var(--tw-bg-opacity));
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
  transition-duration: 300ms;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.about-me .social-icons a:hover {
  --tw-scale-x: 1.1;
  --tw-scale-y: 1.1;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y))
    rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y))
    scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
  --tw-bg-opacity: 1;
  background-color: rgb(255 147 1 / var(--tw-bg-opacity));
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.dark .about-me .social-icons a {
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.about-me .social-icons a:nth-child(5),
.about-me .social-icons a:nth-child(1) {
  top: -25px;
}

.about-me .social-icons a:nth-child(4),
.about-me .social-icons a:nth-child(2) {
  top: -8px;
}

.about-info .title {
  margin-bottom: 30px;
}

.about-info .info-list {
  padding-top: 15px;
}

.about-info .info-list ul {
  margin: 0px;
  list-style-type: none;
  padding: 0px;
}

.about-info .info-list li {
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
}

.about-info .info-list label {
  margin: 0px;
  padding-right: 10px;
  font-weight: 500;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.dark .about-info .info-list label {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

/* Feature Box
-----------------------------------*/

.feature-box-01 {
  position: relative;
  z-index: 1;
  overflow: hidden;
  border-radius: 10px;
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
  padding: 25px;
}

.feature-box-01::before {
  content: var(--tw-content);
  position: absolute;
}

.feature-box-01::after {
  content: var(--tw-content);
  position: absolute;
}

.feature-box-01:hover {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.dark .feature-box-01 {
  --tw-bg-opacity: 1;
  background-color: rgb(24 25 29 / var(--tw-bg-opacity));
}

@media (min-width: 768px) {
  .feature-box-01 {
    padding: 40px;
  }
}

.feature-box-01:before {
  top: -220px;
  left: -220px;
  z-index: -1;
  height: 200px;
  width: 200px;
  border-radius: 0px;
  --tw-bg-opacity: 1;
  background-color: rgb(24 25 29 / var(--tw-bg-opacity));
  transition-property: all;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 500ms;
}

.feature-box-01:after {
  top: -72px;
  left: -40px;
  z-index: -2;
  height: 200px;
  width: 200px;
  border-radius: 50%;
  --tw-bg-opacity: 1;
  background-color: rgb(255 147 1 / var(--tw-bg-opacity));
  transition-property: all;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 500ms;
}

.feature-box-01 .icon {
  display: inline-flex;
  height: 60px;
  align-items: center;
  font-size: 40px;
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.feature-box-01 .feature-content {
  padding-top: 25px;
}

.feature-box-01 h5 {
  margin-bottom: 1rem;
  font-size: 20px;
  font-weight: 500;
  line-height: 1.2;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.dark .feature-box-01 h5 {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.feature-box-01:hover h5 {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.feature-box-01:hover:before {
  top: -72px;
  left: -40px;
  border-radius: 9999px;
}

.feature-box-01:hover:after {
  top: -10%;
  left: -10%;
  height: 120%;
  width: 120%;
  border-radius: 0px;
}

.feature-box-02 {
  display: flex;
  overflow: hidden;
  border-radius: 10px;
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
  padding: 15px;
}

.dark .feature-box-02 {
  --tw-bg-opacity: 1;
  background-color: rgb(24 25 29 / var(--tw-bg-opacity));
}

.feature-box-02 .icon {
  width: 70px;
}

.feature-box-02 .media-body {
  flex: 1 1 0%;
  padding-left: 15px;
}

.feature-box-02 h6 {
  margin-bottom: 0.25rem;
  font-size: 1.125rem;
  line-height: 1.75rem;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.dark .feature-box-02 h6 {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.feature-box-02 p {
  margin: 0px;
  font-size: 0.875rem;
  line-height: 1.25rem;
}

/* testimonial
-----------------------------------*/

.testimonial-01 {
  margin-top: 15px;
  margin-bottom: 25px;
  display: flex;
  overflow: hidden;
  border-radius: 10px;
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
  padding: 35px;
}

.dark .testimonial-01 {
  --tw-bg-opacity: 1;
  background-color: rgb(24 25 29 / var(--tw-bg-opacity));
}

.testimonial-01 .avatar {
  height: 50px;
  width: 50px;
  overflow: hidden;
  border-radius: 9999px;
}

@media (min-width: 768px) {
  .testimonial-01 .avatar {
    height: 100px;
    width: 100px;
  }
}

.testimonial-01 .media-body {
  flex: 1 1 0%;
  padding-left: 25px;
}

.testimonial-01 h6 {
  margin-bottom: 0.25rem;
  margin-top: 1rem;
  font-weight: 500;
  line-height: 1.2;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.dark .testimonial-01 h6 {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.testimonial-01 span {
  font-size: 0.75rem;
  line-height: 1rem;
}

/* Experience
-----------------------------------*/

.resume-box {
  padding-top: 15px;
}

.resume-row {
  border-radius: 15px;
  --tw-bg-opacity: 1;
  background-color: rgb(247 247 255 / var(--tw-bg-opacity));
  padding: 35px;
}

.dark .resume-row {
  --tw-bg-opacity: 1;
  background-color: rgb(20 20 22 / var(--tw-bg-opacity));
}

.resume-row + .resume-row {
  margin-top: 30px;
}

.resume-row h6 {
  margin-bottom: 0.75rem;
  font-size: 1.25rem;
  line-height: 1.75rem;
  font-weight: 500;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.dark .resume-row h6 {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.resume-row .rb-left {
  min-height: 100%;
}

@media (min-width: 768px) {
  .resume-row .rb-left {
    border-left-width: 1px;
    border-color: rgb(255 255 255 / var(--tw-border-opacity));
    --tw-border-opacity: 0.05;
  }

  .dark .resume-row .rb-left {
    border-color: rgb(24 25 29 / var(--tw-border-opacity));
    --tw-border-opacity: 0.05;
  }
}

.resume-row .rb-left h6 {
  margin-bottom: 5px;
}

.resume-row .rb-left label {
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-style: italic;
}

.resume-row .rb-left p {
  margin-top: 5px;
  margin-bottom: 8px;
  line-height: 1.5;
}

.resume-row .rb-left .rb-time {
  display: inline-block;
  border-radius: 3px;
  --tw-bg-opacity: 1;
  background-color: rgb(255 147 1 / var(--tw-bg-opacity));
  padding-left: 10px;
  padding-right: 10px;
  padding-top: 5px;
  padding-bottom: 5px;
  font-size: 0.75rem;
  line-height: 1rem;
  font-weight: 500;
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.skill-lt {
  position: relative;
  padding-left: 80px;
}

.skill-lt span {
  position: absolute;
  left: 0px;
  top: 8px;
  font-size: 30px;
  font-weight: 500;
  line-height: 1;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.dark .skill-lt span {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.skill-lt:not(:first-child) {
  margin-top: 45px;
}

.skill-lt h6 {
  margin-bottom: 10px;
  font-size: 15px;
  font-weight: 400;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.dark .skill-lt h6 {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.skill-lt .skill-bar {
  position: relative;
  background-color: rgb(24 25 29 / var(--tw-bg-opacity));
  --tw-bg-opacity: 0.05;
}

.dark .skill-lt .skill-bar {
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
  --tw-bg-opacity: 0.05;
}

.skill-lt .skill-bar .skill-bar-in {
  position: relative;
  height: 10px;
  width: 80px;
  --tw-bg-opacity: 1;
  background-color: rgb(255 147 1 / var(--tw-bg-opacity));
  transition-property: all;
  transition-duration: 1000ms;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.aducation-box {
  margin-bottom: 10px;
  list-style-type: none;
  border-radius: 10px;
  --tw-bg-opacity: 1;
  background-color: rgb(247 247 255 / var(--tw-bg-opacity));
  padding: 35px;
}

.dark .aducation-box {
  --tw-bg-opacity: 1;
  background-color: rgb(20 20 22 / var(--tw-bg-opacity));
}

@media (min-width: 1024px) {
  .aducation-box {
    margin-bottom: 0px;
  }
}

.aducation-box h6 {
  margin-top: 5px;
  margin-bottom: 5px;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.dark .aducation-box h6 {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.aducation-box li + li {
  margin-top: 25px;
}

/* Portfolio Start
------------------------------*/

.grid-col-3 {
  margin-left: -10px;
  margin-right: -10px;
  display: flex;
  flex-wrap: wrap;
}

.grid-col-3 .grid-item {
  width: 100%;
  flex: 0 0 100%;
  padding: 10px;
}

@media (min-width: 640px) {
  .grid-col-3 .grid-item {
    width: 50%;
    flex: 0 0 50%;
  }
}

@media (min-width: 1024px) {
  .grid-col-3 .grid-item {
    width: 33.333333%;
    flex: 0 0 33.333333333%;
  }
}

.portfolio-filter-01 {
  padding-top: 1rem;
  padding-bottom: 1rem;
}

.portfolio-filter-01 .filter {
  overflow-x: auto;
  padding-bottom: 0.75rem;
}

.portfolio-filter-01 .filter li {
  position: relative;
  margin-right: 2rem;
  cursor: pointer;
  padding-left: 5px;
  padding-right: 5px;
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 400;
  line-height: 1.5;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.portfolio-filter-01 .filter li::after {
  content: var(--tw-content);
  position: absolute;
}

.dark .portfolio-filter-01 .filter li {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

@media (min-width: 768px) {
  .portfolio-filter-01 .filter li {
    font-size: 1rem;
    line-height: 1.5rem;
  }
}

.portfolio-filter-01 .filter li:after {
  left: 0px;
  right: 0px;
  bottom: 0px;
  margin: auto;
  height: 2px;
  width: 0px;
  --tw-bg-opacity: 1;
  background-color: rgb(255 147 1 / var(--tw-bg-opacity));
  transition-duration: 300ms;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.portfolio-filter-01 .filter li.active:after {
  width: 100%;
}

.portfolio-box-01 {
  position: relative;
  overflow: hidden;
  border-radius: 10px;
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
}

.portfolio-box-01 .portfolio-img {
  position: relative;
}

.portfolio-box-01 .portfolio-img img {
  width: 100%;
}

.portfolio-box-01 .portfolio-icon {
  position: absolute;
  bottom: 20px;
  right: 20px;
  opacity: 0;
  transition-duration: 300ms;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.portfolio-box-01 .portfolio-icon a {
  display: inline-flex;
  height: 40px;
  width: 40px;
  align-items: center;
  justify-content: center;
  border-radius: 5px;
  --tw-bg-opacity: 1;
  background-color: rgb(24 25 29 / var(--tw-bg-opacity));
  font-size: 24px;
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.portfolio-box-01 .portfolio-info {
  position: absolute;
  top: 20px;
  left: 20px;
  right: 20px;
  --tw-bg-opacity: 1;
  background-color: rgb(24 25 29 / var(--tw-bg-opacity));
  padding: 20px;
  text-align: center;
  opacity: 0;
  transition-duration: 300ms;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.portfolio-box-01 .portfolio-info h5 {
  margin-bottom: 0.25rem;
  font-size: 22px;
  font-weight: 500;
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.portfolio-box-01 .portfolio-info h5 a {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.portfolio-box-01 .portfolio-info span {
  color: rgb(255 255 255 / var(--tw-text-opacity));
  --tw-text-opacity: 0.6;
}

.portfolio-box-01:hover .portfolio-info {
  opacity: 1;
}

.portfolio-box-01:hover .portfolio-icon {
  opacity: 1;
}
/* Blog Start
------------------------------*/

.blog-grid .blog-img {
  overflow: hidden;
  border-radius: 10px;
}

.blog-grid .blog-img img {
  --tw-scale-x: 1;
  --tw-scale-y: 1;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y))
    rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y))
    scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
  transition-duration: 300ms;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.blog-grid .blog-info {
  padding-top: 15px;
}

.blog-grid .blog-info .meta {
  font-size: 0.75rem;
  line-height: 1rem;
}

.blog-grid .blog-info h6 {
  padding-top: 10px;
  font-size: 20px;
}

@media (min-width: 1024px) {
  .blog-grid .blog-info h6 {
    font-size: 24px;
  }
}

.blog-grid .blog-info a {
  background-image: linear-gradient(to top, var(--tw-gradient-stops));
  --tw-gradient-from: #18191d;
  --tw-gradient-to: rgb(24 25 29 / 0);
  --tw-gradient-stops: var(--tw-gradient-from), var(--tw-gradient-to);
  --tw-gradient-to: #18191d;
  background-repeat: no-repeat;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
  transition-duration: 300ms;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.dark .blog-grid .blog-info a {
  --tw-gradient-from: #fff;
  --tw-gradient-to: rgb(255 255 255 / 0);
  --tw-gradient-stops: var(--tw-gradient-from), var(--tw-gradient-to);
  --tw-gradient-to: #fff;
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.blog-grid .blog-info a {
  background-position: 0% 100%;
  background-size: 0% 1px;
}

.blog-grid:hover .blog-info a {
  background-size: 100% 2px;
}

.blog-grid:hover .blog-img img {
  --tw-scale-x: 1.1;
  --tw-scale-y: 1.1;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y))
    rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y))
    scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
  --tw-grayscale: grayscale(1);
  filter: var(--tw-blur) var(--tw-brightness) var(--tw-contrast)
    var(--tw-grayscale) var(--tw-hue-rotate) var(--tw-invert) var(--tw-saturate)
    var(--tw-sepia) var(--tw-drop-shadow);
}

/* Contact Us
-----------------------------------*/

.contact-info {
  margin-bottom: 20px;
}

@media (min-width: 1024px) {
  .contact-info {
    margin-bottom: 0px;
  }
}

.contact-info h4 {
  margin-bottom: 1rem;
  font-size: 34px;
  line-height: 1.2;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.dark .contact-info h4 {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.contact-info p {
  font-size: 16px;
}

.contact-info ul {
  margin: 0px;
  list-style-type: none;
  padding-top: 30px;
}

.contact-info li {
  position: relative;
  display: flex;
  font-size: 18px;
  font-weight: 500;
  line-height: 1.3;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.dark .contact-info li {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.contact-info li i {
  width: 30px;
  flex: 0 0 30px;
  text-align: center;
  font-size: 22px;
  --tw-text-opacity: 1;
  color: rgb(255 147 1 / var(--tw-text-opacity));
}

.contact-info li span {
  padding-left: 16px;
}

.contact-info li + li {
  padding-top: 20px;
}

.contact-form {
  padding-bottom: 20px;
}

@media (min-width: 1024px) {
  .contact-form {
    padding-bottom: 0px;
  }
}

.contact-form h4 {
  margin-bottom: 20px;
  font-size: 22px;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
}

.dark .contact-form h4 {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.contact-form .form-control {
  width: 100%;
  border-radius: 0.375rem;
  border-width: 1px;
  border-color: rgb(24 25 29 / var(--tw-border-opacity));
  --tw-border-opacity: 0.1;
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
  padding-left: 15px;
  padding-right: 15px;
  padding-top: 12px;
  padding-bottom: 12px;
  font-size: 0.875rem;
  line-height: 1.25rem;
  --tw-text-opacity: 1;
  color: rgb(24 25 29 / var(--tw-text-opacity));
  --tw-shadow: 0 0 #0000;
  --tw-shadow-colored: 0 0 #0000;
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000),
    var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
  outline: 2px solid transparent;
  outline-offset: 2px;
}

.dark .contact-form .form-control {
  border-color: rgb(255 255 255 / var(--tw-border-opacity));
  --tw-border-opacity: 0.05;
  background-color: rgb(55 65 81 / var(--tw-bg-opacity));
  --tw-bg-opacity: 0.2;
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

.contact-form .form-control.invalid {
  --tw-border-opacity: 1 !important;
  border-color: rgb(239 68 68 / var(--tw-border-opacity)) !important;
}

.google-map {
  margin-top: 15px;
  overflow: hidden;
  border-radius: 10px;
}

@media (min-width: 768px) {
  .google-map {
    margin-top: 0px;
  }
}

.google-map iframe {
  --tw-grayscale: grayscale(1);
  filter: var(--tw-blur) var(--tw-brightness) var(--tw-contrast)
    var(--tw-grayscale) var(--tw-hue-rotate) var(--tw-invert) var(--tw-saturate)
    var(--tw-sepia) var(--tw-drop-shadow);
}

/* Popup
------------------------------*/

.px-modal {
  position: relative;
  margin-left: auto;
  margin-right: auto;
  margin-top: 1.25rem;
  margin-bottom: 1.25rem;
  max-width: 800px;
  border-radius: 0.375rem;
  --tw-bg-opacity: 1 !important;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity)) !important;
  padding: 1.25rem;
}

.dark .px-modal {
  --tw-bg-opacity: 1 !important;
  background-color: rgb(24 25 29 / var(--tw-bg-opacity)) !important;
}

.px-modal .mfp-close {
  border-radius: 0.375rem;
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
  opacity: 1;
}

.dark .px-modal .mfp-close {
  --tw-bg-opacity: 1;
  background-color: rgb(35 38 47 / var(--tw-bg-opacity));
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

article h1,
article h2,
article h3,
article h4,
article h5,
article h6 {
  margin-bottom: 1rem;
  --tw-text-opacity: 1;
  color: rgb(0 0 0 / var(--tw-text-opacity));
}

.dark article h1,
.dark article h2,
.dark article h3,
.dark article h4,
.dark article h5,
.dark article h6 {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

article h6 a {
  font-weight: 600;
  text-transform: uppercase;
}

article h2 {
  font-size: 28px;
  font-weight: 600;
}

article p {
  margin-bottom: 1rem;
}

.hover\:text-theme-500:hover {
  --tw-text-opacity: 1;
  color: rgb(255 147 1 / var(--tw-text-opacity));
}

.dark .dark\:border-white {
  --tw-border-opacity: 1;
  border-color: rgb(255 255 255 / var(--tw-border-opacity));
}

.dark .dark\:border-opacity-10 {
  --tw-border-opacity: 0.1;
}

.dark .dark\:bg-white {
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity));
}

.dark .dark\:bg-mode-300 {
  --tw-bg-opacity: 1;
  background-color: rgb(24 25 29 / var(--tw-bg-opacity));
}

.dark .dark\:text-white {
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity));
}

@media (min-width: 640px) {
  .sm\:col-span-6 {
    grid-column: span 6 / span 6;
  }

  .sm\:gap-7 {
    gap: 1.75rem;
  }
}

@media (min-width: 768px) {
  .md\:col-span-4 {
    grid-column: span 4 / span 4;
  }

  .md\:col-span-8 {
    grid-column: span 8 / span 8;
  }

  .md\:col-span-6 {
    grid-column: span 6 / span 6;
  }

  .md\:justify-start {
    justify-content: flex-start;
  }

  .md\:pb-0 {
    padding-bottom: 0px;
  }

  .md\:text-right {
    text-align: right;
  }
}

@media (min-width: 1024px) {
  .lg\:col-span-8 {
    grid-column: span 8 / span 8;
  }

  .lg\:col-span-4 {
    grid-column: span 4 / span 4;
  }

  .lg\:col-span-5 {
    grid-column: span 5 / span 5;
  }

  .lg\:col-span-7 {
    grid-column: span 7 / span 7;
  }

  .lg\:flex {
    display: flex;
  }

  .lg\:hidden {
    display: none;
  }

  .lg\:pl-16 {
    padding-left: 4rem;
  }
}

@media (min-width: 1280px) {
  .xl\:col-span-3 {
    grid-column: span 3 / span 3;
  }

  .xl\:col-span-9 {
    grid-column: span 9 / span 9;
  }

  .xl\:col-span-4 {
    grid-column: span 4 / span 4;
  }

  .xl\:col-span-8 {
    grid-column: span 8 / span 8;
  }
}
</style>
