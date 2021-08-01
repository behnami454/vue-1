<template>
  <div>
    <navbar />,
    <br>
    <card />,
    <message />
    <clock />
    <refresh />
    <close />
    <open />
    <footar />

    
   
    
    
  </div>
</template>

<script>


import navbar from './navbar.vue'
import footar from './footar.vue'
import close from './close.vue'
import card from './card.vue'
import message from './message.vue'
import clock from './clock.vue'
import refresh from './refresh.vue'
import open from './open.vue'

export default {
  name: 'App',
  components: {
    navbar,
    footar,
    card,
    message,
    clock,
    refresh,
    open,
    close
    
   
    
    
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 10px;
}
</style>
