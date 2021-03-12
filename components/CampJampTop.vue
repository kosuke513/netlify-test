<template>
  <img
    class="to-top-button"
    src="~@/assets/to_top_button.gif"
    @click="jampToTop()"
  />
</template>

<script>
export default {
  methods: {
    jampToTop() {
      window.scroll(0, 164)
    },
  },
}
</script>

<style scoped>
img {
  cursor: pointer;
  position: relative;
  left: 65%;
  margin-top: 30px;
  margin-bottom: 30px;
}
</style>
