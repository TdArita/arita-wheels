<template>
  <svg class="icon" :class="name">
    <use :xlink:href="`#i-${name}`" />
  </svg>
</template>

<script>
export default {
  props: ['name'],
}
</script>

<style lang="scss" scoped>
.g-icon {
  width: 1em;
  height: 1em;
}
</style>
