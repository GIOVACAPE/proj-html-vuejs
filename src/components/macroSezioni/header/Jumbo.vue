<script >
import Bianco from '../../Microsezioni/bottoni/Bianco.vue';
import Title from '../../Microsezioni/title/Title.vue'
import SText from '../../Microsezioni/text/SText.vue';
export default {
    name: 'Jumbo',
    components: { Bianco, Title, SText },
    data() {
        return {
            textWhite: 'JOIS US TODAY',
            title: 'GENUINE MONEY TRASACTION',
            text: 'Assertively Communicate AN Expanded Array Of Mindshare Rather Than Diverse Technologies For Magnetic Applications Eamlessly Virtual Then Conveniently Monetize Synergistic Human Capital'
        }
    }
}
</script>

<template>
    <div class="og">
        <h1 class="my-3">ONLINE GAME</h1>
        <title class="my-3" :title="title"></title>
        <s-text :text="text"></s-text>
        <bianco class="my-3" :textWhite="textWhite"></bianco>
    </div>
</template>

<style lang="scss">
.og {
    margin: 130px 0;
    width: 55%;

    h1 {
        font-weight: 700;
        font-size: 50px;
    }
}
</style>
