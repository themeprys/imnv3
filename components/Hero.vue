<template>
<section class="hero is-large">
  <div class="hero-head">
    <nav class="navbar">
      <div class="container">
        <div class="navbar-brand">
          <nuxt-link to="/" class="navbar-item">
            <img src="~/static/img/iman_logo.svg" alt="Iman Fattah" height="100px">
          </nuxt-link>
          <span class="navbar-burger" data-target="navbarMenuHeroB">
            <span></span>
            <span></span>
            <span></span>
          </span>
        </div>
        <div id="navbarMenuHeroB" class="navbar-menu">
          <div class="navbar-end">
            <a class="navbar-item" href="/">
              Rupa Suara
            </a>
            <a class="navbar-item is-active" href="#about_me">
              About Me
            </a>
            <a class="navbar-item" href="#portfolio">
              Porfolio
            </a>
            <a class="navbar-item"  href="#contact">
              Contact
            </a>
          </div>
        </div>        
        <div id="navbarMenuHeroB" class="navbar-menu">
          <div class="navbar-end">
            <span class="navbar-item">
              <a href="/files/Resume_Iman_Fattah.pdf" class="button is-dark" download>
              <i class="fas fa-angle-double-down"></i>
                <span class="pl-2">Download Resume</span>
              </a>
            </span>
          </div>
        </div>
      </div>
    </nav>
  </div>

  <div class="hero-body imn_hero">
    <div class="container">
      <div class="columns">
        <div class="column">
      <h2 class="title imn_title">
        Iman Fattah
      </h2>
      <h3 class="subtitle imn_subtitle">
        Language and Ontology Engineer | Musician and Audio Technologist | Author
      </h3>

      <div class="imn_social">
        <a href="#" target="_blank">
              <i class="fab fa-facebook"></i>
        </a>
        <a href="#" target="_blank">
              <i class="fab fa-instagram"></i>
        </a>
        <a href="#" target="_blank">
              <i class="fab fa-twitter"></i>
        </a>
        <a href="#" target="_blank">
              <i class="fab fa-linkedin"></i>
        </a>
      </div>

      <div class="imn_cta_home buttons">
              <nuxt-link to="/" class="button is-primary is-large">
                <span class="pl-2">Pre-Order My Book</span>
              </nuxt-link>

        <!-- <button class="button is-primary is-large">Download My Resume</button> -->
      </div>
        </div>
        <div class="column">

      <div class="imn_foto_hero_home">
        <img src="~/static/img/iman_hero_book.jpg" />
      </div>

        </div>
      </div>



    </div>
  </div>

</section>
</template>
