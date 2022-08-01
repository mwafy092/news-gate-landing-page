<template>
    <div
        class="row news__feeds gy-2 g-md-3 g-lg-4 my-5"
        style="--bs-gutter-y: 14px"
    >
        <div class="col-12 col-md-12 col-lg-8">
            <swiper
                :pagination="{ clickable: true }"
                :modules="modules"
                class="mySwiper"
            >
                <swiper-slide v-for="n in 4" :key="n">
                    <NFGeneric />
                </swiper-slide>
            </swiper>
        </div>
        <div class="col-12 col-md-12 col-lg-4 news__feeds__latest">
            <div class="row gy-2 g-md-4 g-lg-1" style="--bs-gutter-y: 14px">
                <div class="news__feeds__main col-md-6 col-lg-12">
                    <NFGeneric />
                </div>
                <div class="news__feeds__main col-md-6 col-lg-12">
                    <NFGeneric />
                </div>
            </div>
        </div>
    </div>
</template>

<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from 'swiper/vue';

// Import Swiper styles
import 'swiper/css';

import 'swiper/css/pagination';
import { Pagination } from 'swiper';
import NFGeneric from './generic/NFGeneric.vue';
export default {
    name: 'NewsFeeds',
    components: {
        Swiper,
        SwiperSlide,
        NFGeneric,
    },
    setup() {
        return {
            modules: [Pagination],
        };
    },
};
</script>

<style lang="scss">
@import '../styles/news-feeds.scss';
</style>
