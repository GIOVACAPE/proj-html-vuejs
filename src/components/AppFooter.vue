<script >
import Info from './macroSezioni/footer/Info.vue'
import MainF from './macroSezioni/footer/MainF.vue'
import UltimaParte from './macroSezioni/footer/UltimaParte.vue'
export default {
    name: 'AppFooter',
    components: { Info, MainF, UltimaParte }
}
</script>

<template>
    <div class="custom-bgi">
        <div class="container">
            <info></info>
            <main-f></main-f>
        </div>
    </div>
    <ultima-parte></ultima-parte>
</template>

<style lang="scss">

</style>
