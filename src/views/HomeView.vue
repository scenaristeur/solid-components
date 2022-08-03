<template>
  <div class="home">
    <YourComponent label="Click ici" size="medium" primary="true"/>
    <!-- <FlashCard msg="Test flash card" /> -->
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
// import FlashCard from '@/stories/Button.vue'
import YourComponent from '@/components/YourComponent.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    // FlashCard,
    YourComponent
  }
}
</script>
