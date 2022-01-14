<template>
    <div class="thumb">
        <div class="img-container">
            <img :src="img" :alt="alt">
        </div>
        <span class="subtitle">{{title}}</span>
    </div>
</template>

<script>
export default {
    name: "Thumb",
    props: ["img", "alt", "title", "type", "price"],
    data(){
        return {

        }
    }
}
</script>

<style lang="scss">
.thumb {
    width: 200px;
    .img-container {
        height: 200px;
        width: 200px;
        overflow: hidden;
        margin-bottom: 1em;
        img {
            width: 100%;
        }
    }
    .subtitle {
        color: white;
        text-transform: uppercase;
        font-size: 0.8em;
    }
}
</style>