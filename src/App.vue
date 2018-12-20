<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/> -->
    <Wedding/>
  </div>
</template>
<script>
import Wedding from "@/views/Wedding";
export default {
  components: {
    Wedding
  }
}
</script>
