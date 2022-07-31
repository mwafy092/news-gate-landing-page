<template>
    <div
        class="row news__feeds gy-2 g-md-3 g-lg-4 my-5"
        style="--bs-gutter-y: 14px"
    >
        <div class="col-12 col-md-12 col-lg-8">
            <swiper
                :pagination="{ clickable: true }"
                :modules="modules"
                class="mySwiper"
            >
                <swiper-slide
                    ><div class="news__feeds__main">
                        <img src="../assets/news.jpeg" />
                        <div class="news__details">
                            <div class="news__details__title">
                                <div class="news__details__title__info">
                                    <div class="news__details__title__source">
                                        <img
                                            src="../assets/ahramlogo.png"
                                            alt=""
                                        />
                                    </div>
                                    <p>بوابة الأهرام</p>
                                </div>
                                <div class="news__details__title__controllers">
                                    <div class="news__details__like">
                                        <p>٢٩٢</p>
                                        <img src="../assets/like.png" alt="" />
                                    </div>
                                    <div class="separator"></div>
                                    <img src="../assets/dotted.png" alt="" />
                                </div>
                            </div>
                            <div class="news__details__info">
                                <p class="news__details__info__main">
                                    الرئيس السيسي يوجه بالمحافظة على استمرارية
                                    المخزون الإستراتيجي للدولة من السلع الغذائية
                                </p>
                                <div class="news__details__info__date">
                                    <span>أخبار مصر</span>
                                    .
                                    <span>منذ ساعتين</span>
                                </div>
                            </div>
                        </div>
                    </div></swiper-slide
                >
                <swiper-slide
                    ><div class="news__feeds__main">
                        <img src="../assets/news.jpeg" />
                        <div class="news__details">
                            <div class="news__details__title">
                                <div class="news__details__title__info">
                                    <div class="news__details__title__source">
                                        <img
                                            src="../assets/ahramlogo.png"
                                            alt=""
                                        />
                                    </div>
                                    <p>بوابة الأهرام</p>
                                </div>
                                <div class="news__details__title__controllers">
                                    <div class="news__details__like">
                                        <p>٢٩٢</p>
                                        <img src="../assets/like.png" alt="" />
                                    </div>
                                    <div class="separator"></div>
                                    <img src="../assets/dotted.png" alt="" />
                                </div>
                            </div>
                            <div class="news__details__info">
                                <p class="news__details__info__main">
                                    الرئيس السيسي يوجه بالمحافظة على استمرارية
                                    المخزون الإستراتيجي للدولة من السلع الغذائية
                                </p>
                                <div class="news__details__info__date">
                                    <span>أخبار مصر</span>
                                    .
                                    <span>منذ ساعتين</span>
                                </div>
                            </div>
                        </div>
                    </div></swiper-slide
                >
                <swiper-slide
                    ><div class="news__feeds__main">
                        <img src="../assets/news.jpeg" />
                        <div class="news__details">
                            <div class="news__details__title">
                                <div class="news__details__title__info">
                                    <div class="news__details__title__source">
                                        <img
                                            src="../assets/ahramlogo.png"
                                            alt=""
                                        />
                                    </div>
                                    <p>بوابة الأهرام</p>
                                </div>
                                <div class="news__details__title__controllers">
                                    <div class="news__details__like">
                                        <p>٢٩٢</p>
                                        <img src="../assets/like.png" alt="" />
                                    </div>
                                    <div class="separator"></div>
                                    <img src="../assets/dotted.png" alt="" />
                                </div>
                            </div>
                            <div class="news__details__info">
                                <p class="news__details__info__main">
                                    الرئيس السيسي يوجه بالمحافظة على استمرارية
                                    المخزون الإستراتيجي للدولة من السلع الغذائية
                                </p>
                                <div class="news__details__info__date">
                                    <span>أخبار مصر</span>
                                    .
                                    <span>منذ ساعتين</span>
                                </div>
                            </div>
                        </div>
                    </div></swiper-slide
                >
                <swiper-slide
                    ><div class="news__feeds__main">
                        <img src="../assets/news.jpeg" />
                        <div class="news__details">
                            <div class="news__details__title">
                                <div class="news__details__title__info">
                                    <div class="news__details__title__source">
                                        <img
                                            src="../assets/ahramlogo.png"
                                            alt=""
                                        />
                                    </div>
                                    <p>بوابة الأهرام</p>
                                </div>
                                <div class="news__details__title__controllers">
                                    <div class="news__details__like">
                                        <p>٢٩٢</p>
                                        <img src="../assets/like.png" alt="" />
                                    </div>
                                    <div class="separator"></div>
                                    <img src="../assets/dotted.png" alt="" />
                                </div>
                            </div>
                            <div class="news__details__info">
                                <p class="news__details__info__main">
                                    الرئيس السيسي يوجه بالمحافظة على استمرارية
                                    المخزون الإستراتيجي للدولة من السلع الغذائية
                                </p>
                                <div class="news__details__info__date">
                                    <span>أخبار مصر</span>
                                    .
                                    <span>منذ ساعتين</span>
                                </div>
                            </div>
                        </div>
                    </div></swiper-slide
                >
            </swiper>
        </div>
        <div class="col-12 col-md-12 col-lg-4 news__feeds__latest">
            <div class="row gy-2 g-md-4 g-lg-1" style="--bs-gutter-y: 14px">
                <div class="news__feeds__main col-md-6 col-lg-12">
                    <img src="../assets/news.jpeg" />
                    <div class="news__details">
                        <div class="news__details__title">
                            <div class="news__details__title__info">
                                <div class="news__details__title__source">
                                    <img src="../assets/ahramlogo.png" alt="" />
                                </div>
                                <p>بوابة الأهرام</p>
                            </div>
                            <div class="news__details__title__controllers">
                                <div class="news__details__like">
                                    <p>٢٩٢</p>
                                    <img src="../assets/like.png" alt="" />
                                </div>
                                <div class="separator"></div>
                                <img src="../assets/dotted.png" alt="" />
                            </div>
                        </div>
                        <div class="news__details__info">
                            <p class="news__details__info__main">
                                الرئيس السيسي يوجه بالمحافظة على استمرارية
                                المخزون الإستراتيجي للدولة من السلع الغذائية
                            </p>
                            <div class="news__details__info__date">
                                <span>أخبار مصر</span>
                                .
                                <span>منذ ساعتين</span>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="news__feeds__main col-md-6 col-lg-12">
                    <img src="../assets/news.jpeg" />
                    <div class="news__details">
                        <div class="news__details__title">
                            <div class="news__details__title__info">
                                <div class="news__details__title__source">
                                    <img src="../assets/ahramlogo.png" alt="" />
                                </div>
                                <p>بوابة الأهرام</p>
                            </div>
                            <div class="news__details__title__controllers">
                                <div class="news__details__like">
                                    <p>٢٩٢</p>
                                    <img src="../assets/like.png" alt="" />
                                </div>
                                <div class="separator"></div>
                                <img src="../assets/dotted.png" alt="" />
                            </div>
                        </div>
                        <div class="news__details__info">
                            <p class="news__details__info__main">
                                الرئيس السيسي يوجه بالمحافظة على استمرارية
                                المخزون الإستراتيجي للدولة من السلع الغذائية
                            </p>
                            <div class="news__details__info__date">
                                <span>أخبار مصر</span>
                                .
                                <span>منذ ساعتين</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from 'swiper/vue';

// Import Swiper styles
import 'swiper/css';

import 'swiper/css/pagination';
import { Pagination } from 'swiper';

export default {
    name: 'NewsFeeds',
    components: {
        Swiper,
        SwiperSlide,
    },
    setup() {
        return {
            modules: [Pagination],
        };
    },
};
</script>

<style lang="scss">
@import '../styles/news-feeds.scss';
</style>
