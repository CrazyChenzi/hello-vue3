<template>
  <router-view />
</template>

<script>
import { defineComponent } from 'vue'
import HelloWorld from './views/HelloWorld.vue'

export default defineComponent({
  name: 'App',
  components: {
    HelloWorld
  }
})
</script>
