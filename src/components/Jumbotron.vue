<template>
    <div class="background">
    </div>
</template>

<script>
export default {
    name: 'Jumbotron',
    data(){
        return {
            
        }
    }
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/style.scss";
    .background {
        background-image: url(../assets/img/jumbotron.jpg);
        background-size: cover;
        height: 400px;
    }
</style>