<template>
  <div id="app">
    <Header />
    <main>
      <Main/>
    </main>
    <Nav/>
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Main from '@/components/Main.vue'
import Nav from '@/components/Nav.vue'
export default {
  name: 'App',
  components: {
    Header,
    Main,
    Nav,
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: sans-serif;
  text-decoration: none;
	

}

img{
  max-width: 100%;
}

.container{
  max-width: 1280px;
  margin: 0 auto;
  padding: 0 16px;
}
</style>
