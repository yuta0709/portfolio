<template>
    <div>
        <h3>{{title}}</h3>
    </div>
</template>

<script>
    export default {
        name: "CardTitle",
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

    h3 {
        font-family: 'Poiret One', cursive;
        text-align: center;
        padding: 20px;
        font-size: 2rem;
        letter-spacing: 0.4rem;
    }
</style>