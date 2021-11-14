<template>
  <div class="main-content">
    <img src="../../assets/loading-burger.png" width="200" />
    <div class="loading">
      <h3>Loading</h3>
      <div class="loading-bar">
        <div class="percentage" :style="{ width: percentage + '%' }"></div>
      </div>
    </div>
  </div>
</template>

<script>
import "./Loading.css";
// import router from "../../router";

export default {
  name: "Loading",
  
  methods: {
  // redirectPage() {
  //   setInterval(() => {
  //     // alert("Mounted Loading");
  //     // router.push("/about") ;
  //   }, 3000);
  // },  
  },

  mounted() {
    console.log("Componente Loading inicializado")
  },
  
};
</script>
