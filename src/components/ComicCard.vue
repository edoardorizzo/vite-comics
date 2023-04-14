<script>
export default {
    name: 'ComicCard',
    props: {
        image: String,
        name: String,
    },
    data() {
        return {

        }
    }

}
</script>

<template>
    <div class="card">
        <div class="comics_container">
            <img :src="image" :alt="name">
        </div>
        <div class="comic_name"> {{ name }}</div>
    </div>
</template>



<style lang="scss" scoped>
@use '../assets/partials/variables' as *;

.card {
    width: calc(100% / 8);
    height: 240px;
    margin: 2rem 1rem;

    .comics_container {
        width: 100%;
        height: 240px;
    }

    img {
        width: 100%;
        height: 100%;
    }

    .comic_name {
        margin: 8px 0;
        color: $white;
        font-weight: bold;

        &:hover {
            color: $blue;
        }
    }
}
</style>