<template>
  <div id="root">
    <p>{{ originalPrice }}</p>
    <p>{{ doublePrice }}</p>
    <p>{{ triplePrice }}}</p>
  </div>
</template>
<script>
export default {
  computed: {
    originalPrice() {
      this.$store.getters.originalPrice ;
    },
    doublePrice() {
      this.$store.getters.doublePrice;
    },
    triplePrice() {
      this.$store.getters.triplePrice;
    }
  }
}
</script>
<style>

</style>