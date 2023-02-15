<script >
import Info from './macroSezioni/header/Info.vue';
import MainHeader from './macroSezioni/header/MainHeader.vue';
import Jumbo from './macroSezioni/header/Jumbo.vue';
export default {
    name: 'AppHeader',
    components: { Info, MainHeader, Jumbo }
}

</script>

<template>
    <div class="custom-bgi">
        <div class="container">
            <info></info>
            <main-header></main-header>
            <jumbo></jumbo>
        </div>
    </div>
</template>

<style lang="scss">
.custom-bgi {
    background-image: url('imgs/bg.jpg');
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    height: 100vh;
}
</style>
