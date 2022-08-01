<template>
    <div class="generic-card">
        <div class="text-container" :class="custom">
            <div class="post-details">
                <div class="newspaper-name__right">
                    <img src="../assets/header-logo1.jpg" class="news-source" />
                    <h4 class="newspaper-title">أخبار اليوم</h4>
                </div>
                <div class="newspaper-name__left">
                    <span class="icon-dots-three-horizontal"></span>
                </div>
            </div>
            <div>
            <p class="post-info">{{postTitle}}
            </p>
            <div class="post-details">
                <div class="post-category-container">
                    <h4 class="post-category">الرياضة</h4>
                    <span class="post-category-divider">.</span>
                    <h4 class="post-time">منذ ساعتين</h4>
                </div>
                <div class="post-category-container post-category-container--likes">
                    <h4 class="post-likes">25</h4>
                    <span class="icon-like"></span>
                </div>
            </div>
            </div>
        </div>
        <div class="img-container" :class="hide">
            <img :src="img" class="image">
        </div>

    </div>
</template>

<script>
import "../assets/styling/GenericCard.scss"
    export default {
        name:'GenericCard',
        props:['postTitle','img','hide','custom']
        
    }
</script>
