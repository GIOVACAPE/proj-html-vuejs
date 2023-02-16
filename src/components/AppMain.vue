<script>
import TodaySection from './macroSezioni/main/TodaySection.vue'
import WhoSection from './macroSezioni/main/WhoSection.vue'
import AnySection from './macroSezioni/main/AnySection.vue'
import TeamSection from './macroSezioni/main/TeamSection.vue'
import VideoSection from './macroSezioni/main/VideoSection.vue'
import ShopSection from './macroSezioni/main/ShopSection.vue'
import PartnerSection from './macroSezioni/main/PartnerSection.vue'
import NewsSection from './macroSezioni/main/NewsSection.vue'
import TestimonialsSection from './macroSezioni/main/TestimonialsSection.vue'
export default {
    name: 'AppMain',
    components: { TodaySection, WhoSection, AnySection, TeamSection, VideoSection, ShopSection, PartnerSection, NewsSection, TestimonialsSection }
}
</script>

<template>
    <section id="today" class="text-center">
        <today-section></today-section>
    </section>
    <section id="who">
        <div class="custom-mis">
            <who-section></who-section>
        </div>
    </section>
    <section id="any" class="text-center">
        <any-section></any-section>
    </section>
    <section id="team" class="text-center">
        <team-section></team-section>
    </section>
    <section id="video" class="text-center">
        <video-section></video-section>
    </section>
    <section id="shop" class="text-center">
        <shop-section></shop-section>
    </section>
    <section id="partner" class="text-center">
        <partner-section></partner-section>
    </section>
    <section id="news" class="text-center">
        <news-section></news-section>
    </section>
    <section id="testimonials" class="text-center">
        <testimonials-section></testimonials-section>
    </section>
</template>

<style lang="scss" scoped>
#today {
    background-color: #131661;
    padding: 3.5rem;
}

#who {
    background-color: #131661;
    padding: 3.5rem;

    .custom-mis {
        max-width: 1140px;
        margin: 0 auto;
    }
}

#any {
    background-image: url('imgs/bg (1).jpg');
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    padding: 3.5rem;
}

#team {
    background-color: #131661;
    padding: 3.5rem;
}

#video {
    background-image: url('imgs/bg (3).jpg');
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    padding: 3.5rem;
}

#shop {
    background-color: #131661;
    padding: 3.5rem;
}

#partner {
    background-color: #131661;
    padding: 3rem;
}

#news {
    background-image: url('imgs/bg (2).jpg');
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    padding: 3.5rem;
}

#testimonials {
    background-color: #131661;
    background-image: url('imgs/bg.png');
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    padding: 3.5rem;
}
</style>