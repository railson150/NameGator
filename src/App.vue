<template>
  <div>
    <div id="slogan" class="text-center">
      <h1>NomeGator</h1>
      <br />
      <h6 class="text-secondary">Gerador de Nomes utilizando Vue.js, GraphQl e Node</h6>
    </div>
    <div id="main">
      <DomainList></DomainList>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";
import "font-awesome/css/font-awesome.css";
import DomainList from "./components/DomainList";

export default {
  name: "App",
  components: {
    DomainList
  }
};
</script>

<style>
#slogan {
  margin: 30px 0px;
}
#main {
  background-color: #f1f1f1;
  padding: 30px 0px;
}
</style>
