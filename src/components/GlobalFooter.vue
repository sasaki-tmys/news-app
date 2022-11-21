<template>
    <v-footer>
        <v-card elevation="0" rounded="0" width="100%" class="bg-grey text-center">
            <v-divider></v-divider>
            <v-card-text>
                {{ new Date().getFullYear() }} — <strong>test-app</strong>
            </v-card-text>
        </v-card>
    </v-footer>
</template>

<script>

</script>
<style>
.v-footer{
    top: 10%;
}
</style>