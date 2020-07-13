<template>
  <div class="d-flex justify-content-center">
    <div class="d-flex" style="width:1000px;">
      <flickity
        class="flickity"
        style="width:300px;"
        :options="flickityOptions"
      >
        <div class="carousel-cell">
          <img src="../assets/I.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/S.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/H.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/W.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/A.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/R.png" id="images" alt="" />
        </div>
      </flickity>
      <flickity
        class="flickity"
        style="width:300px;"
        :options="flickityOptions"
      >
        <div class="carousel-cell">
          <img src="../assets/S.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/H.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/W.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/A.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/R.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/I.png" id="images" alt="" />
        </div>
      </flickity>
      <flickity
        class="flickity"
        style="width:300px;"
        :options="flickityOptions"
      >
        <div class="carousel-cell">
          <img src="../assets/H.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/W.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/A.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/R.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/I.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/S.png" id="images" alt="" />
        </div>
      </flickity>
      <flickity
        class="flickity"
        style="width:300px;"
        :options="flickityOptions"
      >
        <div class="carousel-cell">
          <img src="../assets/W.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/A.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/R.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/I.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/S.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/H.png" id="images" alt="" />
        </div>
      </flickity>
      <flickity
        class="flickity"
        style="width:300px;"
        :options="flickityOptions"
      >
        <div class="carousel-cell">
          <img src="../assets/A.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/R.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/I.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/S.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/H.png" id="images" alt="" />
        </div>
        <div class="carousel-cell">
          <img src="../assets/W.png" id="images" alt="" />
        </div>
      </flickity>
    </div>
  </div>
</template>

<script>
import Flickity from "vue-flickity";

export default {
  components: {
    Flickity,
  },
  data() {
    return {
      items: [1, 1, 1, 1, 1, 1],
      flickityOptions: {
        initialIndex: 0,
        prevNextButtons: false,
        pageDots: false,
        groupCells: false,
        contain: true,
        autoPlay: 500,
        freeScroll: true,
        wrapAround: true,
        pauseAutoPlayOnHover: false,
        // draggable: false
        // any options from Flickity can be used
      },
    };
  },
};
</script>

<style scoped>
.carousel-cell {
  width: 320px;
  height: 400px;
  border-radius: 5px;
  margin-right: 10px;
}

#images {
  width: 40%;
}
</style>
