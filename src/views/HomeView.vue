<template>
  <div class="home">
    <YourComponent label="Your Component" size="medium" primary/>
    <FlashCard label="Flash Card" size="medium" primary/>
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import FlashCard from '@/components/FlashCard.vue'
import YourComponent from '@/components/YourComponent.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    FlashCard,
    YourComponent
  }
}
</script>
