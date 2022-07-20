<template>
  <button>{{text}}</button>
</template>

<script>
export default {
  props : {
    text: String,
  }
}
</script>

<style>
  button {
    width: 100%;
    padding: 10px;
    background: green;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    color: white;
  }
  button:hover {
    background: rgb(4, 180, 4);
  }
</style>