<template>
    <div id="inline-handler">
        <button class="btn1" @click="say('hi')">Say hi</button>
        <button class="btn2" @click="say('what')">Say what</button>
    </div>
</template>

<script>
export default {
    name: 'EventMethod1',
     methods: {
    say(message) {
      alert(message)
    }
  }
}
</script>

<style>
    .btn1 {
        color: blueviolet;
        background-color: yellow;
    }
    .btn2 {
        color:black;
        background-color: green;
    }
</style>