<script >
export default {
    name: 'Stext',
    props: { text: String }
}
</script>

<template>
    <p>{{ text }}</p>
</template>

<style lang="scss">
p {
    font-size: 16px;
    line-height: 20px;
}
</style>
