<template>
  <div id="nav">
    <router-link to="/" id="logo-url"><img id="logo" :src="logo" alt=""></router-link>
    <router-link to="/">Início</router-link>
    <router-link to="/products">Produtos</router-link>
    <router-link to="/scheduling">Agendamento</router-link>
    <router-link to="/about">Sobre</router-link>
    <router-link to="/contacts">Contatos</router-link>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  data() {
    return {
      logo: 'img/pet-shop.png'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

  #nav {
    background-color: #1E90FF;
    padding: 20px 50px;
    border-bottom: 1px solid #4682B4;
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }

  #logo-url {
    margin: auto;
    margin-left: 0;
  }

  #nav a{
    text-decoration: none;
    margin-left: 25px;
    color: #FFD700;
    font-family: 'Poppins';
    font-weight: 900;
  }
</style>
