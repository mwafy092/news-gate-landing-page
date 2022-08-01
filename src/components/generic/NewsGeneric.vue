<template>
    <div
        :class="[
            'news__for__you',
            position && 'news__for__you--h',
            img && 'news__for__you__image__placement',
        ]"
    >
        <div class="news__for__you__text">
            <div
                :class="[
                    'news__for__you__text__title',
                    position && 'news__for__you--dir',
                ]"
            >
                <div class="news__for__you__title__source">
                    <div class="news__for__you__img">
                        <img src="../../assets/ahramlogo.png" alt="" />
                    </div>
                    <p>بوابة الأهرام</p>
                </div>
                <img
                    src="../../assets/dotted-gray.jpeg"
                    alt=""
                    class="dotted__icon"
                />
            </div>
            <div class="news__for__you__main__text">
                موعد مباراة بيراميدز وزاناكو في الكونفدرالية الإفريقية والقناة
                الناقلة
            </div>
            <div
                :class="[
                    'news__for__you__footer',
                    position && 'news__for__you--dir',
                ]"
            >
                <div class="news__for__you__date">
                    <span class="news__for__you__news__source">أخبار مصر</span>
                    .
                    <span class="news__for__you__timing">منذ ساعتين</span>
                </div>
                <div class="news__for__you__controller">
                    <p>292</p>
                    <img src="../../assets/like-gray.png" alt="" />
                </div>
            </div>
        </div>
        <div class="news__for__you__image" v-if="!img">
            <img src="../../assets/news.jpeg" />
        </div>
    </div>
</template>

<script>
export default {
    name: 'NewsGeneric',
    props: ['position', 'img'],
};
</script>

<style lang="scss">
@import '../../styles/news-for-you.scss';
</style>
