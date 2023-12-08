<template>
  <div>
    <header>
      <div class="wrapper">
        <nav>
          <RouterLink to="/">首页</RouterLink>
          <RouterLink to="/about">反诈资讯</RouterLink>
          <RouterLink to="/about"></RouterLink>
          <RouterLink to="/about">反诈资讯</RouterLink>
        </nav>
      </div>
    </header>
    <main>
      <router-view/>
    </main>
    <footer>
    </footer>
  </div>
</template>

<script setup lang="ts">
import {RouterLink} from "vue-router";

</script>

<style scoped>

</style>