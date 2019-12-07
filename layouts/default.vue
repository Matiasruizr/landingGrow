<template>
  <div>
    <section class="main-content columns">
      <div class="container column is-12">
        <nuxt />
      </div>
    </section>
  </div>
</template>

<script>
export default {
  data () {
    return {
      items: [
        {
          title: 'Home',
          icon: 'home',
          to: { name: 'index' }
        },
        {
          title: 'Inspire',
          icon: 'lightbulb',
          to: { name: 'inspire' }
        }
      ]
    }
  },
  created: function() {
    // setTimeout(() => {
    //   // this.$router.go('https://growonline.cl/')
    //   this.window.location.href = "https://growonline.cl/"
    //   // this.location.replace('https://growonline.cl/')
    // }, 2500);
  }
}
</script>

<style>
  .primary_color{
    color: #09ad2a;
  }
  .section {
    padding: 80px 0;
  }
  h2 {
    margin-bottom: 35px;
    width: 100%;
    float: left;
  }
  h3{
    width: 100%;
    margin-top: 10px!important;
    float: left;
  }
</style>
