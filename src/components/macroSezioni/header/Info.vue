<script >
export default {
    name: 'Info',
    data() {
        return {

        }
    }
}
</script>

<template>
    <div class="d-flex justify-content-between">
        <ul class="d-flex justify-content-between">
            <li>
                <a href="#">
                    <i class="fa-solid fa-phone"></i>
                    <span>+800-123-4567-6587</span>
                </a>
            </li>
            <li>
                <a href="">
                    <i class="fa-solid fa-location-dot"></i>
                    <span>Beaverly,New York 224 USA</span>
                </a>
            </li>
        </ul>
        <ul class="d-flex justify-content-between">
            <li> <a href="#"></a><i class="fa-brands fa-facebook-messenger"></i></li>
            <li> <a href="#"></a><i class="fa-brands fa-twitter"></i></li>
            <li> <a href="#"></a><i class="fa-brands fa-vimeo-v"></i></li>
            <li> <a href="#"></a><i class="fa-brands fa-skype"></i></li>
            <li> <a href="#"></a><i class="fa-solid fa-wifi"></i></li>
        </ul>
    </div>
</template>

<style lang="scss">
div {
    ul {
        list-style-type: none;

        li {
            padding: 10px;

            a {
                text-decoration: none;
                color: white;

                i {
                    padding: 10px;
                }
            }
        }
    }
}
</style>
