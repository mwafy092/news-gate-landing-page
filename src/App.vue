<template>
    <div class="container">
        <NewsFeeds />
        <NewsForYou />
        <MostRead />
        <EcoNews />
    </div>
    <div class="loading__screen" v-if="loading">
        <ClipLoader :loading="loading" color="#fff" size="60px" />
    </div>
</template>

<script>
import NewsFeeds from './components/NewsFeeds.vue';
import NewsForYou from './components/NewsForYou.vue';
import MostRead from './components/MostRead.vue';
import EcoNews from './components/EcoNews.vue';
import ClipLoader from 'vue-spinner/src/ClipLoader.vue';

export default {
    name: 'App',
    components: {
        NewsFeeds,
        NewsForYou,
        MostRead,
        EcoNews,
        ClipLoader,
    },
    data() {
        return {
            loading: false,
        };
    },
    mounted: function () {
        this.loading = true;
        document.body.classList.add('overflow__hidden');
        setTimeout(() => {
            this.loading = false;
            document.body.classList.remove('overflow__hidden');
        }, 1500);
    },
};
</script>

<style lang="scss">
body {
    background-color: #f4f4f4;
    padding: 20px;
}
.overflow__hidden {
    overflow-y: hidden !important;
}
.loading__screen {
    background-color: #000;
    height: 100vh;
    width: 100vw;
    position: absolute;
    top: 0;
    bottom: 0;
    right: 0;
    left: 0;
    z-index: 99999;
    display: grid;
    justify-content: center;
    align-content: center;
    opacity: 0.9;
}
</style>
