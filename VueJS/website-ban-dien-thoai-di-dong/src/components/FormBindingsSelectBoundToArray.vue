<template>
  <div id="v-model-select" class="demo">
  <select v-model="selected" multiple>
    <option>A</option>
    <option>B</option>
    <option>C</option>
  </select>
  <br />
  <span>Selected: {{ selected }}</span>
</div>
</template>

<script>
export default {
    name: 'FormBindingsSelectBoundToArray',
    data() {
    return {
      selected: ''
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