<template>
<section class="hero is-large">
  <div class="hero-head">
    <nav class="navbar">
      <div class="container">
        <div class="navbar-brand">
          <a class="navbar-item">
            <img src="~/static/img/iman_logo.svg" alt="Iman Fattah" height="100px">
          </a>
          <span class="navbar-burger" data-target="navbarMenuHeroB">
            <span></span>
            <span></span>
            <span></span>
          </span>
        </div>
        <div id="navbarMenuHeroB" class="navbar-menu">
          <div class="navbar-end">
            <a class="navbar-item is-active" href="/">
              Home
            </a>
            <a class="navbar-item" href="#about_me">
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
              <nuxt-link to="/rupa-suara" class="button is-primary">
                <font-awesome-icon icon="bookmark"/>
                <span class="pl-2">Pre-Order Book</span>
              </nuxt-link>
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
          <font-awesome-layers class="fa-2x mx-2">
            <font-awesome-icon :icon="['fab', 'facebook']"/>
          </font-awesome-layers>
        </a>
        <a href="#" target="_blank">
          <font-awesome-layers class="fa-2x mx-2">
            <font-awesome-icon :icon="['fab', 'instagram']"/>
          </font-awesome-layers>
        </a>
        <a href="#" target="_blank">
          <font-awesome-layers class="fa-2x mx-2">
          <font-awesome-icon :icon="['fab', 'twitter']"/>
          </font-awesome-layers>        </a>
        <a href="#" target="_blank">
          <font-awesome-layers class="fa-2x mx-2">
          <font-awesome-icon :icon="['fab', 'linkedin']"/>
          </font-awesome-layers>
        </a>
      </div>

      <div class="imn_cta_home buttons">
        <button class="button is-primary is-large">Download My Resume</button>
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

<script>
export default {

}
</script>

<style>
.imn_title {
  font-size: 80px;
}
.imn_subtitle {
  max-width: 500px;
  padding-bottom: 20px;
}
.imn_cta_home {
  margin-top:50px;
}
.hero-body.imn_hero {
  padding: 100px 0px !important;
}
.navbar {
  height: 100px !important;
}
.navbar-item img {
  max-height: 70px;
}
.imn_social .fa-2x {
  font-size: 25px !important;
}
.hero {
  background: url(~/static/img/bg1.jpeg);
}
.imn_foto_hero_home img {
-webkit-box-shadow: 2px 5px 20px -6px rgba(0,0,0,0.65); 
box-shadow: 2px 5px 20px -6px rgba(0,0,0,0.65);
}
.navbar-menu {
  font-weight: bold;
}
a.navbar-item:focus, a.navbar-item:focus-within, a.navbar-item:hover, a.navbar-item.is-active, .navbar-link:focus, .navbar-link:focus-within, .navbar-link:hover, .navbar-link.is-active {
  background-color: transparent !important;
}
</style>