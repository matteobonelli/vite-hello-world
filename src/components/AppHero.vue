<template>
    <div class="jumbotron">
        <div class="container">
            <h2>il mio jumbotron!</h2>
        </div>
    </div>
</template>

<script>
export default {
    name: 'AppHero'
}
</script>

<style lang="css" scoped>
.jumbotron {
    padding: 30px;
    background-color: #111;
    background-image: url('/images/big-bridge.jpg');

}

.container {
    width: 1170px;
    height: 600px;
    margin: 0 auto;
    padding: 0 15px;
}

h2 {
    text-align: center;
    font-size: 100px;
    color: white;
    text-transform: uppercase;
}
</style>