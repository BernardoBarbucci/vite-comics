<template>
    <div class="comic-card">
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
            type: Array,
            required: true,
        },
    },
};
</script>
