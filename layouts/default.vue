<template>
  <div>
    <p>hello from layout</p>
    <!-- <NuxtPage /> -->
    <nav>
      <NuxtLink to="/">home</NuxtLink>
      <NuxtLink to="about">About</NuxtLink>
      <NuxtLink to="profile">profile</NuxtLink>

    </nav>
    <slot></slot>
  </div>
</template>
