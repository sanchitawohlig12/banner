<template>
  <div v-if="!$vuetify.breakpoint.smAndDown">
    <img class="one" src="/images/one.jpg" alt="" />
  </div>
</template>

<script>
export default {}
</script>

<style>
.one {
  width: 100%;
  height: 100%;
  /* position: absolute; */
}
</style>