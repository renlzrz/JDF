<template>
    <section :class="cname" >
        <swiper :options="options" :not-next-tick="options.notNextTick">
            <!-- slides -->
            <swiper-slide v-for="item in items" :key="item.href">
                <router-link :to="{name: item.href}">
                    <img :src="item.src" alt="">
                </router-link>
            </swiper-slide>
            <!-- Optional controls -->
            <div class="swiper-pagination"  v-if="options.pagination"></div>

        </swiper>
    </section>
</template>

<script>
    import {swiper,swiperSlide} from "vue-awesome-swiper"
    export default {
        name: "slider",
        comments: {
            swiper,
            swiperSlide
        },
        props: {
            options: {
                type:Object,
                default() {
                    return {
                        autoplay:true,
                        loop:true,
                        pagination: {
                            el: ".swiper-pagination"
                        },
                        notNextTick:false
                    }
                }
            },
            items: {
                type:Array,
                default() {
                    return [{href:'',src:''}];
                }

            }

        },
        data() {
            return {
                swiperOption: {
                    // some swiper options/callbacks
                    // 所有的参数同 swiper 官方 api 参数
                    // ...
                }
            }
        },
    }
</script>

<style lang="scss" scoped>
    @import "~swiper/dist/css/swiper.css";
    @import "../../css/element.scss";
    .panel {
        @include panel;
    }


</style>