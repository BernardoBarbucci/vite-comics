<template>
    <footer>
        <section id="footer-info">
            <div class="container">
                <div class="info-list-left">
                    <h1>DC COMICS</h1>
                    <ul>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                    <h1>SHOP</h1>
                    <ul>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </div>
            </div>
        </section>

    </footer>
</template>

<script>
export default {
    name: 'Appfooter'
}
</script>

<style lang="scss" scoped>
#footer-info{
    height: 18rem;
    background-image: url('../assets/vue-dc-comics-1/img/footer-bg.jpg');
    h1{
    font-size: 1rem;
    font-weight: bold;
    margin-top: 1.1rem;
    margin-bottom: .35rem;
    }
    li{
        font-size: .8rem;
        margin-bottom: .3rem;
        list-style: none;
        color: #828982;
        transition: transform 0.3s ease-in-out;
    }
    li:hover{
        transform: scale(1.2);
        transform-origin: right right;
    }
}
</style>