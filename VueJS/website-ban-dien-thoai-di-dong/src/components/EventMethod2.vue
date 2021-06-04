<template>
    <button @click="warn('Form cannot be submitted yet.', $event)">
        Submit
    </button>
</template>

<script>
export default {
    name: 'EventMethod2',
    methods: {
    warn(message, event) {
    // now we have access to the native event
    if (event) {
      event.preventDefault()
    }
    alert(message)
  }
}
}
</script>

<style>

</style>