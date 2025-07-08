<template>
  <AppHeader></AppHeader>
  <div>
    {{ message }}
  </div>
  <button @click="showAlert">click</button>
</template>

<script>
// import 컴포넌트이름 from './컴포넌트 경로'
import AppHeader from './components/AppHeader.vue';
  export default {
    components:{
      AppHeader
    },
    data() {
      return {
        message: 'hi'
      }
    },
    methods: {
      showAlert(){
        alert('heyji');
      }
    }
  }
</script>

<style scoped>

</style>