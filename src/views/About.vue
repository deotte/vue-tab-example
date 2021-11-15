<template>
  <div class="about">
    <h1>This is an about page</h1>
    <div class="links">
      <router-link to="/about">History</router-link>
      <router-link to="/about/contact">Contact</router-link>
    </div>
    <router-view></router-view>
  </div>
</template>
