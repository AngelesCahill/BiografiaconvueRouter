<template>
  <div class="hello">
     <div class="card" style="width: 18rem;">
  <img src="../assets/img/116.JPG" class="card-img-top" alt="imagen">
  <div class="card-body">
    <h5 class="card-title">M. Angeles </h5>
    <p class="card-text">"La vida es una obra de teatro que no permite ensayos; por eso canta, ríe, baila, llora y vive intensamente cada momento de tu vida…antes que el telón baje y la obra termine sin aplausos" Charles Chaplin</p>
    <ul>
      <li>Colegio: Verbo Divino de Los Angeles</li>
      <li>Estudios: Interpretacion</li>
      <li>Ocupación: Corredora de Propiedades</li>
      <li>Estado Civil: Casada</li>
      <li>Hijos: 2</li>
      <li>Hobby: Pintura y Mosaicos</li>
    </ul>
  </div>
</div> 
  </div>
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
<style scoped>
h3 {
  margin: 40px 0 0;
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
