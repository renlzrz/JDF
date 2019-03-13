<template>
    <div>
        <Header></Header>
        <Slider></Slider>
        <Ada></Ada>
        <Money></Money>
        <Adb></Adb>
        <Finance></Finance>
        <Adc></Adc>
        <Footer cname="mfooter"></Footer>
        <Navbar></Navbar>

    </div>
</template>

<script>
    import Header from "../public/header"
    import Slider from "./mslider"
    import Ada from "./ada"
    import Money from "./money"
    import Adb from "./adb"
    import Finance from "./finance"
    import Adc from "./adc"
    import Footer from "../public/footer"
    import Navbar from "../public/navbar"
    export default {
        components: {
            Header,
            Slider,
            Footer,
            Navbar,
            Ada,
            Adb,
            Adc,
            Money,
            Finance
        }
    }
</script>

<style lang="scss" scoped>
    .mfooter {
        margin-top: 0 !important;
        ul {
            li:first-child {
                display: none;
            }
        }
    }

</style>
