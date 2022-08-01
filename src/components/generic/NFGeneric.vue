<template>
    <div class="news__feeds__main">
        <img src="../../assets/news.jpeg" alt="" />
        <div class="news__details">
            <div class="news__details__title">
                <div class="news__details__title__info">
                    <div class="news__details__title__source">
                        <img src="../../assets/ahramlogo.png" alt="" />
                    </div>
                    <p>بوابة الأهرام</p>
                </div>
                <div class="news__details__title__controllers">
                    <div class="news__details__like">
                        <p>٢٩٢</p>
                        <img src="../../assets/like.png" alt="" />
                    </div>
                    <div class="separator"></div>
                    <img src="../../assets/dotted.png" alt="" />
                </div>
            </div>
            <div class="news__details__info">
                <p class="news__details__info__main">
                    الرئيس السيسي يوجه بالمحافظة على استمرارية المخزون
                    الإستراتيجي للدولة من السلع الغذائية
                </p>
                <div class="news__details__info__date">
                    <span>أخبار مصر</span>
                    .
                    <span>منذ ساعتين</span>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'NFGeneric',
};
</script>

<style>
@import '../../styles/news-feeds.scss';
</style>
