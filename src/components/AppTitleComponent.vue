<template>
  <h1 class="titolo">{{ titolo }}</h1>
</template>

<script>
export default {
  name: "AppTitleComponent",
  data() {
    return {
      titolo: "La mia prima app con Vite!",
    };
  },
};
</script>

<style lang="css" scoped>
.titolo {
  text-align: center;
  margin-top: 8rem;
  font-size: 40px;
  color: white;
}
</style>
