<template>
    <header>
        <div class="container">
            <div class="logo">
                <img src="../assets/vue-dc-comics-1/img/dc-logo.png" alt="logo">
            </div>
            <nav class="navbar">
                <ul class="nav-list">
                    <li>CHARACTER</li>
                    <li>COMICS</li>
                    <li>MOVIES</li>
                    <li>TV</li>
                    <li>GAMES</li>
                    <li>COLLECTIBLES</li>
                    <li>VIDEOS</li>
                    <li>FANS</li>
                    <li>NEWS</li>
                    <li>SHOP</li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
export default {
    name: 'Appheader'
}
</script>
    
<style lang="scss" scoped>
.nav-list>li {
    font-size: .8rem;
    font-weight: 500;
    margin: 8px;
    transition: border-bottom 0.3s ease;
    &:hover {
        color: rgb(47 131 241);
        font-weight: bold;
        // qua sopra si potrebbe collegare in qualche modo al second-color?
    }
}
.logo{
    height: 80%;
    img{
        height: 100%;
    }
    img:hover{
        filter: drop-shadow(0 0 1rem  rgb(47 131 241));
    }
}
</style>