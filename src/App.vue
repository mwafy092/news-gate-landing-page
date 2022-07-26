<template>
    <div class="container">
        <NewsFeeds />
    </div>
</template>

<script>
import NewsFeeds from './components/NewsFeeds.vue';
export default {
    name: 'App',
    components: {
        NewsFeeds,
    },
};
</script>

<style lang="scss">
body {
    background-color: #f4f4f4;
}
</style>
