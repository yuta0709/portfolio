<template>
    <div>
        <CardTitle :title="title"></CardTitle>
        <CardContent :content="content"></CardContent>
    </div>
</template>

<script>
    import CardTitle from "@/components/atoms/CardTitle";
    import CardContent from "@/components/atoms/CardContent";

    export default {
        name: "Card",
        components: {
            CardTitle,
            CardContent
        },
        props: {
            title: {
                type: String,
                required: true
            },
            content: {
                type: String,
                required: true
            },

        }
    }
</script>

<style scoped>

</style>