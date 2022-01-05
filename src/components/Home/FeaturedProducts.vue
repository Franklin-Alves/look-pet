<template>
  <div class="featured">
    <h1>Produtos em Destaque</h1>
    <div class="featured-container">
      <div class="card-product">
        <img src="img/racao.jpg" alt="" />
        <div class="card-content">
          <h3>Ração Magnus</h3>
          <p>R$ 121,00</p>
        </div>
      </div>
      <div class="card-product">
        <img src="img/racao.jpg" alt="" />
        <div class="card-content">
          <h3>Ração Magnus</h3>
          <p>R$ 121,00</p>
        </div>
      </div>
      <div class="card-product">
        <img src="img/racao.jpg" alt="" />
        <div class="card-content">
          <h3>Ração Magnus</h3>
          <p>R$ 121,00</p>
        </div>
      </div>
      <div class="card-product">
        <img src="img/racao.jpg" alt="" />
        <div class="card-content">
          <h3>Ração Magnus</h3>
          <p>R$ 121,00</p>
        </div>
      </div>
    </div>
    <a href="" class="link-type-1">Ver Produtos</a>
  </div>
</template>

<script>
export default {
  name: "FeaturedProducts",
};
</script>

<style scoped>

.featured h1 {
  font-size: 25px;
  margin: 60px 0 40px 30px;
}

.featured-container {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 20px;
  
}

.card-product {
  width: 250px;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  padding: 10px 0;
  border: 2px solid #dcdcdc;
  border-radius: 6px;
}

.card-product img {
  width: 200px;
}

.card-product h3 {
  font-size: 16px;
}

 .featured .link-type-1 {
  margin: 40px auto;

}

</style>