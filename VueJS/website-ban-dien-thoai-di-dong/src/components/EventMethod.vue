<template>
    <div id="event-with-method">
        <!-- `greet` is the name of a method defined below -->
        <button class="btn" @click="greet">Greet</button>
    </div>
</template>

<script>
export default {
    name: 'EventMethod',
    data() {
    return {
      name: 'Vue.js'
    }
  },
  methods: {
    greet(event) {
      // `this` inside methods points to the current active instance
      alert('Hello ' + this.name + '!')
      // `event` is the native DOM event
      if (event) {
        alert(event.target.tagName)
      }
    }
    
  }
}
</script>

<style>
    .btn {
        background-color: aqua;
        color: red;
    }
</style>