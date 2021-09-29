<template>
  <div v-if="$vuetify.breakpoint.smAndDown">
    <img class="two" src="/mobile/375-667.jpg" alt="" />
  </div>
</template>

<script>
export default {}
</script>

<style>
.two {
  width: 100%;
  height: 100%;
  position: fixed;
}
</style>