<template>

    <v-container>
        <v-row class="name">
            <v-col class="col-12"><Title title="Contact"></Title></v-col>
            <v-col class="col-sm-12 col-md-4"><a href="https://www.instagram.com/yutakd/"><CardTitle title="Instagram"/></a></v-col>
            <v-col class="col-sm-12 col-md-4"><a href="https://twitter.com/yuta_2I"><CardTitle title="Twitter"/></a></v-col>
            <v-col class="col-sm-12 col-md-4"><a href="mailto://yuta0709dev@gmail.com"><CardTitle title="Mail"/></a></v-col>
        </v-row>

    </v-container>
</template>

<script>
    import Title from "../atoms/Title";
    import CardTitle from "../atoms/CardTitle";

    export default {
        name: "Contact",
        components: {
            Title,
            CardTitle
        }
    }
</script>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Poiret+One&display=swap');

    h1 {
        font-family: 'Poiret One', cursive;
        text-align: center;
        font-size: 3rem;
        letter-spacing: 1rem;
    }

    .name {
        padding: 1.4rem;
    }
    a{
        color: black;
    }
</style>



