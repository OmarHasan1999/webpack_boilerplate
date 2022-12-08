<template>
    <div id="main">
    </div>
  </template>
  
  <script>
  import { store } from "./js/store.js";
  import {animate} from "./js/cube.js";

  export default {
    name: "App",
    data() {
      return {
        store,
      };
    },
    mounted(){
        animate();
    },
  };
  </script>
  
  <style>
  @import "./css/App.css";
  </style>
  