<template>
    <div>
        <p>{{content}}</p>
    </div>
</template>

<script>
    export default {
        name: "CardContent",
        props:{
            content:{
                type:String,
                required:true
            }
        }
    }
</script>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Poiret+One&display=swap');
    p {
        font-family: 'Poiret One', cursive;
        text-align: center;
        padding: 10px;
        font-size: 1.2rem;
        letter-spacing: 0.4rem;
    }
</style>