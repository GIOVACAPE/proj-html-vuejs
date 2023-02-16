<script>
export default {
    name: 'WhiteButton',
    props: { textWhite: String }
}
</script>

<template>
    <button type="button" class="btn">{{ textWhite }}</button>
</template>

<style lang="scss" scoped>
button {
    background-color: rgb(230, 227, 227);
    color: #ff0052;
    box-shadow: #ff0052 3px 4px;
    font-weight: 700;

    &:hover {
        color: #ff0052;
        background-color: #fff;

    }
}
</style>