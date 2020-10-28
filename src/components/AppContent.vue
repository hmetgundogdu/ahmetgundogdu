<template>
  <section class="app-container">
    Hello I'm Ahmet, this is my first personal web site.You can find here things
    about me, cheers.
  </section>
  <section class="app-container">
    <Timeline id="hmetgundogdu" sourceType="list" :options="{ theme: 'dark' }"/>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.app-container {
  margin: 5px;
}
</style>