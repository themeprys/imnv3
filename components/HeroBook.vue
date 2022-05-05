<template>
<section class="hero is-large">
  <div class="hero-head">
    <nav class="navbar">
      <div class="container">
        <div class="navbar-brand">
          <nuxt-link to="/" class="navbar-item">
            <img src="~/static/img/iman_logo.svg" alt="Iman Fattah" height="100px">
          </nuxt-link>
        </div>
        <div id="navbarMenuHeroB" class="navbar-menu">
          <div class="navbar-end">
            <nuxt-link to="/" class="navbar-item is-active">
              Rupa Suara
            </nuxt-link>
            <nuxt-link class="navbar-item" to="/about">
              About Me
            </nuxt-link>
            <a class="navbar-item" href="/about/#portfolio">
              Porfolio
            </a>
            <a class="navbar-item"  href="/about/#contact">
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
        <div class="column is-4">
            <div class="imn_foto_hero_home">
                <img src="~/static/img/rupa-suara.jpg" class="img-fluid" />
            </div>
        </div>

        <div class="column details">
          <h2 class="title imn_book_title">
            Out Now: Rupa Suara
          </h2>
          <h3 class="subtitle imn_book_subtitle">
            Buku Memoar Catatan Perjalanan Iman Fattah
          </h3>
          <div class="imn_cta_book buttons">
            <a class="button is-primary is-large" href="#" target="_blank">
                  <i class="fas fa-hand-point-right"></i>&nbsp;&nbsp;Buy IDR 90.000
            </a>
          </div>
          <div class="imn_book_text">
          <p>I'm baby cloud bread tote bag raclette tbh brunch taxidermy. Cred brooklyn PBR&B, meggings shabby chic bitters air plant ramps pickled vexillologist direct trade forage +1 intelligentsia.</p><p>Cronut before they sold out normcore fashion axe mixtape actually adaptogen pitchfork vinyl. Crucifix marfa cronut master cleanse farm-to-table craft beer bushwick asymmetrical jianbing la croix pabst.</p>
          <p>I'm baby cloud bread tote bag raclette tbh brunch taxidermy. Cred brooklyn PBR&B, meggings shabby chic bitters air plant ramps pickled vexillologist direct trade forage +1 intelligentsia.</p><p>Cronut before they sold out normcore fashion axe mixtape actually adaptogen pitchfork vinyl. Crucifix marfa cronut master cleanse farm-to-table craft beer bushwick asymmetrical jianbing la croix pabst.</p>
            <!-- <h3 class="subtitle has-text-weight-bold">Pembayaran Via:</h3>
            <img src="~/static/img/payment.png" /> -->
          </div>
        </div>
      </div>
    </div>
  </div>

</section>
</template>
