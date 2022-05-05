<template>
  <div>
      <HeroBook />
      <Blurb />
      <VideoBook />
      <PreOrder />
      <!-- <AboutMe />
      <Portfolio /> -->
      <Contact />
  </div>
</template>


<script>
export default {
  head: {
    title: 'Rupa Suara - Buku Memoar Catatan Perjalanan Iman Fattah',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      {
        hid: 'description',
        name: 'description',
        content: 'Beli Buku Rupa Suara, Memoar Catatan Perjalanan bermusik Iman Fattah sebagai musisi, sound artist, dan penulis dari Indonesia.'
      }
    ],
    link: [{ rel: 'icon', type: 'image/x-icon', href: '/favicon.ico' }]
  }
}
</script>