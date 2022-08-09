<template>
  <div>
    <h2>{{ name }}</h2>
    <div :class="classStr"></div>
  </div>
</template>

<script>
export default Vue.extend({
  name: "Bing",
  data() {
    return {
      name: "冰",
      classStr: "demo",
    };
  },
});
</script>

<style>
.demo {
  width: 200px;
  height: 200px;
  background-color: dodgerblue;
}
</style>