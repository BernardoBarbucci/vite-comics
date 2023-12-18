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
    margin-right: 1rem;
    margin-left: 1rem;
    margin-bottom: 5rem;
    color: white;
    transition: transform .4s ease-in-out;

    &:hover {
        transform: scale(1.25);
        transform-origin: center center;
    }

    img {
        width: 100%;
        height: 100%;
    }

    h3 {
        font-size: .8rem;
        font-weight: 600;
    }

    p {
        font-size: .7rem;
    }
}
</style>