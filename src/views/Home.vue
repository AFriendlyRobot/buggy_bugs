<template>
  <div class="home">
    <buggy-bugs-game-display />
  </div>
</template>

<script>
// @ is an alias to /src
import BuggyBugsGameDisplay from '../components/BuggyBugsGameDisplay/BuggyBugsGameDisplay.vue';

export default {
  name: 'Home',
  components: {
    BuggyBugsGameDisplay,
  },
};
</script>

<style lang="stylus" scoped>
  @import '../styles/globals.styl'
</style>
