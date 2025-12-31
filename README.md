<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <script
      src="https://kit.fontawesome.com/6487f0a3d4.js"
      crossorigin="anonymous"
    ></script>
    <script src="index.js"></script>
    <title>Project 1 </title>
  </head>
  <body>
    <section id="landing">
      <nav>
        <div class="row nav__row">
          <div class="nav__logo">
            <img
              class="nav__logo--img"
              src="https://module-2-fp-example-website.vercel.app/assets/logo.2c489fc453a1783cbadacf914efa3df6.svg"
              alt="LOGO"
            />
            <div class="nav__logo--title">Treact</div>
          </div>
          <div class="nav__links">
            <a href="#" class="nav__link">About</a>
            <a href="#" class="nav__link">Blog</a>
            <a href="#" class="nav__link">Pricing</a>
            <a href="#" class="nav__link">Contact Us</a>
            <a href="#" class="nav__link login">Login</a>
            <a href="#" class="nav__link nav__link--primary">Sign Up</a>
          </div>
          <button class="btn__menu" onclick="openMenu()">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="btn__menu--svg"
            >
              <line x1="3" y1="12" x2="21" y2="12"></line>
              <line x1="3" y1="6" x2="21" y2="6"></line>
              <line x1="3" y1="18" x2="21" y2="18"></line>
            </svg>
          </button>
        </div>
      </nav>
      <div class="menu">
        <button class="btn__menu btn__menu--close" onclick="closeMenu()">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="light___StyledCloseIcon-lj69nl-14 fASujC"
          >
            <line x1="18" y1="6" x2="6" y2="18"></line>
            <line x1="6" y1="6" x2="18" y2="18"></line>
          </svg>
        </button>
        <div class="menu__links">
          <a href="#about" class="menu__link" onclick="closeMenu()">About</a>
          <a href="#blog" class="menu__link" onclick="closeMenu()">Blog</a>
          <a href="#pricing" class="menu__link" onclick="closeMenu()"
            >Pricing</a
          >
          <a href="#contact__us" class="menu__link" onclick="closeMenu()"
            >Contact Us</a
          >
          <a href="#login" class="menu__link" onclick="closeMenu()">Login</a>
          <a
            href="#signup"
            class="menu__link menu__link--primary"
            onclick="closeMenu()"
            >Sign up</a
          >
        </div>
      </div>
      <header>
        <div class="container">
          <div class="row">
            <div class="header__description">
              <h1>
                Beautiful React Templates <span class="purple">for you.</span>
              </h1>
              <p class="header__description--para">
                Our templates are easy to setup, understand and customize. Fully
                modular components with a variety of pages and components.
              </p>
              <div class="header__email">
                <input
                  type="text"
                  class="header__email--input"
                  placeholder="Your E-mail Address"
                />
                <button class="header__email--btn">Get Started</button>
              </div>
              <p class="header__customers--title">OUR TRUSTED CUSTOMERS</p>
              <img
                src="https://module-2-fp-example-website.vercel.app/assets/customers-logo-strip.680ac7c2e8ae28161d2c.png"
                class="header__customers"
              />
            </div>
            <figure class="header__img--wrapper">
              <img
                src="https://module-2-fp-example-website.vercel.app/assets/design-illustration-2.6da6a00b20c07c4a9b65d1870679e1b8.svg"
                class="header__img"
              />
            </figure>
          </div>
        </div>
      </header>
    </section>
    <main>
      <section id="features">
        <div class="container">
          <div class="row__narrow">
            <h4 class="section__tag">FEATURES</h4>
            <h2 class="section__title">
              We Have Amazing <span class="purple">Service.</span>
            </h2>
            <div class="section__para">
              As a team we focus on providing the best service for our customers. While
                we work hard to achieve this, we also like to have fun.
            </div>
            <div class="features">
              <div class="feature">
                <div class="feature__row">
                  <figure class="feature__img--wrapper">
                    <img
                      src="https://module-2-fp-example-website.vercel.app/assets/shield-icon.daefe14b320b14fbd9cbd18908ac93ec.svg"
                      class="feature__img"
                    />
                  </figure>
                  <div class="feature__text">
                    <h2 class="feature__title">Secure</h2>
                    <p class="feature__para">
                      Our donors are our biggest priority. We ensure that all of our
                        systems are secure and up to date.
                    </p>
                  </div>
                </div>
              </div>
              <div class="feature">
                <div class="feature__row">
                  <figure class="feature__img--wrapper">
                    <img
                      src="https://module-2-fp-example-website.vercel.app/assets/support-icon.f9253ffa8cb6ffde5bbaa05eb5136375.svg"
                      class="feature__img"
                    />
                  </figure>
                  <div class="feature__text">
                    <h2 class="feature__title">24/7 Support</h2>
                    <p class="feature__para">
                      The support team is available 24/7 to assist you with any issues
                      you may have.
                    </p>
                  </div>
                </div>
              </div>
              <div class="feature">
                <div class="feature__row">
                  <figure class="feature__img--wrapper">
                    <img
                      src="https://module-2-fp-example-website.vercel.app/assets/reliable-icon.1367510a8f0a1bec76dc425d25f92f43.svg"
                      class="feature__img"
                    />
                  </figure>
                  <div class="feature__text">
                    <h2 class="feature__title">Customizable</h2>
                    <p class="feature__para">
                      Our templates are easy to customize to fit your needs. Change
                        colors, fonts, layouts, and more.
                    </p>
                  </div>
                </div>
              </div>
              <div class="feature">
                <div class="feature__row">
                  <figure class="feature__img--wrapper">
                    <img
                      src="/assets/reliable-icon.1367510a8f0a1bec76dc425d25f92f43.svg"
                      class="feature__img"
                    />
                  </figure>
                  <div class="feature__text">
                    <h2 class="feature__title">Reliable</h2>
                    <p class="feature__para">
                      Our services are reliable and always available when you need them.
                    </p>
                  </div>
                </div>
              </div>
              <div class="feature">
                <div class="feature__row">
                  <figure class="feature__img--wrapper">
                    <img
                      src="https://module-2-fp-example-website.vercel.app/assets/fast-icon.dbb971a73d4805d2fc3bcdacdb55beba.svg"
                      class="feature__img"
                    />
                  </figure>
                  <div class="feature__text">
                    <h2 class="feature__title">Fast</h2>
                    <p class="feature__para">
                       Speed is our priority. We ensure that our services are fast and
                      efficient.
                    </p>
                  </div>
                </div>
              </div>
              <div class="feature">
                <div class="feature__row">
                  <figure class="feature__img--wrapper">
                    <img
                      src="https://module-2-fp-example-website.vercel.app/assets/simple-icon.673b7e1750b2a4ef32907fc164828d00.svg"
                      class="feature__img"
                    />
                  </figure>
                  <div class="feature__text">
                    <h2 class="feature__title">Easy</h2>
                    <p class="feature__para">
                      Our services are easy to use and understand. We provide clear
                      instructions and support.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section id="quality">
        <div class="container">
          <div class="row">
            <div class="quality__description">
              <div class="section__tag">QUALITY WORK</div>
              <h2 class="section__title">
                Designed & Developed by
                <span class="purple">Profressionals.</span>
              </h2>
              <p class="section__para">
                 Our team of professionals are dedicated to providing the best quality
                work for our customers. We take pride in our work and strive to exceed
                expectations.
              </p>
              <button class="btn">Learn More</button>
            </div>
            <figure class="quality__img--wrapper">
              <img
                src="https://module-2-fp-example-website.vercel.app/assets/hero-screenshot-1.40a097b525c2f8c9808e.png"
                class="quality__img"
              />
              <svg viewBox="0 0 1280 1280" class="quality__grid">
                <path
                  d="M55 33.5C44.5 37 35 47.6 32.8 58.3c-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM183 33.5c-15.1 5-25.3 21.6-22.2 36.2 2.5 11.9 13.6 23 25.4 25.5 19.4 4.1 39.5-14.2 37.5-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM311 33.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM439 33.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM567 33.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM695 33.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM823 33.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM951 33.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM1079 33.5c-10.5 3.5-20 14.1-22.2 24.8-2.5 11.7 3.2 24.4 14.2 31.9 10.7 7.4 22.9 7.5 33.7.3 17.7-11.8 20.1-33.8 5.3-48.5-8.5-8.6-20.7-11.9-31-8.5zM1207 33.5c-10.5 3.5-20 14.1-22.2 24.8-2.5 11.7 3.2 24.4 14.2 31.9 10.7 7.4 22.9 7.5 33.7.3 17.7-11.8 20.1-33.8 5.3-48.5-8.5-8.6-20.7-11.9-31-8.5zM55 161.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM183 161.5c-15.1 5-25.3 21.6-22.2 36.2 2.5 11.9 13.6 23 25.4 25.5 19.4 4.1 39.5-14.2 37.5-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM311 161.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM439 161.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM567 161.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM695 161.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM823 161.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM951 161.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM1079 161.5c-10.5 3.5-20 14.1-22.2 24.8-2.5 11.7 3.2 24.4 14.2 31.9 10.7 7.4 22.9 7.5 33.7.3 17.7-11.8 20.1-33.8 5.3-48.5-8.5-8.6-20.7-11.9-31-8.5zM1207 161.5c-10.5 3.5-20 14.1-22.2 24.8-2.5 11.7 3.2 24.4 14.2 31.9 10.7 7.4 22.9 7.5 33.7.3 17.7-11.8 20.1-33.8 5.3-48.5-8.5-8.6-20.7-11.9-31-8.5zM55 289.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM183 289.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM311 289.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM439 289.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM567 289.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM695 289.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM823 289.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM951 289.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM1079 289.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM1207 289.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM55 417.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM183 417.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM311 417.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM439 417.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM567 417.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM695 417.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM823 417.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM951 417.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM1079 417.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM1207 417.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM55 545.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM183 545.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM311 545.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM439 545.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM567 545.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM695 545.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM823 545.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM951 545.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM1079 545.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM1207 545.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM55 673.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM183 673.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM311 673.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM439 673.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM567 673.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM695 673.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM823 673.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM951 673.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM1079 673.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM1207 673.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM55 801.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM183 801.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM311 801.5c-10.5 3.5-20 14.1-22.2 24.8-2.5 11.7 3.2 24.4 14.2 31.9 10.7 7.4 22.9 7.5 33.7.3 17.7-11.8 20.1-33.8 5.3-48.5-8.5-8.6-20.7-11.9-31-8.5zM439 801.5c-10.5 3.5-20 14.1-22.2 24.8-2.5 11.7 3.2 24.4 14.2 31.9 10.7 7.4 22.9 7.5 33.7.3 17.7-11.8 20.1-33.8 5.3-48.5-8.5-8.6-20.7-11.9-31-8.5zM567 801.5c-15.1 5-25.3 21.6-22.2 36.2 2.5 11.9 13.6 23 25.5 25.5 19.3 4.1 39.4-14.2 37.4-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM695 801.5c-15.1 5-25.3 21.6-22.2 36.2 2.5 11.9 13.6 23 25.5 25.5 19.3 4.1 39.4-14.2 37.4-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM823 801.5c-15.1 5-25.3 21.6-22.2 36.2 2.5 11.9 13.6 23 25.5 25.5 19.3 4.1 39.4-14.2 37.4-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM951 801.5c-15.1 5-25.3 21.6-22.2 36.2 2.5 11.9 13.6 23 25.5 25.5 19.3 4.1 39.4-14.2 37.4-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM1079 801.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM1207 801.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM55 929.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM183 929.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM311 929.5c-10.5 3.5-20 14.1-22.2 24.8-2.5 11.7 3.2 24.4 14.2 31.9 10.7 7.4 22.9 7.5 33.7.3 17.7-11.8 20.1-33.8 5.3-48.5-8.5-8.6-20.7-11.9-31-8.5zM439 929.5c-10.5 3.5-20 14.1-22.2 24.8-2.5 11.7 3.2 24.4 14.2 31.9 10.7 7.4 22.9 7.5 33.7.3 17.7-11.8 20.1-33.8 5.3-48.5-8.5-8.6-20.7-11.9-31-8.5zM567 929.5c-15.1 5-25.3 21.6-22.2 36.2 2.5 11.9 13.6 23 25.5 25.5 19.3 4.1 39.4-14.2 37.4-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM695 929.5c-15.1 5-25.3 21.6-22.2 36.2 2.5 11.9 13.6 23 25.5 25.5 19.3 4.1 39.4-14.2 37.4-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM823 929.5c-15.1 5-25.3 21.6-22.2 36.2 2.5 11.9 13.6 23 25.5 25.5 19.3 4.1 39.4-14.2 37.4-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM951 929.5c-15.1 5-25.3 21.6-22.2 36.2 2.5 11.9 13.6 23 25.5 25.5 19.3 4.1 39.4-14.2 37.4-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM1079 929.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM1207 929.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM55 1057.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM183 1057.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM311 1057.5c-10.5 3.5-20 14.1-22.2 24.8-2.5 11.7 3.2 24.4 14.2 31.9 10.7 7.4 22.9 7.5 33.7.3 17.7-11.8 20.1-33.8 5.3-48.5-8.5-8.6-20.7-11.9-31-8.5zM439 1057.5c-10.5 3.5-20 14.1-22.2 24.8-2.5 11.7 3.2 24.4 14.2 31.9 10.7 7.4 22.9 7.5 33.7.3 17.7-11.8 20.1-33.8 5.3-48.5-8.5-8.6-20.7-11.9-31-8.5zM567 1057.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM695 1057.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM823 1057.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM951 1057.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM1079 1057.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM1207 1057.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM55 1185.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM183 1185.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM311 1185.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM439 1185.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM567 1185.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM695 1185.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM823 1185.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM951 1185.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM1079 1185.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM1207 1185.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6z"
                ></path>
              </svg>
            </figure>
          </div>
        </div>
      </section>
      <section id="steps">
        <div class="container">
          <div class="row">
            <figure class="steps__img--wrapper">
              <img
                src="https://module-2-fp-example-website.vercel.app/assets/hero-screenshot-2.241aac1fbc66db29d873.png"
                class="steps__img"
                alt="Dashboard Screenshot"
              />
              <svg
                viewBox="0 0 1280 1280"
                class="steps__grid"
                xmlns="http://www.w3.org/2000/svg"
              >
                <defs>
                  <path
                    id="line-of-balls"
                    d="M55 33.5C44.5 37 35 47.6 32.8 58.3c-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM183 33.5c-15.1 5-25.3 21.6-22.2 36.2 2.5 11.9 13.6 23 25.4 25.5 19.4 4.1 39.5-14.2 37.5-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM311 33.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM439 33.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM567 33.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM695 33.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM823 33.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM951 33.5c-10.5 3.5-20 14.1-22.2 24.8-4.3 20.6 16.3 41.2 36.9 36.9 15.5-3.2 27.5-19 26-33.9-1.1-10.5-9-21.3-19-26.2-6.1-2.9-15.5-3.6-21.7-1.6zM1079 33.5c-10.5 3.5-20 14.1-22.2 24.8-2.5 11.7 3.2 24.4 14.2 31.9 10.7 7.4 22.9 7.5 33.7.3 17.7-11.8 20.1-33.8 5.3-48.5-8.5-8.6-20.7-11.9-31-8.5zM1207 33.5c-10.5 3.5-20 14.1-22.2 24.8-2.5 11.7 3.2 24.4 14.2 31.9 10.7 7.4 22.9 7.5 33.7.3 17.7-11.8 20.1-33.8 5.3-48.5-8.5-8.6-20.7-11.9-31-8.5z"
                  />
                </defs>

                <!-- Repeat the line 10 times with vertical spacing -->
                <g fill="rgba(100, 21, 255, 0.15)">
                  <use href="#line-of-balls" transform="translate(0, 0)" />
                  <use href="#line-of-balls" transform="translate(0, 100)" />
                  <use href="#line-of-balls" transform="translate(0, 200)" />
                  <use href="#line-of-balls" transform="translate(0, 300)" />
                  <use href="#line-of-balls" transform="translate(0, 400)" />
                  <use href="#line-of-balls" transform="translate(0, 500)" />
                  <use href="#line-of-balls" transform="translate(0, 600)" />
                  <use href="#line-of-balls" transform="translate(0, 700)" />
                  <use href="#line-of-balls" transform="translate(0, 800)" />
                  <use href="#line-of-balls" transform="translate(0, 900)" />
                </g>
              </svg>
            </figure>
            <div class="steps__description">
              <div class="section__tag">STEPS</div>
              <h2 class="section__title">
                Easy to <span class="purple">Get Started.</span>
              </h2>
              <div class="steps__list">
                <div class="step">
                  <div class="step__number">01</div>
                  <div class="step__description">
                    <div class="step__title">Register</div>
                    <p class="step__para">
                      Create an account with us using Google or Facebook.
                    </p>
                  </div>
                </div>
                <div class="step">
                  <div class="step__number">02</div>
                  <div class="step__description">
                    <div class="step__title">Download</div>
                    <p class="step__para">
                      Browse and Download the template that you like from the
                      marketplace.
                    </p>
                  </div>
                </div>
                <div class="step">
                  <div class="step__number">03</div>
                  <div class="step__description">
                    <div class="step__title">Run</div>
                    <p class="step__para">
                      Follow the instructions to setup and customize the
                      template to your needs.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section id="values">
        <div class="container">
          <div class="row">
            <div class="values__description">
              <div class="section__tag">VALUES</div>
              <h2 class="section__title">
                We Always Abide by Our <span class="purple">Principles.</span>
              </h2>
              <div class="section__para">
               our values define who we are and what we do. They guide our
                actions and decisions, and help us to create a positive impact
              </div>
              <div class="values__list">
                <div class="value">
                  <div class="value__title">
                    <figure class="value__img--wrapper">
                      <!-- TO GET THIS ICON GO TO https://feathericons.com -->
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="24"
                        height="24"
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke="rgba(39, 103, 73, 1)"
                        stroke-width="2"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        class="value__img"
                      >
                        <line x1="12" y1="1" x2="12" y2="23"></line>
                        <path
                          d="M17 5H9.5a3.5 3.5 0 0 0 0 7h5a3.5 3.5 0 0 1 0 7H6"
                        ></path>
                      </svg>
                    </figure>
                    <div class="value__name">Affordable</div>
                  </div>
                  <div class="value__para">
                    We promise to offer you the best rate we can - at par with
                    the industry standard.
                  </div>
                </div>
                <div class="value">
                  <div class="value__title">
                    <figure class="value__img--wrapper">
                      <!-- TO GET THIS ICON GO TO https://feathericons.com -->
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="24"
                        height="24"
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke="rgba(155, 44, 44, 1)"
                        stroke-width="2"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        class="value__img"
                      >
                        <rect
                          x="2"
                          y="7"
                          width="20"
                          height="14"
                          rx="2"
                          ry="2"
                        ></rect>
                        <path
                          d="M16 21V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v16"
                        ></path>
                      </svg>
                    </figure>
                    <div class="value__name">Professionalism</div>
                  </div>
                  <div class="value__para">
                    We assure you that our templates are designed and created by
                    professional designers.
                  </div>
                </div>
              </div>
              <button class="btn">Learn More</button>
            </div>
            <img
              class="values__img"
              src="https://module-2-fp-example-website.vercel.app/assets/prototype-illustration.21bc4b3f612a2f257c3d361067582485.svg"
            />
          </div>
        </div>
      </section>
      <section id="pricing">
        <div class="container">
          <div class="row">
            <div class="section__tag">pricing</div>
            <h2 class="section__title">
              Reasonable &amp; Flexible <span class="purple">Plans.</span>
            </h2>
            <p class="section__para">
              Choose a pricing plan that fits your needs. You can upgrade,
                downgrade, or cancel anytime.
            </p>
            <div class="plans">
              <div class="plan">
                <div class="plan__stripe"></div>
                <div class="plan__top">
                  <div class="plan__name">PERSONAL</div>
                  <div class="plan__price">$17.99</div>
                  <div class="plan__duration">MONTHLY</div>
                </div>
                <div class="plan__middle">
                  <div class="plan__target">For Individuals</div>
                  <p class="plan__feature">30 Templates</p>
                  <p class="plan__feature">7 Landing Pages</p>
                  <p class="plan__feature">12 Internal Pages</p>
                  <p class="plan__feature">Basic Assistance</p>
                </div>
                <div class="plan__bottom">
                  <button class="plan__button">buy now</button>
                </div>
              </div>
              <div class="plan">
                <div class="plan__stripe"></div>
                <div class="plan__top">
                  <div class="plan__name">BUSINESS</div>
                  <div class="plan__price">$37.99</div>
                  <div class="plan__duration">MONTHLY</div>
                </div>
                <div class="plan__middle">
                  <div class="plan__target">For Small Businesses</div>
                  <p class="plan__feature">60 Templates</p>
                  <p class="plan__feature">15 Landing Pages</p>
                  <p class="plan__feature">22 Internal Pages</p>
                  <p class="plan__feature">Priority Assistance</p>
                </div>
                <div class="plan__bottom">
                  <button class="plan__button">buy now</button>
                </div>
              </div>
              <div class="plan">
                <div class="plan__stripe"></div>
                <div class="plan__top">
                  <div class="plan__name">ENTERPRISE</div>
                  <div class="plan__price">$57.99</div>
                  <div class="plan__duration">MONTHLY</div>
                </div>
                <div class="plan__middle">
                  <div class="plan__target">For Large Companies</div>
                  <p class="plan__feature">90 Templates</p>
                  <p class="plan__feature">27 Landing Pages</p>
                  <p class="plan__feature">37 Internal Pages</p>
                  <p class="plan__feature">Personal Assistance</p>
                </div>
                <div class="plan__bottom">
                  <button class="plan__button">buy now</button>
                </div>
              </div>
              <svg
                width="600"
                height="600"
                viewBox="0 0 600 600"
                xmlns="http://www.w3.org/2000/svg"
                class="plans__blob"
              >
                <g transform="translate(300,300)">
                  <path
                    d="M82,-98.3C129.8,-57.7,208.2,-54.1,229.6,-26.6C251.1,1,215.6,52.5,172.9,74.9C130.2,97.2,80.3,90.4,37.8,107.5C-4.8,124.7,-40,165.7,-63.3,162.3C-86.5,158.8,-97.8,110.9,-109.3,72.2C-120.7,33.5,-132.2,4.1,-140.1,-37.4C-147.9,-79,-152.1,-132.6,-128.1,-177.3C-104.1,-222.1,-52.1,-258,-17.5,-237.2C17.1,-216.4,34.3,-138.9,82,-98.3Z"
                    fill="#FFB4BC"
                  ></path>
                </g>
              </svg>
            </div>
          </div>
        </div>
      </section>
      <section id="testimonials">
        <div class="container">
          <div class="row">
            <img
              src="https://module-2-fp-example-website.vercel.app/assets/love-illustration.c759090fa833369ad6ffb6eb19cacb3e.svg"
              alt=""
              class="testimonials__img"
            />
            <div class="testimonials__description">
              <div class="section__tag">testimonials</div>
              <h2 class="section__title">
                Our Clients <span class="purple">Love Us.</span>
              </h2>
              <p class="section__para">
                Hear what our satisfied customers have to say about our
                templates and services.
              </p>
              <div class="testimonial">
                <div class="testimonial__rating">
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                </div>
                <h3 class="testimonial__title">Amazing User Experience</h3>
                <p class="testimonial__para">
                  "The templates provided are not only visually stunning but
                    also incredibly user-friendly. Setting up my website was a
                    breeze!"
                </p>
                <div class="testimonial__bottom">
                  <div class="testimonial__profile">
                    <img
                      src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=3.25&amp;w=512&amp;h=512&amp;q=80"
                      class="testimonial__img"
                    />
                    <div class="testimonial__details">
                      <div class="testimonial__name">Charlotte Hale</div>
                      <div class="testimonial__role">Director, Delos Inc.</div>
                    </div>
                  </div>
                  <div class="testimonial__buttons">
                    <button class="testimonial__button">
                      <svg
                        fill="none"
                        stroke="rgb(100,21,255)"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="3"
                        viewBox="0 0 24 24"
                      >
                        <path d="M10 19l-7-7m0 0l7-7m-7 7h18"></path>
                      </svg>
                    </button>
                    <div class="divider"></div>
                    <button class="testimonial__button">
                      <svg
                        fill="none"
                        stroke="rgb(100,21,255)"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="3"
                        viewBox="0 0 24 24"
                      >
                        <path d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
                      </svg>
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section id="start">
        <div class="container">
          <div class="row">
            <svg viewBox="0 0 600 600" class="start__blob--1">
              <g transform="translate(300,300)">
                <path
                  d="M153.6,-239C199.1,-209.8,236,-167.2,258.4,-118C280.9,-68.9,288.9,-13.1,281.2,40.4C273.5,93.9,250.1,145.2,214.7,186.1C179.3,226.9,131.9,257.4,80,272.6C28.2,287.8,-28.2,287.8,-80,272.6C-131.9,257.4,-179.3,226.9,-214.7,186.1C-250.1,145.2,-273.5,93.9,-281.2,40.4C-288.9,-13.1,-280.9,-68.9,-258.4,-118C-236,-167.2,-199.1,-209.8,-153.6,-239C-108.1,-268.3,-54.1,-284.1,0,-284.1C54.1,-284.1,108.1,-268.3,153.6,-239Z"
                  fill="rgb(80,17,204)"
                ></path>
              </g>
            </svg>
            <svg viewBox="0 0 600 600" class="start__blob--2">
              <g transform="translate(300,300)">
                <path
                  d="M153.6,-239C199.1,-209.8,236,-167.2,258.4,-118C280.9,-68.9,288.9,-13.1,281.2,40.4C273.5,93.9,250.1,145.2,214.7,186.1C179.3,226.9,131.9,257.4,80,272.6C28.2,287.8,-28.2,287.8,-80,272.6C-131.9,257.4,-179.3,226.9,-214.7,186.1C-250.1,145.2,-273.5,93.9,-281.2,40.4C-288.9,-13.1,-280.9,-68.9,-258.4,-118C-236,-167.2,-199.1,-209.8,-153.6,-239C-108.1,-268.3,-54.1,-284.1,0,-284.1C54.1,-284.1,108.1,-268.3,153.6,-239Z"
                  fill="rgb(80,17,204)"
                ></path>
              </g>
            </svg>
            <div class="start__container">
              <div class="start__row">
                <div class="start__title">
                  Developers all over the world are happily using Treact.
                </div>
                <div class="start__buttons">
                  <button class="start__button btn">Get Started</button>
                  <button class="start__button btn">Contact Us</button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
    <footer>
      <svg viewBox="0 0 600 600" class="footer__blob--1">
        <g transform="translate(300,300)">
          <path
            d="M153.6,-239C199.1,-209.8,236,-167.2,258.4,-118C280.9,-68.9,288.9,-13.1,281.2,40.4C273.5,93.9,250.1,145.2,214.7,186.1C179.3,226.9,131.9,257.4,80,272.6C28.2,287.8,-28.2,287.8,-80,272.6C-131.9,257.4,-179.3,226.9,-214.7,186.1C-250.1,145.2,-273.5,93.9,-281.2,40.4C-288.9,-13.1,-280.9,-68.9,-258.4,-118C-236,-167.2,-199.1,-209.8,-153.6,-239C-108.1,-268.3,-54.1,-284.1,0,-284.1C54.1,-284.1,108.1,-268.3,153.6,-239Z"
            fill="rgba(80,17,204)"
          ></path>
        </g>
      </svg>
      <svg viewBox="0 0 600 600" class="footer__blob--2">
        <g transform="translate(300,300)">
          <path
            d="M153.6,-239C199.1,-209.8,236,-167.2,258.4,-118C280.9,-68.9,288.9,-13.1,281.2,40.4C273.5,93.9,250.1,145.2,214.7,186.1C179.3,226.9,131.9,257.4,80,272.6C28.2,287.8,-28.2,287.8,-80,272.6C-131.9,257.4,-179.3,226.9,-214.7,186.1C-250.1,145.2,-273.5,93.9,-281.2,40.4C-288.9,-13.1,-280.9,-68.9,-258.4,-118C-236,-167.2,-199.1,-209.8,-153.6,-239C-108.1,-268.3,-54.1,-284.1,0,-284.1C54.1,-284.1,108.1,-268.3,153.6,-239Z"
            fill="rgba(80,17,204)"
          ></path>
        </g>
      </svg>
      <div class="row footer__row">
        <div class="footer__columns">
          <div class="footer__column">
            <div class="footer__column--title">MAIN</div>
            <a class="footer__column--link">Blog</a>
            <a class="footer__column--link">FAQs</a>
            <a class="footer__column--link">Support</a>
            <a class="footer__column--link">About Us</a>
          </div>
          <div class="footer__column">
            <div class="footer__column--title">PRODUCT</div>
            <a class="footer__column--link">Log In</a>
            <a class="footer__column--link">Personal</a>
            <a class="footer__column--link">Business</a>
            <a class="footer__column--link">Team</a>
          </div>
          <div class="footer__column">
            <div class="footer__column--title">PRESS</div>
            <a class="footer__column--link">Logos</a>
            <a class="footer__column--link">Events</a>
            <a class="footer__column--link">Stories</a>
            <a class="footer__column--link">Office</a>
          </div>
          <div class="footer__column">
            <div class="footer__column--title">TEAM</div>
            <a class="footer__column--link">Career</a>
            <a class="footer__column--link">Founders</a>
            <a class="footer__column--link">Culture</a>
            <a class="footer__column--link">Onboarding</a>
          </div>
          <div class="footer__column">
            <div class="footer__column--title">LEGAL</div>
            <a class="footer__column--link">GDPR</a>
            <a class="footer__column--link">Privacy Policy</a>
            <a class="footer__column--link">Terms of Service</a>
            <a class="footer__column--link">Disclaimer</a>
          </div>
        </div>
        <div class="footer__divider"></div>
        <div class="footer__bottom">
          <div class="footer__logo">
            <img
              src="https://module-2-fp-example-website.vercel.app/assets/logo-light.d9a5d1b5be5ea077b26864fdfc2e96a4.svg"
              alt=""
              class="footer__logo--img"
            />
            <h5 class="footer__logo--text">Treact Inc.</h5>
          </div>
          <div class="footer__copyright">
            © 2018 Treact Inc. All Rights Reserved.
          </div>
          <div class="footer__socials">
            <a class="footer__social--link">
              <svg fill="currentColor" viewBox="0 0 24 24">
                <path
                  d="M14 13.5h2.5l1-4H14v-2c0-1.03 0-2 2-2h1.5V2.14c-.326-.043-1.557-.14-2.857-.14C11.928 2 10 3.657 10 6.7v2.8H7v4h3V22h4v-8.5z"
                ></path>
              </svg>
            </a>
            <a class="footer__social--link">
              <svg fill="currentColor" viewBox="0 0 24 24">
                <path
                  d="M22.162 5.656a8.384 8.384 0 01-2.402.658A4.196 4.196 0 0021.6 4c-.82.488-1.719.83-2.656 1.015a4.182 4.182 0 00-7.126 3.814 11.874 11.874 0 01-8.62-4.37 4.168 4.168 0 00-.566 2.103c0 1.45.738 2.731 1.86 3.481a4.168 4.168 0 01-1.894-.523v.052a4.185 4.185 0 003.355 4.101 4.21 4.21 0 01-1.89.072A4.185 4.185 0 007.97 16.65a8.394 8.394 0 01-6.191 1.732 11.83 11.83 0 006.41 1.88c7.693 0 11.9-6.373 11.9-11.9 0-.18-.005-.362-.013-.54a8.496 8.496 0 002.087-2.165z"
                ></path>
              </svg>
            </a>
            <a class="footer__social--link">
              <svg fill="currentColor" viewBox="0 0 24 24">
                <path
                  d="M21.543 6.498C22 8.28 22 12 22 12s0 3.72-.457 5.502c-.254.985-.997 1.76-1.938 2.022C17.896 20 12 20 12 20s-5.893 0-7.605-.476c-.945-.266-1.687-1.04-1.938-2.022C2 15.72 2 12 2 12s0-3.72.457-5.502c.254-.985.997-1.76 1.938-2.022C6.107 4 12 4 12 4s5.896 0 7.605.476c.945.266 1.687 1.04 1.938 2.022zM10 15.5l6-3.5-6-3.5v7z"
                ></path>
              </svg>
            </a>
          </div>
        </div>
      </div>
    </footer>
  </body>
</html>


@import url("https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap");
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Inter", sans-serif;
  color: #243e63;
}
html {
  scroll-behavior: smooth;
}
body {
  max-width: 100vw;
  overflow-x: hidden;
}
.row {
  width: 100%;
  max-width: 1280px;
  margin: 0 auto;
}
.row__narrow {
  width: 100%;
  max-width: 1024px;
  margin: 0 auto;
}
.container {
  padding: 96px 0;
}
a {
  display: inline;
  text-decoration: none;
}
img {
  width: 100%;
}
h1 {
  font-size: 48px;
  color: #1a202c;
  line-height: 1.25;
}
.purple {
  color: #6415ff;
}
p {
  font-size: 18px;
  line-height: 1.5;
}
.section__tag {
  font-size: 16px;
  color: #6415ff;
  letter-spacing: 1.6px;
  font-weight: 700;
  text-transform: uppercase;
}
.section__title {
  font-size: 48px;
  font-weight: 900;
  color: rgb(36, 62, 99);
  line-height: 1.5;
  margin: 16px 0;
  letter-spacing: 0.025em;
}
#features .section__title,
#pricing .section__title {
  text-align: center;
}
.section__para {
  font-size: 18px;
  font-weight: 500;
  color: #7c8ba1;
  line-height: 1.625;
}
.btn {
  background-color: #6415ff;
  padding: 12px 32px;
  border: none;
  border-radius: 500px;
  font-size: 14px;
  color: #fff;
  font-weight: bold;
  transition: all 300ms;
}
.btn:hover {
  background-color: rgba(80, 17, 204);
}
button {
  cursor: pointer;
  border: none;
}

/* NAVIGATION */

nav {
  padding-top: 32px;
  display: flex;
}
.nav__logo {
  display: flex;
  align-items: center;
  margin: 8px 0;
  padding-bottom: 4px;
}
.nav__logo--title {
  font-weight: 900;
  font-size: 24px;
  margin-left: 12px;
  padding-bottom: 2px;
  letter-spacing: 0.6px;
}
.nav__logo--img {
  height: 40px;
  width: 40px;
}
.nav__row {
  display: flex;
  justify-content: space-between;
}
.nav__container {
  width: 100%;
  max-width: 1200px;
  padding: 0 24px;
  display: flex;
  justify-content: space-between;
  margin: 0 auto;
}
.nav__links {
  display: flex;
  align-items: center;
  padding-bottom: 2px;
}
.nav__link {
  margin: 0 24px;
}
.nav__link {
  font-size: 14px;
  font-weight: 600;
  padding-top: 4px;
  letter-spacing: 0.35px;
  border-bottom: 2px solid transparent;
  position: relative;
  transition: all 300ms;
}
.nav__link:after {
  content: "";
  position: absolute;
  left: 0;
  bottom: -6px;
  height: 2px;
  width: 100%;
  background: #6415ff;
  transition: all 300ms ease;
  opacity: 0;
}
.nav__link:hover:after {
  opacity: 1;
}
.nav__link--primary {
  margin: 0;
  padding: 10px 32px;
  margin-top: 2px;
  border-radius: 9999px;
  color: #fff;
  background-color: #6415ff;
  line-height: 1.5;
  border: none;
  width: auto;
  transition: all 300ms ease;
}
.nav__link--primary:after {
  content: "";
  width: 0;
  height: 0;
}
.nav__link--primary:hover {
  background-color: rgba(80, 17, 204);
  color: white;
}

.login {
  margin-left: 48px;
}
.btn {
  background-color: #6415ff;
  padding: 12px 32px;
  border: none;
  border-radius: 500px;
  font-size: 14px;
  color: #fff;
  font-weight: bold;
  transition: all 300ms ease;
  cursor: pointer;
}
.btn__menu {
  background-color: transparent;
  border: none;
  display: none;
  transition: all 300ms ease;
}
.btn__menu--svg:hover {
  filter: invert(26%) sepia(94%) saturate(7476%) hue-rotate(261deg)
    brightness(94%) contrast(115%);
}
.btn__menu--close {
  position: fixed;
  top: 24px;
  right: 18px;
}
.menu {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  height: 378px;
  margin: 24px 16px;
  padding: 32px;
  background-color: #fff;
  border: 1px solid rgb(229, 231, 235);
  border-radius: 8px;
  z-index: 4;
  visibility: hidden;
  opacity: 0;
  transform: translateX(300%);
  transition: all 300ms ease;
}
.menu--open {
  max-height: 100vh;
  overflow-y: hidden;
}
.menu--open .menu {
  visibility: visible;
  opacity: 1;
  transform: translateX(0);
}
.menu__links {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.menu__link {
  color: #1a202c;
  font-size: 18px;
  font-weight: 600;
  line-height: 1.5;
  margin: 8px 0;
  padding-bottom: 4px;
  border-bottom: 2px solid transparent;
}
.menu__link--primary {
  color: #f7fafc;
  padding: 12px 32px;
  background: #6415ff;
  border-radius: 500px;
  border: none;
}
.btn__menu--close {
  position: fixed;
  top: 24px;
  right: 18px;
}

/* HEADER / ABOUT US */

section {
  padding: 0 32px;
}
header .row {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.header__description {
  width: 40%;
}
.header__description--para {
  margin: 32px 0;
}
.header__email {
  width: 100%;
  max-width: 448px;
  height: 68px;
  position: relative;
  display: flex;
  justify-content: flex-end;
  align-items: center;
}
.header__email--btn {
  z-index: 2;
  margin: 8px;
  height: calc(100% - 16px);
  border-radius: 500px;
  width: 160px;
  border: none;
  background-color: #6415ff;
  color: #fff;
  font-weight: 700;
  font-size: 16px;
  transition: all 300ms ease;
}
.header__email--btn:hover {
  background-color: rgba(60, 13, 153);
}
.header__email--input {
  width: 100%;
  border-radius: 500px;
  border: 2px solid rgb(229, 231, 235);
  padding: 20px 192px 20px 32px;
  color: rgb(36, 62, 99);
  font-size: 16px;
  font-weight: 500;
  position: absolute;
  top: 0;
  bottom: 0;
  z-index: 1;
  transition: border-color 300ms;
}
.header__email--input::placeholder {
  font-weight: 500;
  color: rgb(158, 170, 189);
}
.header__email--input:hover {
  border-color: rgba(160, 174, 192);
}
.header__email--input:focus,
.header__email--input:active {
  outline: none;
  border-color: rgba(100, 21, 255);
}
.header__customers--title {
  margin-top: 80px;
  color: #a0aec0;
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 0.6;
}
.header__customers {
  margin-top: 16px;
  padding-right: 128px;
  opacity: 0.5;
}
header {
  position: relative;
}
.header__blob {
  position: absolute;
  left: 0;
  bottom: 0;
  opacity: 0.5;
  width: 256px;
  height: 256px;
  transform: matrix(1, 0, 0, 1, -163, 0);
}
.header__img--wrapper {
  width: calc(100% - 40%);
}
.header__img {
  width: 100%;
  max-width: 768px;
}

/* FEATURES */

#features {
  position: relative;
}
#features .row__narrow {
  display: flex;
  flex-direction: column;
  align-items: center;
}
#features .section__title,
#pricing .section__title {
  text-align: center;
}
#features .section__para {
  text-align: center;
  max-width: 576px;
}
.features {
  display: flex;
  flex-wrap: wrap;
  margin-top: 40px;
}
.feature {
  width: calc(100% / 3);
}
.feature__row {
  display: flex;
  align-items: flex-start;
  padding: 32px 24px;
}
.feature__img--wrapper {
  display: flex;
  padding: 20px;
  border: 1px solid #e5e7eb;
  border-radius: 500px;
}
.feature__img {
  width: 24px;
  height: 24px;
}
.feature__text {
  margin-top: 8px;
  margin-left: 16px;
}
.feature__para {
  margin-top: 16px;
  font-size: 16px;
  max-width: calc(634px / 3);
  color: rgb(124, 139, 161);
  line-height: 2;
  font-weight: 500;
}
.features__blob {
  transform: translateX(96px) translateY(192px) scaleX(1) scaleY(1);
  position: absolute;
  right: 0;
  bottom: 0;
  width: 16rem;
  opacity: 0.25;
  padding: 16px;
}
.row__narrow {
  width: 100%;
  max-width: 1024px;
  margin: 0 auto;
}

/* QUALITY WORK */

#quality .row {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
#quality .section__title,
#values .section__title {
  line-height: 1.25;
}
#quality .btn {
  margin-top: 32px;
}
.quality__description {
  max-width: 576px;
  margin-right: 64px;
}
.quality__description,
.quality__img--wrapper {
  width: 50%;
}
.quality__img--wrapper {
  border-radius: 4px;
  border: 1px solid rgb(229, 231, 235);
  position: relative;
  margin: 0 56px;
  z-index: 2;
  display: flex;
}
.quality__grid {
  transform: translateX(50%) translateY(50%) scaleX(1) scaleY(1);
  width: 80px;
  height: 80px;
  position: absolute;
  right: 0px;
  bottom: 0px;
  fill: rgb(100, 21, 255);
  --tw-text-opacity: 1;
  color: rgba(100, 21, 255, var(--tw-text-opacity));
  z-index: 0;
  display: block;
}
.quality__img {
  z-index: 1;
}

/* STEPS */

#steps .row {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.steps__img--wrapper {
  display: flex;
  position: relative;
}
.steps__description,
.steps__img--wrapper {
  width: 50%;
}
.steps__img {
  z-index: 2;
}
.steps__description {
  padding: 32px 0;
  padding-left: 64px;
}
.step {
  display: flex;
  align-items: flex-start;
  margin-top: 32px;
}
.step__number {
  color: #cbd5e0;
  font-size: 36px;
  font-weight: 600;
  line-height: 1;
}
.step__description {
  display: flex;
  flex-direction: column;
  margin-left: 24px;
  max-width: 320px;
}
.step__title {
  font-weight: 600;
  font-size: 20px;
  color: #243e63;
  line-height: 1;
}
.step__para {
  font-size: 14px;
  color: #718096;
  margin-top: 12px;
  font-weight: 500;
  line-height: 2;
}
.steps__grid {
  position: absolute;
  bottom: -100px;
  left: 50%;
  transform: translateX(-50%);
  width: 10rem;
  height: 10rem;
  opacity: 0.8;
  z-index: -10;
  color: rgb(100, 21, 255); /* currentColor will inherit this */
  fill: currentColor;
}

/* VALUES */

#values .row {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
#values .section__title {
  margin-top: 16px;
  margin-bottom: 32px;
}
#values .btn {
  margin-top: 48px;
}
.value {
  margin-top: 2rem;
  margin-right: 2rem;
  align-items: flex-start;
  display: flex;
  flex-direction: column;
}
.values__description {
  padding: 32px 64px 32px 0;
}
.values__description,
.values__img {
  width: 50%;
}
.values__list {
  margin-left: 0px;
  margin-right: 0px;
  display: flex;
  max-width: none;
  flex-direction: row;
}
.value:nth-of-type(1) {
  margin-top: 32px;
  margin-right: 32px;
}
.value:nth-of-type(2) {
  margin-top: 32px;
}
.value__title {
  display: flex;
  align-items: center;
}
.value__img {
  width: 20px;
  height: 20px;
}
.value:nth-child(1) .value__img--wrapper {
  background-color: #9ae6b4;
}
.value:nth-child(2) .value__img--wrapper {
  background-color: #feb2b2;
}
.value__img--wrapper {
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 36px;
  height: 36px;
}
.value__name {
  margin-left: 12px;
  font-size: 20px;
  font-weight: bold;
  color: #243e63;
}
.value__para {
  margin-top: 16px;
  line-height: 1.625;
  color: #718096;
}

/* PRICING */

#pricing .row {
  display: flex;
  flex-direction: column;
  align-items: center;
}
#pricing .section__para {
  max-width: 576px;
  text-align: center;
}
.plan {
  position: relative;
  margin-top: 4rem;
  display: flex;
  width: 100%;
  max-width: 24rem;
  flex-direction: column;
  border-radius: 0.5rem;
  background-color: rgb(255 255 255);
  padding-left: 2rem;
  padding-right: 2rem;
  margin-right: 2rem;
  padding-top: 0.5rem;
  text-align: center;
  color: rgb(26 32 44);
  box-shadow: rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0) 0px 0px 0px 0px,
    rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.06) 0px 1px 2px 0px;
}
.plan__stripe {
  position: absolute;
  left: 0px;
  right: 0px;
  top: 0px;
  height: 0.5rem;
  border-top-left-radius: 0.5rem;
  border-top-right-radius: 0.5rem;
}

.plan__top {
  display: flex;
  flex-direction: column;
  padding-top: 2rem;
  padding-bottom: 2rem;
  text-transform: uppercase;
  line-height: 1.625;
}

.plan__middle {
  margin-left: -2rem;
  margin-right: -2rem;
  display: flex;
  flex: 1 1 0%;
  flex-direction: column;
  border-top-width: 2px;
  border-bottom-width: 2px;
  padding: 2rem;
}

.plan__bottom {
  padding-left: 4rem;
  padding-right: 4rem;
  padding-top: 2rem;
  padding-bottom: 2rem;
}

.plan__name,
.plan__price,
.plan__duration {
  font-weight: bold;
  line-height: 1.625;
}
.plan__name {
  font-size: 20px;
}
.plan__price {
  font-size: 48px;
  margin: 4px 0;
}
.plan__duration {
  font-size: 16px;
  letter-spacing: 0.1em;
}
.plan__feature {
  margin-top: 20px;
  font-weight: 500;
  color: #718096;
  font-size: 16px;
  line-height: 1.5;
}
.plan__target {
  font-size: 20px;
  font-weight: 700;
  line-height: 1.5;
  letter-spacing: 0.025em;
}
.plan__button {
  border-radius: 0.25rem;
  background-color: rgb(100 21 255);
  padding: 0.75rem 2rem;
  font-weight: 700;
  color: rgb(247 250 252);
  transition: all 300ms ease;
  width: 100%;
  border-radius: 9999px;
  padding-top: 1rem;
  padding-bottom: 1rem;
  font-size: 0.875rem;
  text-transform: uppercase;
  letter-spacing: 0.05em;
}
.plan__button:hover {
  transform: translate(1px, -1px);
  box-shadow: rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0) 0px 0px 0px 0px,
    rgba(0, 0, 0, 0.1) 0px 20px 25px -5px,
    rgba(0, 0, 0, 0.04) 0px 10px 10px -5px;
}
.plan:nth-child(1) .plan__stripe,
.plan:nth-child(1) .plan__button {
  color: #f7fafc;
  background: linear-gradient(
    115deg,
    rgb(56, 178, 172) 0%,
    rgb(129, 230, 217) 100%
  );
}
.plan:nth-child(2) {
  background: linear-gradient(
    135deg,
    rgb(76, 81, 191) 0%,
    rgb(102, 126, 234) 100%
  );
}
.plan:nth-child(2) .plan__button {
  color: #6415ff;
  background-color: #f7fafc;
}
.plan:nth-child(2) .plan__stripes {
  visibility: hidden;
}
.plan:nth-child(3) .plan__stripe,
.plan:nth-child(3) .plan__button {
  color: #f7fafc;
  background: linear-gradient(
    115deg,
    rgb(245, 101, 101) 0%,
    rgb(254, 178, 178) 100%
  );
}
.plan:nth-child(odd) .plan__name,
.plan:nth-child(odd) .plan__price,
.plan:nth-child(odd) .plan__target {
  color: #1a202c;
}
.plan:nth-child(odd) .plan__duration {
  color: #a0aec0;
}
.plan:nth-child(2) .plan__name,
.plan:nth-child(2) .plan__price,
.plan:nth-child(2) .plan__target,
.plan:nth-child(2) .plan__duration,
.plan:nth-child(2) .plan__feature {
  color: #f7fafc;
}
.plan:nth-child(1) .plan__middle,
.plan:nth-child(3) .plan__middle {
  border-top: 2px solid rgb(229, 231, 235);
  border-bottom: 2px solid rgb(229, 231, 235);
}
.plan:nth-child(2) .plan__middle {
  border-top: 2px solid rgb(102, 126, 234);
  border-bottom: 2px solid rgb(102, 126, 234);
}
.plans__blob {
  z-index: -10;
  position: absolute;
  left: 0;
  bottom: 0;
  transform: translateX(-50%) translateY(50%) scaleX(1) scaleY(1);
  height: 256px;
  width: 256px;
  opacity: 0.25;
}
.plans {
  display: flex;
  position: relative;
  flex-direction: row;
  width: 100%;
  justify-content: space-between;
}

/* TESTIMONIALS */
section #testimonials {
  padding: 0px;
}

#testimonials .container {
  padding-top: 6rem;
  padding-bottom: 6rem;
}

#testimonials .row {
  margin-left: auto;
  margin-right: auto;
  max-width: 1280px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.testimonials__img,
.testimonials__description {
  width: 50%;
}
.testimonials__description {
  display: flex;
  flex-direction: column;
  padding-left: 64px;
}
#testimonials .section__title {
  margin-bottom: 24px;
  line-height: 1.25;
}
.testimonial {
  margin-top: 40px;
}
.testimonial__rating {
  color: rgba(246, 173, 85);
  margin-right: 2px;
  margin-top: 4px;
}
.testimonial__title {
  color: #4a5568;
  line-height: 1.625;
  margin-top: 1rem;
  font-size: 1.25rem;
  font-weight: 700;
}

.testimonial__name {
  color: #4a5568;
  line-height: 1.625;
  font-size: 1.25rem;
  font-weight: 700;
}

.testimonial__para {
  margin-top: 1rem;
  margin-bottom: 2rem;
  font-weight: 500;
  line-height: 1.625;
  font-size: 16px;
  color: rgb(74 85 104);
}

.testimonial__bottom {
  display: flex;
  justify-content: space-between;
}
.testimonial__profile {
  display: flex;
  align-items: center;
}
.testimonial__details {
  margin-left: 24px;
}
.testimonial__img {
  width: 80px;
  height: 80px;
  border-radius: 50%;
}
.testimonial__role {
  color: #7c8ba1;
  font-weight: 500;
  line-height: 1.5;
}
.testimonial__buttons {
  display: flex;
  align-items: center;
}
.testimonial__button svg {
  width: 16px;
  height: 16px;
}
.testimonial__button {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 16px;
  background: #edf2f7;
  border-radius: 50%;
  margin: 0 12px;
  transition: all 300ms ease;
}
.testimonial__button:hover {
  background-color: rgb(229, 231, 235);
}

.fa-star {
  color: rgb(246 173 85);
  display: inline-block;
  height: 1.25rem;
  width: 1.25rem;
}

.divider {
  margin-top: 0.75rem;
  margin-bottom: 0.75rem;
  border-right-width: 1px;
  width: 0.5px;
  background-color: #edf2f7;
  height: 20px;
}

/* START / CALL TO ACTION */

main {
  margin-bottom: 96px;
}

.start__container {
  padding: 96px 0;
  width: 100%;
  background-color: rgb(100, 21, 255);
  border-radius: 8px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.start__row {
  width: 100%;
  margin: 0 auto;
  max-width: 1024px;
  padding: 0 32px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.start__title,
.start__buttons {
  width: 50%;
}
.start__buttons {
  display: flex;
  justify-content: flex-end;
}
.start__title {
  color: #f7fafc;
  font-size: 30px;
  font-weight: 700;
  line-height: 1.5;
  z-index: 2;
}
.start__button {
  padding: 20px 40px;
  border-radius: 500px;
  font-weight: 700;
  font-size: 16px;
  color: #f7fafc;
  line-height: 1.5;
  letter-spacing: 0.025;
  margin: 1px;
  z-index: 2;
}
.start__button:nth-child(1) {
  background: #f56565;
  box-shadow: rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0) 0px 0px 0px 0px,
    rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.05) 0px 4px 6px -2px;
  margin-right: 32px;
  transition: all 300ms ease;
}
.start__button:hover:nth-child(1) {
  background-color: rgba(229, 62, 62);
}
.start__button:nth-child(2) {
  border: 1px solid rgb(160, 174, 192);
  transition: all 300ms ease;
}
.start__button:hover:nth-child(2) {
  background-color: rgba(247, 250, 252);
  color: rgba(100, 21, 255);
}
#start .row {
  position: relative;
  overflow: hidden;
}
.start__blob--1 {
  position: absolute;
  bottom: 0px;
  left: 0px;
  height: 20rem;
  width: 20rem;
  transform: translate(-5rem, 8rem);
  color: rgb(80 17 204);
  opacity: 0.5;
}
.start__blob--2 {
  position: absolute;
  top: 0px;
  right: 0px;
  height: 20rem;
  width: 20rem;
  transform: translate(5rem, -16rem);
  color: rgb(80 17 204);
  opacity: 0.5;
}

/* FOOTER */

footer {
  padding: 96px 32px;
  background-color: rgb(100, 21, 255);
  margin-bottom: -32px;
  position: relative;
  overflow: hidden;
}
.footer__columns {
  margin-top: -48px;
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}
.footer__column {
  margin-top: 48px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  z-index: 2;
}
.footer__column--title {
  font-weight: 700;
  color: #f7fafc;
  line-height: 1.5;
}
.footer__column--link {
  color: #f7fafc;
  font-size: 14px;
  margin-top: 12px;
  line-height: 1.5;
  font-weight: 500;
  position: relative;
  cursor: pointer;
}
.footer__column--link:after {
  content: "";
  position: absolute;
  left: 0;
  bottom: -6px;
  height: 2px;
  width: 100%;
  background: #fff;
  transition: all 300ms ease;
  opacity: 0;
}
.footer__column--link:hover:after {
  opacity: 1;
}
.footer__column--link:nth-child(2) {
  margin-top: 24px;
}
.footer__divider {
  width: 100%;
  height: 2px;
  margin: 64px 0;
  background: rgb(116, 44, 255);
}
.footer__bottom {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.footer__logo {
  display: flex;
  align-items: center;
}
.footer__logo--img {
  height: 32px;
  width: 32px;
}
.footer__logo--text {
  font-size: 20px;
  color: #f7fafc;
  font-weight: 900;
  margin-left: 8px;
  letter-spacing: 0.05em;
}
.footer__socials {
  display: flex;
  align-items: center;
  margin-left: -16px;
}
.footer__social--link svg {
  height: 16px;
  width: 16px;
}
.footer__social--link {
  margin-left: 16px;
  padding: 8px;
  background: #f7fafc;
  display: flex;
  justify-content: center;
  border-radius: 50%;
  z-index: 2;
  cursor: pointer;
  transition: all 300ms ease;
}
.footer__social--link:hover {
  background-color: rgba(203, 213, 224);
}
.footer__copyright {
  color: #cbd5e0;
  font-weight: 500;
}
.footer__blob--1 {
  position: absolute;
  top: 0;
  left: 0;
  width: 320px;
  height: 320px;
  transform: translateX(-80px) translateY(-128px);
  z-index: 1;
  opacity: 0.5;
}
.footer__blob--2 {
  position: absolute;
  bottom: 0;
  right: 0;
  width: 320px;
  height: 320px;
  transform: translateX(128px) translateY(192px);
  z-index: 1;
  opacity: 0.5;
}

/* MOBILE RESPONSIVENESS */

@media (max-width: 1280px) {
  header .row {
    align-items: flex-end;
  }

  .steps__grid {
    height: 5rem;
    width: 5rem;
    bottom: -50px;
  }
  h1 {
    font-size: 36px;
    color: #1a202c;
    line-height: 1.25;
  }
  .header__description--para {
    font-size: 16px;
  }
  .header__customers {
    padding-right: 64px;
  }
  .header__img--wrapper {
    display: flex;
    justify-content: flex-end;
  }
  .header__img {
    max-width: 512px;
  }
  .plan__button {
    max-width: none;
  }

  .plan__bottom {
    padding-left: 2rem;
    padding-right: 2rem;
  }
  .testimonials__img {
    width: 40%;
  }
  .testimonials__description {
    width: calc(100% - 40%);
  }
}
@media (max-width: 1024px) {
  .nav__links {
    display: none;
  }
  .btn__menu {
    display: block;
  }
  header .row {
    flex-direction: column;
    align-items: center;
  }
  .header__description,
  .header__img--wrapper {
    width: 100%;
    max-width: 512px;
    margin: 0 auto;
  }
  .header__description {
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  h1 {
    font-size: 30px;
  }
  .header__description--para {
    margin: 20px 0;
  }
  .header__customers {
    padding-right: 0px;
  }
  .header__customers--title,
  .header__img--wrapper {
    margin-top: 48px;
  }
  .features {
    max-width: 768px;
  }
  .feature {
    width: calc(50%);
  }
  .feature__title {
    line-height: 1;
  }
  .feature__row {
    padding: 32px 8px;
    margin: 0 16px;
  }
  .feature__para {
    max-width: none;
  }
  .section__para {
    font-size: 16px;
  }
  .section__title {
    font-size: 36px;
  }
  .quality__description {
    margin-right: 0px;
    padding-right: 48px;
  }
  .value {
    margin-top: 2.5rem;
  }

  .values__list {
    max-width: 20rem;
    flex-direction: column;
  }
  .plans {
    flex-direction: column;
    align-items: center;
  }

  .plan {
    margin-right: 0px;
  }
  #features .section__title,
  #pricing .section__title {
    font-size: 48px;
  }

  #testimonials .container {
    padding-top: 5rem;
    padding-bottom: 5rem;
  }
  .testimonials__description {
    padding-left: 48px;
  }

  #start .container {
    padding-top: 5rem;
    padding-bottom: 5rem;
  }

  .start__row {
    flex-direction: column;
  }
  .start__title {
    text-align: center;
    width: 100%;
    max-width: 512px;
  }
  .start__buttons {
    width: auto;
    margin-top: 24px;
  }
  .start__button {
    padding: 16px 32px;
  }
  footer {
    padding: 80px 32px;
  }
}
@media (max-width: 768px) {
  .features {
    justify-content: center;
  }
  .feature {
    width: auto;
    max-width: 384px;
  }
  .section__para {
    font-size: 14px;
  }
  #quality .row,
  #values .row {
    flex-direction: column-reverse;
  }
  .quality__description,
  .steps__description,
  .values__description,
  .testimonials__description {
    padding: 0;
    margin-top: 64px;
    text-align: center;
  }
  .quality__description,
  .quality__img--wrapper,
  .steps__description,
  .steps__img--wrapper,
  .values__description,
  .values__img,
  .testimonials__description,
  .testimonials__img {
    width: 100%;
    max-width: 448px;
  }
  #steps .row,
  #testimonials .row {
    flex-direction: column;
  }

  .step {
    flex-direction: column;
    align-items: center;
  }
  .step__description {
    margin-top: 12px;
    margin-left: 0;
  }
  .values__list {
    margin-left: auto;
    margin-right: auto;
  }
  .value:nth-of-type(1) {
    margin-right: 0px;
  }
  .value {
    margin-right: 0px;
    align-items: center;
  }
  #pricing .row {
    margin-top: 40px;
  }
  .testimonials__description {
    padding-left: 0;
  }
  .footer__columns {
    justify-content: flex-start;
  }
  .footer__column {
    width: calc(100% / 3);
  }
  .footer__bottom {
    flex-direction: column;
    align-items: center;
  }
  .footer__copyright,
  .footer__socials {
    margin-top: 32px;
  }
  .footer__socials {
    margin-left: 0px;
  }
  .footer__social--link:first-child {
    margin-left: 0px;
  }
}
@media (max-width: 640px) {
  .section__title {
    line-height: 1.25;
  }
  .container {
    padding: 80px 0;
  }
  .nav__logo {
    margin: 8px 0;
    padding-bottom: 4px;
  }
  .header__email {
    flex-direction: column;
    height: auto;
  }
  .header__email--input {
    position: static;
    padding: 16px 0;
    padding-left: 32px;
    line-height: 1.5;
  }
  .header__email--btn {
    width: 100%;
    padding: 16px 0;
    margin: 16px 0;
    margin-bottom: 0px;
    line-height: 1.5;
  }
  .header__customers--title {
    font-size: 14px;
    letter-spacing: 0.05em;
  }
  .section__title {
    font-size: 30px;
  }
  #features .section__title,
  #pricing .section__title {
    font-size: 36px;
  }
  .feature__row {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }
  .feature__title {
    letter-spacing: 0.025em;
    line-height: 1;
  }
  .feature__text {
    margin-left: 0px;
    margin-top: 16px;
  }
  .feature__para {
    margin-top: 4px;
    line-height: 2;
  }
  #steps .section__title {
    margin: 16px 0 0 0;
  }
  .steps__list {
    margin-top: 48px;
  }
  .btn {
    line-height: 1.5;
  }
  .plan__price {
    font-size: 36px;
  }
  .plan__bottom {
    padding: 2rem 1rem;
  }
  .testimonial__para {
    margin-bottom: 32px;
  }
  .testimonial__bottom {
    flex-direction: column;
    align-items: center;
    padding-top: 4px;
  }
  .testimonial__profile {
    flex-direction: column;
    align-items: center;
  }
  .testimonial__details {
    margin-left: 0;
    margin-top: 8px;
  }
  .testimonial__img {
    height: 64px;
    width: 64px;
  }
  .testimonial__buttons {
    margin-top: 32px;
  }
  .start__title {
    font-size: 24px;
  }
  .start__container {
    padding: 80px 0;
  }
  .start__buttons {
    flex-direction: column;
  }
  .start__button:nth-child(1) {
    margin-right: 0;
  }
  .start__button {
    padding: 12px 24px;
    font-size: 14px;
  }
  .start__button:nth-child(2) {
    margin-top: 16px;
  }
  main {
    margin-bottom: 80px;
  }
  .footer__columns {
    justify-content: center;
  }
  .footer__column {
    width: auto;
    padding: 0 16px;
    text-align: center;
    align-items: center;
  }
  .footer__copyright {
    font-size: 14px;
    text-align: center;
    line-height: 1.5;
  }
}

