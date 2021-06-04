<template>
    <div id="conditional-rendering">
        <span v-if="seen">Now you see me</span>
    </div>
</template>

<script>
export default {
    data() {
    return {
      seen: true
    }
  }
}
</script>

<style>

</style>