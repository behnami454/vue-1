<template>
  <button>
      <button @click="opentab">click to open a new tab</button>
  </button>
</template>

<script>
export default {
    data() {
        return {
            name: 'open',
        };
    },
    methods:{
      opentab () {   
          window.open("", "_blank");    
      }
    }

}
</script>

<style>

</style>