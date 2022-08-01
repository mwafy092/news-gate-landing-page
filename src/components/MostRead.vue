<template>
    <div class="row g-4 my-5">
        <div class="col-xl-8">
            <div class="section__title">
                <span class="section__title__border"></span>
                الاكثر قراءة
            </div>
            <div class="row g-4">
                <div class="col-lg-6">
                    <NewsGeneric />
                </div>
                <div class="col-lg-6 d-grid gap-4">
                    <NewsGeneric position="h" />
                    <NewsGeneric position="h" />
                </div>
                <div class="col-lg-6">
                    <NewsGeneric position="h" />
                </div>
                <div class="col-lg-6">
                    <NewsGeneric position="h" />
                </div>
            </div>
        </div>
        <div class="col-xl-4">
            <div class="section__title" style="color: #b50d0d">
                <span class="section__title__border"></span>
                اخبار عاجلة
            </div>
            <div class="row">
                <div class="col-12">
                    <NewsGeneric position="h" img="false" />
                </div>
                <div class="col-12">
                    <NewsGeneric position="h" img="false" />
                </div>
                <div class="col-12">
                    <NewsGeneric position="h" img="false" />
                </div>
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
