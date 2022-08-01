<template>
  <div class="school">
    <h1>{{ name }}</h1>
    <h1>{{ adress }}</h1>
  </div>
</template>

<script>
    export default {
    name: "School",
    data() {
        return {
        name: "ljs",
        adress: "nj",
        }
    },
    }
</script>

<style>
    .school {
    background-color: blue;
    }
</style>