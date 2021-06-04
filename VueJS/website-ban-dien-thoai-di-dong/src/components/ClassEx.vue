<template>
  <div :class="classObject"></div>
</template>

<script>
export default {
    name: 'ClassEx',
    data() {
        return {
            isActive: true,
            error: null
        }
    },
    computed: {
    classObject() {
        return {
            active: this.isActive && !this.error,
            'text-danger': this.error && this.error.type === 'fatal'
            }
        }
    }
}
</script>

<style>

</style>