<template>
  <div
    id="carouselExampleCaptions"
    class="carousel slide"
    data-bs-ride="carousel"
  >
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img
          src="/img/adorable-dog-with-owner-at-the-pet-shop.jpg"
          class="d-block w-100"
          alt="..."
        />
        <div class="carousel-caption d-none d-md-block">
          <h3 class="slider-description">First slide label</h3>
          <a href="#" class="link-type-1">Saiba Mais</a>
        </div>
      </div>
      <div class="carousel-item">
        <img
          src="/img/cute-little-dog-with-owners-at-the-pet-shop.jpg"
          class="d-block w-100"
          alt="..."
        />
        <div class="carousel-caption d-none d-md-block">
          <h3 class="slider-description">Second slide label</h3>
          <a href="#" class="link-type-1">Saiba Mais</a>
        </div>
      </div>
      <div class="carousel-item">
        <img
          src="/img/cute-little-dog-with-owners-at-the-pet-shop.jpg"
          class="d-block w-100"
          alt="..."
        />
        <div class="carousel-caption d-none d-md-block">
          <h3 class="slider-description">Third slide label</h3>
          <a href="#" class="link-type-1">Saiba Mais</a>
        </div>
      </div>
    </div>
    <button
      class="carousel-control-prev"
      type="button"
      data-bs-target="#carouselExampleCaptions"
      data-bs-slide="prev"
    >
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button
      class="carousel-control-next"
      type="button"
      data-bs-target="#carouselExampleCaptions"
      data-bs-slide="next"
    >
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>

</template>

<script>
export default {
  name: "Carousel",
};
</script>

<style scoped>



.carousel-caption {
  text-align: initial;
  top: 75%;
  left: 5%;
}

.carousel-caption h3 {
  margin-bottom: 40px;
}

/* .carousel-control-next {
  right: -5%;
}

.carousel-control-prev {
  left: -5%;
} */
</style>