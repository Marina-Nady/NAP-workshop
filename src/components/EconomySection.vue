<template>
<div class="generic-section">
  <generic-title title=" اقتصاد " />
    <div class="economy-cards">
                <generic-card
          img="https://picsum.photos/id/237/500/300"
          postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
        />
                <generic-card
          img="https://picsum.photos/id/238/500/300"
          postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
        />
                <generic-card
          img="https://picsum.photos/id/239/500/300"
          postTitle="موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية.. والقناة الناقلة"
        />

    </div>
</div>
</template>

<script>
import GenericTitle from "./GenericTitle.vue";
import GenericCard from "./GenericCard.vue";
import '../assets/styling/EconomySection.scss'

    export default {
        name:'EconomySection',
        components: {
            GenericTitle,
            GenericCard,
        },

        
    }
</script>

