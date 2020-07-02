<template>
    <v-container>
        <v-row class="name">

                <v-col class="col-12">
                    <h1>Yuta</h1>
                </v-col>
        </v-row>
    </v-container>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Poiret+One&display=swap');

    h1 {
        font-family: 'Poiret One', cursive;
        text-align: center;
        font-size: 3rem;
        letter-spacing: 1rem;
    }
    .name{
        padding: 1.4rem;
    }
</style>