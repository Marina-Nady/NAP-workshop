<template>
  <div class="header-section generic-section">
    <div
      id="carouselExampleIndicators"
      class="carousel slide"
      data-bs-ride="carousel"
    >
      <div class="carousel-indicators">
        <button
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide-to="0"
          class="active carousel-btn"
          aria-current="true"
          aria-label="Slide 1"
        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide-to="1"
          aria-label="Slide 2"
          class=" carousel-btn"
        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide-to="2"
          aria-label="Slide 3"
                    class=" carousel-btn"

        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide-to="3"
          aria-label="Slide 4"
                    class=" carousel-btn"

        ></button>
                <button
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide-to="4"
          aria-label="Slide 5"
                    class=" carousel-btn"

        ></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <generic-card
            img="https://picsum.photos/id/237/500/300"
            postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
            class="bg-image-card"
            custom="custom-design"
          />
        </div>
        <div class="carousel-item">
          <generic-card
            img="https://picsum.photos/id/238/500/300"
            postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
            class="bg-image-card"
            custom="custom-design"
          />
        </div>
        <div class="carousel-item">
          <generic-card
            img="https://picsum.photos/id/239/500/300"
            postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
            class="bg-image-card"
            custom="custom-design"
          />
        </div>
        <div class="carousel-item">
          <generic-card
            img="https://picsum.photos/id/239/500/300"
            postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
            class="bg-image-card"
            custom="custom-design"
          />
        </div>
      </div>
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#carouselExampleIndicators"
        data-bs-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#carouselExampleIndicators"
        data-bs-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
    <div class="sm-custom-cards">
      <generic-card
        img="https://picsum.photos/id/237/500/300"
        postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
        class="bg-image-card"
        custom="custom-design"
      />

      <generic-card
        img="https://picsum.photos/id/239/500/300"
        postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
        class="bg-image-card"
        custom="custom-design"
      />
    </div>
  </div>
</template>

<script>
import GenericCard from "./GenericCard.vue";
import "../assets/styling/HeaderSection.scss";

export default {
  name: "HeaderSection",
  components: {
    GenericCard,
  },
};
</script>
