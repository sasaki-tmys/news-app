<template>
  <v-app>
    <TestAppRouter/>
  </v-app>
</template>

<script>
import TestAppRouter from './components/NewsAppRouter.vue'

export default {
  name: 'App',
  components: {
    TestAppRouter,
},

  data: () => ({
  }),
}
</script>
