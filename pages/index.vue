<template>
  <div>
    <br> <br>
    <div class="applogo">
    <AppLogo />
    </div>
    <section class="container">

      <tensorflowExample />
    </section>
  </div>
</template>

<script>
  import AppLogo from '~/components/AppLogo.vue'
  import tensorflowExample from '~/components/tensorflowExample.vue'
  export default {
    components: {
      AppLogo,
      tensorflowExample
    }
  }

</script>

<style>
.applogo{
  margin: 0 auto;
  text-align: center;


}
  .container {
    min-height: 85vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }

  .title {
    font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    /* 1 */
    display: block;
    font-weight: 300;
    font-size: 100px;
    color: #35495e;
    letter-spacing: 1px;
  }

  .subtitle {
    font-weight: 300;
    font-size: 42px;
    color: #526488;
    word-spacing: 5px;
    padding-bottom: 15px;
  }

  .links {
    padding-top: 15px;
  }

</style>
