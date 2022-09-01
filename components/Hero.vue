<template>
  <ssr-carousel
    :slides-per-page="1"
    :autoplay-delay="3"
    loop
    show-arrows
    show-dots
    class="slider_container"
  >
    <slide :index="1" class="slide slider-img">
      <div class="carousel-content">
        <div class="info">
          <p class="naturals">Naturals By Watsons</p>
          <h1>The new 2021 collection</h1>
          <p class="text">
            Known as "the miracle plant", Aloe Vera helps to nourish, moisturize
            and keep the hair looking smooth. Let your hair be flexible and
            fresh.
          </p>
          <button>SHOP NOW</button>
        </div>
        <div class="image-container">
          <img src="../assets/images/slider-image-sm.png" alt="foto" />
        </div>
      </div>
    </slide>
    <slide :index="2" class="slide slider-img">
      <div class="carousel-content">
        <div class="info">
          <p class="naturals">Naturals By Watsons</p>
          <h1>The new 2021 collection</h1>
          <p class="text">
            Known as "the miracle plant", Aloe Vera helps to nourish, moisturize
            and keep the hair looking smooth. Let your hair be flexible and
            fresh.
          </p>
          <button>SHOP NOW</button>
        </div>
        <div class="image-container">
          <img src="../assets/images/slider-image-sm.png" alt="foto" />
        </div>
      </div>
    </slide>
    <slide :index="3" class="slide slider-img">
      <div class="carousel-content">
        <div class="info">
          <p class="naturals">Naturals By Watsons</p>
          <h1>The new 2021 collection</h1>
          <p class="text">
            Known as "the miracle plant", Aloe Vera helps to nourish, moisturize
            and keep the hair looking smooth. Let your hair be flexible and
            fresh.
          </p>
          <button>SHOP NOW</button>
        </div>
        <div class="image-container">
          <img src="../assets/images/slider-image-sm.png" alt="foto" />
        </div>
      </div>
    </slide>
  </ssr-carousel>
</template>

<script>
export default {}
</script>
