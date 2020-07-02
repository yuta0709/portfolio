<template>
    <div>
        <v-container>
            <v-row>
                <v-col class="col-12">
                    <Title title="About me"></Title>
                </v-col>
            </v-row>
            <v-row>
                <v-col class="col-md-4 col-sm-12" v-for="profile in profiles" :key="profile.title">
                    <Card :title="profile.title" :content="profile.detail"></Card>
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
                profiles: [
                    {title:'Birthday',detail:'2003/07/09'},
                    {title:'School',detail: 'NIT-Toyota-College'},
                    {title:'Department',detail: 'Information and Computer Engineering'}

                ]
            }
        }
    }
</script>

<style scoped>

</style>