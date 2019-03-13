<template>
    <div>
        <Header></Header>
        <Slider></Slider>
        <Welfare></Welfare>
        <Footer></Footer>
        <Navbar></Navbar>

    </div>
</template>

<script>
    import Header from "../public/header"
    import Slider from "./islider"
    import Welfare from "./welfare"
    import Footer from "../public/footer"
    import Navbar from "../public/navbar"
    export default {
        components: {
            Header,
            Slider,
            Footer,
            Navbar,
            Welfare

        }
    }
</script>

<style lang="scss" scoped>


</style>
