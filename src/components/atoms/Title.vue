<template>
    <div>
        <h2>{{title}}</h2>
    </div>
</template>

<script>
    export default {
        name: "Title",
        props: {
            title: {
                type: String,
                required: true
            }
        }
    }
</script>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Poiret+One&display=swap');
    h2{
        font-family: 'Poiret One', cursive;
        text-align: center;
        padding: 30px;
        font-size: 2.5rem;
        letter-spacing: 1rem;
    }
</style>