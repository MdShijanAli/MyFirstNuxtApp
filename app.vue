<template>

<header>
    <nav>
      <ul class="menu">
        <li><NuxtLink to="/">Home</NuxtLink></li>
        <li><NuxtLink to="/about">About</NuxtLink></li>
      </ul>
    </nav>
  </header>
  <div>
   <h1>Welcome to My Nuxt Project</h1>
  </div>

  <NuxtPage />
</template>


<style scoped>
.menu{
  list-style: none;
  display: flex;
  gap: 10px;
}
</style>