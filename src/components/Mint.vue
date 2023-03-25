
<template>
    <div class="hello">
        <img class="backgroundimg" src="https://pbs.twimg.com/profile_banners/1308196317852655618/1614891929/1500x500" />
    </div>
</template>

<script>
export default {
    name: 'HelloWorld',
    props: {
        msg: String
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.backgroundimg {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.hello {
    width: 100%;
    height: 100%;
    margin: 0;
}
</style>