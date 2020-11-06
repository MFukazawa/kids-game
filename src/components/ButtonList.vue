<template>
  <div class="flex justify-center items-center">
    <SingleButton v-for="i in 10" :key="i.index" text="asdfasdf" />
  </div>
</template>

<script>
import SingleButton from './SingleButton'

export default {
components: {
  SingleButton
}
}
</script>

<style>

</style>