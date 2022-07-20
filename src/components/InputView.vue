<template>
  <input type="{{type}}">
</template>

<script>
export default {
  props : {
    type: String
  }
}
</script>

<style>
  input {
    width: 100%;
    box-sizing: border-box;
    padding: 10px;
    margin: 5px 0px;
  }
</style>