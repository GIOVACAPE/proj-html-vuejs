<script>
import InfoFooter from './macroSezioni/footer/InfoFooter.vue';
import MainFooter from './macroSezioni/footer/MainFooter.vue'
import LastElement from './macroSezioni/footer/UltimaParte.vue';
export default {
    name: 'AppFooter',
    components: { InfoFooter, MainFooter, LastElement }
}
</script>

<template>
    <div class="custom-bgi">
        <div class="container">
            <info-footer></info-footer>
            <main-footer></main-footer>
        </div>
    </div>
    <last-element></last-element>


</template>

<style lang="scss" scoped>
.custom-bgi {
    background-image: url('imgs/bg (3).jpg');
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    padding: 3rem;
}
</style>