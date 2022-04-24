<template>
  <div id="contact" class="imn_section container">
        <h3 class="has-text-centered title">Contact.</h3>
        <p class="has-text-centered subtitle">Do you have questions, business offer or just want to say hi?<br>Feel free to reach me via email to halo@imanfattah.rocks or imanfattah@gmail.com</p>
        <div class="imn_contact_content columns">
            <div class="column imn_contact_logo has-text-centered">
                <img src="~/static/img/iman_logo_icon.png" width="300px" />
            </div>
        </div>

      <div class="imn_social has-text-centered">
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
  </div>
</template>

<style>
#contact.imn_section {
  padding: 60px 0 !important;
}
#contact .subtitle {
  font-size: 16px !important;
}
</style>