<script setup>
</script>

<template>
  <header>
    <h1 class="nav-logo"><router-link class="not-text-link" :to="{ name: 'Home' }">Axel Marcial</router-link></h1>
    <nav>
      <router-link class="not-text-link link-hover" :to="{ name: 'About' }">About</router-link>
      <router-link class="not-text-link link-hover" :to="{ name: 'Work' }">Work</router-link>
      <router-link class="not-text-link link-hover" :to="{ name: 'Contact' }">Contact</router-link>
    </nav>
  </header>
</template>

<style scoped>
  header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: var(--pad-nav-top) var(--pad-nav-x);
  }
  h1 a{
    display: flex;
    gap: 1rem;
    font-size: var(--fs-nav-logo);
    text-transform: uppercase;
    font-weight: var(--fw-extrabold);
  }
  nav{
    display: flex;
    align-items: center;
    gap: 2rem;
  }
  nav a{
    font-size: var(--fs-nav-link);
    font-weight: var(--fw-medium);
    text-transform: uppercase;
  }
</style>
