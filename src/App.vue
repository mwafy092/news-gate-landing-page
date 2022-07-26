<template>
    <div class="container">
        <NewsFeeds />
        <NewsForYou />
    </div>
</template>

<script>
import NewsFeeds from './components/NewsFeeds.vue';
import NewsForYou from './components/NewsForYou.vue';
export default {
    name: 'App',
    components: {
        NewsFeeds,
        NewsForYou,
    },
};
</script>

<style lang="scss">
body {
    background-color: #f4f4f4;
}
</style>
