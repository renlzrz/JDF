<template>
    <div>
        <Header></Header>
        <Slider></Slider>
        <Daily></Daily>
        <In></In>
        <More></More>
        <Footer cname="mfooter"/>
        <Navbar></Navbar>
    </div>
</template>

<script>
    import Header from "../public/header.vue"
    import Footer from "../public/footer.vue"
    import Navbar from "../public/navbar.vue"
    import Slider from "./rslider.vue"
    import Daily from "./daily.vue"
    import In from "./in.vue"
    import More from "./more.vue"
    export default {
        components: {
            Header,
            Slider,
            Daily,
            In,
            More,
            Footer,
            Navbar,
        },
    }
</script>

<style lang="scss">
    .mfooter{
        margin-top: 0!important;
        ul{
            li:first-child{
                display: none;
            }
        }
    }
</style>
