<template>
<section class="hero is-large">
  <div class="hero-head">
    <nav class="navbar">
      <div class="container">
        <div class="navbar-brand">
          <nuxt-link to="/" class="navbar-item">
            <img src="~/static/img/iman_logo.svg" alt="Iman Fattah" height="100px">
          </nuxt-link>
          <div class="mt-5 navbar-burger">
          <nuxt-link to="/about">
                My Profile <i class="fas fa-user"></i>
          </nuxt-link>
          </div>

        </div>
        <div id="navbarMenuHeroB" class="navbar-menu">
          <div class="navbar-end">
            <nuxt-link to="/" class="navbar-item is-active">
              Rupa Suara
            </nuxt-link>
            <nuxt-link class="navbar-item" to="/about">
              Tentang Saya
            </nuxt-link>
            <nuxt-link class="navbar-item"  to="/contact">
              Kontak
            </nuxt-link>

            <a class="navbar-item"  href="https://www.imanfattah.rocks/" target="_blank">
              Imanfattah.rocks&nbsp;&nbsp;<i class="fas fa-external-link-alt"></i>
            </a>
          </div>
        </div>        
        <div id="navbarMenuHeroB" class="navbar-menu">
          <div class="navbar-end">
            <span class="navbar-item">
              <a href="https://xabi.us" class="button is-dark" target="_blank">
                <span class="pl-2">Pra-Pesan Buku</span>&nbsp;&nbsp;
              <i class="fas fa-external-link-alt"></i>                
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
            Rupa Suara, Catatan Perjalanan Bebunyian oleh Iman Fattah
          </h2>
          <!-- <h3 class="subtitle imn_book_subtitle">
            Buku Memoar Catatan Perjalanan Iman Fattah
          </h3> -->
          <div class="imn_cta_book buttons">
            <a class="button is-primary is-large" href="https://xabi.us/?add-to-cart=4291" target="_blank">
                  <i class="fas fa-hand-point-right"></i>&nbsp;&nbsp;Pra-Pesan IDR 90.000
            </a>&nbsp;&nbsp;<i class="fas fa-external-link-alt"></i>
          </div>
          <div class="imn_book_text">
<p>Rupa Suara adalah sebuah memoar perjalanan seorang Iman Fattah. Catatan ini menceritakan perjalanan Iman sebagai seorang musisi, seniman, sound designer, hingga produser musik.</p>
<p>Perjalanan tersebut berada di rentang dua dekade antara 1990an akhir hingga 2020. Dengan apik Iman menjabarkan perjalanannya bermusik dengan berbagai proyek seperti LAIN, Zeke and The Popo, hingga Raksasa.</p>
<p>Buku ini juga menceritakan bagaimana Iman juga berkecimpung di dunia sound design di sebuah pertunjukan opera bertajuk ONROP MUSIKAL, hingga menjadi produser musik untuk Kartika Jahja.</p>
<p>Secara luas, buku ini dapat dimaknai sebagai sebuah catatan bagaimana skena musik lokal Indonesia berkembang di era pasca-reformasi. Buku ini adalah tentang tempat, ruang, dan waktu.</p>
          </div>
        </div>
      </div>
    </div>
  </div>

</section>
</template>
