<template>
  <div id="demo">{{ fullName }}</div>
</template>

<script>
export default {
    name: 'Watch',
    data() {
    return {
      firstName: 'Foo',
      lastName: 'Bar',
      fullName: 'Foo Bar'
    }
  },
  watch: {
    firstName(val) {
      this.fullName = val + ' ' + this.lastName
    },
    lastName(val) {
      this.fullName = this.firstName + ' ' + val
    }
  }
}
</script>

<style>

</style>