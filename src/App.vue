<template>
    <div class="container">
        <NewsFeeds />
        <NewsForYou />
        <MostRead />
    </div>
</template>

<script>
import NewsFeeds from './components/NewsFeeds.vue';
import NewsForYou from './components/NewsForYou.vue';
import MostRead from './components/MostRead.vue';
export default {
    name: 'App',
    components: {
        NewsFeeds,
        NewsForYou,
        MostRead,
    },
};
</script>

<style lang="scss">
body {
    background-color: #f4f4f4;
}
</style>
