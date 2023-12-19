<script>
export default {

}
</script>
<template>
    <section class="mainFooter">
        <div class="container-mainFooter">
            <div class="container-col-footer">
                <div class="col-dc-footer">
                    <h3>DC comics</h3>
                    <ul>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                    <h3>shop</h3>
                    <ul>
                        <li>shop DC</li>
                        <li>shop DC Collectibles</li>
                    </ul>
                </div>
                <div class="col-dc-footer">
                    <h3>DC</h3>
                    <ul>
                        <li>Terms of Use</li>
                        <li>Privacy policy(new)</li>
                        <li>AD choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscription</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>    
                    </ul>
                </div>
                <div class="col-dc-footer">
                    <h3>Sites</h3>
                    <ul>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
                </div>
            </div>
            <img class="img-dc-footer" src="../../vue-dc-comics-1/img/dc-logo-bg.png" alt="">
        </div>
    </section>
</template>
<style lang="scss" scoped>
@use '../style/partials/mixin';
@use '../style/partials/variables';

img {
    width: 35rem;
    z-index: 3;
    position: absolute;
    bottom: -5rem;
    right: 0;
}

ul {
    list-style-type: none;
    margin-bottom: 1.5rem;
}

li {
    color: gray;
    font-size: 0.75rem;
    font-family: sans-serif;
    margin-bottom: 0.5rem;
}

h3 {
    text-transform: uppercase;
    color: white;
    font-family: sans-serif;
    margin-bottom: 1rem;
}

.mainFooter {
    height: 25rem;//42vh
    width: 100%;
    background: url(../../vue-dc-comics-1/img/footer-bg.jpg);
    background-size: cover;
    display: flex;
    justify-content: center;

    .container-mainFooter {
        width: variables.$container-width;
        height: 100%;
        display: flex;
        align-items: center;
        position: relative;

        .container-col-footer {
            display: flex;
            padding-top: 2rem;

            .col-dc-footer {
                display: flex;
                flex-direction: column;
                margin-right: 2rem;
            }
        }
    }
}
</style>