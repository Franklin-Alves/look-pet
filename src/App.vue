<template>
  <Navbar />
  <router-view/>
</template>

<script>
import Navbar from './components/Navbar.vue';

export default {
  name: 'App',
  components: {
    Navbar
  }
}
</script>

<style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins';
  }

  #app{
    width: 100%;
    height: 100%;
  }

  .link-type-1 {
  width: 150px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 16px;
  text-transform: uppercase;
  padding: 5px 0;
  text-decoration: none;
  background-color: navy;
  color: #fff000;
  border-radius: 20px;
}
</style>