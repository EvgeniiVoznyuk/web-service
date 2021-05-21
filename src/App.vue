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
      style="width: 500px; height: 600px;"
      class="mb-2"
    >
    </b-card>
    <b-card
      title=""
      tag="article"
      style="width: 500px; height: 600px;"
      class="mb-2"
    >
    </b-card>
    <b-card
      title=""
      tag="article"
      style="width: 500px; height: 600px;"
      class="mb-2"
    >
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
  gap: 60px;
}
</style>
