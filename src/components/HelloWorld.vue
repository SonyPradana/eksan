<template>
<!-- html -->
  <h1>Nama Saya</h1>
  <h2>{{ nama }}</h2>
</template>

<script>
// js
export default {
  data() {
    return {
      nama: 'eksan'
    }
  },
}
</script>

<style scoped>
/* css */
h1 {
  color: red;
}
</style>
