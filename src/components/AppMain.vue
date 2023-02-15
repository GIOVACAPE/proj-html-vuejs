<script >
import Today from './macroSezioni/main/Today.vue'
import Any from './macroSezioni/main/Any.vue'
import News from './macroSezioni/main/News.vue'
import VideoMain from './macroSezioni/main/VideoMain.vue'
import Who from './macroSezioni/main/Who.vue'
import Testimonials from './macroSezioni/main/Testimonials.vue'
import Team from './macroSezioni/main/Team.vue'
import Shop from './macroSezioni/main/Shop.vue'
import Partner from './macroSezioni/main/Partner.vue'
export default {
    name: 'AppMain',
    components: { Today, Any, Shop, Partner, Team, Testimonials, Who, News, VideoMain }
}

</script>

<template>
    <section id="today" class="text-center">
        <today></today>
    </section>
    <section id="who" class="text-center">
        <who></who>
    </section>
    <section id="any" class="text-center">
        <any></any>
    </section>
    <section id="team" class="text-center">
        <team></team>
    </section>
    <section id="video" class="text-center">
        <video-main></video-main>
    </section>
    <section id="shop" class="text-center">
        <shop></shop>
    </section>
    <section id="partner" class="text-center">
        <partner></partner>
    </section>
    <section id="news" class="text-center">
        <news></news>
    </section>
    <section id="testimonials" class="text-center">
        <testimonials></testimonials>
    </section>
</template>

<style lang="scss" >

</style>
