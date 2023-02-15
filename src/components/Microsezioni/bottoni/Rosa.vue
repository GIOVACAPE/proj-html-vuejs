<script >
export default {
    name: 'Rosa',
    props: { textPink: String }
}
</script>

<template>
    <button type="button" class="btn">{{ textPink }}</button>
</template>

<style lang="scss">
button {
    color: white;
    box-shadow: #fff 2px 3px;
    font-weight: 700;
    background-color: rgb(55, 5, 55);

    &:hover {
        color: #fff;
        background-color: #ff0052;
    }
}
</style>
