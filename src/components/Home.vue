<template>
  <div class="home">
    <section class="hero">
      <div class="hero-body">
        <div class="container">
          <h1 class="title"></h1>
          <div class="is-two-thirds column ispaddingless">
            <h2 class="subtitle is-4"></h2>
            <a href="" class="button is-large is-primary"></a>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
<script>
export default {
  name: 'home',
  data(){ return{
      heading:"Soaring to new heights",
      subheading:"Lorem ipsum"
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="sass" scoped>
@import "../mq"
</style>
