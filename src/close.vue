<template>
  <button>
      <button @click="closetab">click close this tab</button>
  </button>
</template>

<script>
export default {
    data() {
        return {
            name: 'close',
        };
    },
    methods:{
      closetab () {   
          window.close();    
      }
    }

}
</script>

<style>

</style>