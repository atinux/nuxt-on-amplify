<script setup>
const rendered = useState(() => new Date().toISOString())
</script>

<template>
  <div>
    <h1>Hello Nuxt + AWS Amplify</h1>
    <p>Rendered at: {{ rendered }}</p>
  </div>
</template>
