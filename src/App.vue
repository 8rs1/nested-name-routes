<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link
      :to="{
        name: 'programming',
        query: { name: 'Ali', lastname: 'Jafari', age: 18 },
        params: { id: 1 },
        hash: '#test'
      }"
      >program</router-link
    >
    <router-link to="/about">About</router-link>
  </nav>
  <router-view />
</template>