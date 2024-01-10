<script setup>
import { useRoute } from "vue-router"
</script>
<template>
  <h1>programming view page</h1>
  <h2>{{ useRoute().params.id }}</h2>
  <h2>{{ useRoute().query.name }} {{ useRoute().query.lastname }}</h2>
  <h3>Age: {{ $route.query.age }}</h3>
</template>