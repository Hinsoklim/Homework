<template>
   <li>{{text}}</li>
</template>

<script>
export default {
    props : {
        text: String,
    }
}
</script>

<style>
    li {
        list-style: none;
        text-transform: uppercase;
        margin: 0 15px;
        color: white;
        padding: 15px;
        border-radius: 5px;
    }
    li:hover {
        background: rgb(70, 1, 24);
        cursor: pointer;
    }
</style>