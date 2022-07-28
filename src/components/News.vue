<template>
<div class="generic-section">
  <generic-title title="اخبار من أجلك" />
  <div class="news-section">
    <generic-card
      img="https://picsum.photos/id/237/500/300"
      postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
    />
    <generic-card
      img="https://picsum.photos/id/240/500/300"
      postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
    />
    <div class="sm-card-container">
      <generic-card
        img="https://picsum.photos/id/238/500/300"
        postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
        class="sm-card"
      />
      <generic-card
        img="https://picsum.photos/id/237/500/300"
        postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
        class="sm-card"
      />
    </div>
    <div class="sm-card-container">
      <generic-card
        img="https://picsum.photos/id/239/500/300"
        postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
        class="sm-card"
      />
      <generic-card
        img="https://picsum.photos/seed/picsum/500/300"
        postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
        class="sm-card"
      />
    </div>
    <generic-card
      img="https://picsum.photos/id/239/500/300"
      postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
    />
    <generic-card
      img="https://picsum.photos/id/238/500/300"
      postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
    />
  </div>
</div>
</template>

<script>
import GenericCard from "./GenericCard.vue";
import GenericTitle from "./GenericTitle.vue";

import "../assets/styling/News.scss";
export default {
  name: "NewsSection",
  components: {
    GenericCard,
    GenericTitle,
  },
};
</script>
