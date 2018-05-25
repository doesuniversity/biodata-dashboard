<template>
  <section>
    <h3>{{msg}}</h3>
    <div class="container">
      <div class="row">
        <div class="col-md-6">colom 1 of 2</div>
        <div class="col-md-6">colom 2 of 2</div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import '../scss/variable.scss';

h3 {
  margin: 40px 0 0;
  color: $color_red;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
