<template>
  <main class="user-layout">
    <article class="sidebar">
      <p>Dashboard</p>
      <p>settings</p>
    </article>
    <section>
      <slot></slot>
    </section>
  </main>
</template>
<style scoped>
.sidebar {
  display: flex;
  flex-directon: column;
}
.user-layout{
    display:flex;
    
}
</style>
