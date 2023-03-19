<template>
  <header>
    <div class="fs-1 text-center bg-dark header p-3">
      Rachel Gamble
    </div>
    <!-- <Navbar /> -->
  </header>
  <main class="bg-dark">
    <!-- <router-view /> -->
  </main>
  <footer class="bg-dark text-light text-center">
    <div class="fs-6 footerr">
      Made with ✨🌙💀 by Sautrah
    </div>
  </footer>
</template>

<script>
import { computed } from 'vue'
import { AppState } from './AppState'
import Navbar from './components/Navbar.vue'

export default {
  setup() {
    return {
      appState: computed(() => AppState)
    }
  },
  components: { Navbar }
}
</script>
<style lang="scss">
.footerr {
  color: hotpink;
  text-shadow: 1px 1px 1px darkblue;
}

.header {
  color: hotpink;
  text-shadow: 1px 1px 1px darkblue;
}

@import "./assets/scss/main.scss";
</style>
