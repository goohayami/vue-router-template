<template>
  <header></header>
  <div class="main-container">
    <nav>
      <router-link class="router" to="/">HOME</router-link><br />
      <router-link class="router" to="/add1">ADD1</router-link><br />
      <router-link class="router" to="/add2">ADD2</router-link><br />
      <router-link class="router" to="/add3">ADD3</router-link><br />
    </nav>
    <router-view></router-view>
  </div>
</template>

<script></script>

<style>
nav {
  display: flex;
  justify-content: space-between;
  padding: 5px 40px;
  background-color: azure;
}
</style>
