<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  // type inference enabled
  props: {
    name: String
  },
  data() {
    return {
      count: 1
    }
  },
  mounted() {
    console.log(this.name)
  }

})

</script>

<template>
  <div class="main-vue">
    <p>Hi {{ name }}! WELCOME TO CAT RENTAL</p>
  </div>
</template>

<style scoped>
</style>
