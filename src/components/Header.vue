<template>
    <header>
        <div class="container text-center">
            <img src="../assets/img/dc-logo.png" alt="">
            <ul>
                <li><a href="#">characters</a></li>
                <li><a href="#">comics</a></li>
                <li><a href="#">movies</a></li>
                <li><a href="#">tv</a></li>
                <li><a href="#">games</a></li>
                <li class="active"><a href="#" class="blue">collectibles</a></li>
                <li><a href="#">videos</a></li>
                <li><a href="#">fans</a></li>
                <li><a href="#">news</a></li>
                <li><a href="#">shop</a></li>
            </ul>
        </div>
    </header>
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
    header {
        height: 100px;
        background-color: $headerBackground;
        width: 100%;

        .container {
            margin: 0 auto;
            display: flex;
            height: 100%;
            align-items: center;
            justify-content: space-between;

        img {
            height: 70px;
            margin: 1em;
        }

        ul {
            list-style: none;
            height: 100%;
            display: flex;
            justify-content: center;
            li {
                display: flex;
                align-items: center;
                text-transform: uppercase;
                margin: 0 1em 0 1em;
                a {
                    text-decoration: none;
                    display: inline-block;
                    font-weight: 500;
                    font-size: 0.9em;
                    height: 100%;
                    line-height: 100px;
                    color: black;
                    &.blue,
                    &:hover {
                        color: $lightblue;
                        border-bottom: 0.2em solid $lightblue;
                    }
                }
                
            }
        }
    }
    }
    
</style>