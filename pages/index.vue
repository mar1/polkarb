<template>
<div id="wrapper">
  <TopBar ref="childref"/>
  <ConnectModal/>
  <Hero/>
  <Features/>
  <ModePicker/>
  <FAQ/>
  <Footer/>
  <Tutorial/>
</div>
</template>

<script lang="ts">
import Vue from 'vue'



export default Vue.extend({
  name: 'IndexPage',
    data() {
      return {

      }
    },
async mounted() {

    /*
    // We want the modal to close when the OK button is clicked
    button.onclick = function() {
    modal.style.display = "none";
    }
    */
    let button = document.getElementById("ok-btn");


  },
  methods: {

  }
})
</script>

<style>
html {
  scroll-behavior: smooth;
}
</style>