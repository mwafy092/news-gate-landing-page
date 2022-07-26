<template>
    <div class="container">
        <NewsFeeds />
        <NewsForYou />
        <MostRead />
        <EcoNews />
    </div>
</template>

<script>
import NewsFeeds from './components/NewsFeeds.vue';
import NewsForYou from './components/NewsForYou.vue';
import MostRead from './components/MostRead.vue';
import EcoNews from './components/EcoNews.vue';
export default {
    name: 'App',
    components: {
        NewsFeeds,
        NewsForYou,
        MostRead,
        EcoNews,
    },
};
</script>

<style lang="scss">
body {
    background-color: #f4f4f4;
    padding: 20px;
}
</style>
