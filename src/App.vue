<template>
  <div class="app-content">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <router-view class="content" />
  </div>
</template>

<style lang="stylus">
@import 'styles/globals.styl'
#app
  font-family Avenir, Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
.app-content
  background-color $offWhite
  margin 0
  padding 0
  width 100vw
  height 100vh
  position fixed
  top 0
</style>
