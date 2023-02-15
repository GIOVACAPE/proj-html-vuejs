<script >
export default {
    name: 'Bianco',
    props: { textWhite: String }
}
</script>

<template>
    <button class="btn" type="button">{{ textWhite }}</button>
</template>

<style lang="scss">
button {
    background-color: white;
    color: #ff0052;
    box-shadow: #ff0052;
    font-weight: 700;

    &:hover {
        color: #ff0052;
        background-color: white;
    }
}
</style>
