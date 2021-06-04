<template>
    <div id="v-model-checkbox" class="demo">
        <input type="checkbox" id="checkbox" v-model="checked" />
        <label for="checkbox">{{ checked }}</label>
    </div>
</template>

<script>
export default {
    name: 'FormBindingsCheckbox',
    data() {
    return {
      checked: false
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