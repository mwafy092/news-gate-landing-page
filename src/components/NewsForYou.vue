<template>
    <div class="section__title">
        <span class="section__title__border"></span>
        اخبار من اجلك
    </div>
    <div class="row g-4">
        <div class="col-md-6 col-xl-4">
            <NewsGeneric />
        </div>
        <div class="col-md-6 col-xl-4">
            <NewsGeneric />
        </div>
        <div class="col-md-6 col-xl-4 d-grid gap-4">
            <NewsGeneric position="h" />
            <NewsGeneric position="h" />
        </div>
        <div class="col-md-6 col-xl-4 d-grid gap-4">
            <NewsGeneric position="h" />
            <NewsGeneric position="h" />
        </div>
        <div class="col-md-6 col-xl-4">
            <NewsGeneric />
        </div>
        <div class="col-md-6 col-xl-4">
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
