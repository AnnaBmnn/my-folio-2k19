<template>
  <div class="home">
    <div>Hello i'm</div>
    <h1 class="home__title">Anna Baumann,</h1>
    <div>a front-end developer looking for a six-month intership.</div>
    <div>
      <div>My totems emojis are </div>
      <div class="emojis">☀️🐬🥨</div>
    </div>
    <div>I had fun working on this projects</div>
    <div> yoyoyo.photos, agathe et anna, indiscipline </div>
    <div>You can find my cyber me on linkedin, instagram and github</div>
    <div>I also love to experiment cool stuff on the internet :</div>
    <div>generative design, video canvas, threes.js</div>
    <div>I also love contemporary art, sun,  big diner with my friends, scenography, italo disco music, fashion, cooking, flowers, the blaze, blurred pictures , beers, partir en week-end, the sea
</div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>
<style scoped lang="scss">
.home {
  padding: 20vh 10vw;
  font-size: 4vw;
}
.home__title {
  font-size: 6vw;
}
.emojis {
  position: relative;
  .emojis__line {
    display: flex;
    flex-direction: column;
    height: 100vh;
    font-size: 20vh;
  }
  &:hover {

  }
}
</style>
