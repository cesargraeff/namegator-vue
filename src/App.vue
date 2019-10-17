<template>
  <div>
    <div id="slogan" class="text-center">
      <h1>NameGator</h1>
      <br>
      <h6 class="text-secondary">Gerador de nomes utilizando Vue.js, GraphQL e Node.js</h6>
    </div>
    <div id="main">
		<DomainList></DomainList>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.min.css";
import "font-awesome/css/font-awesome.min.css";
import DomainList from "./components/DomainList";

export default {
	name: "app",
	components: {
		DomainList
	}
};
</script>

<style>
#slogan{
    margin-top: 30px;
    margin-bottom: 30px;
}
#main{
  background-color: #F1F1F1;
  padding: 30px 0;
}
</style>