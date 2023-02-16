<script>
import SectionTitle from '../../utilities/SectionTitle.vue'
import Title from '../../utilities/Title.vue'
import ShopCard from '../../utilities/ShopCard.vue'
export default {
    name: 'ShopSection',
    components: { SectionTitle, Title, ShopCard },
    data() {
        return {
            section: 'GAMER T-SHIRT`S',
            title: 'EXPLORE OUR PRODUCTS',
            items: [
                { img: 'toro', name: 'PRIMA MAGLIA', price: '$380.00' },
                { img: 'toro 2', name: 'SECONDA MAGLIA', price: '$380.00' },
                { img: 'toro 3', name: 'TERZA MAGLIA', price: '$380.00' },
                { img: 'toro 4', name: 'MAGLIA PORTIERE', price: '$380.00' }
            ]
        }
    }
}
</script>

<template>
    <section-title :section="section"></section-title>
    <Title :title="title"></Title>
    <shop-card :items="items"></shop-card>
    <hr>
</template>

<style lang="scss" scoped>
hr {
    color: #fff;
    width: 50%;
    margin: 45px 350px;
}
</style>