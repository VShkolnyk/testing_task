<template>
  <div class="container">
    <img class="background" src="@/assets/images/Background.png" alt="">
    <Header/>
    <Nav/>
    <MainContent/>
  </div>
</template>

<script>
import Header from "@/components/Header";
import Nav from "@/components/Nav";
import MainContent from "@/components/MainContent";

export default {
  name: "Wrapper",
  components: {MainContent, Nav, Header}
}
</script>

<style scoped>

</style>