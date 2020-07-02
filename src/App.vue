<template>

    <v-container>
        <Header/>
        <hr>
        <About/>
        <hr>
        <Skills/>
        <hr>
        <Contact/>
    </v-container>

</template>

<script>

    import Header from "@/components/organisms/Header";
    import Skills from "@/components/organisms/Skills";
    import About from "@/components/organisms/About"
    import Contact from "@/components/organisms/Contact";

    export default {
        name: 'App',

        components: {
            Header,
            Skills,
            About,
            Contact

        },

        data: () => ({
            //
        }),
    };
</script>
