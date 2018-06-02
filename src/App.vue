<template>
  <v-app dark>
    <appHeader></appheader>
    <v-content>
      <router-view/>
    </v-content>
   
    <appFooter></appfooter>
  </v-app>
</template>

<script>
import appHeader from '@/components/Shared/Header'
import appFooter from '@/components/Shared/Footer'
export default {
  data () {
    return {
    }
  },
  components: {
    appHeader,
    appFooter
  },
  name: 'App'
}
</script>
