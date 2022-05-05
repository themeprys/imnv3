<template>
  <div class="container">
      <div class="columns">
          <div class="column imn_preorder">
                <h2 class="is-size-2 has-text-weight-bold has-text-centered">Pre Order Now</h2>
                <p class="has-text-centered">Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita, iusto accusamus officiis doloribus accusantium repellat</p>
                <div class="imn_preorder_logo">
                        <img src="~/static/img/payment.png" />
                </div>
                <div class="imn_cta_book preorder buttons ">
                    <a class="button is-primary is-large" href="#" target="_blank">
                        <i class="fas fa-hand-point-right"></i>&nbsp;&nbsp;Buy Now IDR 90.000
                    </a>
                </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.imn_preorder  {
    width: 700px;
    margin: 0 auto 0 !important;
}
.imn_cta_book.preorder.buttons a {
    margin: 0 auto 0;
    width: 300px;
}
</style>