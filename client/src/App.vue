<template>
  <div id="app">
    <Navbar/>
    <br>
    <br>
    <div class="container">
      <router-view/>
    </div>
  </div>
</template>
<script>
import { mapGetters } from "vuex";
import Navbar from "@/components/Navbar";
export default {
  components: {
    Navbar
  }
};
</script>
<style>
.card {
  border-radius: 0px;
}
.btn {
  border-radius: 0px;
}
</style>
