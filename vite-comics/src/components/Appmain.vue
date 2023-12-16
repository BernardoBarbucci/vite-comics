<template>
    <main>
        <section id="content">
        </section>
        <section id="categories">
            <div class="container">
                <ul class="comics-categ">
                    <li class="comic-card">
                        <img src="../assets/vue-dc-comics-1/img/buy-comics-digital-comics.png" class="comic-img" alt="digital comics">
                        <p>DIGITAL COMICS</p>
                    </li>
                    <li class="comic-card">
                        <img src="../assets/vue-dc-comics-1/img/buy-comics-merchandise.png" class="comic-img" alt="merch">
                        <p>DC MERCHANDISE</p>
                    </li>
                    <li class="comic-card">
                        <img src="../assets/vue-dc-comics-1/img/buy-comics-subscriptions.png" class="comic-img" alt="subs">
                        <p>SUBSCRIPTION</p>
                    </li>
                    <li class="comic-card">
                        <img src="../assets/vue-dc-comics-1/img/buy-comics-shop-locator.png" class="comic-img" alt="shops location">
                        <p>COMIC SHOP LOCATOR</p>
                    </li>
                    <li class="comic-card">
                        <img src="../assets/vue-dc-comics-1/img/buy-dc-power-visa.svg" class="last-comic-img" alt="battery">
                        <p>DC POWER VISA</p>
                    </li>
                </ul>
            </div>
        </section>
    </main>
</template>

<script>
export default {
    name: 'Appmain'
}
</script>

<style lang="scss" scoped>
.last-comic-img{
    height: 1.7rem;
}
#content{
    background-image: url('../assets/vue-dc-comics-1/img/jumbotron.jpg');
    
}
</style>