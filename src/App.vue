<template>
  <nav>
    <NavBar text="Home"/>
    <NavBar text="About Us"/>
    <NavBar text="Services"/>
    <NavBar text="Help?"/>
  </nav>
  <div class="form">
    <form>
      <InputView type="text" placeholder="First Name" />
      <InputView type="text" placeholder="Last Name" />
      <InputView type="text" placeholder="Comment" />
      <ButtonView text="ADD" />
    </form>
  </div>
  <div class="container">
    <Card />
    <Card />
  </div>
</template>

<script>

import NavBar from './components/NavBar.vue';
import InputView from './components/InputView.vue';
import ButtonView from './components/ButtonView.vue';
import Card from './components/CardView.vue'
export default {
  components: {
    NavBar,
    InputView,
    ButtonView,
    Card
  },
}
</script>

<style>
  body{
    font-family: sans-serif;
  }
  nav {
    background: rgb(207, 7, 41);
    margin: 10px 50px;
    display: flex;
    padding: 15px;
    border-radius: 5px;
  }
  .form {
    display: flex;
    justify-content: center;
  }
  form{
    padding: 20px;
    width: 30%;
    box-shadow: rgba(0, 0, 0, 0.12) 0px 1px 3px, rgba(0, 0, 0, 0.24) 0px 1px 2px;
  }

</style>
