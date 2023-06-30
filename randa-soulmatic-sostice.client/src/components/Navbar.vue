<template>
  <div class="d-flex justify-content-between my-3 text-uppercase bg-secondary">
    <p class="fw-bold fs-5">Soulmatic Solstice</p>
    <p class="selectable">about</p>
    <p class="selectable">services</p>
    <p class="selectable">contact</p>
    <Login />
  </div>
</template>

<script>
import Login from './Login.vue';
export default {
  setup() {
    return {}
  },
  components: { Login }
}
</script>

<style scoped>

</style>
