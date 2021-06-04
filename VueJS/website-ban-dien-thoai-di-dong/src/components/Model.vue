<template>
    <div id="two-way-binding">
        <p>{{ message }}</p>
        <input class="model" v-model="message" />
    </div>
</template>

<script>
export default {
    data() {
    return {
      message: 'Hello Vue!'
    }
  }
}

</script>

<style>
    .model {
        color:aqua;
        background:blueviolet;
    }
</style>