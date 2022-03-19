<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>Build a powerful ecosystem. Soon.</h3>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<style scoped lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Outfit:wght@800&display=swap");

.hello {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

   & h1, h3 {
    margin: 0;
    font-size: calc(1rem + 5vw);
    font-family: "Outfit", sans-serif;
    color: white;
    text-shadow: 0 0 5px white;
  }

   & h3 {
    font-size: 15pt;
   }
}
</style>
