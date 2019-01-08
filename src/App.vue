<template>
  <div id="app">
      <navigation-guest></navigation-guest>
      <navigation-logged></navigation-logged>
    <router-view/>
  </div>
</template>

<script>
  import NavigationLogged from '@/components/Navigations/Logged'
  import NavigationGuest from '@/components/Navigations/Guest'

  export default {
    components: {
      NavigationLogged,
      NavigationGuest
    }
  }
</script>