<template>
    <div class="row my-5 g-4">
        <div class="section__title">
            <span class="section__title__border"></span>
            اخبار من اجلك
        </div>
        <div class="col-12 col-lg-6 col-xxl-4">
            <NewsGeneric />
        </div>
        <div class="col-12 col-lg-6 col-xxl-4">
            <NewsGeneric />
        </div>
        <div class="col-12 col-lg-6 col-xxl-4">
            <div class="row g-4">
                <NewsGeneric position="h" />
                <NewsGeneric position="h" />
            </div>
        </div>
        <div class="col-12 col-lg-6 col-xxl-4">
            <div class="row g-4">
                <NewsGeneric position="h" />
                <NewsGeneric position="h" />
            </div>
        </div>
        <div class="col-12 col-lg-6 col-xxl-4">
            <NewsGeneric />
        </div>
        <div class="col-12 col-lg-6 col-xxl-4">
            <NewsGeneric />
        </div>
    </div>
</template>

<script>
import NewsGeneric from './generic/NewsGeneric.vue';
export default {
    name: 'NewsForYou',
    components: {
        NewsGeneric,
    },
};
</script>

<style lang="scss">
@import '../styles/news-for-you.scss';
</style>
