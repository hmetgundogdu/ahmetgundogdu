<template>
  <header>{{ title }}</header>
</template>

<script>
const title = "Ahmet Furkan Gundogdu - @hmetgundogdu";

export default {
  data: () => ({
    title,
  })
};
</script>

<style scoped>
header {
  font-size: 1.1em;
  font-weight: 900;
  white-space: inherit;
  color: white;
  background-color: #2c3e50;
  width: 100%;
  text-align: left;
}
</style>