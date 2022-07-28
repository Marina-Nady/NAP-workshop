<template>
  <div class="third-section">
    <generic-title title="الاكثر قراءة" class="most-read-title"/>

    <div class="most-read ">
      <div class="most-read-cards">
        <generic-card
          img="https://picsum.photos/id/238/500/300"
          postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
        />
        <div class="sm-card-container">
          <generic-card
            img="https://picsum.photos/id/237/500/300"
            postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
            class="sm-card"
          />

          <generic-card
            img="https://picsum.photos/id/239/500/300"
            postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
            class="sm-card"
          />
        </div>
        <div class="most-read-bottom">
          <generic-card
            img="https://picsum.photos/id/240/500/300"
            postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
            class="sm-card"
          />
          <generic-card
            img="https://picsum.photos/id/241/500/300"
            postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
            class="sm-card"
          />
        </div>
      </div>
    </div>

    <generic-title title="اخبار عاجلة" class="urgent-news-title"/>

    <!-- <div class="urgent-news"> -->
    <div class="sm-card-container without-image">
      <generic-card
        postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
        class="sm-card"
        hide="hide-img"
      />

      <generic-card
        postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
        class="sm-card"
        hide="hide-img"
      />
      <generic-card
        postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
        class="sm-card"
        hide="hide-img"
      />
    </div>

    <!-- </div> -->
  </div>
</template>

<script>
import GenericTitle from "./GenericTitle.vue";
import GenericCard from "./GenericCard.vue";
import "../assets/styling/MostRead.scss";

export default {
  name: "MostRead",
  components: {
    GenericTitle,
    GenericCard,
  },
};
</script>
