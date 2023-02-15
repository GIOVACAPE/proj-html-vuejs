<script >
export default {
    name: 'STitle',
    props: { section: String }
}
</script>

<template>
    <h3 class="mb-3">{{ section }}</h3>
</template>

<style lang="scss">
h3 {
    font-size: 15px;
    font-weight: 700;
    color: #ff0052;
}
</style>
