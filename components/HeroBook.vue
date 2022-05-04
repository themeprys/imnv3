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
            <nuxt-link to="/" class="navbar-item">
              Home
            </nuxt-link>
            <a class="navbar-item" href="/#about_me">
              About Me
            </a>
            <a class="navbar-item" href="/#portfolio">
              Porfolio
            </a>
            <a class="navbar-item"  href="/#contact">
              Contact
            </a>
          </div>
        </div>        
        <div id="navbarMenuHeroB" class="navbar-menu">
          <div class="navbar-end">
            <span class="navbar-item">
              <nuxt-link to="/rupa-suara" class="button is-dark">
                <font-awesome-icon icon="angle-double-down"/>
                <span class="pl-2">Download Resume</span>
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
        <div class="column is-4">
            <div class="imn_foto_hero_home">
                <img src="~/static/img/rupa-suara.jpg" />
            </div>
        </div>

        <div class="column pl-6">
      <h2 class="title imn_book_title">
        Out Now: Rupa Suara
      </h2>
      <h3 class="subtitle imn_book_subtitle">
        Buku Memoar Catatan Perjalanan Iman Fattah
      </h3>
      <div class="imn_cta_book buttons">
        <button class="button is-primary is-large"><font-awesome-icon icon="hand-point-right"/>&nbsp;&nbsp;Buy IDR 90.000</button>
      </div>

      <div class="imn_book_text">
      <p>I'm baby cloud bread tote bag raclette tbh brunch taxidermy. Cred brooklyn PBR&B, meggings shabby chic bitters air plant ramps pickled vexillologist direct trade forage +1 intelligentsia.</p><p>Cronut before they sold out normcore fashion axe mixtape actually adaptogen pitchfork vinyl. Crucifix marfa cronut master cleanse farm-to-table craft beer bushwick asymmetrical jianbing la croix pabst.</p>
        <h3 class="subtitle has-text-weight-bold">Pembayaran Via:</h3>
        <img src="~/static/img/payment.png" />
      </div>
      <!-- <div class="imn_social">
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
      </div> -->

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
.imn_book_title {
  font-size: 60px;
}
.imn_book_subtitle {
  /* padding-bottom: 20px; */
}
h3.imn_book_subtitle {
  font-size: 25px !important;
}
.imn_cta_book {
  /* margin-top:50px; */
  margin: 30px 0 !important;
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
.imn_book_text p {
    font-size: 22px;
    padding-bottom:20px;
}
</style>