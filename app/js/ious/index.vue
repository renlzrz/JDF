<template>
    <div>
        <Header></Header>
        <Slider></Slider>
        <Welfare></Welfare>
        <Service></Service>
        <Footer cname="mfooter"></Footer>
        <Navbar></Navbar>

    </div>
</template>

<script>
    import Header from "../public/header"
    import Slider from "./islider"
    import Welfare from "./welfare"
    import Service from "./service"
    import Footer from "../public/footer"
    import Navbar from "../public/navbar"
    export default {
        components: {
            Header,
            Slider,
            Footer,
            Navbar,
            Welfare,
            Service

        }
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
