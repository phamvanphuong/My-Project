<template>
    <div id="v-model-basic" class="demo">
        <input v-model="message" placeholder="edit me" />
        <p>Message is: {{ message }}</p>
    </div>
    <div id="v-model-textarea" class="demo">
    <span>Multiline message is:</span>
        <p style="white-space: pre-line;">{{ message }}</p>
        <br />
    <textarea v-model="message" placeholder="add multiple lines"></textarea>
    </div>
</template>

<script>
export default {
    name: 'FormInputBindings',
     data() {
    return {
      message: ''
    }
  }
}
</script>

<style>
    .demo {
  font-family: sans-serif;
  border: 1px solid #eee;
  border-radius: 2px;
  padding: 20px 30px;
  margin-top: 1em;
  margin-bottom: 40px;
  user-select: none;
  overflow-x: auto;
}
</style>