<template>


  <div>
      <Header />
      <main>
          main
      </main>
      <Footer />
  </div>

</template>

<script>
import Header from './components/partials/Header';
import Footer from './components/partials/Footer';

export default {
    name: "App",

    components:{
        Header,
        Footer
    }
}
</script>

<style lang="scss">

</style>