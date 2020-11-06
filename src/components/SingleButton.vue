<template>
  <div class="border border-black flex items-center justify-center p-6">
    {{ text }}
  </div>
</template>

<script>
export default {
props: {
  text: {
    type: String,
    default: ''
  }
}
}
</script>

<style>

</style>