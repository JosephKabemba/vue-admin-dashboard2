<template>
  <div class="home">
    <Header />
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld
      msg="Joseph Madras, author of the most popular Java cross-platform mobile framework"
    />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import Header from "@/components/Header.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    Header
  }
};
</script>
