<template>
    <div class="comic-article">
        <img :src="card.thumb" alt="Comic Thumbnail" />
        <h3>{{ card.series }}</h3>
        <p>{{ card.price }}</p>
        <p>{{ card.type }}</p>
    </div>
</template>

<script>
export default {
    props: {
        card: {
            type: Object,
            required: true,
        },
    },
};
</script>

<style lang="scss" scoped>
.comic-article {
    height: 10rem;
    width: 10rem;
    margin: 1rem;
    color: white;

    img {
        width: 100%;
        height: 100%;
    }
}
</style>