<template>
  <div id="app">
    <Header />

    <main>
      <Hero/>
      <Main/>
    </main>

    <Nav/>

    <footer>
      <FooterLinks/>
      <FooterAbout/>
    </footer>
  </div>
</template>

<script>

import Header from '@/components/Header.vue'
import Main from '@/components/Main.vue'
import Nav from '@/components/Nav.vue'
import FooterLinks from '@/components/FooterLinks.vue'
import FooterAbout from '@/components/FooterAbout.vue'
import Hero from '@/components/Hero.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Nav,
    FooterLinks,
    FooterAbout,
    Hero
  }
}
</script>

<style lang="scss">
@import '@/styles/globals'
</style>

