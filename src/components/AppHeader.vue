<script>
import InfoHeader from './macroSezioni/header/InfoHeader.vue';
import MainHeader from './macroSezioni/header/MainHeader.vue';
import JumboHeader from './macroSezioni/header/JumboHeader.vue';
export default {
    name: 'AppHeader',
    components: { InfoHeader, MainHeader, JumboHeader }
}
</script>

<template>
    <div class="custom-bgi">
        <div class="container">
            <info-header></info-header>
            <main-header></main-header>
            <jumbo-header></jumbo-header>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.custom-bgi {
    background-image: url('imgs/bg.jpg');
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    height: 100vh;
}
</style>