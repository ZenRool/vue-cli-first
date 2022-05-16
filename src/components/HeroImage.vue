<template>
  <div class="jumbo">
    <img :src="require(`../assets/img/${srcImage}`)" alt="Banner" />
  </div>
</template>

<script>
export default {
  name: "HeroImage",
  data: function () {
    return {
      srcImage: "jumbo.png",
    };
  },
};
</script>
<style scoped>
.jumbo {
  width: 100%;
  height: auto;
}
img {
  width: 100%;
  object-fit: contain;
}
</style>
