<template>
  <div class="hello-world">
    <h3 class="text-2xl">{{ msg }}</h3>
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

<style scoped lang="scss"></style>
