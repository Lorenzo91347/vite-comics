<script>
import AppHead from "./components/AppHead.vue";
import AppMain from "./components/appMain.vue";
import AppBlue from "./components/AppBlue.vue";
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
    AppBlue,
    AppFoot,
    AppSticky

  }


}
</script>
<template>
  <body>


    <header>
      <AppHead />
    </header>
    <main>
      <AppMain />
    </main>
    <div>
      <AppBlue/>
    </div>
    <footer>
      <AppFoot />
    </footer>
    <sticky-bar>
      <AppSticky />
    </sticky-bar>
  </body>
</template>
<style lang="scss">
@use "../src/assets/styles/general.scss"
</style>