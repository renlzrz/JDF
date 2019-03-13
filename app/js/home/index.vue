<template lang="html">
    <div>
        <Header></Header>
        <Slider></Slider>
        <Novice></Novice>
        <Borrow></Borrow>
        <Money></Money>
    </div>
</template>

<script>
    import Header from "../public/header"
    import Slider from "./hslider"
    import Novice from "./novice"
    import Borrow from "./borrow"
    import Money from "./money"
    export default {
            components: {
                Header,
                Slider,
                Novice,
                Borrow,
                Money
            }
    }
</script>

<style lang="scss">
  @import '../../css/reset.scss';

</style>
