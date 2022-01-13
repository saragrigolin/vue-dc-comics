<template>
    <main>
        <div class="container">
            <h1>--> Content goes here</h1>
        </div>
    </main>
</template>

<script>
export default {
    name: 'Header',
    data(){
        return {
            title: "Lorem Ipsum"
        }
    }
}
</script>

<style lang="scss" scoped>
    @import "../assets/scss/style.scss";
    main {
        height: 100px;
        background-color: $mainBackground;
        h1 {
            color: white;
        }
    }
</style>