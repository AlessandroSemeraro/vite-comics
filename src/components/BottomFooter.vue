<script>
export default {

}
</script>
<template>
    <section class="bottomFooter">
        <div class="container-bottomfooter">
            <button>Sign-up now!</button>
            <div class="footer-socials-bar">
                <p class="text-socials">Follow us</p>
                <ul>
                    <li><img src="../../vue-dc-comics-1/img/footer-facebook.png" alt="facebook logo"></li>
                    <li><img src="../../vue-dc-comics-1/img/footer-twitter.png" alt="twitter logo"></li>
                    <li><img src="../../vue-dc-comics-1/img/footer-youtube.png" alt="youtube logo"></li>
                    <li><img src="../../vue-dc-comics-1/img/footer-pinterest.png" alt="pinterest logo"></li>
                    <li><img src="../../vue-dc-comics-1/img/footer-periscope.png" alt="periscope logo"></li>
                </ul>
            </div>
        </div>
    </section>
</template>
<style lang="scss" scoped>
@use '../style/partials/mixin';
@use '../style/partials/variables';

button {
    padding: 0.8rem 1.2rem;
    text-transform: uppercase;
    background-color: #1E1E1E;
    color: white;
    border: 2px solid #0282F9;
}

ul {
    list-style-type: none;
    display: flex;
}

li{
    margin-right: 1rem;
}

.bottomFooter {
    position: relative;
    z-index: 5;
    width: variables.$full-width;
    height: 11vh;
    background-color: #1E1E1E;
    display: flex;
    justify-content: center;

    .container-bottomfooter {
        width: variables.$container-width;
        display: flex;
        justify-content: space-between;
        align-items: center;

        .footer-socials-bar {
            display: flex;
            align-items: center;

            .text-socials {
                color: #0282F9;
                text-transform: uppercase;
                font-family: sans-serif;
                font-weight: 700;
                margin-right: 1rem;
            }
        }
    }
}
</style>