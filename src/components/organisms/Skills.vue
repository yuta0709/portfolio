<template>
    <div>
        <v-container>
            <v-row>
                <v-col class="col-12">
                    <Title title="Skills"></Title>
                </v-col>
            </v-row>
            <v-row>
                <v-col class="col-md-4 col-sm-12" v-for="skill in skills" :key="skill.name">
                    <Card :title="skill.name" :content="skill.detail"></Card>
                </v-col>

            </v-row>

        </v-container>
    </div>
</template>

<script>
    import Title from "@/components/atoms/Title";
    import Card from "@/components/molecules/Card";

    export default {
        name: "Skills",
        components: {
            Title,
            Card
        },
        data: function () {
            return {
                skills: [
                    {name: "Python", detail: "Django / Flask / OpenCV"},
                    {name: "JavaScript", detail: "Node.js / Express / jQuery / Socket.io / Vue.js"},
                    {name: "Swift", detail: "UIKit"},
                    {name: "HTML", detail: "Jinja2 / ejs"},
                    {name: "CSS", detail: "Bootstrap"},
                    {name: "Database", detail: "PostgreSQL / MongoDB"},
                    {name:"Docker",detail: "Docker / Docker Compose"}
                ]
            }
        }
    }
</script>

<style scoped>

</style>