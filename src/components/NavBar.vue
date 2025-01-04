<script setup>
</script>

<template>
  <nav>
    <ul>
      <li>
        <router-link to="/">Dashboard</router-link>
      </li>
      <li>
        <router-link to="/about">Projets</router-link>
      </li>
      <li>
        <router-link to="/about">History</router-link>
      </li>
    </ul>
  </nav>
</template>

<style>
nav {
  display: flex;
  flex-direction: column;
}

nav ul {
  list-style: none;
  padding: 0;
}

nav a {
  text-decoration: none;
  color: white;
}
</style>
