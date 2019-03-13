<template lang="html">
    <div>
        <Header></Header>
        <Slider></Slider>
        <Ada></Ada>
        <Money></Money>
        <Adb></Adb>
        <Finance></Finance>
        <Footer></Footer>
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
            Money,
            Finance
        }
    }
</script>

<style lang="scss">
    @import '../../css/reset.scss';

</style>
