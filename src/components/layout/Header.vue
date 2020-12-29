<template>
  <header class="header">
    <h1 class="title">Vue js - Route demo</h1>
    <div id="nav">
      <router-link to="/" class="active">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/contact">Contact</router-link>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
  .title{
    margin-bottom: 20px;
  }
  .header {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
  }

  .header a {
    color: #d4d4d4;
    padding-right: 5px;
    text-decoration: none;
    transition: all .3s;
  }

  .header a.active,
  .header a:hover,
  .header a:focus {
    color: #fff;
  }
</style>


