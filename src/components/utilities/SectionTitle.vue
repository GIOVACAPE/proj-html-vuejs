<script>
export default {
    name: 'SectionTitle',
    props: { section: String }
}
</script>

<template>
    <h3 class="mb-3">{{ section }}</h3>
</template>

<style lang="scss" scoped>
h3 {
    font-size: 15px;
    font-weight: 700;
    color: #ff0052;
}
</style>