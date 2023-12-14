<template>
    <header>
        <div class="container">
            <div class="logo">

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
    font-size: .7rem;
    font-weight: bold;
    margin: 8px;

    &:hover {
        color: rgb(47 131 241);
        // qua sopra si potrebbe collegare in qualche modo al second-color?
    }
}
</style>