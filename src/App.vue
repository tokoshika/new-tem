<template>
  <header>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </header>

  <section>
    <div>
      <router-view />
      <Home />
    </div>
  </section>
</template>

<script>
</script>

<style>
#app {
  margin: 0;
  padding: 0;
}
body {
  background: rgb(231, 226, 226);
  font-size: 32px;
  text-align: center;
  margin: 0;
  padding: 0;
}
p {
  margin: 0;
}
section {
  margin-top: 0;
  margin-left: 12%;
  margin-right: 12%;
  background: rgb(218, 195, 195);
  margin-bottom: 0;
}

header {
  margin: 0;
  padding: 0;
  z-index: 999;
  width: 100%;
  color: white;
  background-color: black;
  position: fixed;
}
</style>
