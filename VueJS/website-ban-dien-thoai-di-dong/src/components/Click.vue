<template>
    <div id="event-handling">
        <p>{{ message }}</p>
        <button class="btn" v-on:click="reverseMessage">Reverse Message</button>
    </div>
</template>

<script>
export default {
    data() {
    return {
      message: 'Hello Vue.js!'
    }
  },
  methods: {
    reverseMessage() {
      this.message = this.message
        .split('')
        .reverse()
        .join('')
    }
  }
  
}
</script>
  
<style>
  .btn {
    color:aqua;
  }
</style>