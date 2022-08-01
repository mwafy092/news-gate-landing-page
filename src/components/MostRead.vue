<template>
    <div class="row g-4 my-5">
        <div class="col-8">
            <div class="section__title">
                <span class="section__title__border"></span>
                الاكثر قراءة
            </div>
            <div class="row g-4">
                <div class="col-12 col-lg-6">
                    <NewsGeneric />
                </div>
                <div class="col-12 col-lg-6">
                    <div class="row g-4">
                        <NewsGeneric position="h" v-for="n in 3" :key="n" />
                    </div>
                </div>

                <NewsGeneric position="h" v-for="n in 2" :key="n" />
            </div>
        </div>
        <div class="col-4">
            <div class="section__title" style="color: #b50d0d">
                <span class="section__title__border"></span>
                اخبار عاجلة
            </div>
            <div class="row">
                <NewsGeneric position="h" img="false" v-for="n in 3" :key="n" />
            </div>
        </div>
    </div>
</template>

<script>
import NewsGeneric from './generic/NewsGeneric.vue';
export default {
    name: 'MostRead',
    components: {
        NewsGeneric,
    },
};
</script>

<style lang="scss"></style>
