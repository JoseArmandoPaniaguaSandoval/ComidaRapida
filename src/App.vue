<template>
  <div class="azul">
    <div class="container">
      <div class="row text-white">
        <div class="col-md-6 ">Nuestros  Platos  Mi cuenta  Blog Contato</div>
        <div class="col-md-6">0952 03 99 50-whatsapp:622515113  info</div>
      </div>
    </div>
  </div>
  <br>
  <header>
    <div class="container">
      <nav class="menu">

      <ul>
        <li><img src="https://www.lacocinadeelisa.es/wp-content/uploads/2020/12/logo-la-cocina-de-elisa.png" alt="Logo VUE" width="250" height="100"></li>

        <li><a class="text-white btn btn-info" href="">ENSALADA</a></li>
        <li><a class="text-white btn btn-info" href="">ARROCES</a></li>
        <li><a class="text-white btn btn-info" href="">PESCADO</a></li>
        <li><a class="text-white btn btn-info" href="">CARNES</a></li>
        <li><a class="text-white btn btn-info" href="">POSTRES</a></li>

      </ul>

    </nav>
    </div>
    <div class="container gris">
      <h5>Nuestros platos</h5>
      <p><a class="btn">inicio</a>   /    <a class="btn">Nuestros platos</a></p>
    </div>
  </header>
  <div>
    <div class="container">
      <div class="row">
        <div class="col-md-12 center azul text-white">Télefono para pedidos: 952 03 99 50   -   Whatsapp: 622 51 51 13</div>
      </div>
    </div>
  </div>
  <div class="container center">
    <h1>Ensalada y entrantes</h1>
    <card url="https://content-cocina.lecturas.com/medio/2018/07/19/ajoblanco-con-langostinos_aedfeb8f_800x800.jpg" nombre="Ajo blaco" />
    <card url="https://cocinarrecetasdepostres.net/wp-content/uploads/2019/11/Ensalada-de-Manzana-Asada-y-Radicchio.jpg" nombre="Ensalada con Manzana Asada" />
    <card url="https://images.hola.com/imagenes/cocina/recetas/20210528190446/ensalada-rucula-jamon-tomate-parmesano/0-957-715/jamon-salad-adobe-m.jpg" nombre="Ensalada de jamon serrano" />
  
  </div>

</template>


<script>
  import Card from "./components/Card.vue";
  export default{
    components: { Card},
    
  };
</script>

<style scoped>
h1 {
  text-align: center;
}
footer{
  background-color: red;
}
.center{
  align-content: center;
  text-align: center;
  align-items: center;
}
.der{
  text-align: left;
}
.gris{
  background-color: #E8EAE9;
}
.azul{
  background-color: #0A9BF3;
}

.menu ul {

  display: flex;
  padding: 0;
  margin: 0;
  list-style: none;

  }

.menu a {
  display: block;
  padding: 0.5em;
  background-color: #0A9BF3;
  text-decoration: none;
  color: #191C26;

                }

.menu a:hover {

                               background-color: #CC673B;

                }

.menu ul li ul {

                               display: none;

                }

.menu ul li a:hover + ul, .menu ul li ul:hover {

                               display: block;

                }

</style>