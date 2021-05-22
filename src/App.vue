<template>
  <div id="app">
    <b-navbar type="dark" variant="dark">
      <b-navbar-nav>
        <b-nav-item href="#"></b-nav-item>
        <b-nav-item href="#">Система моніторингу стану</b-nav-item>
      </b-navbar-nav>
    </b-navbar>
    <div class="container mt-3">
      <b-card
        title=""
        tag="article"
        style="width: 600px; height: 400px"
        class="mb-2"
      >
        <div class="content">
          <img class="img" src="~@/assets/img/1.png" alt="" />
          <b-card-text> Температура: 18 C </b-card-text>
        </div>
      </b-card>
      <b-card
        title=""
        tag="article"
        style="width: 600px; height: 400px"
        class="mb-2"
      >
         <div class="content">
          <img class="img" src="~@/assets/img/2.png" alt="" />
          <b-card-text> Вологісті: 67 % </b-card-text>
        </div>
      </b-card>
      <b-card
        title=""
        tag="article"
        style="width: 600px; height: 400px"
        class="mb-2"
      >
         <div class="content">
          <img class="img" src="~@/assets/img/3.png" alt="" />
          <b-card-text> Освітленість: 150 Люкс </b-card-text>
        </div>
      </b-card>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
};
</script>

<style lang="scss">
.container {
  padding-top: 150px;
  display: flex;
  gap: 80px;
}
.img {
  width: 300px;
}
.content {
  height: 300px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 50px;
  font-size: 20px;
  font-weight: bold;
}
</style>
