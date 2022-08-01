<template>
    <div class="row g-4 my-5">
        <div class="section__title">
            <span>
                <span class="section__title__border"></span>
                اقتصاد
            </span>
        </div>
        <div class="col-12 col-lg-6 col-xl-4" v-for="n in 3" :key="n">
            <NewsGeneric />
        </div>
    </div>
</template>

<script>
import NewsGeneric from './generic/NewsGeneric.vue';
export default {
    name: 'EcoNews',
    components: {
        NewsGeneric,
    },
};
</script>

<style lang="scss"></style>
