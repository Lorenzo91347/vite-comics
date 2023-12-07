<script>
import AppHead from "./components/Apphead.vue";
import AppMain from "./components/AppMain.vue";
import AppFoot from "./components/AppFoot.vue";
import AppSticky from "./components/AppSticky.vue";


export default {
  data() {
    return {

    }
  },
  components: {
    AppHead,
    AppMain,
    AppFoot,
    AppSticky

  }


}
</script>
<template>
  <header>
    <AppHead />
  </header>
  <main>
    <AppMain />
  </main>
  <footer>
    <AppFoot />
  </footer>
  <sticky-bar>
    <AppSticky />
  </sticky-bar>
</template>
<style lang="scss">
@use "../src/assets/styles/general.scss"
</style>