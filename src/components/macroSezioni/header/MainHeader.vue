<script >
import GamerLogo from '../../Microsezioni/logo/GamerLogo.vue'
import Bianco from '../../Microsezioni/bottoni/Bianco.vue';
import Rosa from '../../Microsezioni/bottoni/Rosa.vue';
export default {
    name: 'MainHeader',
    components: { GamerLogo, Bianco, Rosa },
    data() {
        return {
            voice: [
                { url: '#', text: 'HOME' },
                { url: '#', text: 'FEATURES +' },
                { url: '#', text: 'ACHIEVEMENT' },
                { url: '#', text: 'BLOG +' },
                { url: '#', text: 'CONTACT' },
            ],
            textWhite: 'LOG IN',
            textPink: 'SIGN UP'
        }
    }
}
</script>

<template>
    <div class="d-flex justify-content-between align-items-center">
        <gamer-logo></gamer-logo>
        <ul class="d-flex justify-content-between align-items-center">
            <a v-for="option in voice" href="{{ option.url }}">
                <li>{{ option.text }}</li>
            </a>
            <li>
                <Bianco :textWhite="textWhite" class="py-2 px-3 me-1"></Bianco>
                <Rosa :textPink="textPink" class="py-2 px-3"></Rosa>

            </li>
        </ul>
    </div>
</template>

<style lang="scss">
ul {
    list-style-type: none;

    a {
        color: white;
        text-decoration: none;

        li {
            padding: 0 15px;
            font-size: 15px;
            cursor: pointer;

        }
    }
}
</style>
