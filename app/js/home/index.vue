<template lang="html">
    <div>
        <Header></Header>
        <Slider></Slider>
        <Novice></Novice>
        <Borrow></Borrow>
        <Money></Money>
        <Product></Product>
        <Live></Live>
        <Footer></Footer>
        <Navbar></Navbar>
    </div>
</template>

<script>
    import Header from "../public/header"
    import Slider from "./hslider"
    import Novice from "./novice"
    import Borrow from "./borrow"
    import Money from "./money"
    import Product from "./product"
    import Live from "./life"
    import Footer from "../public/footer"
    import Navbar from "../public/navbar"
    export default {
            components: {
                Header,
                Slider,
                Novice,
                Borrow,
                Money,
                Product,
                Live,
                Footer,
                Navbar
            }
    }
</script>

<style lang="scss">
  @import '../../css/reset.scss';

</style>
