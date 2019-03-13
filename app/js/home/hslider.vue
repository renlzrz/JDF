<template>
    <article>
        <Slider></Slider>
        <section class="list">

        </section>

    </article>
</template>

<script>
    import Slider from "../core/slider"
    export default {
        name: "hslider",
        components: {
            Slider
        },
        data() {
            return {
                items: []
            }
        }
    }
</script>

<style scoped>

</style>