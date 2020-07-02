<template>

    <v-container>
        <Header/>
        <About/>
        <Skills/>
    </v-container>

</template>

<script>

    import Header from "@/components/organisms/Header";
    import Skills from "@/components/organisms/Skills";
    import About from "@/components/organisms/About";

    export default {
        name: 'App',

        components: {
            Header,
            Skills,
            About

        },

        data: () => ({
            //
        }),
    };
</script>
